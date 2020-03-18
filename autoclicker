Hotkey, *LButton, Toggle
Hotkey, *RButton, Toggle

Gui, Add, Tab, x2 y-1 w297 h225 , About|Autoclicker|FastPlace|Help|Credits
Gui, Tab, About
Gui, Font, S30 CDefault, Impact
Gui, Add, Text, x65 y70 w200 h70 , ahkClicker
Gui, Font, S20 CDefault, Verdana
Gui, Add, Text, x65 y110 w200 h40 , Formerly Tap
Gui, Font, S10 CDefault, Verdana
Gui, Add, Text, x5 y205 w210 h17 , Version: 2.0
Gui, Tab, Autoclicker
Gui, Add, Text, x10 y29 w277 h20 , Minimum Delay (milliseconds)
Gui, Add, Slider, x10 y49 w277 h30 vMin gMin ToolTip Range0-500, 21
Gui, Add, Text, x10 y89 w277 h20 , Maximum Delay (milliseconds)
Gui, Add, Slider, x10 y109 w277 h30 vMax gMax ToolTip Range0-500, 116
Gui, Tab, FastPlace
Gui, Add, Text, x10 y29 w277 h20 , Minimum Delay (milliseconds)
Gui, Add, Slider, x10 y49 w277 h30 vMinBuild gMinBuild ToolTip Range0-500, 25
Gui, Add, Text, x10 y89 w277 h20 , Maximum Delay (milliseconds)
Gui, Add, Slider, x10 y109 w277 h30 vMaxBuild gMaxBuild ToolTip Range0-500, 62
Gui, Tab, Help
Gui, Add, Text, x12 y29 w220 h30 , Autoclicker Toggle: Alt
Gui, Add, Text, x12 y49 w220 h30 , Autoclicker Use: Hold Left Click
Gui, Add, Text, x12 y69 w220 h30 , FastPlace Toggle: '
Gui, Add, Text, x12 y89 w220 h30 , FastPlace Use: Hold Right Click
Gui, Add, Text, x12 y129 w220 h32 , You can change these keys in the script. (exmaples below)
Gui, Add, Text, cBlue gAExample, Autoclicker Hotkey Example (click)
Gui, Add, Text, cBlue gFExample, FastPlace Hotkey Example (click)
Gui, Tab, Credits
Gui, Add, Text, cBlue gWebsite, Website (click)
Gui, Add, Text, cBlue gSource, Source code (click)
;string:RXIoGYvt39c2skj8UnTy
Gui, Show, x50 y50 h225 w300, nTyoGTIoG584DXyRXIskj
Gui, Submit, NoHide
Return

Min:
{
Gui, Submit, NoHide
}
return

Max:
{
Gui, Submit, NoHide
}
return

MinBuild:
{
Gui, Submit, NoHide
}
return

MaxBuild:
{
Gui, Submit, NoHide
}
return

;Autoclicker
Alt::Hotkey, *LButton, Toggle
*LButton::
Send,{LButton}
While GetKeyState("LButton", "P")
{
Send,{LButton}
Random, delay, %Min%, %Max%
Sleep %delay%
}
return

;FastPlace
'::Hotkey, *RButton, Toggle
*RButton::
Send,{RButton}
While GetKeyState("RButton", "P")
{
Send,{RButton}
Random, delay, %MinBuild%, %MaxBuild%
Sleep %delay%
}
return

AExample:
run https://gyazo.com/1a92e27086d312400bf62735adc21f73
return

FExample:
run https://gyazo.com/57a6b2b6c6d471aee47e9bfbd30e9733
return

Website:
run https://tapclient.weebly.com
return

Source:
run https://gist.github.com
return

GuiClose:
ExitApp
