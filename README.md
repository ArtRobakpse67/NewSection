# NewSection
For $a = 1 To 5     IniWrite(@DesktopDir &amp; "\my.ini", "NewSection" &amp; $a, "MyKey", "Val") Next  Sleep(1000)  IniDelete(@DesktopDir &amp; "\my.ini", "NewSection3")
