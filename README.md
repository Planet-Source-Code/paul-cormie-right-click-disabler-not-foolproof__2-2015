<div align="center">

## \_ Right click disabler \_ \(not foolproof\) \_


</div>

### Description

<b><br>SUPER EASY CODE!</b><br><br>1 line is all it takes to stop users from either saving pictures on your site or viewing source.<br>disables the right click. See the screen capture for the alert that comes up.<br>Very easy to customize this alert...into, for example a copyright notice.<br><br><br><br> Enjoy....LOTS more to come (note : this is not foolproof - nothing is...)
 
### More Info
 
absolutely nothing at all! The html is in the code so it's as easy as cut and paste!

msgBox "Disabled"


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[paul\_cormie](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/paul-cormie.md)
**Level**          |Intermediate
**User Rating**    |4.3 (51 globes from 12 users)
**Compatibility**  |
**Category**       |[Alerts & Prompts](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/alerts-prompts__2-85.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/paul-cormie-right-click-disabler-not-foolproof__2-2015/archive/master.zip)





### Source Code

```
<html>
<head>
<title>Just try to right click on me</title>
</head>
<script>
<!-- JavaScript Start -----
function click() {if (event.button==2) { alert('Disabled') } } document.onmousedown=click
----- JavaScript End ------>
</script>
<body>
Just try to right click
</body>
</html>
```

