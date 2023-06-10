
<!DOCTYPE html>
<html>
<head>
<title>倒计时跳转</title>
<h1>请注意 本金幣號 只限用於購買帖子 不能發帖子發帖獲取威望米粒，不然會被封號。如有人違規發帖被封，只能下個月再重新提供號。金幣號數量有限，且用且珍惜</h1>
</head>
<body>

    <div id="msg"></div>
    <script>
        var times=2;
        function test(){
            document.getElementById("msg").innerHTML="页面将在"+times+"后跳转";
            times-=1;
            if(times<=0){
                window.clearInterval(doTEST);
                window.location.href="http://y6e.xyz/zu/2048.html";
            }
        }
        var doTEST;
        window.clearInterval(doTEST);
        doTest=window.setInterval("test()",1000);
    </script>

</body>
</html>
