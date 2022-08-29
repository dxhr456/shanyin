<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <div class="top">
    <img src="./image/top-enlogo.png" alt="" />
    <img src="./image/top-cnlogo.png" alt="" />
    <p class="solgen">免费送货　让打印更轻松　价格更低</p>
    <a class="link" href="#">请登录</a>
  </div>
  <div class="tips">
    一张纸也送哦。目前仅支持宿迁市城区免费送货。如果您是外地客户或者需要寄快递的，我们统一发顺丰快递到付快递费。
  </div>
  <div class="buiness">
    <div class="buiness-title">
      <ul>
        <li class="li-ative">
          <a class="a-ative" href="">数码快印</a>
        </li>
        <li class="li">
          <a class="a" href="">画册制作</a>
        </li>
        <li class="li">
          <a class="a" href="">标书装订</a>
        </li>
        <li class="li">
          <a class="a" href="">文本装订</a>
        </li>
        <li class="li">
          <a class="a" href="">喷绘写真</a>
        </li>
        <li class="li">
          <a class="a" href="">照片冲印</a>
        </li>
        <li class="li">
          <a class="a" href="">横幅锦旗</a>
        </li>
      </ul>
    </div>
    <div class="fenlei">
      <div class="tel-box">
        <sapn class="color-box"></sapn>
        <div class="title">数码快印报价</div>
        <div style="margin-right: 10px">客服电话：</div>
        <div style="color: red; margin-right: 40px">177 6891 8751</div>
        <div style="margin-right: 10px">客服QQ：</div>
        <div style="color: red">267 847 5217</div>
      </div>
      <div class="paper-bigbox">
        <div class="name-box">
          <p>纸张类型</p>
          <div>普通纸</div>
          <div>128克铜版纸</div>
          <div>157克铜版纸</div>
          <div>200克铜版纸</div>
          <div>150克铜版纸</div>
          <div>300克铜版纸</div>
          <div>250克白卡纸</div>
          <div>250克珠光纸</div>
        </div>
        <div class="name-box">
          <p>成品尺寸</p>
          <div>A6 (105x145mm)</div>
          <div>A5 (145x210mm)</div>
          <div>A4 (210x297mm)</div>
          <div>A3 (297x420mm)</div>
          <div>自定义</div>
          <input class="input-dis" type="text" placeholder="长边（单位mm）" />
          <input class="input-dis" type="text" placeholder="短边（单位mm）" />
        </div>
        <div class="name-box">
          <p>单双面</p>
          <div>单面</div>
          <div>双面</div>
        </div>
        <div class="name-box">
          <p>打印颜色</p>
          <div>黑白</div>
          <div>彩色</div>
        </div>
        <div class="name-box">
          <p>P数</p>
          <input class="input-dis" type="text" placeholder="P数/页数" />
        </div>
        <div class="name-box">
          <p>份数</p>
          <input class="input-dis" type="text" placeholder="份数" />
          <button>计算价格</button>
        </div>
        <div class="name-box">
          <p>价格</p>
          <span class="price">
            <span style="font-size: 20px">￥</span>288.00</span>
        </div>
        <div class="name-box">
          <p>报价详情</p>
          <p class="order-info">
            数码快印 - 200克铜版纸 - A4 (210x297mm) - 双面 - 彩色 - 29P - 10份
          </p>
        </div>
        <div class="name-box" style="margin-left: 20px; margin-bottom: 20px">
          <button style="width: 300px">立即下单</button>
        </div>
      </div>
      <div class="tel-box" style="margin-top: 10px">
        <sapn class="color-box"></sapn>
        <div class="title">上传文件</div>
      </div>
      <div class="file-page">
        <div class="file-win">
          <img style="width: 60px; margin-bottom: 10px" src="./image/UploadFile.png" />
          <div>点击上传文件</div>
        </div>
        <div style="margin-bottom: 20px">
          <div class="file-namebox">
            <div class="file-name">这个今天印刷200份.jpg</div>
            <div class="file-jindubox">
              <div class="file-jindu"></div>
              <div class="file-name">100%</div>
              <img class="img-close" src="./image/close.png">
            </div>
          </div>
        </div>
        <div class="name-box">
          <p>联系方式</p>
          <input class="input-dis" type="text" placeholder="手机号码" />
        </div>
      </div>
      <div class="tel-box" style="margin-top: 10px">
        <sapn class="color-box"></sapn>
        <div class="title">收货信息</div>
      </div>
      <div class="file-page">
        <div class="address-wrap" style="margin-bottom: 20px"></div>
        <div class="name-box">
          <p>收货形式</p>
          <div>免费送货</div>
          <div>自提</div>
          <div>顺丰快递</div>
        </div>
        <div class="add-box">
          <p>收货人信息</p>
          <div class="addinfo-box">
            <img style="width:25px; height:25px; margin-top: -2px" src="./image/name.png">
            <div class="add-info">王宇</div>
            <img style="width:21px; height:21px" src="./image/tel.png">
            <div class="add-info">13072558912</div>
            <img style="width:25px; height:25px; margin-top: -2px" src="./image/add.png">
            <div class="add-info">江苏省宿迁市宿城区恒昌阳光里S1-12号商铺</div>
            <div style="display: flex; cursor: pointer;">
              <img style="width:25px; height:25px; margin-left:80px; margin-top: -2px" src="./image/bianji.png">
              <div class="add-info">更改地址</div>
            </div>
          </div>
        </div>
        <div class="name-box">
          <p>总价格</p>
          <span class="price">
            <span style="font-size: 20px">￥</span>288.00</span>
        </div>
        <div class="name-box" style="margin-bottom:10px">
          <p>备注</p>
          <textarea></textarea>
        </div>
        <div style="margin-left:200px; font-size:16px; color: red; margin-bottom: 40px">注：当备注里面描写了制作要求时，如果和上边所选的制作要求冲突的话，一律按照上方选择的要求制作。</div>
        <div class="name-box" style="margin-left: 180px; margin-bottom: 20px">
          <button style="width: 300px">提交订单</button>
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
</style>
