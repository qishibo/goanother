---

lang: zh-CN
description: 更快、更好、更稳定的Redis桌面(GUI)管理客户端，兼容Windows、Mac、Linux，性能出众，轻松加载海量键值


---

{{ site.lang }}
<img align="right" width="110" src="https://cdn.jsdelivr.net/gh/qishibo/img/ano-square-icon-128.png">

## Another Redis Desktop Manager

> <i>支持哨兵, 集群, ssh通道, ssl认证, stream, subscribe订阅, 树状视图, 命令行, 以及暗黑模式; 多种格式化方式, 甚至能够自定义格式化脚本, 满足你的一切需求.</i>

[![github @qishibo](https://img.shields.io/badge/Github-@qishibo-blue.svg)](https://github.com/qishibo)
[![twitter @qii404](https://img.shields.io/badge/Twitter-@qii404-blue.svg)](https://twitter.com/qii404)
[![shiboooo](https://img.shields.io/badge/Weibo-@shiboooo-blue.svg)](https://weibo.com/shiboooo?is_hot=1)


## 界面展示

![redis status dark](https://cdn.jsdelivr.net/gh/qishibo/img/1630655843497-status.png)

![redis key hash dark](https://cdn.jsdelivr.net/gh/qishibo/img/1630655844559-str.png)

![redis console dark](https://cdn.jsdelivr.net/gh/qishibo/img/1630655846107-cli.png)

![redis exec log](https://cdn.jsdelivr.net/gh/qishibo/img/1630655847740-log.png)


<span id="download"></span>

## 下载

**Windows**:
- 可以在[github](https://github.com/qishibo/AnotherRedisDesktopManager/releases) 或者 [gitee](https://gitee.com/qishibo/AnotherRedisDesktopManager/releases)下载`exe`安装包
- 或者通过**winget**: `winget install qishibo.AnotherRedisDesktopManager`
- 或者通过**chocolatey**: `choco install another-redis-desktop-manager`
- 或者通过Win Store**赞助**, 然后让Win Store帮你自动更新版本
<br/>[![windows store](https://cdn.jsdelivr.net/gh/qishibo/img/windows-store-icon182-56.png)](https://www.microsoft.com/store/apps/9MTD84X0JFHZ)

**Linux**：
- 可以在[github](https://github.com/qishibo/AnotherRedisDesktopManager/releases) 或者 [gitee](https://gitee.com/qishibo/AnotherRedisDesktopManager/releases)下载`AppImage`包
 - 或者通过**snap**: `sudo snap install another-redis-desktop-manager`
**Tips**: 如果选择私钥时提示权限不足，执行`sudo snap connect another-redis-desktop-manager:ssh-keys`来获取对~/.ssh文件夹的权限
<br/>[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/another-redis-desktop-manager)

**Mac** 用户:

> 如果通过brew或者dmg安装后无法打开，执行下面命令后再启动即可:<br>`sudo xattr -rd com.apple.quarantine /Applications/Another\ Redis\ Desktop\ Manager.app`

- 通过 **brew**: `brew install --cask another-redis-desktop-manager`
- 或者通过App Store**赞助**, 然后让App Store帮你自动更新版本
<br/>[![app store](https://cdn.jsdelivr.net/gh/qishibo/img/avail_app_store180.svg)](https://apps.apple.com/app/id1516451072)


## 里程碑

- 2023-05-26: Stream类型搜索支持 && 支持慢日志查询
- 2023-04-01: List类型搜索支持 && Deflate raw 支持
- 2022-10-07: Key列表方向键 && 内存分析支持指定文件夹
- 2022-08-05: 克隆连接 && Tabs右键和滚轮支持
- 2022-04-01: Protobuf 支持 && 内存占用分析
- 2022-03-03: 只读模式 && Mointor 支持
- 2022-01-24: 导出为命令支持
- 2022-01-05: 一次性加载全部key支持
- 2022-01-01: Brotli\Gzip\Deflate\解压缩支持 && RedisJSON支持
- 2021-11-26: JSON编辑支持 && 订阅支持
- 2021-08-30: 命令执行日志 && 快捷键
- 2021-08-16: 自定义文本视图
- 2021-06-30: 哨兵支持
- 2021-06-24: Redis>=6.0的ACL支持
- 2021-05-03: Stream 视图支持 && Cli命令行提示
- 2021-02-28: 链接颜色标记 && 搜索历史提示
- 2021-02-03: 多选支持 && Msgpack视图支持
- 2020-12-30: 树状列表
- 2020-11-03: Binary视图 && SSH Passparse\Timeout 支持
- 2020-09-04: SSH 集群支持 
- 2020-06-18: SSL/TLS 支持
- 2020-04-28: 页面缩放 && 大键值Scan操作 && 自动Json
- 2020-04-18: 不可见键值对支持
- 2020-04-04: 集群支持
- 2020-03-13: 暗黑模式
- 2020-02-16: SSH 私钥支持
- 2020-02-13: Cli新Tab打开
- 2019-06-14: 自定义字体支持
- 2019-05-28: Key列表调节宽度
- 2019-05-09: Hash List Set Zset搜索支持
- 2019-04-26: 自动更新
- 2019-04-09: SSH 通道支持
- 2019-04-01: 精确搜索
- 2019-02-22: 单链接支持
- 2019-01-08: 项目孵化



## 赞助

- 在[Github](https://github.com/qishibo/AnotherRedisDesktopManager)上点颗星⭐⭐
- 通过 [OpenCollective](https://opencollective.com/AnotherRedisDesktopManager)
- 通过[App Store](https://apps.apple.com/app/id1516451072)购买赞助
- 通过[Win Store](https://www.microsoft.com/store/apps/9MTD84X0JFHZ)购买赞助
- 微信赞赏码 [觉得好用就赞助一杯咖啡]

  <img width="150px" src="https://cdn.jsdelivr.net/gh/qishibo/img/202109031655807.jpeg" />


## 贡献者

项目的发展壮大离不开以下做过贡献的人
[![contributors](https://opencollective.com/AnotherRedisDesktopManager/contributors.svg?width=890&button=false)](https://github.com/qishibo/AnotherRedisDesktopManager/graphs/contributors)
[![backers](https://opencollective.com/AnotherRedisDesktopManager/backers.svg)](https://opencollective.com/AnotherRedisDesktopManager)


