# ProxyHuntr
ProxyHuntr is a Free and OpenSource Proxy Finder and Checker. ProxyHuntr is written in Python 3(.5). ProxyHuntr has an GUI thanks to PyQt5. ProxyHuntr has got two dependencies: PyQt5 and Requests.

## Features
- ProxyHuntr checks proxies **Multi Threathed**!
- ProxyHuntr verifies the anonymity of the proxies.
- ProxyHuntr finds Country Information.
- ProxyHuntr can verify if your IP is really hidden (only Anonymous and Elite proxies since Transparent proxies will leak your IP).
- ProxyHuntr is fast and does not need much computing power to run.
- ProxyHuntr can scrape proxies from the internet and check them OR check proxies from a file.
- ProxyHuntr can export proxies bassed on anonymity.

## Technical
ProxyHuntr check proxies by using them as they would be used: make an HTTP request and verify the result.

## How to Install
#### Windows
If you're on windows and not planning on changing the sourcecode, download the latest pre-compiled release. This will make sure that ProxyHuntr works without having to install Python and different modules!

#### All Platforms
1. Install Python 3.x (3.5 has been tested).
2. Run `pip install -r requirements.txt` to install the dependencies.
3. Run `python main.py` or `python3 main.py`.

## Downloads
Latests Version: `RC2 (Pre-Release)`

[Windows Installer (.exe)](https://github.com/J0113/ProxyHuntr/releases/download/RC2/ProxyHuntr.Setup.RC2.exe)(60MB)

[Windows Protable (.zip)](https://github.com/J0113/ProxyHuntr/releases/download/RC2/ProxyHuntr.Windows.RC2.zip)(85MB)

[Source Code (.zip)](https://github.com/J0113/ProxyHuntr/archive/RC2.zip)

> NOTE: If you use the windows installer and install to the default directory. RUN ProxyHuntr EVERYTIME as ADMIN, ProxyHuntr saves files in it's relative directory; it needs admin rights to do that in the program files dir. Will be fixed later!