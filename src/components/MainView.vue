<template>
    <el-container>
      <el-header>Header</el-header>

      <el-container>
        <el-aside width="200px" style="height: 800px;">
          <ul class="infinite-list" v-infinite-scroll="load" >
            <li v-for="i in count" v-bind:key="i" class="infinite-list-item">
              <img width="100" height="60" src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg?cs=srgb&dl=beautiful-beauty-blue-414612.jpg&fm=jpg">
            </li>
          </ul>
        </el-aside>
        <el-container>
          <el-main>

            <el-row>
              <el-col :span="16">
                <video width="600" height="480" src="https://n10-pl-agv.autohome.com.cn/video-1/E3BD4E39114FD258/2019-06-19/0ED55E080967FE43-400.mp4">
                </video>
              </el-col>
              
              <el-col :span="8">
                <el-card class="box-card">
                  <div slot="header" class="clearfix">
                    <span>卡片名称</span>
                    <el-button style="float: right; padding: 3px 0" type="text">操作按钮</el-button>
                  </div>
                  <div>
                    <i class="el-icon-edit"></i>
                    <i class="el-icon-share"></i>
                    <i class="el-icon-delete"></i>
                  </div>
                  <div>
                    <i class="el-icon-edit"></i>
                    <i class="el-icon-share"></i>
                    <i class="el-icon-delete"></i>
                  </div>
                  <div>
                    <i class="el-icon-edit"></i>
                    <i class="el-icon-share"></i>
                    <i class="el-icon-delete"></i>
                  </div>
                  <div>
                    <i class="el-icon-edit"></i>
                    <i class="el-icon-share"></i>
                    <i class="el-icon-delete"></i>
                  </div>
                </el-card>
              </el-col>

            </el-row>

          </el-main>
          <el-footer style="height: 180px;">
            <div class="track-container"><div class="vhc-scroll-container"><div class="vhc-scroll-content" style="width: 2500px;"><div class="marker-line" style="display: block;"></div> <div class="vhc-scroll-wrapper"><div class="scroll-placeholder" style="width: 0px;"></div> <div class="scale" style="width: 126.312px;"><span>00:00:00:00</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:04:22:03</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:08:44:07</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:13:06:10</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:17:28:14</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:21:50:18</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:26:12:21</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:30:35:00</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:34:57:03</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:39:19:07</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:43:41:11</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:48:03:14</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:52:25:18</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>00:56:47:21</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>01:01:10:00</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>01:05:32:04</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>01:09:54:07</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>01:14:16:11</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>01:18:38:14</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div><div class="scale" style="width: 126.312px;"><span>01:23:00:18</span> <div class="sub-scales"><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i><i></i></div></div></div> <div class="vhc-extra"><div><div class="tracks"><div class="track" style="height: 30px;"> <div class="drop-placeholder" style="width: 0px; display: none;"></div> <div class="current-duration" style="display: none;">
                    
                </div></div><div class="track" style="height: 30px;"> <div class="drop-placeholder" style="width: 0px; display: none;"></div> <div class="current-duration" style="display: none;">
                    
                </div></div><div class="track" style="height: 70px;"><div class="draggable-target"><div class="draggable"><div class="draggable resizer" style="transform: translateX(-12px); background-color: transparent;"><div class="resizer-l"></div></div> <div class="draggable resizer" style="transform: translateX(1206px); background-color: transparent;"><div class="resizer-r"></div></div> <div data-track-item-uid="2_1" class="segment" style="transform: translateX(0px); background-color: transparent; width: 1214px;"><div class="segment-view"><div class="track-item-preview" style="background-image: url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00001.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00003.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00005.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00007.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00009.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00012.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00014.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00016.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00018.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00020.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00023.jpg&quot;), url(&quot;//cdn.zenvideo.cn/assets/youtube/GxEEqVPiF8E/thumbnail-00025.jpg&quot;); background-position: 0px 0px, 106.057px -1280px, 212.114px -2560px, 318.171px -3840px, 424.229px -5120px, 530.286px 0px, 636.343px -1280px, 742.4px -2560px, 848.457px -3840px, 954.514px -5120px, 1060.57px -64px, 1166.63px -1344px; background-size: 106.057px; background-repeat: no-repeat; height: 64px;"><!----> <div class="wave-wrapper"><!----> <canvas class="wave canvas_2_1" width="1214" height="20"></canvas></div> <div class="processingStatus" style="display: none;"></div> <div class="black-background" style="display: none;"></div></div> <div title="武林外传 79 李大嘴遭遇老情敌 杨蕙兰展开新人生" class="track-item-name"><!---->武林外传 79 李大嘴遭遇老情敌 杨蕙兰展开新人生
                  <span></span> <span class="percentage failed"></span></div> <!----> <!----><div class="resize-sensor" style="position: absolute; left: 0px; top: 0px; right: 0px; bottom: 0px; overflow: hidden; z-index: -1; visibility: hidden;"><div class="resize-sensor-expand" style="position: absolute; left: 0; top: 0; right: 0; bottom: 0; overflow: hidden; z-index: -1; visibility: hidden;"><div style="position: absolute; left: 0px; top: 0px; transition: all 0s ease 0s; width: 100000px; height: 100000px;"></div></div><div class="resize-sensor-shrink" style="position: absolute; left: 0; top: 0; right: 0; bottom: 0; overflow: hidden; z-index: -1; visibility: hidden;"><div style="position: absolute; left: 0; top: 0; transition: 0s; width: 200%; height: 200%"></div></div></div></div> <!----> <!----></div> <!----></div></div> <!----> <div class="current-duration" style="display: none;">
                    
                </div></div><div class="track" style="height: 30px;"> <div class="drop-placeholder" style="width: 0px; display: none;"></div> <div class="current-duration" style="display: none;">
                    
                </div></div><div class="track" style="height: 30px;"> <div class="drop-placeholder" style="width: 0px; display: none;"></div> <div class="current-duration" style="display: none;">
                    
                </div></div></div></div></div> <div class="draggable"><div class="pointer" style="transform: translateX(25.0364px);"><i class="iconfont"></i></div></div> <div class="adsorbed-mark" style="opacity: 0; transform: translateX(-1px);"></div></div></div></div>
          </el-footer>
        </el-container>
      </el-container>

    </el-container>

</template>
<script>
  export default {
    data: () => ({
      items: [
        {title: "iii1"},
        {title: "iii0"},
        {title: "iii2"},
      ],
      count: 0,
      lorem: `Lorem ipsum dolor sit amet, mel at clita quando. Te sit oratio vituperatoribus, nam ad ipsum posidonium mediocritatem, explicari dissentiunt cu mea. Repudiare disputationi vim in, mollis iriure nec cu, alienum argumentum ius ad. Pri eu justo aeque torquatos.`
    }),
    methods: {
      load () {
        this.count += 2
      }
    }
  }
</script>
<style>
  .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }
  
  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 100px;
  }

  .el-aside ul {
    list-style-type: none;
    padding-inline-start: 0px;
  }
  
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    /*line-height: 160px;*/
  }

  .track-container {
      width: 100%;
      overflow: auto;
      flex: 1;
      position: relative;
  }

  .vhc-scroll-container {
      overflow: auto;
      flex: 1;
      height: 100%;
  }

  .vhc-scroll-container .vhc-scroll-content {
      height: 100%;
      min-width: 100%;
      position: relative;
      overflow: hidden;
      display: flex;
      flex-direction: column;
  }

  .vhc-scroll-container .vhc-scroll-content .vhc-scroll-wrapper {
      height: 44px;
      border-bottom: 1px solid #dee1e8;
      white-space: nowrap;
      font-size: 0;
  }

  .vhc-scroll-container .vhc-scroll-content .vhc-scroll-wrapper .scroll-placeholder {
      height: 44px;
      display: inline-block;
  }

  .vhc-scroll-container .vhc-scroll-content .vhc-scroll-wrapper .scale {
      position: relative;
      height: 44px;
      display: inline-block;
  }

  .vhc-scroll-container .vhc-scroll-content .vhc-scroll-wrapper .scale span {
      position: absolute;
      left: 0;
      bottom: 10px;
      color: #606266;
      font-size: 10px;
  }

  .vhc-scroll-container .vhc-scroll-content .vhc-scroll-wrapper .scale .sub-scales {
      display: flex;
      justify-content: space-between;
      position: absolute;
      width: 100%;
      bottom: 0;
  }

  .vhc-scroll-container .vhc-scroll-content .vhc-scroll-wrapper .scale .sub-scales i:first-child {
      border-left-color: #606266;
      height: 8px;
  }

  .vhc-scroll-container .vhc-scroll-content .vhc-scroll-wrapper .scale .sub-scales i{
    border-left: 1px solid #dee1e8;
    width: 0;
    height: 4px;
  }
  
</style>
