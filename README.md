# Windows Credentials Grabber for Bash Bunny Mark 2
Credit goes to https://github.com/AlexanderWyt for the original payload I just added dynamic drive mapping for use on multiple systems originally this was hardcoded for drive D:\


<b>Future Ideas</b>
<br>
- Making payload.txt launch a powershell script that can run hidden for less visual disturbance
- Adding password cracking locally
- Flush PowerShell History (Remove-Item (Get-PSReadlineOption).HistorySavePath -Force -ErrorAction SilentlyContinue)
- Disable Event Logging Temporarily
- Dump BitLocker Recovery Keys
- RAM Dump
- Possibly add some exploits to priv escalate for users who are not admin
