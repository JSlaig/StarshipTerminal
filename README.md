
#Installation of the Starship Terminal'

##Windows

###Install chocolatey

```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))```

###Install Starship via chocolatey
```choco install starship```

###Config filepaths


##Linux

###Shellscript installation
```sh -c "$(curl -fsSL https://startship.rs/install.sh)"```

###Config filepaths


##MacOs

###Homebrew installation
```brew install starship```

