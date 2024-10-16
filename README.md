# My config file for OhMyPosh.

## OhMyPosh
- latest installation and configuration instructions can be found here: [OhMyPosh](https://ohmyposh.dev/)
- download & install "RobotoMono Nerd Font" from [Nerd Fonts](https://www.nerdfonts.com/font-downloads)
- change font in Terminal

## Enabling this theme
To enable this theme in the power shell add the following line to the Microsoft.PowerShell.ps1 file.
- edit profile by entering `notepad $PROFILE` in the terminal
- add `oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/Korben85/OhMyPoshConfig/main/.mytheme.omp.json' | Invoke-Expression`
- save the file and reload profile by executing `.$PROFILE` in the terminal or reopen powershell
