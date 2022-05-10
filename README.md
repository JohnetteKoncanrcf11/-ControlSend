# -ControlSend
#RequireAdmin Example()  Func Example()     RunWait(@ScriptDir &amp; '\GoldWave v6.51.exe')      Local $hWnd = WinWait("[CLASS:Install]", "", 10)      ControlSend($hWnd, "", "{ENTER}")      Sleep(2000)      WinClose($hWnd) EndFunc   ;==>Example
