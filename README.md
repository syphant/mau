<div align="center">

  <img src="https://raw.githubusercontent.com/syphant/mau/refs/heads/main/preview2.png" />
  <br>

# mau

**mau** is a [catppuccin](https://github.com/catppuccin/catppuccin)-inspired [zebar](https://github.com/glzr-io/zebar) config, to be used with [glazewm](https://github.com/glzr-io/glazewm).

<br>

![preview2](https://raw.githubusercontent.com/syphant/mau/refs/heads/main/preview1.png)
</div>

## Features
- JetBrains Mono webfont & nerd font icons
- CPU/RAM utilization percentages
  - Percentage turns red if > 90%
- Battery percentage with dynamic icon based on battery level / charging
  - Battery section hidden on systems with no battery
- Volume percentage with dynamic icon based on volume level / mute state
  - Left click to mute/unmute
  - Scroll up/down to control volume level
  - Right click to open Windows sound settings
- Media controls (previous, play/pause, next)
- Scrolling media title for currently playing media
  - `<youtube-channel-name> – <video-title>`
  - `<artist-name> – <song-title>`
- Workspace indicator/selector
- System tray with monochrome interactive icons
  - ⚠️ Left click / double left-click is **borked**, right-click works fine (oops)
- Local weather conditions and temperature
  - Hover to show tooltip with current weather conditions
  - Click to toggle between °F/°C (defaults to °F)
- Short day of week + date display in `EEE M/d/yyyy` format
- 12h clock in `h:mm:ss a` format

## Installation
1. Run `git clone https://github.com/syphant/mau.git C:\Users\$env:username\.glzr\zebar\mau` in PowerShell if you have Git for Windows installed
   - Alternatively, download the zip file in [releases](https://github.com/syphant/mau/releases) and extract the contents to `C:\Users\$USER\.glzr\zebar\mau`
2. In zebar's context menu, choose `Empty cache & reload configs`, or alternatively just kill and relaunch zebar
3. In zebar's context menu, choose `Widget packs` > `mau` > `default` > `Run 'default'`
4. Optionally, in zebar's context menu, choose `Widget packs` > `mau` > `default` > `Run on start-up` > `default`
