[![Join us on https://gitter.im/qtoggle/community](https://badges.gitter.im/qtoggle/community.png)](https://gitter.im/qtoggle/community?utm_source=badge&utm_medium=badge&utm_content=badge)

---


## About qToggle

qToggle is a way of interconnecting sensors, actuators and other data sources. qToggle works by leveraging the power of a flexible [API](https://github.com/qtoggle/docs/wiki/API-Specifications), which lays the groundwork of a simple, common communication scheme.

qToggle attempts to impose a standard that allows managing, provisioning and talking to devices. Rather than reinventing the wheel, qToggle makes use of existing, widely used, technologies, such as RESTful APIs on top of HTTP, passing over data encoded as JSON.

There currently are two opensource implementations of the qToggle API:
 * [qToggleServer](https://github.com/qtoggle/qtoggleserver), offering a backend written in Python and a frontend in the form of a [progressive web app](https://github.com/qtoggle/qtoggleserver/wiki/Web-App)
 * [espQToggle](https://github.com/qtoggle/espqtoggle), supplied as firmware for the [ESP8266/8285-based devices](https://en.wikipedia.org/wiki/ESP8266)

In addition to these, [qToggleOS](https://github.com/qtoggle/qtoggleos) is a ready-to-use lightweight OS image for the Raspberry Pi devices, which embeds a preinstalled qToggleServer, along with some other nice-to-have features.


## Getting Started

### Choose Your Devices

The first thing you'll want to do is order some devices from the [supported devices](https://github.com/qtoggle/espqtoggle/wiki/Supported-Devices) based on the ESP8266 chip.

You may also need a Raspberry Pi board (variants 3 or 4 are recommended), with accessories. The Pi board may have three roles in a qToggle setup:
 * it could act as a qToggle device, when equipped with peripherals such as sensors or relay boards
 * it could act as a [hub](https://github.com/qtoggle/qtoggleserver/wiki/Hub-Setup) (master) for other qToggle devices
 * it could help installing the ESP firmware on some devices, when running [Tuya Convert OS](https://github.com/qtoggle/espqtoggle/wiki/Tuya-Convert-OS)

### Documentation

Most of the documentation can be found on GitHub, on the wiki pages of each project. Here are a few pages to get you up to speed with qToggle:

 * The [basic notions](https://github.com/qtoggle/docs/wiki/Basic-Notions) page will get you better acquainted with qToggle terms, components and scenarios.
 * The [FAQ](https://github.com/qtoggle/docs/wiki/FAQ) will hopefully answer some of the questions you may have.
 * The [qToggleServer's Getting Started](https://github.com/qtoggle/qtoggleserver/wiki/Getting-Started) page will help you set up your hub.
 * Finally, check out the [espQToggle Wiki](https://github.com/qtoggle/espqtoggle/wiki) if you want to use an ESP-based device with qToggle.
