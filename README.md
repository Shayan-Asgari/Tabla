# Tableau
Voice Filter Command Tableau API application


<!DOCTYPE html>
<html>
<head>
<div align = "center">
<textarea rows="10" cols="53" 
style="font-family:Times New Roman;
font-size: 14pt;">
</textarea>
<style>
textarea{
display:inline-block;

}
body
{
background-color: #F9FFE6;
}

}

.button {


  border: none;
  color: white;
  padding: 3px 3px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}

.button1 {
  position:absolute;
  background-color: green; 
  color: #FFFF1C; 
  left: 60px;
  border: 2px solid green;
}

.button2 {
 position:absolute;
 left: 120px;
  background-color: orange; 
  color: #E64329; 
  border: 2px solid orange;
}
.clearButton {
 position:absolute;
  right: 60px;
  background-color: #678DE6; 
  color: #FFFFFF; 
  border: 2px solid #678DE6;
}
.yesButton {
 position:absolute;
  left: 185px;
  background-color: #678DE6; 
  color: #FFFFFF; 
  border: 2px solid #678DE6;
}
.button1:hover
{
transition-duration: 1s;
background-color : #FFFF1C;
color: grey;
}
.button2:hover
{
transition-duration: 1s;
background-color : #E64329;
color: white;
}
.clearButton:hover
{
transition-duration: 1s;
background-color : white;
color: #678DE6;

}
.yesButton:hover
{
transition-duration: 1s;
background-color : white;
color: #678DE6;
}



.button1 {border-radius: 8px;}
.button2 {border-radius: 8px;}
.clearButton {border-radius: 8px;}
.yesButton {border-radius: 8px;}

 p 
{ 
margin-left:50px; 
color: #262626;
font-style: oblique;
font-size: 14pt;
font-weight: 900;
}

</style>
</head>
<body>
<p></p>
<button class="button button1">Enable</button>
<button class="button button2">Disable</button>
<button class="clearButton">Clear</button>
<button class="yesButton">Yes</button>
<br/>
<br/>

<div align = "left">
<p>Say, "hey, Tableau" to begin</p>



</body>
</html>
