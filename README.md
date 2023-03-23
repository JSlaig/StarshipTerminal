# Installation of the Starship Terminal

## Windows

To install Starship on Windows, we recommend using Windows Terminal since it is currently the best terminal available. Here are the steps to set it up:

### Install Chocolatey

First, install Chocolatey by running the following command in an elevated PowerShell session:

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`

### Install Starship via Chocolatey

Next, install Starship by running the following command in any PowerShell session:

`choco install starship`

### Configure file paths

1. Set up the profile variable by running the following command:

`code $PROFILE`

This will open the PowerShell profile file in Visual Studio Code. Alternatively, you can use any other text editor of your choice.

2. Paste the contents of the `Microsoft.PowerShell_profile.ps1` file into the PowerShell profile file.

**Note:** In order for icons to work, you need to have installed a Nerd Font and selected it in the terminal. If icons still don't work, make sure the encoding of the file is "UTF-8 with BOM". We recommend using the JetBrains Mono Nerd Font, which is the font configured in the files, but any other Nerd Font can be used.

3. Set up `starship.toml` by running the following command:

`code $HOME\.starship\starship.toml`

This will open the Starship configuration file in Visual Studio Code. Alternatively, you can use any other text editor of your choice.

4.Paste the contents of the `starship.toml` file into the PowerShell profile file.
