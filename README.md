<div align="center">

## Change Entire Row Background Color


</div>

### Description

This is just a simple script that I use when I have a lot of rows and columns in a table. It will change the background color of whichever row your mouse is over. I use this commonly with PHP, as it makes it easier to view the data.
 
### More Info
 
Make sure to change the values of sColor to whatever colors you want.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[bleh](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/bleh.md)
**Level**          |Beginner
**User Rating**    |4.8 (24 globes from 5 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/bleh-change-entire-row-background-color__2-2532/archive/master.zip)





### Source Code

```
<script>
function changeBG(objRow, mouseState)
{
  if (mouseState == 'on')
  {
  	  sColor = '#789ddc';
  }
  else if (mouseState == 'off')
  {
  	  sColor = '#FFFFFF';
  }
  objRow.bgColor = sColor;
}
</script>
<table cellpadding="0" cellspacing="2" align="center">
<tr onMouseOver="changeBG(this, 'on');" onMouseOut="changeBG(this, 'off');">
    <td> Col 1 Row 1 </td>
    <td> Col 2 Row 1 </td>
    <td> Col 3 Row 1 </td>
    <td> Col 4 Row 1 </td>
    <td> Col 5 Row 1 </td>
</tr>
<tr onMouseOver="changeBG(this, 'on');" onMouseOut="changeBG(this, 'off');">
    <td> Col 1 Row 2 </td>
    <td> Col 2 Row 2 </td>
    <td> Col 3 Row 2 </td>
    <td> Col 4 Row 2 </td>
    <td> Col 5 Row 2 </td>
</tr>
<tr onMouseOver="changeBG(this, 'on');" onMouseOut="changeBG(this, 'off');">
    <td> Col 1 Row 3 </td>
    <td> Col 2 Row 3 </td>
    <td> Col 3 Row 3 </td>
    <td> Col 4 Row 3 </td>
    <td> Col 5 Row 3 </td>
</tr>
</table>
```

