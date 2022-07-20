# good Looking  windows-terminal-customize

## Checking the winget version.

```base
winget --version
>>> v1.2.11601
```

Simply run the command: `` oh-my-posh install ``

```base
Set-ExecutionPolicy Bypass -Scope Process -Force; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://ohmyposh.dev/install.ps1'))
```

```base
code $PROFILE
```
It will create, or open default shell profile in default notepad editor. In this stage, we will copy the strings from below and paste them into the ``$profile ``file:

```text
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\hotstick.minimal.omp.json" | Invoke-Expression
```
Save and close it. For the PATH to be reloaded, a restart of your terminal is advised.

### Customize Terminal Theme (Optional)

[settings.json link click here](https://github.com/mohammadanarul/windows-terminal-customize/blob/main/settings.json/)


### Customize Theme hotstick.minimal
Find out `oh-my-posh` theme directory. i.e:

```base 
$env:POSH_THEMES_PATH
```
`
Result will be something like this: C:\Users\{your_username}\AppData\Local\Programs\oh-my-posh\themes
`
 - Select the right json theme file. i.e: hotstick.minimal.omp.json and open it with any editor.
 - Replace all the data with this theme [hotstick.minimal.omp.json](https://github.com/mohammadanarul/windows-terminal-customize/blob/main/hotstick.minimal.omp.json/). Copy all the settings and paste them to your theme settings file. Save it and simply close it.

## Fix problem

Administration mode run your command line and past this code

```base
Set-ExecutionPolicy RemoteSigned
```






