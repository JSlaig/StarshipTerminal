
# Installation of the Starship Terminal

## Windows
For Windows, I am setting it up on windows terminal since it is the best one currently available hands down.

### Install chocolatey

```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))```

### Install Starship via chocolatey
```choco install starship```

### Config filepaths

1. Firstly we need to set up the profile variable:

```code $PROFILE``` or ```nvim $PROFILE``` or any other text editor we may have installed

2. Then we paste inside the content of the file named:

```Microsoft.PowerShell_profile.ps1```

2.1. NOTE: It is mandatory for icons to work to have installed a Nerd Font, and to select it in the terminal. If icons still don't work, make sure the encoding of the file is "UTF-8 with BOM"

3.

## Linux

### Shellscript installation
```sh -c "$(curl -fsSL https://startship.rs/install.sh)"```

### Config filepaths


## MacOs

### Homebrew installation
```brew install starship```

### Config filepaths
