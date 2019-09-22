# html-file
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1" charset="utf-8">
<title>登录界面</title>
</head>

<body background="D:\2.jpeg" style="background-repeat:no-repeat; background-size:100% 100%; background-attachment: fixed;">
    <center>
    <br><br><br><br><br><br><br><br><br><br><br>
    <h1 style="color:white">登入</h1>
    <br>
    <form name="loginForm" action="login_check.jsp" method="post">   
          <table Border="0" >
                    <tr >
                    
                        <td>账号：</td>
                        <td><input type="text" name="username"></td>
                    </tr>
                    <tr>
                        <td>密码：</td>
                        <td><input type="password" name="password">
                        </td>
                    </tr>
               </table>
               <br>
                <input type="submit" value="登录" style="color:black">
                <input type="submit" value="注册" style="color:black">
    </form>
    </center>

</body>
</html>
