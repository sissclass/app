<template>
  <view class="content">
    <view style="display:flex;align-item:center;flex:1;width:100%">
      <uni-icons type="search" size="30"></uni-icons>
      <uni-easyinput
        v-model="goods"
        placeholder="大家都在搜“520情人节礼物”"
      ></uni-easyinput>
      <uni-icons type="chat" size="30"></uni-icons>
    </view>
    <view>
      <text class="title">{{ title }}</text>
    </view>
  </view>
</template>

<script>
export default {
  data() {
    return {
      title: 'Hello',
      goods: '',
    }
  },
  onLoad() {},
  methods: {
    aa() {},
  },
}
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.logo {
  height: 200rpx;
  width: 200rpx;
  margin: 200rpx auto 50rpx auto;
}

.text-area {
  display: flex;
  justify-content: center;
}

.title {
  font-size: 36rpx;
  color: #8f8f94;
}
</style>
