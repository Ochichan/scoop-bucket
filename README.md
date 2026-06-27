# scoop-bucket

Scoop bucket for [ytm-tui](https://github.com/Ochichan/ytm-tui) — a fast, low-RAM YouTube Music
player for your terminal.

```powershell
scoop bucket add ytm-tui https://github.com/Ochichan/scoop-bucket
scoop install ytm-tui
```

Then run `ytt`. For playback you also need `mpv` and `yt-dlp`:

```powershell
scoop install mpv yt-dlp
```

Downloads are saved to `$HOME\Music\ytm-tui` by default.

Cookies are optional. Public search and playback work without a cookie file. For signed-in
YouTube Music access or gated tracks, export a Netscape-format `cookies.txt` to:

```powershell
$HOME\Music\ytm-tui\cookies.txt
```

Keep that file private; it can act like a logged-in browser session.
