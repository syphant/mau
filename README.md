# mau

**mau** is a [catppuccin](https://github.com/catppuccin/catppuccin)-inspired [zebar](https://github.com/glzr-io/zebar) config, to be used with [glazewm](https://github.com/glzr-io/glazewm).

### Features
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