## Install requirments

Are you already installed below softwares, you can skip Install requirments

1. Open powershell as admin & copy below script to install choco for install requirement softwares easily.

```sh
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

2. Install ffmpeg

```sh
choco install ffmpeg
```

3. Install yt-dlp

```sh
choco install yt-dlp
```

4. Install python

```sh
choco install python
```

5. Next exit current powershell window & run command prompt as admin. in new window.

```sh
pip install spotdl
```

