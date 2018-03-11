# test5
#饥人谷习题预览
<html>

<head>
<meat charset="UTF-8">
<title></title>
</head>

<body>
	<form action="/abc" method="post">
	<div class="username">
		<label>姓名：</label>
		<input type="text" name="username" placeholder="用户名">
	</div>

	<div class="password">
		<label>密码：</label>
		<input type="password" name="passname">
	</div>

	<div class="sex">
		<label>性别：</label>
		<input type="radio" name="sex" value="男">男
		<input type="radio" name="sex" value="女">女
	</div>

	<div class="sexual orientation">
		<label>取向：</label>
		<input type="radio" name="sexual orientation" value="男">男
		<input type="radio" name="sexual orientation" value="女">女
	</div>

	<div class="hobby">
		<label>爱好：</label>
		<input type="checkbox" name="hobby" value="dota">dota
		<input type="checkbox" name="hobby" value="旅游">旅游
		<input type="checkbox" name="hobby" value="宠物">宠物
	</div>

	<div class="textarea">
		<label>评论:</label>
		<textarea name="discuss">
				ddd
		</textarea>
	</div>

	<div class="select">
		<label>我的Car:</label>
		<select name="brand">
			<option value="Benz">奔驰</option>
			<option value="BMW">宝马</option>
			<option value="Volvo">沃尔沃</option>
			<option value="Sabo" selected>萨博</option>
	</div>
	
	<input type="submit" value="提交">

	</form>
</body>
</html>
