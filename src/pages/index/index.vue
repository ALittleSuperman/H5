<template>
  <view class="index">
    <AtTabBar
      :tabList=tabList
    />
  </view>
</template>

<script>
import { AtTabBar } from 'taro-ui'
export default {
  name: 'Index',
  data() {
    return {
      tabList:[
        { title: '待办事项', text: 8 },
        { title: '拍照' },
        { title: '通讯录', dot: true }
      ]
    }
  },
  comments:{
    AtTabBar,
  }
}
</script>

<style>
</style>
