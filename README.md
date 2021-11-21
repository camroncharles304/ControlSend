# ControlSend
$WindowTitle = WinGetTitle("","")  While 1     $nMsg = GUIGetMsg()     Switch $nMsg         Case $GUI_EVENT_CLOSE             Exit         Case $Space             ControlSend($WindowTitle,"","","{Space}")     EndSwitch WEnd
