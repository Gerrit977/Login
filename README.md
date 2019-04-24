# Login
Just another repository
<body>
<form name="loginForm" method="post" action="login.php">
<table width="20%" bgcolor="#ffb56a" align="center">

<tr>
<td colspan=4><h2 align="center" style="color:#ffffff;  font-weight:bold;"><font size=5><b> Login Page</b></font></center></td>
</tr>

<tr>
<td>Username:</td>
<td><input type="text" size=28




name="userid"></td>
</tr>

<tr>
<td>Password:</td>
<td><input type="Password" size=28 name="pwd"></td>
</tr>

<tr>


<td ><input type="Reset"></td>
<td><input type="submit" onclick="return check(this.form)" value="Login"></td>
</tr>



</table>
</form>
<script language="javascript">
function check(form)
{

if(form.userid.value == "Roseindia" && form.pwd.value == "Roseindia")
{
	return true;
}
else
{
	alert("Error Password or Username")
	return false;
}
}
</script>

</body>
