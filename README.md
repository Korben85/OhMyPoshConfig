# My config file for OhMyPosh.

## OhMyPosh
Installation and configuration can be found here: [OhMyPosh](https://ohmyposh.dev/)

## Enabling this theme
To enable this theme in the power shell add the following line to the Microsoft.PowerShell.ps1 file.
- edit profile by entering `notepad $PROFILE` in the terminal
- add `oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/Korben85/OhMyPoshConfig/main/.mytheme.omp.json' | Invoke-Expression`
- save the file and reload profile by executing `.$PROFILE` in the terminal or reopen powershell
