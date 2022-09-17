## How to use
Download the script from <a href="https://github.com/asur-pbs/Media-Downloader/releases">release</a> section. Unzip it in anywhere. Installed the <a href="https://github.com/asur-pbs/Media-Downloader#install-requirments">requirements</a>. Run it.

## Install requirments

Are you already installed below softwares, you can skip Install requirments

1. Open powershell as admin & copy below script to install <a href="https://chocolatey.org">choco</a> for install requirement softwares easily.

```sh
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

2. Install <a href="https://ffmpeg.org">ffmpeg</a>

```sh
choco install ffmpeg
```

3. Install <a href="https://github.com/yt-dlp/yt-dlp">yt-dlp</a>

```sh
choco install yt-dlp
```

4. Install <a href="https://www.python.org">python</a>

```sh
choco install python
```

5. Next exit current powershell window & open command prompt.

6. Install <a href="https://github.com/spotDL/spotify-downloader">spotdl</a>
```sh
pip install spotdl
```
