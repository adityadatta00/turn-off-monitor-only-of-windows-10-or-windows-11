# turn-off-monitor-only-of-windows-10-or-windows-11

# Link: https://www.majorgeeks.com/
# Link: https://www.majorgeeks.com/files/details/turn_off_monitor_only_on_demand.html

# Turn off display via a batch (.bat) file in Windows 10 or Windows 11:

# Type the following in a text editor and give it a name while saving with .bat extension:

# powershell (Add-Type '[DllImport(\"user32.dll\")]^public static extern int SendMessage(int hWnd, int hMsg, int wParam, int lParam);' -Name a -Pas)::SendMessage(-1,0x0112,0xF170,2)
