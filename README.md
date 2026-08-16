# BMX Timing

Live timing for BMX track sessions, read directly from the
track's own decoders — no per-rider Sqorz fees.

This repository only holds installers for download — there's no source
code here. Grab the latest version from
**[Releases](https://github.com/DavidH667/bmx-timing-releases/releases)**.

## Installing

1. Go to [Releases](https://github.com/DavidH667/bmx-timing-releases/releases)
   and download the `.exe` under the most recent version (e.g.
   `bmx-timing-setup-1.0.0.exe`).
2. Run it. Windows will show a blue **"Windows protected your PC"**
   screen — this is expected for every version, not a sign something's
   wrong. Click **More info**, then **Run anyway**.
3. The installer runs with no extra prompts — it installs to a folder
   in your own user profile, no admin password needed. A shortcut
   appears on your desktop automatically.
4. The first time you launch it, Windows Firewall will ask to allow
   network access — click **Allow**. This is what lets other phones and
   tablets on the same Wi-Fi view the board (see below).
5. A browser tab opens automatically showing the track selector. Pick
   your track (or add it, the first time) and confirm the board loads.

That's it — from then on, just double-click the desktop shortcut before
a session. A tray icon (bottom-right of your screen, near the clock)
shows it's running; right-click it and choose **Quit** to stop at the
end of the day.

## Updating to a new version

Repeat the steps above with the new installer — it replaces the old
version in place and keeps all your existing track data untouched.
SmartScreen and the Firewall prompt will both reappear on every update,
same as the first install; that's normal, not a sign of a problem.

## Viewing the board on a phone or tablet

Join the same Wi-Fi network the timing PC is on (not mobile data), then
browse to the PC's address - it looks like `http://192.168.x.x:8000`. 
This address can change between sessions, so always at the admin hut 
rather than a saved bookmark.

## Something not working?

Get in touch with David Harkness / david.harkness.nz@gmail.com — mention 
which version you're running (shown at the bottom of the track selector screen) 
and roughly when the issue happened. The app keeps its own log file for
troubleshooting, so there's usually no need to reproduce a problem live.
