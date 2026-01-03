# BBSky
Telnet server for Bluesky, for connecting to Bluesky on retro computers.

## Connection
- In your telnet terminal of choice, connect to "placeholder:23"
- When asked, enter your Bluesky handle, and your app password (NOT your actual password!)
- Once connected, select the corresponding option you'd like to select, ie; your home feed, your messages, notifications, etc.
- To log off, just press "Q" at the main menu.

## Installation (server)
- Install "atproto" via pip ("pip install atproto")
- Copy the latest "BBSky-Server" release from releases
- Run "python3 bbsky-server.py"
- Once you see "BBSky is running on port 23", you can connect to your BBSky telnet instance by typing in your IP address followed by port 23 in your telnet terminal.

## TODO:
- Add alternate ATProto server support
- Add post search support
- Add feed/list support
- Add user profile viewing
