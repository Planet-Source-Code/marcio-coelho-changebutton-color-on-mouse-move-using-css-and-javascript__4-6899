<div align="center">

## changebutton color on Mouse move using CSS and Javascript


</div>

### Description

Better Interface
 
### More Info
 
This code demonstrates how the button change color when the mouse is over it.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Marcio Coelho](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/marcio-coelho.md)
**Level**          |Beginner
**User Rating**    |4.7 (33 globes from 7 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML
**Category**       |[System Services/ Functions](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/system-services-functions__4-23.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/marcio-coelho-changebutton-color-on-mouse-move-using-css-and-javascript__4-6899/archive/master.zip)





### Source Code

```
<html>
<style>
.Over
{
  BACKGROUND-COLOR: #708090;
  COLOR: #ffffff;
  CURSOR: hand
}
.Out
{
  BACKGROUND-COLOR: #c0c0c0;
  COLOR: #000000;
  CURSOR: default
}
</STYLE>
<Body>
<INPUT type="button" tagName="BUTTON" value="Button" id=button1 name=button1>
</body>
<script FOR="document" EVENT="onmouseover" LANGUAGE="javascript">
<!--
document_onmouseover()
//-->
</script>
<script LANGUAGE="javascript" FOR="document" EVENT="onmouseout">
<!--
 document_onmouseout()
//-->
</script>
<script language="Javascript">
<!--
function document_onmouseout()
	{
		if (event.srcElement.tagName == "BUTTON")
			{
			event.srcElement.className = "Out";
			}
	}
	function document_onmouseover()
	{
		if (event.srcElement.tagName == "BUTTON")
			{
			event.srcElement.className = "Over";
			}
 }
	//-->
</script>
</html>
```

