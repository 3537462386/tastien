# 塔斯汀小程序模仿项目

- 界面模仿采用markman做标记
    1. 没有设计稿，1:1还原
    2. 拍屏得到小程序截图
    3. 使用在线大小[转换工具](https://www.gaitubao.com/)，将图片改为宽750,以后在写wxss时，可直接量取，得到像素，因为小程序以750rpx作为设计稿标准大小帮我们自动适配，很好用。
    4. 现在使用[markman](http://www.getmarkman.com/) 测量并标注，以后在工作时，设计师会搞好设计稿。

- 项目配置在根目录app.json
  - 隐藏并定制navigationBar
    "navigationStyle": "custom"
  - 启动定位功能
  
- 使用了BEM 国际css命名规范
  tst_banners  广告位 Block
  tst_banners__img  Element

- css 技巧
  1. 能不用定位就不要用定位
    脱离文档流
  2. 移动端多用弹性布局 