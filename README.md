# Assigment-1
Create a form like this Using simple HTML &amp; CSS
<!DOCTYPE html>
<html>
<head>
<style>
input {
    line-height: 2em; // 2em is (2 * default line height)
}
submit{
     bgcolor:red;
}
</style>
<script type="text/javascript" src="validate.js"></script>
</head>
<body bgcolor="red">
<form action="#" name="Contactus" onSubmit="return(validate());">

<table cellpadding="10" width="30%" bgcolor="white" align="center"
cellspacing="10">

<tr>
<td>Contact us for custom quote</td>
</tr>
<br>

<center>
<tr>
<center>
<td><input type=text  name=textnames id="textname" placeholder="Your name" size="30"></td>
</center>
</tr>
<br>
</center>

<center>
<tr>
<tr>
<td><input type="text" name="emailid" id="emailid" placeholder="Your Email Address" size="30"></td>
</tr>
<br>
</center>

<center>
<tr>
<td><input type="text" name="mobileno" id="mobileno" placeholder="Your Phone Number(Optinal)" size="30"></td>
</tr>
<br>
</center>

<center>
<tr>
<td><input type=text name=textnames id="textname" placeholder="Your Web Site(Optional)" size="30"></td>
</tr>
<br>
</center>

<center>
<tr>
<td><input type=text name=textnames id="textname" placeholder="Type your message here..." size="30"></td>
</tr>
<br>
</center>

<center>
<tr>
<td><input type="submit" bgcolor="red" value="Submit" width="48" height="48"/></td>
</tr>
</center>
</table>
</form>
</body>
</html>
