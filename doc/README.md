Pulse Core
=====================

Setup
---------------------
[Pulse Core](http://pulse.me) is the original Pulse client and it builds the backbone of the network. However, it downloads and stores the entire history of Pulse transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run Pulse on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/pulse-qt (GUI, 32-bit) or bin/32/pulsed (headless, 32-bit)
- bin/64/pulse-qt (GUI, 64-bit) or bin/64/pulsed (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run pulse-qt.exe.

### OSX

Drag Pulse-Qt to your applications folder, and then run Pulse-Qt.

### Need Help?

* See the documentation at the [Pulse Wiki](https://en.bitcoin.it/wiki/Main_Page) ***TODO***
for help and more information.
* Join our Discord server [Discord Server](https://discord.pulse.org)

Building
---------------------
The following are developer notes on how to build Pulse on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Pulse repo's [root README](https://github.com/Pulse-Developer/Pulse-Core/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/) ***TODO***
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
