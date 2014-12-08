custom-widget-css
=================

This sample is to show how to customize the css of widget in javascript API

measurement
-----------------------

Changing the color of the result label of the measurement widget
```
document.getElementsByClassName("result")[0].style.color = "red";
document.getElementsByClassName("resultLabel")[0].style.color = "blue";      document.getElementsByClassName("resultTable")[0].style.color = "green";
```
