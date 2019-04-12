Paste code to profile:

```
Import-Module posh-git

$GitPromptSettings.DefaultPromptPath.ForegroundColor = 'Orange'
$GitPromptSettings.DefaultPromptBeforeSuffix.Text = '`n$([DateTime]::now.ToString("MM-dd HH:mm:ss")) '
$GitPromptSettings.DefaultPromptBeforeSuffix.ForegroundColor = 0xa076e8
$GitPromptSettings.EnableStashStatus = $true
```

to open profile you can use command: `notepad.exe $profile`
to reload profile you can use command: `. $profile`
