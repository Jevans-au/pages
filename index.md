## jevans-au

Testing out GitHub Pages at the moment, with a very 'quaint' index.md file at present.

```
### Python Scriptblock
```python
import math
a = 1 + 1
print(a)
```
### XML Scriptblock (Which we're having to use for XAML)
```XML
<!-- comment -->
<CheckBox Content="1" Margin="0,5,5,0"/>
<CheckBox Content="2" Margin="0,5,5,0"/>
<CheckBox Content="3" Margin="0,5,5,0"/>
<CheckBox Content="4" Margin="0,5,5,0"/>
```

### PowerShell ScriptBlock
```PowerShell
function Get-FrameWorkElementType {
    [CmdletBinding()]
    param (
        [Parameter()]
        [string]
        $ElementType
    )
    $FrameWorkElement = [System.Windows.FrameworkElement]
    Write-Output $FrameWorkElement.Assembly.DefinedTypes
}
```
[Link to above function in GitHub repo.](https://github.com/Jevans-au/JevDev/blob/main/PowerShell/CommonFunctions/Get-FrameWorkElementType.ps1)
