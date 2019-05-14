<html>
 <head>
  <script type="application/javascript">
function draw() {
   var canvas = document.getElementById('canvas');
if (canvas.getContext) {
  var ctx = canvas.getContext('2d');
ctx.beginPath(); // 开始路径绘制
ctx.moveTo(20, 20); // 设置路径起点，坐标为(20,20)
ctx.lineTo(100, 20); // 绘制一条到(200,20)的直线
ctx.lineTo(200,200); // 绘制一条到(200,20)的直线
// ctx.lineTo(20, 20); // 绘制一条到(200,20)的直线
ctx.closePath()
ctx.lineWidth = 5.0; // 设置线宽
ctx.strokeStyle = '#CC0000'; // 设置线的颜色
ctx.stroke(); // 进行线的着色，这时整条线才变得可见
}
  
}
  </script>
 </head>
 <body onload="draw();" style="margin: 0;padding: 0">
   <canvas id="canvas" width="200" height="200" ></canvas>
   <input type="" name="">
   123
 </body>
</html> 
