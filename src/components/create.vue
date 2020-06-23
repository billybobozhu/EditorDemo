<style lang="scss">
  // .container {
  //       width: 500px;
  //       height: 300px;
  //       padding: 20px;
  //       border: 1px solid #ccc;
  //       position: relative;
  //   }
    // .card-item {
    //     width: 700px;
    //     height: 200px;
    //     line-height: 198px;
    //     text-align: center;
    //     font-size: 18px;
    //     border-radius: 5px;
    //     position: absolute;
    // }
    // .card-item.t30 {
    //     top: 30px;
    //     animation: positionAnimate1 1.1s
    // }
    // .card-item.t60 {
    //     top: 60px;
    //     animation: positionAnimate1 0.9s
    // }
    // .card-item.t90 {
    //     top: 90px;
    //     animation: positionAnimate1 0.7s
    // }
    // .card-item.t120 {
    //     top: 120px;
    //     box-shadow: 0 0 2px 2px #fff;
    //     animation: positionAnimate 0.5s
    // }
    // .card-item.t150 {
    //     top: 150px;
    //     box-shadow: 0 0 2px 2px #fff;
    //     animation: positionAnimate 0.3s
    // }
    // @keyframes positionAnimate1 {
    //     0% {
    //         opacity: 0;
    //         transform: scale(0.9);
    //     }
    //     100% {
    //         transform: scale(1);
    //         opacity: 1;
    //     }
    // }
    // @keyframes positionAnimate {
    //     0% {
    //         opacity: 0;
    //         transform: scale(1.1);
    //     }
    //     100% {
    //         transform: scale(1);
    //         opacity: 1;
    //     }
    // }
    // .card-item.z1 {
    //     z-index:  1;
    // }
    // .card-item.z2 {
    //     z-index:  2;
    // }
    // .card-item.z3 {
    //     z-index:  3;
    // }
    // .card-item.z4 {
    //     z-index:  4;
    // }
    // .card-item.z5 {
    //     z-index:  5;
    // }
    // .card-item.red {
    //     border: 1px solid grey;
    //     background-color: grey;
    // }
    // .card-item.blue {
    //     border: 1px solid blue;
    //     background-color: blue;
    // }
    // .card-item.yellow {
    //     border: 1px solid brown;
    //     background-color: brown;
    // }
    // .card-item.green {
    //     border: 1px solid green;
    //     background-color: green;
    // }
    // .card-item.black {
    //     border: 1px solid pink;
    //     background-color: pink;
    // }
  .Sidebar {

    // position: relative;
    // width: 20%;
    // min-width: 400px;
    // margin: 20px auto;
    // @media (min-width: 520px) {
    //   width: 100%;
    // }
     flex: 1;
        flex-grow: 0;
        align-self: flex-end;
        float: left;
        display: inline-block;
        background-color: #fff;
        box-shadow: 0 0 2px rgba(0,0,0,.12), 0 2px 4px rgba(0,0,0,.24);
        .sidebar-li {
          cursor: pointer;
          padding: 10px 12px;
        }
    }
  .form-create-wrap {
    $green: #4ca2ae;
    $grey: rgba(0,0,0,.5);
    position: relative;
    width: 80%;
    min-width: 400px;
    margin: 30px auto;
    @media (min-width: 520px) {
      width: 100%;
    }
     .fa-home {
        font-size: 20px !important;
    }

    .nav-sm .fa-home {
        font-size: 32px !important;
    }

    .Sidebar {
    position: relative;
    width: 20%;
    height: 800px;
    min-width: 40px;
    margin: 20px auto;
    @media (min-width: 520px) {
      width: 20%;
    }
     flex: 1;
        flex-grow: 0;
        align-self: flex-end;
        display: inline-block;
        background-color: #fff;
        box-shadow: 0 0 2px rgba(0,0,0,.12), 0 2px 4px rgba(0,0,0,.24);
        .sidebar-li {
          cursor: pointer;
          padding: 10px 12px;
        }
    }
    .wrap {
      width: 780px;
      min-height: 100px;
      margin: 0 auto;
      @media (max-width: 920px) {
        width: 100%;
      }
      display: flex;

      .content-wrap {
        flex: 1;
        background-color: #fff;
        box-shadow: 0 0 2px rgba(0,0,0,.12), 0 2px 4px rgba(0,0,0,.1);
        margin-right: 10px;
      }
      .form-sidebar {
        flex: 1;
        flex-grow: 0;
        align-self: flex-end;
        display: inline-block;
        background-color: #fff;
        box-shadow: 0 0 2px rgba(0,0,0,.12), 0 2px 4px rgba(0,0,0,.24);
        .sidebar-li {
          cursor: pointer;
          padding: 10px 12px;
        }
      }
    }
    .item {
      padding: 16px 24px 24px 42px;
      .li-right {
        text-align: right;
      }
      .li-left {
        text-align: left;
        .q-select {
          display: inline-block;
          width: 120px;
        }
      }
    }
    .title-focus {
      border-left-color: $green !important;
    }
    .title {
      border-left: 3px solid transparent;
      position: relative;
      .add-list {
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background-color: #e9e9e9;
        position: absolute;
        left: 50%;
        transform: translateX(-50%);
        bottom: -15px;
        display: flex;
        align-items: center;
        justify-content: center;
        cursor: pointer;
        i {
          color: $green;
          font-size: 22px;
        }
      }
    }
    .q-wrap {
      .q-li-focus {
        border-left-color: $green !important;
        box-shadow: 0 -2px 2px 0 rgba(0,0,0,0.2), 0 2px 6px 0 rgba(0,0,0,0.24);
      }
      .q-li {
        border-left: 3px solid transparent;
      }
      .q-title-wrap {
        display: flex;
        align-items: center;
        margin-bottom: 25px !important;
        .q-index {
          flex: 1;
          flex-grow: 0;
          margin-right: 10px;
        }
        .q-title {
          flex: 1;
          flex-grow: 2;
          .li {
            margin-bottom: 0;
          }
        }
        .q-select {
          flex: 1;
          flex-shrink: 0;
        }
      }
      .drap-area {
        padding: 5px;
        cursor: move;
        .icon-tuozhuai {
          color: lightgray;
          font-size: 20px;
          margin-left: 37px;
        }
      }
      .q-item-wrap {
        padding:  16px 24px 24px 42px;
      }
      .q-item {
        margin-bottom: 10px;
        /*overflow: hidden;*/
        .q-radio {
          margin: 15px auto;
          display: flex;
          align-items: center;
          .icon-radio {
            width: 15px;
            height: 15px;
            border: 2px solid transparent;
            margin-right: 15px;
          }
          .icon-cirle {
            border: 2px solid lightgray;
            border-radius: 50%;
          }
          .icon-square {
            border: 2px solid lightgray;
            border-radius: 0;
          }
          input {
            flex: 2;
            margin-right: 15px;
            border: 1px solid transparent;
            padding-bottom: 3px;
            &:focus {
              border-bottom: 1px solid lightgray;
            }
          }
          i {
            flex: 1;
            flex-grow: 0;
            color: rgba(0,0,0,0.3);
            cursor: pointer;
          }
          .radio-add {
            color: $green;
            font-weight: bold;
            cursor: pointer;
            flex: 0;
          }
        }
      }
      .line-wrap {
        .q-item-line {
          display: flex;
          align-items: center;
          .el-select {
            width: 70px;
            .el-input {
              border: none !important;
            }
          }
          .line-tip {
            padding: 15px;
          }
        }
        .q-radio {
          input {
            border-bottom: 1px solid lightgray !important;
            flex: 0;
          }
        }
      }
      .text-wrap {
        color: $grey;
        border-bottom: 1px dotted lightgray;
        padding-bottom: 5px;
        width: 60%;
        text-align: left;
      }
      .square-wrap {
        display: flex;
        .square-li {
          flex: 1
        }
      }
      .option-wrap {
        overflow: hidden;
        border-top: 1px solid lightgray;
        .option-list {
          float: right;
          li {
            float: left;
            list-style: none;
            margin: 20px 0 0 25px;
            .icon-copy {
              font-size: 20px;
            }
            .el-icon-delete {
              font-size: 21px;
              vertical-align: middle;
            }
            i {
              cursor: pointer;
            }
          }
          .lang-li {
            margin: 15px 8px;
            display: flex;
            align-items: center;
            span {
              margin-left: 10px;
              cursor: pointer;
              color: $green;
              font-weight: bold;
            }
            .el-select {
              width: 120px;
            }
          }
        }
      }
      .lang-wrap {
        border-top: 1px dotted lightgray;
        padding-top: 20px;
        .lang-li-wrap {
          display: flex;
          .li-text {
            margin-right: 15px;
            i {
              display: block;
              margin-top: 20px;
              cursor: pointer;
            }
            .el-icon-delete {
              font-size: 21px;
            }
          }
          .li-content {
            flex: 1;
          }
        }
      }
    }
    .li {
      position: relative;
      margin-bottom: 15px;
      height: 100%;
      &:after {
        content: '';
        width: 100%;
        height: 1px;
        position: absolute;
        bottom: -1px;
        left: 0;
        transform: scaleX(0);
        background-color: $green;
        transition-duration: 0.3s;
        transition-timing-function: ease;
        transition-delay: 0s;
      }
      &:hover:after {
        border-bottom: 1px solid transparent;
        transform: scaleX(1);
      }
      .form-title {
        font-size: 24px;
        &::-webkit-input-placeholder {
          font-size: 24px;
        }
      }
      .title-area {
        font-size: 20px;
        &::-webkit-input-placeholder {
          font-size: 20px;
        }
      }
      .q-area {
        font-size: 18px;
        &::-webkit-input-placeholder {
          font-size: 18px;
        }
      }
    }
    textarea {
      background-color: transparent;
      border: none;
      resize: none;
      display: block;
      width: 100%;
      height: 35px;
    }
    .expand-area {
      position: relative;
      textarea {
        position: absolute;
        top: 0;
        left: 0;
        height: 100%;
        overflow: hidden;
      }
      pre {
        display: block;
        visibility: hidden;
        min-height: 100px;
        margin: 0;
      }
    }
    .add-lang {
      .li-item {
        display: flex;
        align-items: center;
        .label {
          margin-right: 15px;
        }
      }
    }
    input::-webkit-input-placeholder, textarea::-webkit-input-placeholder {
      color: $grey;
    }
    .el-tabs__item.is-active, .el-tabs__new-tab:hover {
      color: $green;
    }
  }
</style>
<template>
  <div class="form-create-wrap">
    <loading :loading="loading"></loading>
    <!-- <div class="container">
        <div class="card-item" v-for="(item,index) in cardArrs"
             :class="[item.bgColor ,'z'+item.zIndex, 't'+item.zIndex*30]"
             @click.stop="changeArrIndex(index)">
            {{item.text}}
        </div>
    </div> -->
    <div class="Sidebar" >
      <!-- <div class="swiper-container">
        <div class="swiper-wrapper">
          <div class="swiper-slide" v-for="(item,index) in images" :key="index">
            <img class="swiper-img" :src="item" />
          </div>
        </div>
      </div> -->
        <div class="sidebar-li" @click="addNodeFn">
          <i class="el-icon-plus"></i>
        </div>
        <div>
          <svg class="d3-tree-vi width-100-percent" />
        </div>
    </div>

    <div class="wrap" v-if="!loading">
      <div class="content-wrap">
        <div class="item title" @click="focusTitle($event)" :class="{'title-focus': focusIndex === 'title'}">
          <div class="li">
            <textarea class="form-title" id=tagmanager placeholder="Casptone Project" v-model="data.display_name" @focus="$autoText($event)" @input="$autoText($event)"></textarea>
          </div>
          <el-tabs v-model="tabLang" type="card" editable @edit="handleTabsEdit">
            <el-tab-pane
              v-for="item in editableTabs"
              :key="item"
              :label="item"
              :name="item">
            </el-tab-pane>
          </el-tabs>

          <div class="li" v-for="i in data.name" v-if="i.language === langCode[langList.indexOf(tabLang)]">
            <textarea class="title-area" id=titlearea placeholder="Title" v-model="i.componentnaire_name" @focus="$autoText($event)" @input="$autoText($event)"></textarea>
          </div>
          <div class="li" v-for="i in data.name" v-if="i.language === langCode[langList.indexOf(tabLang)]">
            <textarea class="title-area" id=intro placeholder="Introduction" v-model="i.desc" @focus="$autoText($event)" @input="$autoText($event)"></textarea>
          </div>
          <div class="li-right">
            <!-- <span>允许重复提交</span>
            <el-switch :width="40" on-color="#4ca2ae" v-model="data.repeat_submit" on-text="" off-text="">
            </el-switch> -->
          </div>
          <div class="add-list" @click="addListFn" v-if="!data.component.length">
            <i class="el-icon-plus"></i>
          </div>
        </div>
        <div class="q-wrap">
          <draggable v-for="data, index in data.component" :key="index" v-model="data.component" :options="{group:'people'}" :move="onMove" @start="drag=true" @end="onEnd">
            <!-- <div class="container"> -->
           <!-- <div class="card-item" v-for="(item,index) in cardArrs"
             :class="[item.bgColor ,'z'+item.zIndex, 't'+item.zIndex*30]"
             @click.stop="changeArrIndex(index)">
            {{item.text}}
            </div> -->
            <!-- </div> -->
            <div class="q-li" :class="{'q-li-focus': focusIndex === index}" id="items" @click="focusItem($event, index)">
              <div class="drap-area">
                <i class="iconfont icon-tuozhuai"></i>

              </div>

              <div class="q-item-wrap" v-for="content, index1 in data.content" v-if="content.language === langCode[langList.indexOf(tabLang)]">
                <div class="q-item q-title-wrap">
                  <div class="q-title">
                    <div class="li">
                      <textarea class="q-area" id="testing" placeholder="Content" v-model="content.title" @focus="$autoText($event)" @input="$autoText($event)"></textarea>
                    </div>
                  </div>
                  <el-select class="q-select" v-if="focusIndex === index" v-model="data.types" filterable placeholder="请选择">
                    <el-option
                      v-for="item in selectOptions"
                      :key="item"
                      :label="item"
                      :value="item">
                    </el-option>
                  </el-select>
                </div>
                <div class="q-item" v-if="data.types === '下拉列表' || data.types === 'Situation' || data.types === '多选题' || data.types === '优先级'">
                  <div class="q-radio" v-for="item, i in content.condition">
                    <div class="icon-radio" v-if="data.types === '下拉列表' || data.types === '优先级'">{{i + 1}}.</div>
                    <div v-else class="icon-radio" :class="{'icon-cirle': data.types === 'Situation', 'icon-square': data.types === '多选题'}"></div>
                    <input class="radio-input" id='testing2' v-model="item.description">
                    <i class="el-icon-close" v-if="focusIndex === index" @click="deleteRadioFn(index, index1, i)"></i>
                  </div>
                  <div class="q-radio" v-if="focusIndex === index">
                    <div class="icon-radio" v-if="data.types === '下拉列表' || data.types === '优先级'">{{content.condition.length + 1}}.</div>
                    <div v-else class="icon-radio" :class="{'icon-cirle': data.types === 'Situation', 'icon-square': data.types === '多选题'}"></div>
                    <input class="radio-add" v-model="addRadio" @focus="addRadioFn(index, index1)">
                  </div>
                </div>
                <div class="q-item line-wrap" v-if="data.types === '线性量表'">
                  <div class="q-item-line">
                    <el-select v-model="content.line_condition.line_value">
                      <el-option
                        v-for="i in lineOptions"
                        :key="i"
                        :value="i">
                      </el-option>
                    </el-select>
                    <span class="line-tip">到</span>
                    <el-select v-model="content.line_condition.line_end_value">
                      <el-option
                        v-for="i in lineEndOptions"
                        :key="i"
                        :value="i">
                      </el-option>
                    </el-select>
                  </div>
                  <div class="q-radio">
                    <div class="icon-radio">1.</div>
                    <input class="radio-input" v-model="content.line_condition.line_tag" placeholder="标签（选填）">
                  </div>
                  <div class="q-radio">
                    <div class="icon-radio">2.</div>
                    <input class="radio-input" v-model="content.line_condition.line_end_tag" placeholder="标签（选填）">
                  </div>
                </div>
                <div class="q-item text-wrap" v-if="data.types === '文本题'"></div>
                <div class="q-item line-wrap square-wrap" v-if="data.types === '矩阵量表'">
                  <div class="square-li">
                    <h4>行</h4>
                    <div class="q-item-line">
                      <el-select v-model="content.line_condition.line_value">
                        <el-option
                          v-for="i in lineOptions"
                          :key="i"
                          :value="i">
                        </el-option>
                      </el-select>
                      <span class="line-tip">到</span>
                      <el-select v-model="content.line_condition.line_end_value">
                        <el-option
                          v-for="i in lineEndOptions"
                          :key="i"
                          :value="i">
                        </el-option>
                      </el-select>
                    </div>
                    <div class="q-radio">
                      <div class="icon-radio">1.</div>
                      <input class="radio-input" v-model="content.line_condition.line_tag" placeholder="标签（选填）">
                    </div>
                    <div class="q-radio">
                      <div class="icon-radio">2.</div>
                      <input class="radio-input" v-model="content.line_condition.line_end_tag" placeholder="标签（选填）">
                    </div>
                  </div>
                  <div class="square-li">
                    <h4>列</h4>
                    <div class="q-radio" v-for="item, i in content.condition">
                      <div class="icon-radio">{{i + 1}}.</div>
                      <input class="radio-input" v-model="item.description">
                      <i class="el-icon-close" v-if="focusIndex === index" @click="deleteRadioFn(index, index1, i)"></i>
                    </div>
                    <div class="q-radio" v-if="focusIndex === index">
                      <div class="icon-radio">{{content.condition.length + 1}}.</div>
                      <input class="radio-add" v-model="addRadio" @focus="addRadioFn(index, index1)">
                    </div>
                  </div>
                </div>
                <div class="q-item option-wrap" v-if="focusIndex === index">
                  <ul class="option-list">
                    <li>
                      <i class="iconfont icon-baocun-tianchong" @click="saveCurrentCell(index)"></i>
                    </li>
                    <li>
                      <i class="el-icon-delete" @click="deleteListFn(index)"></i>
                    </li>
                    <li>
                      <!-- <span>必填</span>
                      <el-switch :width="40" on-color="#4ca2ae" v-model="data.is_required" on-text="" off-text="">
                      </el-switch> -->
                    </li>
                  </ul>
                </div>
              </div>
              <!-- <div class="form-sidebar" v-if="data.component.length"> -->
                <div class="sidebar-li" @click="addListFn(index)">
                  <i class="el-icon-plus"></i>
                </div>
              <!-- </div> -->
            </div>
          </draggable>
        </div>
      </div>
    </div>
    <div class="form-save" @click="saveFn" v-if="!loading" >Submit</div>
    <el-dialog class="add-lang" title="Add new" :visible.sync="addLangVisible" :close-on-click-modal="false" top="34%">
      <div class="li-item">
        <span class="label">Choose</span>
        <el-select class="q-select" v-model="defaultLang" filterable placeholder="Please Choose">
          <el-option
            v-for="item in langList"
            :key="item"
            :label="item"
            :value="item">
          </el-option>
        </el-select>
      </div>
      <div slot="footer" class="dialog-footer">
        <el-button @click="addLangVisible = false">Cancel</el-button>
        <el-button type="primary" @click=addLangFn>Confirm</el-button>
      </div>
    </el-dialog>
    </div>
</template>

<script>
  import * as d3 from 'd3'
  import draggable from 'vuedraggable'
  import loading from '@/components/loading.vue'
  // import {init,update} from '@/components/g6Utils.min.js'

  let lineEndOptions = Array.apply(null, Array(9)).map((item, i) => {
    return i + 2
  })

  let that
  export default {
    data () {
      that = this
      return {
         cardArrs: [
                    {
                        text: "card-1",
                        zIndex: 1,
                        bgColor: "red"
                    },
                    {
                        text: "card-2",
                        zIndex: 2,
                        bgColor: "blue"
                    },
                    {
                        text: "card-3",
                        zIndex: 3,
                        bgColor: "yellow"
                    },
                    {
                        text: "card-4",
                        zIndex: 4,
                        bgColor: "green"
                    },
                    {
                        text: "card-5",
                        zIndex: 5,
                        bgColor: "black"
                    }
                ],
                maxLength: 5,

        auth: false,
        loading: false,
        selectOptions: ['Situation', 'Story'],
        langCode: ['cn', 'en', 'kr', 'jp', 'fr', 'de', 'ru', 'sp', 'po', 'it', 'nl', 'id', 'tr', 'thai', 'zh', 'fa', 'ro', 'ar'],
        langList: ['Normal', 'Alternative'],
        defaultLang: 'Normal',
        tabLang: 'Normal',
        editableTabs: ['Normal'],
        addLangVisible: false,
        defaultOption: 'Situation',
        addRadio: 'Add',
        lineOptions: [0, 1],
        lineEndOptions: lineEndOptions,
        langArray: [],
        data: {
          display_name: '',
          name: [{
            componentnaire_name: '',
            desc: '',
            language: 'cn'
          }],
          repeat_submit: false,
          component: [{
            component_id: 0,
            child: [],
            parent: 0,
            types: 'Situation',
            is_required: false,
            content: [
              {
                language: 'cn',
                title: '',
                condition: [{
                  condition_id: 1,
                  description: 'Condition 1'
                }]
              }
            ]}
          ]
        },
        // data2: {
        //   display_name: '',
        //   name: [{
        //     componentnaire_name: '',
        //     desc: '',
        //     language: 'cn'
        //   }],
        //   repeat_submit: false,
        //   component: [{
        //     component_id: 1,
        //     types: 'Story',
        //     is_required: false,
        //     content: [
        //       {
        //         language: 'cn',
        //         title: ''
        //       }
        //     ]}
        //   ]

        // },
        editable: true,
        focusIndex: 0,
        tree_data:{
          'name':0,
          // 'children': that.data.component[0].child
          // 'children':[{'name':20,'children':[{'name':30,'children':[]}]},{'name':50}]
          'children':[]
        }
      }
    },
    mounted () {
      // let tree_data = {
      //   'name':that.data.component[0].component_id,
      //   // 'children': that.data.component[0].child
      //   'children':[{'name':2,'children':[{'name':3,'children':[]}]}]
      // }
      // let clientWidth = document.body.clientWidth
      // let clientHeight = document.body.clientHeight
      // this.width = Math.floor(clientWidth * 0.16)
      // this.height = clientHeight - 72
      // console.log('width: ' + this.width + ' height: ' + this.height) // eslint-disable-line
      // let margin = ({ top: 30, right: 200, bottom: 1000, left: 40 })
      // let width = this.width
      // let dy = width / 4
      // let dx = 30
      // let tree = d3.tree().nodeSize([dx, dy])
      // let diagonal = d3.linkHorizontal().x(d => d.x).y(d => d.y)
      // const root = d3.hierarchy(that.tree_data)
      // root.x0 = 0
      // root.y0 = 0
      // root.descendants().forEach((d, i) => {
      //   d.id = i
      //   d._children = d.children
      //   if (d.depth && d.data.name.length !== 4) d.children = null
      // })
      // let svg = d3
      //   .select('svg.d3-tree-vi')
      //   .attr('viewBox', [-margin.left, -margin.top, width, dx])
      // const gLink = svg.append('g')
      //   .attr('fill', 'none')
      //   .attr('stroke', '#555')
      //   .attr('stroke-opacity', 0.4)
      //   .attr('stroke-width', 1.5)
      // const gNode = svg.append('g')
      //   .attr('cursor', 'pointer')
      //   .attr('pointer-events', 'all')
      // // ****************  zoom ************************
      // // add zoom capabilities
      // let zoomHandler = d3.zoom()
      //   .on('zoom', zoomActions)
      //   .scaleExtent([1 / 2, 8])
      // svg.call(zoomHandler).on('dblclick.zoom', null)
      // zoomHandler(svg)
      // // Zoom functions
      // function zoomActions () {
      //   gNode.attr('transform', d3.event.transform)
      //   gLink.attr('transform', d3.event.transform)
      // }
      // // ***********************************************
      // function update (source) {
      //   const duration = d3.event && d3.event.altKey ? 2500 : 250
      //   const nodes = root.descendants().reverse()
      //   const links = root.links()
      //   // Compute the new tree layout.
      //   tree(root)
      //   // console.log('root ', root)
      //   let left = root
      //   let right = root
      //   root.eachBefore(node => {
      //     if (node.x < left.x) left = node
      //     if (node.x > right.x) right = node
      //   })
      //   const height = right.x - left.x + margin.top + margin.bottom
      //   const transition = svg.transition()
      //     .duration(duration)
      //     .attr('viewBox', [-margin.left, left.x - margin.top, width, height])
      //     // .attr('viewBox', [-240, 0, 846, 10])
      //     .tween('resize', window.ResizeObserver ? null : () => () => svg.dispatch('toggle'))
      //   // Update the nodes…
      //   const node = gNode.selectAll('g')
      //     .data(nodes, d => d.id)
      //   // Enter any new nodes at the parent's previous position.
      //   const nodeEnter = node.enter().append('g')
      //     .attr('transform', () => `translate(${source.y0},${source.x0})`)
      //     .attr('fill-opacity', 0)
      //     .attr('stroke-opacity', 0)
      //     .on('click', d => {
      //       d.children = d.children ? null : d._children
      //       update(d)
      //     })
      //   nodeEnter.append('circle')
      //   // .attr('class', 'node')
      //   // .attr('r', 1e-6)
      //   // .style('fill', function (d) {
      //   //   return d._children ? '#c9e4ff' : '#fff'
      //   // })
      //     .attr('r', 10)
      //     .attr('fill', d => d._children ? '#c9e4ff' : '#fff')
      //     //  .style('fill', function (d) {
      //     //           return d._children ? '#c9e4ff' : '#fff'
      //     //         })
      //     .attr('stroke-width', 2)
      //     .attr('stroke', '#c9e4ff')
      //   nodeEnter.append('text')
      //     .attr('dy', '0.31em')
      //     // .attr('x', d => d._children ? -6 : 6)
      //     .attr('x', d => d._children ? -14 : 14)
      //     .attr('text-anchor', d => d._children ? 'end' : 'start')
      //     .text(d => d.data.name)
      //     .clone(true).lower()
      //     .attr('stroke-linejoin', 'round')
      //     .attr('stroke-width', 3)
      //     .attr('stroke', 'white')
      //   // Transition nodes to their new position.
      //   const nodeUpdate = node.merge(nodeEnter).transition(transition)
      //     .attr('transform', d => `translate(${d.x},${d.y})`)
      //     // .attr('r', 10)
      //     // .style('fill', function (d) {
      //     //   return d._children ? '#c9e4ff' : '#fff'
      //     // })
      //     // .attr('cursor', 'pointer')
      //     .attr('fill-opacity', 1)
      //     .attr('stroke-opacity', 1)
      //   console.log(nodeUpdate) // eslint-disable-line
      //   // Transition exiting nodes to the parent's new position.
      //   const nodeExit = node.exit().transition(transition).remove()
      //     .attr('transform', () => `translate(${source.y},${source.x})`)
      //     .attr('fill-opacity', 0)
      //     .attr('stroke-opacity', 0)
      //   console.log(nodeExit) // eslint-disable-line
      //   // Update the links…
      //   const link = gLink.selectAll('path')
      //     .data(links, d => d.target.id)
      //   // Enter any new links at the parent's previous position.
      //   const linkEnter = link.enter().append('path')
      //     .attr('d', () => {
      //       const o = { x: source.x0, y: source.y0 }
      //       return diagonal({ source: o, target: o })
      //     })
      //   // Transition links to their new position.
      //   link.merge(linkEnter).transition(transition)
      //     .attr('d', diagonal)
      //   // Transition exiting nodes to the parent's new position.
      //   link.exit().transition(transition).remove()
      //     .attr('d', () => {
      //       const o = { x: source.x, y: source.y }
      //       return diagonal({ source: o, target: o })
      //     })
      //   // Stash the old positions for transition.
      //   root.eachBefore(d => {
      //     d.x0 = d.x
      //     d.y0 = d.y
      //   })
      // }
      // update(root)
      this.drawGraph()
    },
    components: {
      draggable,
      loading
    },
    methods: {
      changeArrIndex(index){
                let _zIndex = "";
                let _newArr = [];
                this.cardArrs.forEach((item,idx)=> {
                    let _obj = {};
                    if(idx == index) {
                        _zIndex = item.zIndex;
                        _obj.zIndex = this.maxLength;
                        _obj.bgColor = item.bgColor;
                        _obj.text = item.text;
                        _obj.flag = true;
                        _newArr.push(_obj)
                    }else {
                        _newArr.push(item)
                    }
                });
                _newArr.forEach((obj)=>{
                   if(obj.zIndex == this.maxLength && !obj.flag) {
                       obj.zIndex = _zIndex;
                   }
                });
                _newArr.map((item)=>{
                    delete item.flag;
                });
                this.cardArrs = _newArr;
            },
      onEnd () {
        that.drag = false
      },
      onMove ({relatedContext, draggedContext}) {
        let relatedIndex = relatedContext.index
        let index = draggedContext.index
        relatedContext.element.component_id = index + 1
        draggedContext.element.component_id = relatedIndex + 1
      },
      focusTitle (event) {
        let classList = event.target.classList
        if (classList.contains('add-list') || classList.contains('el-icon-plus')) return
        that.focusIndex = 'title'
      },
      focusItem (event, i) {
        let classList = event.target.classList
        if (classList.contains('el-icon-delete') || classList.contains('icon-copy') || that.focusIndex === i) return
        that.focusIndex = i
      },
      addRadioFn (i, j) {
        let list = that.data.component[i].content[j].condition
        that.addFormFn(list)
      },
      deleteRadioFn (i, j, k) {
        that.data.component[i].content[j].condition.splice(k, 1)
      },
      addFormFn (list) {
        let index = list.length ? parseInt(list[list.length - 1].description.substr(2)) + 1 : '1'
        let text = index ? 'Condition' + index : 'Condition1'
        list.push({condition_id: list.length + 1, description: text})
        that.$nextTick(() => {
          let input = document.querySelectorAll('.radio-input')
          input[input.length - 1].focus()
        })
      },
      saveCurrentCell (index) {
        var FileSaver = require('file-saver')
        window.alert('Saving...')
        let titleName = that.data.name
        window.alert(titleName)
        let content = JSON.stringify(that.data.component[index])
        var blob = new Blob([content], {type: 'text/plain;charset=utf-8'})
        FileSaver.saveAs(blob, 'save.json')
      },

      addListFn (index) {
        let codeList = that.editableTabs.map((i) => {
          return that.langCode[that.langList.indexOf(i)]
        })
        let contentList = codeList.map((i) => {
          return {
            language: i,
            title: '',
            condition: [{
              condition_id: 1,
              description: 'Condition1'
            }]
          }
        })
        let list = {
          component_id: that.data.component.length ,
          child:[],
          parent:index,
          types: 'Situation',
          is_required: false,
          content: contentList
        }
        that.data.component.push(list)
        that.data.component[index].child.push({'name':list.component_id,'children':[]})
        //that.tree_data.children=that.data.component[0].child
        //alert(that.data.component[index].child)
        that.focusIndex = that.data.component.length - 1

        var start = Number(index)
        var trace = Number(index)
        if(trace==0){
          that.tree_data.children.push({'name':list.component_id,'children':[]})
          //alert(that.tree_data.children)
        }else{
          var parent_list = [start]
          while (that.data.component[trace].parent> 0){
            //alert("parent"+that.data.component[trace-1].parent)
            trace=that.data.component[index].parent
            parent_list.push(trace)
          }
          //alert(Number(parent_list[parent_list.length-1]))
          var dad=0
          for(var m=1;m<that.tree_data.children.length;m++){
            if(that.tree_data.children[m].name==parent_list[parent_list.length-1]){
              dad = m
            }
          }
          //alert(dad)
          var par = that.tree_data.children[dad]
          for (var i=parent_list.length-1;i>0;i--){
            for(var k=0;k<par.children.length;k++){
              if (par.children[k].name==parent_list[i]){
                alert('found')
                dad = k
                par = par.children[dad]
                break
              }
            }
          }
          //alert(par.name)
          par.children.push({'name':list.component_id,'children':list.child})
        }
        d3.selectAll("svg > *").remove()
        this.drawGraph()

        // if (index in that.tree_data)
        // this.saveFn(list.component_id)
      },
      addNodeFn () {
        let codeList = that.editableTabs.map((i) => {
          return that.langCode[that.langList.indexOf(i)]
        })
        let contentList = codeList.map((i) => {
          return {
            language: i,
            title: '',
            condition: [{
              condition_id: 1,
              description: 'Condition1'
            }],
            line_condition: {
              line_value: 1,
              line_end_value: 5,
              line_tag: '',
              line_end_tag: ''
            },
            text_condition: ''
          }
        })
        let list = {
          component_id: that.data.component.length ,
          child:[],
          parent:0,
          types: 'Situation',
          is_required: false,
          content: contentList
        }
        that.data.component.push(list)
        that.data.component[0].child.push({'name':list.component_id,'children':list.child})
        that.focusIndex = that.data.component.length - 1
        that.tree_data.children = that.data.component[0].child
        d3.selectAll("svg > *").remove()
        that.drawGraph()
      },
      drawGraph(){
        let clientWidth = document.body.clientWidth
        let clientHeight = document.body.clientHeight
        this.width = Math.floor(clientWidth * 0.16)
        this.height = clientHeight - 72
        console.log('width: ' + this.width + ' height: ' + this.height) // eslint-disable-line
        let margin = ({ top: 30, right: 200, bottom: 1000, left: 40 })
        let width = this.width
        let dy = width / 4
        let dx = 30
        let tree = d3.tree().nodeSize([dx, dy])
        let diagonal = d3.linkHorizontal().x(d => d.x).y(d => d.y)
        const root = d3.hierarchy(that.tree_data)
        root.x0 = 0
        root.y0 = 0
        root.descendants().forEach((d, i) => {
          d.id = i
          d._children = d.children
          if (d.depth && d.data.name.length !== 4) d.children = null
        })
        let svg = d3
          .select('svg.d3-tree-vi')
          .attr('viewBox', [-margin.left, -margin.top, width, dx])
        const gLink = svg.append('g')
          .attr('fill', 'none')
          .attr('stroke', '#555')
          .attr('stroke-opacity', 0.4)
          .attr('stroke-width', 1.5)
        const gNode = svg.append('g')
          .attr('cursor', 'pointer')
          .attr('pointer-events', 'all')
        // ****************  zoom ************************
        // add zoom capabilities
        let zoomHandler = d3.zoom()
          .on('zoom', zoomActions)
          .scaleExtent([1 / 2, 8])
        svg.call(zoomHandler).on('dblclick.zoom', null)
        zoomHandler(svg)
        // Zoom functions
        function zoomActions () {
          gNode.attr('transform', d3.event.transform)
          gLink.attr('transform', d3.event.transform)
        }
        // ***********************************************
        function update (source) {
          const duration = d3.event && d3.event.altKey ? 2500 : 250
          const nodes = root.descendants().reverse()
          const links = root.links()
          // Compute the new tree layout.
          tree(root)
          // console.log('root ', root)
          let left = root
          let right = root
          root.eachBefore(node => {
            if (node.x < left.x) left = node
            if (node.x > right.x) right = node
          })
          const height = right.x - left.x + margin.top + margin.bottom
          const transition = svg.transition()
            .duration(duration)
            .attr('viewBox', [-margin.left, left.x - margin.top, width, height])
            // .attr('viewBox', [-240, 0, 846, 10])
            .tween('resize', window.ResizeObserver ? null : () => () => svg.dispatch('toggle'))
          // Update the nodes…
          const node = gNode.selectAll('g')
            .data(nodes, d => d.id)
          // Enter any new nodes at the parent's previous position.
          const nodeEnter = node.enter().append('g')
            .attr('transform', () => `translate(${source.y0},${source.x0})`)
            .attr('fill-opacity', 0)
            .attr('stroke-opacity', 0)
            .on('click', d => {
              d.children = d.children ? null : d._children
              update(d)
            })
          nodeEnter.append('circle')
          // .attr('class', 'node')
          // .attr('r', 1e-6)
          // .style('fill', function (d) {
          //   return d._children ? '#c9e4ff' : '#fff'
          // })
            .attr('r', 10)
            .attr('fill', d => d._children ? '#c9e4ff' : '#fff')
            //  .style('fill', function (d) {
            //           return d._children ? '#c9e4ff' : '#fff'
            //         })
            .attr('stroke-width', 2)
            .attr('stroke', '#c9e4ff')
          nodeEnter.append('text')
            .attr('dy', '0.31em')
            // .attr('x', d => d._children ? -6 : 6)
            .attr('x', d => d._children ? -14 : 14)
            .attr('text-anchor', d => d._children ? 'end' : 'start')
            .text(d => d.data.name)
            .clone(true).lower()
            .attr('stroke-linejoin', 'round')
            .attr('stroke-width', 3)
            .attr('stroke', 'white')
          // Transition nodes to their new position.
          const nodeUpdate = node.merge(nodeEnter).transition(transition)
            .attr('transform', d => `translate(${d.x},${d.y})`)
            // .attr('r', 10)
            // .style('fill', function (d) {
            //   return d._children ? '#c9e4ff' : '#fff'
            // })
            // .attr('cursor', 'pointer')
            .attr('fill-opacity', 1)
            .attr('stroke-opacity', 1)
          console.log(nodeUpdate) // eslint-disable-line
          // Transition exiting nodes to the parent's new position.
          const nodeExit = node.exit().transition(transition).remove()
            .attr('transform', () => `translate(${source.y},${source.x})`)
            .attr('fill-opacity', 0)
            .attr('stroke-opacity', 0)
          console.log(nodeExit) // eslint-disable-line
          // Update the links…
          const link = gLink.selectAll('path')
            .data(links, d => d.target.id)
          // Enter any new links at the parent's previous position.
          const linkEnter = link.enter().append('path')
            .attr('d', () => {
              const o = { x: source.x0, y: source.y0 }
              return diagonal({ source: o, target: o })
            })
          // Transition links to their new position.
          link.merge(linkEnter).transition(transition)
            .attr('d', diagonal)
          // Transition exiting nodes to the parent's new position.
          link.exit().transition(transition).remove()
            .attr('d', () => {
              const o = { x: source.x, y: source.y }
              return diagonal({ source: o, target: o })
            })
          // Stash the old positions for transition.
          root.eachBefore(d => {
            d.x0 = d.x
            d.y0 = d.y
          })
        }
        update(root)
      },
      deleteListFn (i) {
        that.data.component.splice(i, 1)
        that.focusIndex = i === 0 && that.data.component.length > 0 ? i : i - 1
      },
      saveFn () {
        // let k = ''
        // let e = document.getElementsByTagName('input')
        // for (var i = 0; i < e.length; i++) {
        //   if (e[i].getAttribute('id') === 'testing') {
        //     k += e[i].value
        //   }
        // }
        // // window.alert(k)
        // var all = JSON.stringify(that.data.component)
        // var blob1 = new Blob([all], {type: 'text/plain;charset=utf-8'})
        // FileSaver.saveAs(blob1, 'pageall.json')
        let n = document.getElementById('tagmanager').value
        let o = document.getElementById('titlearea').value
        let m = document.getElementById('intro').value
        var FileSaver = require('file-saver')
        let type = 'startnode'
        let data = {
          tag: n,
          nodetype: type,
          intro: m,
          title: o
        }

        var content = JSON.stringify(data)
        var blob = new Blob([content], {type: 'text/plain;charset=utf-8'})
        FileSaver.saveAs(blob, 'pageinfo.json')
        // window.alert(e)
      },
      addLangFn () {
        let value = that.defaultLang
        if (that.editableTabs.indexOf(value) > -1) {
          this.$message({
            type: 'warning',
            message: 'Passage：' + value + 'is already added！'
          })
        } else {
          that.editableTabs.push(value)
          that.tabLang = value
          that.addLangDataFn(value)
        }
        that.addLangVisible = false
      },
      addLangDataFn (value) {
        let code = that.langCode[that.langList.indexOf(value)]
        that.data.component.map((i) => {
          let li = {
            language: code,
            title: '',
            condition: [{
              condition_id: 1,
              description: 'Condition1'
            }]
            // line_condition: {
            //   line_value: 1,
            //   line_end_value: 5,
            //   line_tag: '',
            //   line_end_tag: ''
            // },
            // text_condition: ''
          }
          i.content.push(li)
          return i
        })
        that.data.name.push({
          componentnaire_name: '',
          desc: '',
          language: code
        })
      },
      handleTabsEdit (targetName, action) {
        if (action === 'add') {
          that.addLangVisible = true
        }
        if (action === 'remove') {
          that.$confirm('Delete: ' + targetName + '？', {
            title: ' ',
            confirmButtonText: 'Yes',
            cancelButtonText: 'Cancel',
            type: 'warning',
            closeOnClickModal: false,
            beforeClose: (action, instance, done) => {
              let closeFn = () => {
                instance.confirmButtonLoading = false
                instance.confirmButtonText = 'Yes'
              }
              if (action === 'confirm') {
                let tabs = that.editableTabs
                let activeName = that.tabLang
                if (activeName === targetName) {
                  tabs.forEach((tab, index) => {
                    if (tab === targetName) {
                      let nextTab = tabs[index + 1] || tabs[index - 1]
                      if (nextTab) {
                        activeName = nextTab
                      }
                    }
                  })
                }
                that.tabLang = activeName
                that.editableTabs = tabs.filter(tab => tab !== targetName)
                closeFn()
                done()
              } else {
                closeFn()
                done()
              }
            }
          }).then(() => {
          }).catch(() => {
          })
        }
      }
    },
    // watch: {
    //   dataa() {
    //     console.log('this', that.tree_data);
    //     that.drawGraph
    //   }
    // }
  }
</script>
