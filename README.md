<html>
<head>
  <meta charset="utf-8">
  <title>员工管理系统登录界面</title>
  <style>
        .form{
            width:400px;
            height: 400px;
            padding-top:10px;
            margin: 50px auto;
            background-color:rgba(255,255,255,0.2);
            border-radius: 20px;
            border: 3px solid white;
        }
        .text {
            font-size:20px;
            color:white;
        }
        .option-text {
            font-size:15px;
            color:white;
        }  
        .button1 {
            -webkit-transition-duration: 0.4s;
            transition-duration: 0.4s;
            padding: 16px 60px;
            text-align: center;
            background-color: white;
            color: black;
            border: 2px solid white;
            border-radius:5px;
        }
        .button1:hover {
            background-color: black;
            color: white;
        }
        .input {
            -webkit-transition-duration: 0.4s;
            transition-duration: 0.4s;
            padding: 10px 30px;
            text-align:left;
            background-color: white;
            color: black;
            border: 2px solid white;
            border-radius:5px;
        }
        .input:hover {
            background-color: black;
            color: white;
        }
        .img{
            border:solid 3px white;
            border-radius: 20px;
        }
        </style>
</head>

<body background="F:\2.jpg">
<center>
  <br><br><br><br><br><br><br><br><br>
  <br>
  <form class="form" name="loginForm" action="login_check.jsp" method="post">
    <h1 style="color:white">员工管理系统</h1>
    <br>
    <table Border="0" >
      <tr >
        <td class="text">账号：</td>
        <td><input class="input" type="text" name="username" maxlength="10"></td>
      </tr>
      <tr>
        <td class="text">密码：</td>
        <td><input class="input" type="password" name="password" maxlength="16">
        </td>
      </tr>
    </table>
    <font class="text">请输入验证码：</font><input class="input" type="text" name="Verificationcode" size="10" maxlength="4">
    <br><br>
    <img src="F:\2.jpg" width="300" height="50" class="img"><br><br>
    <button class="button1">登入</button>
    <button class="button1">重置</button>
  </form>
</center>
</body>
</html>



<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>员工管理系统-管理员</title>
	<style type="text/css">
		body{
			padding-top:50px;
			width: 1600px;
			height: 800px;
			margin:auto auto;
		}
		.table{
			border:3px solid white; 
			border-radius: 20px;
		}
		tr,td{
			text-align: center;
		}
		.tb1{
			width: 1600px;
			height: 100px;
			background-color:rgba(255,255,255,0.3);
			border-radius: 20px;
			border: 2px solid white;
			color: white;
		}
		.tb2{
			width: 400px;
			height: 50px;
			background-color:rgba(255,255,255,0.6);
			border-radius: 20px;
			border: 2px solid white;
            -webkit-transition-duration: 0.4s;
            transition-duration: 0.4s;
            color: black;
        }
        .tb2:hover {
            background-color: white;
            color: black;
        }	
		.tb3{
			height: 650px;
			background-color:rgba(255,255,255,0.4);
			border-radius: 20px;
			border: 2px solid white;
		}
		.tb4{
			height: 650px;
			background-color:rgba(255,255,255,0.6);
			border-radius: 20px;
			border: 2px solid white;
		}
		.tb5{
			height: 540px;
			width: 400px;
			background-color:rgba(255,255,255,0.5);
			border-radius: 20px;
			border: 1px solid white;
		}
		.tb6{
			height: 90px;
			width: 400px;
			background-color:rgba(255,255,255,0.5);
			border-radius: 20px;
			border: 1px solid white;
		}
		button{
			text-align: center;
			padding: 5px 25px;
			background-color:rgba(255,255,255,0.6);
            color: black;
            border: 2px solid white;
            border-radius:5px;
		}
		a:link {text-decoration:none;color:black;}
	</style>
</head>
<body background="F:\2.jpg">
	<p align=right><button>管理账号</button>&nbsp<button>注销登入</button></p>
	<table class="table" border="1" cellspacing="2" cellpadding="0">
		<tr>
			<td colspan="4" class="tb1"><h1>员工管理系统-管理员</h1></td>
		</tr>
		<tr>
			<td class="tb2"><a href="#news1">部门列表</a></td>
			<td class="tb2"><a href="#news2">新增部门</a></td>
			<td class="tb2"><a href="#news3">修改部门</a></td>
			<td class="tb2"><a href="#news3">删除部门</a></td>
		</tr>
		<tr>
			<td class="tb3">
				<table>
					<tr>
						<td class="tb5">1</td>
					</tr>
					<tr>
						<td class="tb6">首页&nbsp上一页&nbsp下一页&nbsp尾页</td>
					</tr>
				</table>
			</td>
			<td colspan="3" class="tb4">员工详细信息...</td>
		</tr>
	</table>
</body>
</html>



<html>
<head>
  <meta charset="utf-8">
  <title>员工管理系统-管理账号</title>
  <style>
        .form{
            width:400px;
            height: 400px;
            padding-top:10px;
            margin: 50px auto;
            background-color:rgba(255,255,255,0.2);
            border-radius: 20px;
            border: 3px solid white;
        }
        .text {
            font-size:20px;
            color:white;
        }
        .button1 {
            -webkit-transition-duration: 0.4s;
            transition-duration: 0.4s;
            padding: 15px 150px;
            text-align: center;
            background-color: white;
            color: black;
            border: 2px solid white;
            border-radius:5px;
        }
        .button1:hover {
            background-color: black;
            color: white;
        }
        .input {
            -webkit-transition-duration: 0.4s;
            transition-duration: 0.4s;
            padding: 10px 30px;
            text-align:left;
            background-color: white;
            color: black;
            border: 2px solid white;
            border-radius:5px;
        }
        .input:hover {
            background-color: black;
            color: white;
        }
        </style>
</head>

<body background="F:\2.jpg">
<center>
  <br><br><br><br><br><br><br><br><br>
  <br>
  <form class="form" name="loginForm" action="login_check.jsp" method="post">
    <h1 style="color:white">管理账号</h1>
	<p><h3 style="color:white">修改密码</h3>
    <br>
    <table Border="0" >
      <tr >
        <td class="text">账号：</td>
        <td><input class="input" type="text" name="username" maxlength="10"></td>
      </tr>
      <tr>
        <td class="text">密码：</td>
        <td><input class="input" type="password" name="password" maxlength="16">
        </td>
      </tr>
      <tr >
        <td class="text">新密码：</td>
        <td><input class="input" type="password" name="new_password" maxlength="16"></td>
      </tr>
    </table>
    <br>
    <button class="button1">确定</button>
  </form>
</center>
</body>
</html>
