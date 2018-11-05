
<html>
        <h1>IMAGINE DRAGONS </h1>
    <img src="https://ih1.redbubble.net/image.496534540.8064/flat,550x550,075,f.u3.jpg" alt="Imagine Dragons Logo" width="203">
    <table>
  <thead>
    <tr>
      <th> Title </th>
      <th> Cover </th>
        <th> Description link </th> 
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Night Visions</td>
      <td> https://en.wikipedia.org/wiki/Night_Visions#/media/File:Night_Visions_Album_Cover.jpeg </td>
      <td> Click on </td>
    </tr>
    <tr>
      <td> Smoke + Mirrors </td>
      <td> https://upload.wikimedia.org/wikipedia/en/c/ce/Imagine_Dragons_-_Smoke_%2B_Mirrors.png </td>
       <td> this link to </td>
    </tr>
    <tr>
      <td> Evolve </td>
      <td> https://upload.wikimedia.org/wikipedia/en/b/b5/ImagineDragonsEvolve.jpg </td>
       <td> to view webpage </td>
    </tr>
    <tr>
      <td> Origins </td>
      <td> https://i.redd.it/8atdz8vki3q11.png</td>
      <td> https://docs.google.com/document/d/1UuD8ugx_UQrkkDBW2yTOkwhVx3kvtfJi1feEXLPdud4/edit?usp=sharing </td>
    </tr>
    </tbody>
    </table> 
    </body>
</html>

<head>
<title>
Login page
</title>
</head>
<body>
<h1 style="font-family:Comic Sans Ms;text-align="center";font-size:20pt;
color:#00FF00;>
Simple Login Page
</h1>
<form name="login">
Username<input type="text" name="userid"/>
Password<input type="password" name="pswrd"/>
<input type="button" onclick="check(this.form)" value="Login"/>
<input type="reset" value="Cancel"/>
</form>
<script language="javascript">
function check(form)/*function to check userid & password*/
{
 /*the following code checkes whether the entered userid and password are matching*/
 if(form.userid.value == "myuserid" && form.pswrd.value == "mypswrd")
  {
    window.open('https://www.w3schools.com/js/tryit.asp?filename=tryjson_array_modify')/*opens the target page while Id & password matches*/
  }
 else
 {
   alert("Error Password or Username")/*displays error message*/
  }
}
</script>
</body>

