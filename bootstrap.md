                                                   Bootstrap
1.为什么使用bootstrap?
答：移动设备优先：自 Bootstrap 3 起，框架包含了贯穿于整个库的移动设备优先的样式。
    响应式设计：Bootstrap 的响应式 CSS 能够自适应于台式机、平板电脑和手机。
Bootstrap 提供了一套响应式、移动设备优先的流式网格系统，随着屏幕或视口（viewport）尺寸的增加，系统会自动分为最多12列。
2.基本的网络结构
 <div class="container">
     <div class="row">
        <div class="col-xs-2"></div>/*在手机屏幕上分为两列，第一列占12列中的两列，第二列占12列中的10列*/
        <div class="col-xs-10"></div>
     </div>
     <div class="row">
        ...
     </div>
 </div>
   "col-xs-*":超小设备手机（<768px）    "col-sm-*":小型设备平板电脑（>=768px）
   "col-md-*":中型设备台式电脑（>=992px）  "col-lg-*":大型设备台式电脑（>=1200px）
3.排版
   (1)引导主体副本  <p class="lead">给段落添加强调文本</p>  /*类名为lead,将得到更大更粗、行高更高的文本*/
   (2)强调  <small>本行内容是在标签内</small>   /*设置文本为父文本大小的 85%*/
            <strong>本行内容是在标签内</strong>  /*设置文本为更粗的文本*/
            <p class="text-left">向左对齐文本</p>
            <p class="text-center">居中对齐文本</p>
            <p class="text-right">向右对齐文本</p>
            <p class="text-muted">本行内容是减弱的</p>   /*提示，使用浅灰色（#999）*/
            <p class="text-primary">本行内容带有一个 primary class</p>   /*主要，使用蓝色（#428bca）*/
            <p class="text-success">本行内容带有一个 success class</p>   /*成功，使用浅绿色(#3c763d)*/
            <p class="text-info">本行内容带有一个 info class</p>    /*通知信息，使用浅蓝色（#31708f）*/
            <p class="text-warning">本行内容带有一个 warning class</p>   /*通知信息，使用浅蓝色（#31708f）*/
            <p class="text-danger">本行内容带有一个 danger class</p>   /*危险，使用褐色（#a94442）*/
   (3)列表    <h4>内联列表</h4>
              <ul class="list-inline">
                  <li>Item 1</li>
                  <li>Item 2</li>
                  <li>Item 3</li>
                  <li>Item 4</li>
              </ul>
4.按钮
 .btn   /*为按钮添加样式*/
 .active /*按钮被点击*/
 .disabled  /*禁止按钮*/
 .btn-default  /*默认/标准按钮*/
5.图片
   .img-rounded：添加 border-radius:6px 来获得图片圆角。
   .img-circle：添加 border-radius:50% 来让整个图片变成圆形。
   .img-thumbnail：添加一些内边距（padding）和一个灰色的边框。
   .img-responsive:图片响应式（将很好地扩展到父元素）
6.导航元素：以带有class为nav的无序列表开始
  （1）标签式导航
 <ul class="nav nav-tabs">   /*标签式的导航*/
    <li class="nav-item">    /*表示li是导航*/
       <a href="#" class="nav-link active">Active</a>  /*表示是导航，active是选中*/
    </li>
 </ul>
  
  （2）丸状导航
 <ul class="nav nav-pills"> 
   <li class="nav-item">
     <a href="#" class="nav-link active">Active</a>
   </li>
 </ul>
  （3）堆叠丸状导航
 <ul class="nav nav-pills nav-stacked">
   <li class="nav-item">
     <a href="#" class="nav-link active">Active</a>
   </li>
 </ul>
7.导航栏:在<nav>标签中添加class为.navbar
(1)默认的导航栏
   向<nav>标签中添加.navbar-default:默认的导航栏
   添加带有.nav navbar-nav的无序列表:向导航栏添加链接
   向<div>元素添加一个标题class为navbar-header,内部包含了带有class为navbar-brand的<a>元素，会让文本看起来更大一号
（2）响应式的导航栏
   折叠起来的导航栏实际上是一个带有 class .navbar-toggle 及两个 data- 元素的按钮。第一个是 data-toggle，用于告诉 JavaScript 需要对按钮做什么，第二个是 data-target，指示要切换到哪一个元素。三个带有 class .icon-bar 的 <span> 创建所谓的汉堡按钮。
（3）导航栏中的表单
     .navbar-form class。这确保了表单适当的垂直对齐和在较窄的视口中折叠的行为










