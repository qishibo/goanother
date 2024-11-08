---

lang: en-US
description: A faster, better and more stable redis desktop manager [GUI client], compatible with Linux, Windows, Mac. What's more, it won't crash when loading massive keys.


---

<img align="right" width="110" src="https://cdn.jsdelivr.net/gh/qishibo/img/ano-square-icon-128.png">

## Another Redis Desktop Manager

> <i>Supports redis-sentinel, redis-cluster, ssh-tunnel, ssl-cert, stream, subscribe, tree view, console, dark mode; Various formatting methods, and even custom formatting scripts, to meet all your needs.</i>

[![LICENSE](https://img.shields.io/github/license/qishibo/AnotherRedisDesktopManager)](LICENSE)
[![Release](https://img.shields.io/github/release/qishibo/AnotherRedisDesktopManager.svg)](https://github.com/qishibo/AnotherRedisDesktopManager/releases)
[![Download](https://img.shields.io/github/downloads/qishibo/AnotherRedisDesktopManager/total)](https://github.com/qishibo/AnotherRedisDesktopManager/releases)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fqishibo%2FAnotherRedisDesktopManager.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fqishibo%2FAnotherRedisDesktopManager?ref=badge_shield)
<a href="https://www.producthunt.com/posts/another-redis-desktop-manager?utm_source=badge-featured"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=340552&theme=dark" height="20" width="93" /></a>
[![STARS](https://img.shields.io/github/stars/qishibo/AnotherRedisDesktopManager)](https://github.com/qishibo/AnotherRedisDesktopManager/)


## Interface

![redis status dark](https://cdn.jsdelivr.net/gh/qishibo/img/ardm/202411081318491.png)

![redis key dark](https://cdn.jsdelivr.net/gh/qishibo/img/ardm/202411081318490.png)

![redis exec log](https://cdn.jsdelivr.net/gh/qishibo/img/ardm/202411081318492.png)


<span id="download"></span>

## Download

**Windows**:

- Download latest [exe](https://github.com/qishibo/AnotherRedisDesktopManager/releases) package from release \[or [gitee](https://gitee.com/qishibo/AnotherRedisDesktopManager/releases) in China\], double click to install.
- Or by **chocolatey**: `choco install another-redis-desktop-manager`
- Or by **winget**: `winget install qishibo.AnotherRedisDesktopManager`
- Or **sponsor** by win store, It's not free, and I will be very grateful to you.
<br/><a href="https://apps.microsoft.com/store/detail/9MTD84X0JFHZ?launch=true&cid=github&mode=mini"><img src="https://cdn.jsdelivr.net/gh/qishibo/img/microsoft-store.png" height="58" width="180" alt="get from microsoft store"></a>

**Linux**:

- Download latest [AppImage](https://github.com/qishibo/AnotherRedisDesktopManager/releases) package from release \[or [gitee](https://gitee.com/qishibo/AnotherRedisDesktopManager/releases) in China\], `chmod +x`, double click to run.
- Or by **snap**: `sudo snap install another-redis-desktop-manager`
 **Tips**: If permission denied when selecting private key, run `sudo snap connect another-redis-desktop-manager:ssh-keys` to give access to ~/.ssh folder.
<br/>[![Get it from the Snap Store](https://cdn.jsdelivr.net/gh/qishibo/img/ardm/202411080845423.svg)](https://snapcraft.io/another-redis-desktop-manager)


**Mac**:

> If you can't open it after installation by brew or dmg, exec the following command then reopen:<br>`sudo xattr -rd com.apple.quarantine /Applications/Another\ Redis\ Desktop\ Manager.app`

- Download latest [dmg](https://github.com/qishibo/AnotherRedisDesktopManager/releases) package from release \[or [gitee](https://gitee.com/qishibo/AnotherRedisDesktopManager/releases) in China\], double click to install.
- Or by **brew**: `brew install --cask another-redis-desktop-manager`
- Or **sponsor** by app store, It's not free, and I will be very grateful to you.
<br/>[![get from app store](https://cdn.jsdelivr.net/gh/qishibo/img/avail_app_store180.svg)](https://apps.apple.com/app/id1516451072)


## Feature Log

- 2024-11-03: Import batch commands from files
- 2024-10-07: Hash field TTL support(Redis>=7.4)
- 2024-06-06: Search connections support
- 2024-04-10: DB custom name support
- 2024-02-21: Java/Pickle viewers support
- 2024-02-15: Groups/Consumers in STREAM view
- 2024-01-31: Hey, long time! Command line(CLI) args support
- 2023-06-22: Export\Import keys support
- 2023-05-26: Search support in Stream && Slow log support
- 2023-04-01: Search support in List && Deflate raw support
- 2022-10-07: Arrow Keys support in key list && Memory Analysis in folder
- 2022-08-05: Clone Connection && Tabs Contextmenu\Mousewheel Support
- 2022-04-01: Protobuf Support && Memory Analysis
- 2022-03-03: Readonly Mode && Mointor Support
- 2022-01-24: Command Dump Support
- 2022-01-05: Support To Load All Keys
- 2022-01-01: Brotli\Gzip\Deflate Support && RedisJSON Support
- 2021-11-26: JSON Editable && Subscribe Support
- 2021-08-30: Execution log Support && Add Hot Keys
- 2021-08-16: Custom Formatter View Support!
- 2021-06-30: Sentinel Support!!
- 2021-06-24: ACL Support
- 2021-05-03: Stream Support && Cli Command Tips Support
- 2021-02-28: Connection Color Tag && Search History Support
- 2021-02-03: Multiple Select\Delete && Msgpack Viewer Support
- 2020-12-30: Tree View Support!!!
- 2020-11-03: Binary View Support && SSH Passparse\Timeout Support
- 2020-09-04: SSH Cluster Support && Extension Commands Support
- 2020-06-18: SSL/TLS Support!!!
- 2020-04-28: Page Zoom && Big Key Loads With Scan && Auto Json
- 2020-04-18: Unvisible Key\Value Format Support
- 2020-04-04: Cluster Support!!!
- 2020-03-13: Dark Mode Support!!! && JsonView In Other Place
- 2020-02-16: SSH Private Key Support
- 2020-02-13: Open Cli Console In Tabs
- 2019-06-14: Custom Font-Family Support
- 2019-05-28: Key List Resizable
- 2019-05-09: Search Support In Hash List Set Zset
- 2019-04-26: Auto Updater
- 2019-04-09: SSH Tunnel Connection Support
- 2019-04-01: Extract Search Support
- 2019-02-22: Single Connection Support
- 2019-01-08: Project Start


## Sponsor

- Give me a star ⭐ in [Github](https://github.com/qishibo/AnotherRedisDesktopManager)!
- Through [OpenCollective](https://opencollective.com/AnotherRedisDesktopManager)
- Buy from [App Store](https://apps.apple.com/app/id1516451072)
- Buy from [Win Store](https://www.microsoft.com/store/apps/9MTD84X0JFHZ)
- Wechat sponsor code

  <img width="150px" src="https://cdn.jsdelivr.net/gh/qishibo/img/202109031655807.jpeg" />


## Contributors

This project exists thanks to all the people who contribute.
[![contributors](https://opencollective.com/AnotherRedisDesktopManager/contributors.svg?width=890&button=false)](https://github.com/qishibo/AnotherRedisDesktopManager/graphs/contributors)
[![backers](https://opencollective.com/AnotherRedisDesktopManager/backers.svg)](https://opencollective.com/AnotherRedisDesktopManager)


