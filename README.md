
首先电脑里要有安装npm




``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
如果报错 就试试yarn install

问题 1 在创建界面时 page id应该由数据库指定 需要一个create page的api 那么id这个值什么时候该传进来呢？ 点create的时候就应该有个POST request然后database新建一个page 同时把pagenumber传回前端. 目前待定 或者我在存第一个node的时候就加入page的tag title等等 然后这个json发到server server建立新page 然后分配id 回传给前端 之后的node都会打上这个label.


介绍：
目前的储存逻辑 每编辑完一个component需要点下save， 此时会生成一个带有数字id（有序）的json文件
最后的submit会提交本文的title intro 等 （是json 但格式与前一种json不同）

改进： 1： 用户体验不佳 每次都得手动点save 然后添加新的 很多人喜欢全写好然后save (但是我不会写实时保存功能（可能会用到cookie)) 也许可以把savefunc绑在添加按钮上 但是那样会有bug-->因为在addlist 种得不到index的值 所以无法得到当前conponent的 data这个list.

目前的问题： node怎么在editing page上体现？
            Present page的scroll view怎么做？



目前的json structure for component

question: [{
            question_id: 1,
            types: 'Situation',
            is_required: false,
            content: [
              {
                language: 'cn',
                title: '',
                answer: [{
                  answer_id: 1,
                  description: 'Condition 1'
                }]
              }
            ]}
          ]


目前的json structure for start ndoe

 let data = {
          tag: n,
          nodetype: type,
          intro: m,
          title: o
        }

https://cn.vuejs.org/v2/cookbook/using-axios-to-consume-apis.html
待学习内容
