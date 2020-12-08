# Bootstrap 学习记录

* 网格布局
* 列的排序 col-md-push-* col-md-pull-*
* 嵌套布局
* 偏移列 col-md-offset-*
* 显示与隐藏的响应式工具类 visible-* hidden-* 

#
* 导航栏 
  * 夜间 navbar-inverse
  * 默认 navbar-default
* 固定导航栏  
  * navbar-fixed-top 
  * navbar-fixed-bottom
  * navbar-static-top 随页面的滚动而滚动  
* 响应式导航栏 
  * button data-target="#xxxx" data-toggle="collapse"
  * nav id="xxxx"

# 
* 对话框
  * modal-dialog
  * 布局 modal-header、modal-body、modal-footer
  * 大小 modal-sm、modal-lg
* 打开 
  * button data-toggle="modal" data-target="#login-modal"
  * div .modal #login-modal
* 关闭
  * button data-dismiss="modal"
* 打开过渡动画
  * div .modal.fade
* 暗色背景
  * data-backdrop = "false"
  * javascript: $(function(){$('#login-modal').modal(({show: false, backdrop: false}))})
* 调用同源页面
  * remote
* 方法
  * javascript: $("#login-modal").modal("show")
  * javascript: $("#login-modal").modal("hide")
  * javascript: $("#login-modal").modal("toggle")
* 事件
  * show、shown、hide、hidden、loaded
  * javascript: $("#login-modal").on("show.bs.modal", function(){}) 


# 
* 幻灯片 carousel     
  * 基础 data-ride="carousel"
  * 左滑动 slide
  * 上一页，下一页 
    * a href="#slideshow" data-slide="prev" class="left carousel-control"
    * a href="#slideshow" data-slide="next" class="right carousel-control"
  * 圆点
    * li data-target="#slideshow" data-slide-to="0"
  
# 
* 按钮组 button
* type button
* class.btn
  * .btn-default 默认
  * .btn-success 确定
  * .btn-primary primary
  * .btn-danger 危险
  * .btn-info   信息
  * .btn-warning   警示
  * .btn-link   链接  