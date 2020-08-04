<!-- 校准 -->
<template>
  <div class="calibration">
    <div class="title">2.安装</div>
    <div class="calibrationone"><img src="../../assets/img/device/calibration2.png" alt=""></div>
    <div class="progress">将门（窗）关上，将设备贴在门（窗）任意位置</div>
    <div class="next">开始校准</div>
  </div>
</template>

<script>
export default {
  name: "calibrationone",
  data () {
    return {

    };
  },

  components: {},

  mounted: {},

  methods: {}
}

</script>
<style scoped>
  .calibration{
    width: 100%;
    min-height: 100%;
    background: #fff;
    padding-top: 58px;
  }
  .title{
    color: #303030;
    font-size: 18px;
    text-align: center;
  }
  .calibrationone{
    margin-top: 33.5px;
    text-align: center;
  }
  .calibrationone>img{
    width: 90px;
    height: auto;
  }
  .progress{
    font-size: 15px;
    color: #303030;
    text-align: center;
    margin: 20px 0 118px;
  }
  .next{
    width: 163px;
    height: 45px;
    line-height: 45px;
    text-align: center;
    color: #146DE5;
    font-size: 15px;
    border: 2px solid #146DE5;
    margin: auto;
    border-radius: 22.5px;
  }
</style>