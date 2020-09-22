<div align="center">

## BEGGINER Form On Top


</div>

### Description

Puts Your form on top.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Demian Net](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/demian-net.md)
**Level**          |Beginner
**User Rating**    |3.0 (6 globes from 2 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/demian-net-begginer-form-on-top__1-6043/archive/master.zip)

### API Declarations

```
'Put this in a module
Public Sub FormOnTop(FormName As Form)
   Call SetWindowPos(FormName.hwnd, HWND_TOPMOST, 0&, 0&, 0&, 0&, FLAGS)
End Sub
Public Sub FormNotOnTop(FormName As Form)
  Call SetWindowPos(FormName.hwnd, HWND_NOTOPMOST, 0&, 0&, 0&, 0&, FLAGS)
End Sub
```


### Source Code

```
'To make your form on top:
FormOnTop Form1
'To take you off off of on top:
FormNotOnTop Form1
```

