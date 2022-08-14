ShadowsocksR client with SSRoT for macOS
===========================
[![Build Status](https://travis-ci.org/shadowsocks/shadowsocks-iOS.svg?branch=master)](https://travis-ci.org/shadowsocks/shadowsocks-iOS)

![img05](https://user-images.githubusercontent.com/107175234/184545683-f5fb7ef5-20f9-4f62-98f5-9c821644d367.png)

![img04](https://user-images.githubusercontent.com/30760636/148067488-27cc56ed-4f10-49a1-8b78-ef467aadc216.png)

![tu](server-settings.png)

![img02](https://user-images.githubusercontent.com/30760636/148062744-1e95b202-13e6-4144-89c7-fe4ce82419d7.png)


macOS
-----
[![OSX Icon](https://raw.githubusercontent.com/ShadowsocksR-Live/ssrMac/master/osx_128.png)](https://github.com/shadowsocks/shadowsocks-iOS/wiki/Shadowsocks-for-OSX-Help)  
[OSX Version](https://github.com/shadowsocks/shadowsocks-iOS/wiki/Shadowsocks-for-OSX-Help)


Build from source code
-----
**Dependencies**:
 * **Sodium** [Installation](https://download.libsodium.org/doc/installation/index.html)
 * **mbedTLS** [Installation](https://github.com/ARMmbed/mbedtls#cmake)
 * **libuv** [Installation](https://github.com/libuv/libuv#build-instructions)

Then pull **source code** and submodules
```bash
git clone https://github.com/ShadowsocksR-Live/ssrMac.git
cd ssrMac
git submodule update --init --recursive
git submodule foreach -q 'git checkout $(git config -f $toplevel/.gitmodules submodule.$name.branch || echo master)'
```


License
-------
The project is released under the terms of [GPLv3](https://raw.github.com/shadowsocks/shadowsocks-iOS/master/LICENSE).

Bugs and Issues
----------------

Please visit [issue tracker](https://github.com/ShadowsocksR-Live/ssrMac/issues?state=open)

Also see [troubleshooting](https://github.com/clowwindy/shadowsocks/wiki/Troubleshooting)
