<!DOCTYPE html>
<html>
<head>
<title>clock</title>
<style type="text/css">
h1{
text-align:center;
font-family:vardana;
/*margin-top:250px;*/

/*align-items:center;*/

}
</style>
</head>
<body onload="showTime()">
<h1>manoj</h1>
</body>
<script type="text/javascript">

function showTime(){
setTimeout(showTime,1000)
var d=new Date()
var h=d.getHours()
var m=d.getMinutes()
var s=d.getSeconds()
var time=h+":"+m+":"+s+" "+"PM"

//document.write(time)
document.getElementsByTagName('h1').innerText=time;



}

</script>
</html>
