<script>
export default {
  onLaunch: function() {
    console.log('App 启动')
  },
  onShow: function() {
    console.log('App 显示')
  },
  onLoad() {
    console.log('页面加载完成')
  },
  onHide: function() {
    console.log('App Hide')
  },
}
</script>

<style>
/*每个页面公共css */
@import './styles/base.wxss';
@import './styles/iconfont.css';
</style>
