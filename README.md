<div align="center">

## An easy way to execute any command line in text1\.text


</div>

### Description

Code to execute any file.exe with any command line.

Executes Any dos command line in only 7 lines of code

please comment and rate:):)
 
### More Info
 
requires 1 text box and 2 command buttons

place your command line in the text box

press command1 first then command2


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[gmtt\_dan](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/gmtt-dan.md)
**Level**          |Beginner
**User Rating**    |4.1 (29 globes from 7 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/gmtt-dan-an-easy-way-to-execute-any-command-line-in-text1-text__1-38723/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
Open CurDir & "/commandline.bat" For Output As #1
Print #1, Text1.Text
Close #1
Shell (CurDir & "/commandline.bat"), vbNormalFocus
End Sub
```

