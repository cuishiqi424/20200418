<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>什么名字好呢</title>
</head><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title>无标题文档</title>
</head>

<body style="background-image:url('images/bk.jpg');"fixed>
<audio src="qfl.mp3" id="v" controls autoplay></audio><br>
<button onclick="fastfoward();">fast word</button>
<button onclick="alert('11111');">按就出1</button>
<button onclick="slowfoward();">slow foward</button>
<button onclick="currenttime();">currenttime</button>
<script>
    function fastfoward(){
        v.playbackRate=2*v.playbackRate;
    }
    function slowfoward(){
        v.playbackRate=0.5*v.playbackRate;
    }
    function currenttime(){
        v.currentTime=50.5;
    }
</script>
</body>
</html>

</html>
