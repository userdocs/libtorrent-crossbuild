# libtorrent crossbuilds

Multiarch crossbuilds to use with Debian based platforms.

Deb packages are created and published as releases.

[<img alt="Follow the white rabbit" width="100px" src="black-rabbit.png" />](https://github.com/userdocs/openssl-crossbuild)
[<img alt="Follow the white rabbit" width="100px" src="white-rabbit.png" />](https://github.com/userdocs/qt6-crossbuild)

```bash
wget "https://github.com/userdocs/libtorrent-crossbuild/releases/latest/download/$(. /etc/os-release && printf '%s' "$ID")-$(. /etc/os-release && printf '%s' "$VERSION_CODENAME")-cmake-$(dpkg --print-architecture).deb"
```