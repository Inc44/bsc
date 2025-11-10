# bsc

![Stars](https://img.shields.io/github/stars/Inc44/bsc?style=social)
![Forks](https://img.shields.io/github/forks/Inc44/bsc?style=social)
![Watchers](https://img.shields.io/github/watchers/Inc44/bsc?style=social)
![Repo Size](https://img.shields.io/github/repo-size/Inc44/bsc)
![Language Count](https://img.shields.io/github/languages/count/Inc44/bsc)
![Top Language](https://img.shields.io/github/languages/top/Inc44/bsc)
[![Issues](https://img.shields.io/github/issues/Inc44/bsc)](https://github.com/Inc44/bsc/issues?q=is%3Aopen+is%3Aissue)
![Last Commit](https://img.shields.io/github/last-commit/Inc44/bsc?color=red)
[![Release](https://img.shields.io/github/release/Inc44/bsc.svg)](https://github.com/Inc44/bsc/releases)
[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/Inc44)

High-performance block-sorting data compressor.

## 🚀 Installation

```bash
git clone https://github.com/Inc44/bsc.git
cd libbsc # bsc-m03
makepkg -si
```

## 📦 Publish

```bash
mkdir ~/aur
mkdir ~/aur/libbsc # bsc-m03
cd ~/aur/libbsc # bsc-m03
```

Create:

```bash
cp ~/github/bsc/libbsc/PKGBUILD . # bsc-m03
makepkg --printsrcinfo > .SRCINFO
git -c init.defaultBranch=master init
git add PKGBUILD .SRCINFO
git commit -m "libbsc" # bsc-m03
git remote add aur ssh://aur@aur.archlinux.org/libbsc.git # bsc-m03
git push aur master
```

Update:

```bash
git clone ssh://aur@aur.archlinux.org/libbsc.git ~/aur/libbsc # bsc-m03
cp ~/github/bsc/libbsc/PKGBUILD . # bsc-m03
makepkg --printsrcinfo > .SRCINFO
git add PKGBUILD .SRCINFO
git commit -m "libbsc" # bsc-m03
git push
```

## 🙏 Thanks

Creator of:

- [libbsc](https://github.com/IlyaGrebnov/libbsc)
- [bsc-m03](https://github.com/IlyaGrebnov/bsc-m03)

## 🤝 Contribution

Contributions, suggestions, and new ideas are heartily welcomed. If you're considering significant modifications, please initiate an issue for discussion before submitting a pull request.

## 📜 License

[![GPL-3.0](https://img.shields.io/github/license/Inc44/MaTools)](https://opensource.org/licenses/GPL-3.0)

This project is licensed under the GPL-3.0 License. See the [LICENSE](LICENSE) file for details.

## 💖 Support

[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/xamituchido)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/inc44)
[![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/Inc44)