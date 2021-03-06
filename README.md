Fetcher
======

> Flash OS images to SD cards & USB drives, safely and easily.

Fetcher is a fork of [Etcher](http://etcher.io/), a powerful OS image flasher built with web technologies to ensure flashing an SDCard or USB drive is a pleasant and safe experience. It protects you from accidentally writing to your hard-drives, ensures every byte of data was written correctly and much more. Unfortunately, it doesn't protect you from having data sent from your computer back to the Etcher developers. It does this without telling you or asking your permission, unless you go into the settings, notice the 'send user data' tick box there, and ether opt-out by unticking it, or choose to let the data get by not unticking it.

We created this forked to address that anti-feature. Although we understand that the developers find the data they get that way useful for improving the app, we believe that any code that sends data from a user's computer back to developers ought to be turned off by default, with the user explicity asked for permission to turn it on. The [Etcher developers have made it clear they do not wish to do this](https://github.com/resin-io/etcher/issues/1773), so we used the freedoms protected by their choice of the Apache 2.0 license to do it ourselves.

[Current Release](https://github.com/TheAssassin/fetcher/releases)

Supported Operating Systems
---------------------------

- Linux (most distros)
- macOS 10.9 and later
- Microsoft Windows 7 and later

Note that Fetcher will run on any platform officially supported by
[Electron][electron]. Read more in their
[documentation][electron-supported-platforms].

Installers
----------

Refer to the [downloads page](https://github.com/TheAssassin/fetcher/releases) for the latest pre-made
installers for all supported operating systems.

Support
-------

If you're having any problem, please [raise an issue][newissue] on GitHub and
the Fetcher team will be happy to help.

License
-------

Fetcher is free software, and may be redistributed under the terms specified in
the [license].

[electron]: http://electron.atom.io
[electron-supported-platforms]: http://electron.atom.io/docs/tutorial/supported-platforms/
[SUPPORT]: https://github.com/TheAssassin/fetcher/blob/master/SUPPORT.md
[CONTRIBUTING]: https://github.com/TheAssassin/fetcher/blob/master/docs/CONTRIBUTING.md
[CLI]: https://github.com/TheAssassin/fetcher/blob/master/docs/CLI.md
[USER-DOCUMENTATION]: https://github.com/TheAssassin/fetcher/blob/master/docs/USER-DOCUMENTATION.md
[milestones]: https://github.com/TheAssassin/fetcher/milestones
[newissue]: https://github.com/TheAssassin/fetcher/issues/new
[license]: https://github.com/TheAssassin/fetcher/blob/master/LICENSE
