# INDEX PAGE
- [Click here to see the full website](http://media15live.com/studentsUpload/Tbardini_1586439112/HTMLFORM.HTM)

![Index Page](https://github.com/thiagobardini/HTML5-CSS-BHCC/blob/master/Imagens/Screen%20Shot%202020-04-09%20at%209.34.05%20AM.png)


```html
<!DOCTYPE html>
<html>
<head>
<title>HTML forms</title>

<style>
input
{
  border 1px solid gray;
  padding-top: 6px;
  padding-bottom: 6px;
  padding-left: 6px;
  padding-right: 6px;
  color: gray;
  border-radius: 3px;
}

#submitbutton
{
  border 1px solid red;
  padding-top: 6px;
  padding-bottom: 6px;
  padding-left: 6px;
  padding-right: 6px;
  color: black;
  border-radius:3px;
  background-color:lightgreen;
}

</style>

</head>

<body>
<form method="get" action="formadata.phd">
<h2>Zoo Keeper Aplication Form</h2>
<i>Please complete the form. Mandatory fields are marked with a <span style="color:red">*</span></i>

<h3>Contact Details:</h3>
Applicant Name:
<br>
<input type="text" name="ApplicantName" size="40" maxlength="20"
placeholder="Type your first name and last name" required>
<br>
Phone
<br>
<input type="text" name="phone" size="12" maxlength="10">
<br>
<span style="color:red">*</span>Email
<br>
<input type="text" name="email">
<hr>
<h3>Personal Information:</h3>
<br>
Age:
<br>
<input type="text" name="age">
<br><br>
Gender: <input type="radio" name="gender" value="female"> Female <input type="radio" name="gender" value="male"> Male
<br><br>
Schedule
<br>
<select name="schedule">
  <option value="Moring: 6AM - 11AM">Moring: 6AM - 11AM</option>
  <option value="Day: 11AM - 5PM">Day: 11AM - 5PM</option>
  <option value="Night: 5PM - 11PM">Night: 5PM - 11PM</option>
</select>
<br><br>
Tell us about yourself:
<br>
<textarea name="applicantinfo" rows="9" cols="15"></textarea>
<br><br>
Pick your favorite animmals:
<br>
<input type="checkbox" name="tiger"> Tiger
<input type="checkbox" name="zebra"> Zebra
<input type="checkbox" name="ape"> Ape
<input type="checkbox" name="lion"> Lion
<br><br>

<input id="submitbutton" type="submit" value="Apply now">

<!--HTML TABLES -->
<br><br>Using HTML tables to style the form:


  <hr>

    <div id="table1">
      <table>

      <h3>Contact Form</h3>

      <table border="0"><!--remove border 1px-->

      <tr><td><font color="white">Name</font></td><td><input type="text" name="ApplicantName" size="30" maxlength="20"
       placeholder="Type your first name and last name" required></td></tr>
      <tr><td><font color="white">Phone</font></td><td><input type="text" name="phone" size="12" maxlength="10"></td></tr>
      <tr><td><font color="white">Email</font></td><td><input type="text" name="email" size="30"></td></tr>

      </table>

      <p align="center">
      <input id="submitbutton" type="submit" value="Apply now">
      </p>
    </div>
  </div>


<br><br><br><br><br>

</form>
</body>
</html>
```
