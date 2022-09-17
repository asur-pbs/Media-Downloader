### For preview, <a href="https://github.com/asur-pbs/Media-Downloader/tree/main/screenshots">visit here</a>.

## How to use

### Make it for ready to use

Download the script from <a href="https://github.com/asur-pbs/Media-Downloader/releases">release</a> section. Unzip it in anywhere. Installed the <a href="https://github.com/asur-pbs/Media-Downloader#install-requirments">requirements</a>. Run it.

### Use

To download social-media video , you can copy link by share link. But to download other sites videos you must find the link of the video. You can use browser extensions or developer tools for finding video url. To download drm protected videos , you must find the video url & decryption keys.
Note that we doesn't provide how you can get decryption keys.
                                                               After you get video url & other things, you can open script and choose which type of video url you have. After you can download video easily with providing video url & your simple inputs.
                                                               
                                                               
I recommend you to use <a href="https://chrome.google.com/webstore/detail/mpd-detector/lpoohbdbmggiknlpcmhhdkpaclfcdapk">.MPD Detector</a>, <a href="https://chrome.google.com/webstore/detail/live-cat/cofmpiaddiioohphmmgjnbcpfoiknnkh">Live Cat</a> & <a href="https://microsoftedge.microsoft.com/addons/detail/video-downloadhelper/jmkaglaafmhbcpleggkmaliipiilhldn">Video DownlaodHelper</a> extensions for grabbing video url.

## Requirments

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
