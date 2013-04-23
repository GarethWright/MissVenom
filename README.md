MissVenom
=========

Small standalone SSL proxy for WhatsApp in .NET based on my upcoming MissProxy.

![MissVenom](https://dl.dropboxusercontent.com/u/68235039/proxy.png)

Using WebServer library 2.0 from http://webserver.codeplex.com/

Usage:
- Make sure your mobile device is on the same subnet as your machine
- Install server.crt as trusted root certificate on your mobile device
- Add hosts entry to your mobile device: Host=v.whatsapp.net IP=ip address of your machine
- Unregister WhatsApp app (e.g. wipe app data)
- Start MissVenom.exe
- Register WhatsApp on your device
- Your identity and password will appear in MissVenom

TODO:
- Remove all WebServer source code and include it as an embedded DLL
- Custom icon
- Logging capability
- Test if /v2/register and /v2/code work correctly
- Deserialize GET and JSON for nice formatting
