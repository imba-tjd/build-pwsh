# Build PowerShell

This repo builds Pwsh with:

* RID: win10-x64
* fxdependent-win-desktop
* **CrossGen enabled**

It's suitable if you are originally using the fxdependent-win-desktop version.

You can download binary from Actions artifacts.

Though the content is somewhat different. There are no `ref` and `Microsoft.PowerShell.GlobalTool.Shim.exe`

## Reference

* https://github.com/PowerShell/PowerShell/blob/master/docs/building/windows-core.md
* TODO
  * https://github.com/PowerShell/PowerShell/tree/master/tools/releaseBuild
  * https://powershell.visualstudio.com/PowerShell/_build
