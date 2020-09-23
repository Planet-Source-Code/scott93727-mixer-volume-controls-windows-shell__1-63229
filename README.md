<div align="center">

## Mixer volume controls windows shell


</div>

### Description

Just label a menu name or draw a and command button aand click on the item and paste in the code and your ready to go.

Brings up the windows mixer for easy audio adjustments, works with all win versions
 
### More Info
 
Brings up the windows mixer for easy audio adjustments, works with all win versions


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[scott93727](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/scott93727.md)
**Level**          |Beginner
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/scott93727-mixer-volume-controls-windows-shell__1-63229/archive/master.zip)





### Source Code

```
Dim retval
On Error Resume Next
retval = Shell("c:\windows\sndvol32", 1)
On Error Resume Next
retval = Shell("c:\windows\system32\sndvol32", 1)
```

