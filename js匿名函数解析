<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
 <head>
  <title> new document </title>
  <meta name="generator" content="editplus" />
  <meta name="author" content="" />
  <meta name="keywords" content="" />
  <meta name="description" content="" />

<style type="text/css">

        .l{
            width:10px;
            height:10px;
            border:2px solid #000000;
            border-radius:10px;
            display: inline-block;
		}
	</style>

 </head>

 <body>
  <ul class="u" style=>
<li class="l"></li>
<li class="l"></li>
<li class="l"></li>
</ul>

<script>
//匿名函数在js中使用很多，需要深度理解
var log = document.querySelectorAll('.l');
for(i=0;i<log.length;i++){
console.log("i0=",i);
//所以如果要让i和我们的鼠标绑定事件一致只能用一个内参来定义
(function(i){	
log[i].onmouseover=function(){
var j=0;
for(j=0;j<log.length;j++){
log[j].style.background= '#00ff33';
console.log("j=",j);
}
log[i].style.background= '#ff0033';
console.log("i1=",i);//i在这里已经变成一个内变量了
}
})(i);//和do(i)的意思一样调用一次
};
console.log("i2=",i);//这里已经变成3了，但是我们想让i一直和鼠标事件绑定
</script>
 </body>



</html>
