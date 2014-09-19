#DTimepicker
===========

A simple JQuery timepicker plugin.

##How to use:
---
1. First put a reference to timepicker.min.js and timepicker.css in your html.
```
<link rel="stylesheet" type="text/css" href="js/timepicker/timepicker.css">
<script type="text/javascript" src="js/timepicker/timepicker.min.js"></script>
```
2. In your html markup, like what is shown below, create input element. *Note: Make sure to have a reference to the element by using __id__ or __class__.*
```
<input id='mytimeicker' type='text'/>
```
3. In your javascript code, call the .timepicker() function, as shown below.
```
$('#mytimeicker').timepicker();
```