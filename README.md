# 自托管精选

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-dead-links.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-unmaintained-projects.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://img.shields.io/liberapay/goal/awesome-selfhosted?logo=liberapay)](https://liberapay.com/awesome-selfhosted/)

自托管是指在自己的服务器上托管和管理应用程序，而不是从[SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html)提供商那里消费。

这是一个可以托管在您自己的服务器上的[免费](https://en.wikipedia.org/wiki/Free_software)软件[网络服务](https://en.wikipedia.org/wiki/Network_service)和[Web应用程序](https://en.wikipedia.org/wiki/Web_application)的列表。非免费软件列在[非免费](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/non-free.md)页面上。

**[HTML版本](https://awesome-selfhosted.net/)（推荐）**，[Markdown版本](https://github.com/awesome-selfhosted/awesome-selfhosted)（旧版）。

请参阅[贡献](#contributing)。

--------------------

## 目录

- [软件](#软件)
  - [分析](#分析)
  - [归档和数字保存(DP)](#归档和数字保存-dp)
  - [自动化](#自动化)
  - [备份](#备份)
  - [博客平台](#博客平台)
  - [预订和日程安排](#预订和日程安排)
  - [书签和链接共享](#书签和链接共享)
  - [日历和联系人](#日历和联系人)
  - [通信 - 自定义通信系统](#通信---自定义通信系统)
  - [通信 - 电子邮件 - 完整解决方案](#通信---电子邮件---完整解决方案)
  - [通信 - 电子邮件 - 邮件传递代理](#通信---电子邮件---邮件传递代理)
  - [通信 - 电子邮件 - 邮件传输代理](#通信---电子邮件---邮件传输代理)
  - [通信 - 电子邮件 - 邮件列表和通讯](#通信---电子邮件---邮件列表和通讯)
  - [通信 - 电子邮件 - Webmail客户端](#通信---电子邮件---webmail客户端)
  - [通信 - IRC](#通信---irc)
  - [通信 - SIP](#通信---sip)
  - [通信 - 社交网络和论坛](#通信---社交网络和论坛)
  - [通信 - 视频会议](#通信---视频会议)
  - [通信 - XMPP - 服务器](#通信---xmpp---服务器)
  - [通信 - XMPP - Web客户端](#通信---xmpp---web客户端)
  - [社区支持农业(CSA)](#社区支持农业-csa)
  - [会议管理](#会议管理)
  - [内容管理系统(CMS)](#内容管理系统-cms)
  - [数据库管理](#数据库管理)
  - [DNS](#dns)
  - [文档管理](#文档管理)
  - [文档管理 - 电子书](#文档管理---电子书)
  - [文档管理 - 机构库和数字图书馆软件](#文档管理---机构库和数字图书馆软件)
  - [文档管理 - 集成图书馆系统(ILS)](#文档管理---集成图书馆系统-ils)
  - [电子商务](#电子商务)
  - [联合身份与认证](#联合身份与认证)
  - [Feed阅读器](#feed阅读器)
  - [文件传输和同步](#文件传输和同步)
  - [文件传输 - 分布式文件系统](#文件传输---分布式文件系统)
  - [文件传输 - 对象存储和文件服务器](#文件传输---对象存储和文件服务器)
  - [文件传输 - 对等文件共享](#文件传输---对等文件共享)
  - [文件传输 - 单击和拖放上传](#文件传输---单击和拖放上传)
  - [文件传输 - 基于Web的文件管理器](#文件传输---基于web的文件管理器)
  - [游戏](#游戏)
  - [游戏 - 管理工具和控制面板](#游戏---管理工具和控制面板)
  - [家谱](#家谱)
  - [群件](#群件)
  - [人力资源管理(HRM)](#人力资源管理-hrm)
  - [物联网(IoT)](#物联网-iot)
  - [库存管理](#库存管理)
  - [知识管理工具](#知识管理工具)
  - [学习和课程](#学习和课程)
  - [制造](#制造)
  - [地图和全球定位系统(GPS)](#地图和全球定位系统-gps)
  - [媒体流](#媒体流)
  - [媒体流 - 音频流](#媒体流---音频流)
  - [媒体流 - 多媒体流](#媒体流---多媒体流)
  - [媒体流 - 视频流](#媒体流---视频流)
  - [杂项](#杂项)
  - [金钱、预算和管理](#金钱-预算和管理)
  - [监控](#监控)
  - [笔记和编辑器](#笔记和编辑器)
  - [办公套件](#办公套件)
  - [密码管理器](#密码管理器)
  - [粘贴板](#粘贴板)
  - [个人仪表板](#个人仪表板)
  - [照片和视频画廊](#照片和视频画廊)
  - [投票和活动](#投票和活动)
  - [代理](#代理)
  - [食谱管理](#食谱管理)
  - [远程访问](#远程访问)
  - [资源规划](#资源规划)
  - [搜索引擎](#搜索引擎)
  - [自托管解决方案](#自托管解决方案)
  - [软件开发](#软件开发)
  - [软件开发 - API管理](#软件开发---api管理)
  - [软件开发 - 持续集成和部署](#软件开发---持续集成和部署)
  - [软件开发 - FaaS和无服务器](#软件开发---faas和无服务器)
  - [软件开发 - IDE和工具](#软件开发---ide和工具)
  - [软件开发 - 本地化](#软件开发---本地化)
  - [软件开发 - 低代码](#软件开发---低代码)
  - [软件开发 - 项目管理](#软件开发---项目管理)
  - [软件开发 - 测试](#软件开发---测试)
  - [静态站点生成器](#静态站点生成器)
  - [状态/运行时间页面](#状态-运行时间页面)
  - [任务管理和待办事项列表](#任务管理和待办事项列表)
  - [票务](#票务)
  - [时间跟踪](#时间跟踪)
  - [URL缩短器](#url缩短器)
  - [视频监控](#视频监控)
  - [VPN](#vpn)
  - [Web服务器](#web服务器)
  - [维基](#维基)
- [许可证列表](#许可证列表)
- [反功能](#反功能)
- [外部链接](#外部链接)
- [贡献](#贡献)
- [许可证](#许可证)

--------------------


question = r"""
将一下文本翻译成中文，切记保持md格式

## Software

### Analytics

**[`^        back to top        ^`](#awesome-selfhosted)**

[Analytics](https://en.wikipedia.org/wiki/Analytics) is the systematic computational analysis of data or statistics. It is used for the discovery, interpretation, and communication of meaningful patterns in data.

## 软件

### 分析

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[分析](https://en.wikipedia.org/wiki/Analytics)是对数据或统计数据的系统化计算分析。它用于发现、解释和传达数据中的有意义模式。

_相关：[数据库管理](#database-management)，[个人仪表板](#personal-dashboards)_

- [Aptabase](https://aptabase.com/) - 开源、优先隐私且简单的移动和桌面应用程序分析工具。([源代码](https://github.com/aptabase/aptabase)) `AGPL-3.0` `Docker`
- [AWStats](http://www.awstats.org/) - 从Web、流媒体、FTP或邮件服务器日志文件生成统计数据。([演示](https://www.awstats.org/#DEMO), [源代码](https://github.com/eldy/awstats)) `GPL-3.0` `Perl`
- [Countly Community Edition](https://count.ly) - 实时移动和Web分析、崩溃报告和推送通知平台。([源代码](https://github.com/countly)) `AGPL-3.0` `Nodejs/Docker`
- [Druid](http://druid.io/) - 分布式、面向列的实时分析数据存储。([源代码](https://github.com/apache/druid)) `Apache-2.0` `Java/Docker`
- [EDA](https://github.com/jortilles/EDA) - 用于数据分析和可视化的Web应用程序。`AGPL-3.0` `Nodejs/Docker`
- [GoAccess](http://goaccess.io/) - 实时Web日志分析器和交互式查看器，可在终端中运行。([源代码](https://github.com/allinurl/goaccess)) `GPL-2.0` `C`
- [GoatCounter](https://www.goatcounter.com) - 无需跟踪个人数据的简单Web统计。([源代码](https://github.com/arp242/goatcounter)) `EUPL-1.2` `Go`
- [Litlyx](https://litlyx.com) - 30秒内设置的全能分析解决方案。在AI驱动的仪表板上显示所有数据。完全可以自托管并符合GDPR。([源代码](https://github.com/Litlyx/litlyx)) `Apache-2.0` `Docker`
- [Matomo](https://matomo.org/) - 保护您的数据和客户隐私的Google Analytics替代品。([源代码](https://github.com/matomo-org/matomo)) `GPL-3.0` `PHP`
- [Metabase](https://metabase.com/) - 让您公司中的每个人都能轻松地从数据中提出问题和学习的开源方式。([源代码](https://github.com/metabase/metabase)) `AGPL-3.0` `Java/Docker`
- [Middleware](https://middlewarehq.com/) - 帮助工程领导者使用DORA指标衡量和分析团队有效性的工具。([源代码](https://github.com/middlewarehq/middleware)) `Apache-2.0` `Docker/Python/Nodejs`
- [Mixpost](https://mixpost.app/) - 自托管的社交媒体管理软件。轻松创建、计划、发布和管理一个地方的社交媒体内容（Hootsuite、Buffer等社交媒体工具的替代品）。([源代码](https://github.com/inovector/MixpostApp)) `MIT` `PHP/Docker`
- [Netron](https://netron.app/) - 神经网络和机器学习模型的可视化工具。([源代码](https://github.com/lutzroeder/netron)) `MIT` `Python/Nodejs`
- [Offen](https://www.offen.dev/) - 公平、轻量级和开放的Web分析工具。在用户完全访问他们的数据的同时，获取洞察。([演示](https://www.offen.dev/try-demo/), [源代码](https://github.com/offen/offen)) `Apache-2.0` `Go/Docker`
- [Open Web Analytics](http://www.openwebanalytics.com/) - 让您控制如何检测和分析您网站和应用程序使用的Web分析框架。([源代码](https://github.com/Open-Web-Analytics/Open-Web-Analytics)) `GPL-2.0` `PHP`
- [Plausible Analytics](https://plausible.io/) - 简单、开源、轻量级（< 1 KB）和注重隐私的Web分析。([源代码](https://github.com/plausible/analytics/)) `AGPL-3.0` `Elixir`
- [PostHog](https://posthog.com) - 您可以自托管的产品分析、会话记录、功能标记和A/B测试（Mixpanel/Amplitude/Heap/HotJar/Optimizely的替代品）。([源代码](https://github.com/posthog/posthog)) `MIT` `Python`
- [Prisme Analytics](https://www.prismeanalytics.com) - 基于Grafana的隐私优先和渐进式分析服务。([演示](https://app.prismeanalytics.com/grafana), [源代码](https://github.com/prismelabs/analytics)) `AGPL-3.0/MIT` `Docker`
- [Redash](http://redash.io) - 连接和查询您的数据源，构建可视化数据的仪表板并与您的公司共享它们。([源代码](https://github.com/getredash/redash)) `BSD-2-Clause` `Docker`
- [RudderStack](https://rudderstack.com/) - 收集、统一、转换和存储您的客户数据，并将其路由到广泛的常见、流行的营销、销售和产品工具（Segment的替代品）。([源代码](https://github.com/rudderlabs/rudder-server/)) `AGPL-3.0` `Docker/K8S/Go/Nodejs`
- [Shynet](https://github.com/milesmcc/shynet) - 现代、隐私友好且详细的Web分析，无需使用cookie或JS即可工作。`Apache-2.0` `Python/Docker`
- [Socioboard](https://github.com/socioboard/Socioboard-5.0) `None⚠` - 支持九个社交媒体网络的社交媒体管理、分析和报告平台。`GPL-3.0` `Nodejs`
- [Superset](http://superset.apache.org/) - 现代数据探索和可视化平台。([源代码](https://github.com/apache/superset)) `Apache-2.0` `Python`
- [Swetrix](https://swetrix.com/) - 满足您所有需求的终极、开源Web分析。([演示](https://swetrix.com/projects/STEzHcB1rALV), [源代码](https://github.com/Swetrix/selfhosting)) `AGPL-3.0` `Docker`
- [Umami](https://umami.is/) - 简单、快速、注重隐私的Google Analytics替代品。([演示](https://analytics.umami.is/share/LGazGOecbDtaIwDr/umami.is), [源代码](https://github.com/umami-software/umami)) `MIT` `Nodejs/Docker`


### 归档和数字保存（DP）

**[`^        返回顶部        ^`](#awesome-selfhosted)**

数字[归档](https://en.wikipedia.org/wiki/Archival_science)和[保存](https://en.wikipedia.org/wiki/Digital_preservation)软件。

_相关：[内容管理系统（CMS）](#content-management-systems-cms)_

_另见：[awesome-web-archiving](https://github.com/iipc/awesome-web-archiving)_

- [ArchiveBox](https://archivebox.io/) - 自托管的_wayback machine_，从您的书签、浏览历史、RSS提要或其他来源创建网站的HTML和屏幕截图归档。([源代码](https://github.com/ArchiveBox/ArchiveBox)) `MIT` `Python/Docker`
- [ArchivesSpace](https://archivesspace.org/) - 用于管理和提供Web访问归档、手稿和数字对象的档案信息管理应用程序。([演示](https://archivesspace.org/application/sandbox), [源代码](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- [bitmagnet](https://bitmagnet.io) - 自托管的BitTorrent索引器、DHT爬虫、内容分类器和种子搜索引擎，具有Web UI、GraphQL API和Servarr堆栈集成。([源代码](https://github.com/bitmagnet-io/bitmagnet)) `MIT` `Go/Docker`
- [CKAN](https://ckan.org) - CKAN是用于创建开放数据网站的工具。([源代码](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- [Collective Access - Providence](https://collectiveaccess.org/) - 高度可配置的基于Web的框架，用于管理、描述和发现数字和物理收藏，支持多种元数据标准、数据类型和媒体格式。([源代码](https://github.com/collectiveaccess/providence)) `GPL-3.0` `PHP`
- [Ganymede](https://github.com/Zibbp/ganymede) `None⚠` - Twitch VOD和直播归档平台。为每个归档提供渲染的聊天记录。`GPL-3.0` `Docker`
- [LiveStreamDVR](https://github.com/MrBrax/LiveStreamDVR) `None⚠` - 能够捕获直播、聊天消息和流元数据的自动Twitch录制器。`MIT` `Python/Nodejs/Docker`
- [Omeka S](https://omeka.org/s/) - Omeka S是大学、画廊、图书馆、档案馆和博物馆的Web发布系统。它由一个本地网络组成，该网络由独立策划的展览分享协作构建的项目、媒体和它们的元数据。([源代码](https://github.com/omeka/omeka-s)) `GPL-3.0` `Nodejs`
- [Wallabag](https://www.wallabag.org) - Wallabag，以前称为Poche，是一个Web应用程序，允许您保存文章以便稍后阅读，并提高可读性。([源代码](https://github.com/wallabag/wallabag)) `MIT` `PHP`
- [Wayback](https://github.com/wabarc/wayback) - 一个自托管的工具包，用于将网页归档到Internet Archive、archive.today、IPFS和本地文件系统。`GPL-3.0` `Go`
- [Webarchive](https://github.com/derfenix/webarchive) - 轻量级自托管的_wayback machine_，从您的书签创建HTML和PDF文件。`BSD-3-Clause` `Go`


### 自动化

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[自动化](https://en.wikipedia.org/wiki/Automation)软件旨在减少流程中的人为干预。

_相关：[物联网（IoT）](#internet-of-things-iot)，[软件开发 - 持续集成与部署](#software-development---continuous-integration--deployment)_

- [Activepieces](https://www.activepieces.com) - 像Zapier或Tray一样的无代码业务自动化工具。例如，您可以为每个新的Trello卡片发送Slack通知。([源代码](https://github.com/activepieces/activepieces)) `MIT` `Docker`
- [Apache Airflow](https://airflow.apache.org/) - Airflow是一个用于以编程方式编写、调度和监控工作流的平台。([源代码](https://github.com/apache/airflow/)) `Apache-2.0` `Python/Docker`
- [Automatisch](https://automatisch.io) - 允许您连接不同的服务，如Twitter、Slack等，以自动化您的业务流程的业务自动化工具（Zapier的替代品）。([源代码](https://github.com/automatisch/automatisch)) `AGPL-3.0` `Docker`
- [betanin](https://github.com/sentriz/betanin) - 音乐组织中间件，您的种子客户端和音乐播放器之间的中间件。基于beets.io，类似于Sonarr和Radarr。`GPL-3.0` `Python/Docker`
- [changedetection.io](https://github.com/dgtlmoon/changedetection.io) - 用于保持网站内容变更的最新状态的自托管工具。`Apache-2.0` `Python/Docker`
- [ChiefOnboarding](https://chiefonboarding.com) - 员工入职平台，允许您配置用户账户并创建包含待办事项、资源、文本/电子邮件/Slack消息等的序列！可作为Web门户和Slack机器人使用。([源代码](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Docker`
- [Dagu](https://dagu.readthedocs.io/) - 具有Web UI的强大Cron替代品。它允许您以声明性的YAML格式定义命令之间的依赖关系，作为有向无环图（DAG）。([源代码](https://github.com/dagu-dev/dagu)) `GPL-3.0` `Go/Docker`
- [Discount Bandit](https://discount-bandit.cybrarist.com/) `None⚠` - 跨多个商店（如Amazon、Ebay、Walmart等）跟踪产品的定价和库存状态。([演示](https://discount-bandit.cybrarist.com/screenshots.html), [源代码](https://github.com/Cybrarist/Discount-Bandit)) `GPL-3.0` `PHP/Docker`
- [Dittofeed](https://www.dittofeed.com) - 全渠道客户参与和消息自动化平台（Braze、Customer.io、Iterable的替代品）。([演示](https://demo.dittofeed.com/dashboard/journeys), [源代码](https://github.com/dittofeed/dittofeed)) `MIT` `Docker`
- [feedmixer](https://github.com/cristoper/feedmixer) - FeedMixer是一个WSGI（Python3）微型Web服务，它接受一系列提要URL，并返回一个由每个给定提要的最新n个条目组成的新提要（返回Atom、RSS或JSON）。([演示](https://mretc.net/feedmixer/json?f=https://hnrss.org/newest&f=https://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
- [Github Ntfy](https://github.com/BreizhHardware/ntfy_alerts) `None⚠` - 当Docker Hub或Github上发布新版本时，向NTFY推送通知。([客户端](https://github.com/binwiederhier/ntfy)) `GPL-3.0` `Docker`
- [HandBrake Web](https://github.com/TheNickOfTime/handbrake-web) - 通过Web界面在无头设备上使用一个或多个HandBrake视频转码器实例的平台。`AGPL-3.0` `Docker`
- [Headphones](https://github.com/rembo10/headphones) - 用于NZB和Torrent的自动音乐下载器，用Python编写。它支持SABnzbd、NZBget、Transmission、µTorrent、Deluge和Blackhole。`GPL-3.0` `Python`
- [Healthchecks](https://healthchecks.io/) - 监听ping并在ping延迟时发送警报的Django应用程序。([源代码](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- [HRConvert2](https://github.com/zelon88/HRConvert2) - 具有会话身份验证、自动临时文件维护和日志记录功能的拖放式文件转换服务器。`GPL-3.0` `PHP`
- [Huginn](https://github.com/huginn/huginn) - 允许您构建代理来监控并代表您采取行动。`MIT` `Ruby`
- [Kestra](https://kestra.io) - 事件驱动的、语言无关的平台，用于创建、调度和监控工作流程。用代码协调数据管道和任务，如ETL和ELT。([源代码](https://github.com/kestra-io/kestra)) `Apache-2.0` `Docker`
- [Kibitzr](https://kibitzr.github.io) - 具有强大集成的轻量级个人Web助手。([源代码](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [Krayin](https://krayincrm.com/) - 免费和开源的Laravel CRM应用程序。([演示](https://demo.krayincrm.com/), [源代码](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `None⚠` - LazyLibrarian是一个程序，用于跟踪作者并为您所有的数字阅读需求抓取元数据。它使用Goodreads Librarything和可选的GoogleBooks作为作者信息和书籍信息的来源。`GPL-3.0` `Python`
- [Leon](https://getleon.ai) - 可以生活在您服务器上的开源个人助手。([源代码](https://github.com/leon-ai/leon)) `MIT` `Nodejs`
- [Lidarr](https://lidarr.audio/) - Lidarr是一个音乐收藏管理器，适用于Usenet和BitTorrent用户。([源代码](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#/Docker`
- [LidaTube](https://github.com/TheWicklowWolf/LidaTube) - 通过yt-dlp查找并获取缺少的Lidarr专辑。`GPL-3.0` `Docker`
- [Matchering](https://github.com/sergree/matchering) - 一个容器化的Web应用，用于自动音乐母带制作（LANDR、eMastered和MajorDecibel的替代品）。`GPL-3.0` `Docker`
- [Medusa](https://pymedusa.com/) - 自动电视节目视频库管理器。它会监视您喜欢的节目的新剧集，当它们发布时，它会施展它的魔法。([源代码](https://github.com/pymedusa/Medusa), [客户端](https://github.com/medusajs/nextjs-starter-medusa)) `GPL-3.0` `Python`
- [MetaTube](https://github.com/JVT038/MetaTube) `None⚠` - 一个用于从YouTube自动下载音乐并从Spotify、Deezer或Musicbrainz添加元数据的Web GUI。`GPL-3.0` `Python`
- [MeTube](https://github.com/alexta69/metube) - youtube-dl的Web GUI，支持播放列表。允许从数十个网站下载视频。`AGPL-3.0` `Python/Nodejs/Docker`
- [Mylar3](https://mylarcomics.com/) - 用于从NZB和种子下载漫画书（cbr/cbz）的自动化程序。([源代码](https://github.com/mylar3/mylar3)) `GPL-3.0` `Python/Docker`
- [nefarious](https://github.com/lardbit/nefarious) - 自动下载电影和电视节目的Web应用程序。`GPL-3.0` `Python`
- [OliveTin](https://github.com/OliveTin/OliveTin) - OliveTin是一个用于运行Linux shell命令的Web界面。`AGPL-3.0` `Go`
- [PlexRipper](https://www.plexripper.rocks/) `None⚠` - 一个跨平台的Plex媒体下载器，可以无缝地从其他Plex服务器添加媒体到您自己的服务器。([源代码](https://github.com/PlexRipper/PlexRipper)) `GPL-3.0` `Docker`
- [pyLoad](https://pyload.net/) - 轻量级、可定制且可远程管理的一键托管网站（如rapidshare.com或uploaded.to）的下载器。([源代码](https://github.com/pyload/pyload)) `GPL-3.0` `Python`
- [Radarr](https://radarr.video/) - Radarr是Sonarr的一个独立分支，重新设计用于通过Usenet和BitTorrent自动下载电影，类似于Couchpotato。([源代码](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#/Docker`
- [SickChill](https://sickchill.github.io/) - SickChill是一个自动电视节目视频库管理器。它会监视您喜欢的节目的新剧集，当它们发布时，它会施展它的魔法。([源代码](https://github.com/SickChill/SickChill)) `GPL-3.0` `Python/Docker`
- [Sonarr](https://sonarr.tv/) - 用于从Usenet和BitTorrent自动下载和管理电视节目的工具。它可以抓取、分类和重命名新剧集，并在更高质量的格式可用时自动升级已下载文件的质量。([源代码](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#/Docker`
- [StackStorm](https://stackstorm.com) - StackStorm（又名_IFTTT for Ops_）是用于自动修复、安全响应、故障排除、部署等的事件驱动自动化。包括规则引擎、工作流程、160个集成包和6000多个操作以及ChatOps。([源代码](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- [tubesync](https://github.com/meeb/tubesync) `None⚠` - 将YouTube频道和播放列表同步到本地托管的媒体服务器。`AGPL-3.0` `Docker/Python`
- [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng) - 在远程服务器上启动下载的简单youtube-dl REST API。`GPL-3.0` `Python`
- [YoutubeDL-Material](https://github.com/Tzahi12345/YoutubeDL-Material) - 基于youtube-dl的Material Design启发的YouTube下载器。支持播放列表、质量选择、搜索、暗模式等，所有这些都具有干净而现代的设计。`MIT` `Nodejs/Docker`
- [YoutubeDL-Server](https://github.com/nbr23/youtube-dl-server) - 用于将视频下载到服务器上的Web和REST接口。`MIT` `Python/Docker`
- [yt-dlp Web UI](https://github.com/marcopeocchi/yt-dlp-web-ui) - yt-dlp的Web GUI。`MPL-2.0` `Docker/Go/Nodejs`
- [µTask](https://github.com/ovh/utask) - 模型并执行以yaml声明的业务流程的自动化引擎。`BSD-3-Clause` `Go/Docker`


### 备份

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[备份](https://en.wikipedia.org/wiki/Backup)软件。

**请访问 [awesome-sysadmin/Backups](https://github.com/awesome-foss/awesome-sysadmin#backups)**



### 博客平台

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[博客](https://en.wikipedia.org/wiki/Blog)是一个由离散的、日记风格的文本条目（None帖子）组成的讨论或信息网站。

_相关：[静态网站生成器](#static-site-generators)，[内容管理系统（CMS）](#content-management-systems-cms)_

另请参阅：[WeblogMatrix](https://www.weblogmatrix.org/)

- [Antville](https://antville.org) - 免费的开源项目，旨在开发高性能、功能丰富的博客托管软件。([源代码](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [Castopod](https://castopod.org) - 一个包含最新播客2.0标准、自动化的Fediverse订阅源、分析功能、可嵌入播放器等功能的播客管理托管平台。([源代码](https://code.castopod.org/adaures/castopod)) `AGPL-3.0` `PHP/Docker`
- [Chyrp Lite](https://chyrplite.net) - 超棒的、超轻量的博客引擎。([源代码](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dotclear](https://git.dotclear.org/dev/dotclear) - 掌控你的博客。`GPL-2.0` `PHP`
- [FlatPress](https://flatpress.org/) - 一个轻量级、易于设置的平面文件博客引擎。([源代码](https://github.com/flatpressblog/flatpress)) `GPL-2.0` `PHP`
- [Ghost](https://ghost.org/) - 只是一个博客平台。([源代码](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Haven](https://havenweb.org/) - 带有markdown编辑和内置RSS阅读器的私人博客系统。([演示](https://havenweb.org/demo.html), [源代码](https://github.com/havenweb/haven)) `MIT` `Ruby`
- [HTMLy](https://www.htmly.com/) - 无数据库的PHP博客平台。一个允许你在几秒钟内创建快速、安全和强大的网站或博客的平面文件CMS。([演示](http://demo.htmly.com/), [源代码](https://github.com/danpros/htmly), [客户端](https://www.htmly.com/theme/)) `GPL-2.0` `PHP`
- [Known](https://withknown.com/) - 一个协作式社交发布平台。([源代码](https://github.com/idno/known)) `Apache-2.0` `PHP`
- [Mataroa](https://mataroa.blog/) - Mataroa是一个适合极简主义者的裸露博客平台。([源代码](https://github.com/mataroa-blog/mataroa)) `MIT` `Python`
- [PluXml](https://pluxml.org) - 基于XML的博客/CMS平台。([源代码](https://github.com/pluxml/PluXml)) `GPL-3.0` `PHP`
- [Serendipity](https://docs.s9y.org/) - Serendipity (s9y)是一个高度可扩展和可定制的PHP博客引擎，使用Smarty模板引擎。([源代码](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`
- [WriteFreely](https://writefreely.org) - 用于启动极简主义、联邦博客或整个社区的写作软件。([源代码](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### 预订和调度

**[`^        回到顶部        ^`](#awesome-selfhosted)**

事件调度、预订和预约管理软件。

相关：[投票和活动](#polls-and-events)

- [Alf.io](https://alf.io/) - 开源的票务预订系统。([演示](https://demo.alf.io/authentication), [源代码](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Cal.com](https://cal.com/) - 开源的在线预约调度系统。([演示](https://app.cal.com/bailey), [源代码](https://github.com/calcom/cal.com)) `MIT` `Nodejs`
- [Easy!Appointments](https://easyappointments.org/) - 高度可定制的网络应用程序，允许你的客户通过网络与你预约。([演示](https://demo.easyappointments.org/), [源代码](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`
- [Hi.Events](https://hi.events) - 适用于会议、音乐会等的活动管理和票务平台。提供可定制的活动页面和可嵌入的票务小部件。([演示](https://demo.hi.events/event/1/dog-conf-2030), [源代码](https://github.com/HiEventsDev/hi.events)) `AGPL-3.0` `Docker`
- [QloApps](https://qloapps.com/) - 一个开源的、可定制的和直观的基于网络的酒店预订系统和预订引擎。([演示](https://demo.qloapps.com/), [源代码](https://github.com/webkul/hotelcommerce)) `OSL-3.0` `PHP/Nodejs`
- [Rallly](https://rallly.co) - 创建投票以选择日期和时间（Doodle的替代品）。([演示](https://app.rallly.co), [源代码](https://github.com/lukevella/rallly)) `AGPL-3.0` `Nodejs/Docker`
- [Seatsurfing](https://seatsurfing.app/) - 基于网络的应用程序，用于办公室的座位、办公桌和房间预订。([源代码](https://github.com/seatsurfing/backend)) `GPL-3.0` `Docker`


### 书签和链接共享

**[`^        回到顶部        ^`](#awesome-selfhosted)**

允许用户添加、注释、编辑和共享[书签](https://en.wikipedia.org/wiki/Bookmark_(digital))的软件。

- [Briefkasten](https://github.com/ndom91/briefkasten) - 用于保存和管理你自己的书签的现代应用程序。包括一个浏览器扩展。([演示](https://briefkastenhq.com/auth/signin)) `MIT` `Nodejs/Docker`
- [Buku](https://github.com/jarun/Buku) - 一个功能强大的书签管理器和个人文本迷你网页。`GPL-3.0` `Python/deb`
- [Digibunch](https://ladigitale.dev/digibunch/#/) - 创建链接None捆绑，与你的学习者或同事共享。([演示](https://ladigitale.dev/digibunch/#/b/5f67b12092b60), [源代码](https://codeberg.org/ladigitale/digibunch)) `AGPL-3.0` `Nodejs/PHP`
- [Espial](https://github.com/jonschoning/espial) - 一个开源的、基于网络的书签服务器。`AGPL-3.0` `Haskell`
- [Firefox Account Server](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - 这允许你托管自己的Firefox账户服务器。([源代码](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs/Java`
- [Grimoire](https://grimoire.pro) - 带有现代用户界面、自动内容和元数据提取、分类、过滤等功能的书签管理器。它具有完全文档化的REST API和用于易于部署的Docker镜像。([源代码](https://github.com/goniszewski/grimoire)) `MIT` `Nodejs/Docker`
- [Hackershare](https://github.com/hackershare/hackershare) - 面向黑客的社交书签网站。`MIT` `Ruby`
- [Hoarder App](https://hoarder.app/) - 一个可以自托管的书签一切应用，带有一点AI功能，适用于数据None囤积者。([演示](https://try.hoarder.app), [源代码](https://github.com/hoarder-app/hoarder)) `AGPL-3.0` `Docker`
- [LinkAce](https://www.linkace.org/) - 一个带有自动备份到Internet Archive、链接监控和完整REST API的书签档案。通过Docker或作为简单的PHP应用程序进行安装。([演示](https://demo.linkace.org/guest/links), [源代码](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `Docker/PHP`
- [linkding](https://github.com/sissbruecker/linkding) - 最小化的书签管理，具有快速且干净的用户界面。通过Docker进行简单安装，并且可以运行在你的Raspberry Pi上。`MIT` `Docker/Python/Nodejs`
- [LinkWarden](https://linkwarden.app/) - 一个自托管的书签和档案管理器，用于存储你有用的链接。([源代码](https://github.com/linkwarden/linkwarden)) `MIT` `Docker/Nodejs`
- [NeonLink](https://github.com/AlexSciFier/neonlink) - 自托管的书签服务，具有独特的设计和通过Docker进行简单的安装。`MIT` `Docker`
- [Readeck](https://readeck.org/en/) - Readeck是一个简单的网络应用程序，让你保存你喜欢并希望永远保留的网页的珍贵可读内容。将其视为一个书签管理器和稍后阅读工具。([源代码](https://codeberg.org/readeck/readeck), [客户端](https://codeberg.org/readeck/browser-extension)) `AGPL-3.0` `Go/Docker`
- [Servas](https://github.com/beromir/Servas) - 一个自托管的书签管理工具。它允许通过标签、组和专门用于稍后访问的列表进行组织。它支持多个用户并具有2FA。提供Firefox和Chrome的浏览器扩展作为伴None侣。([客户端](https://github.com/beromir/Servas#browser-extensions)) `GPL-3.0` `Docker/Nodejs/PHP`
- [Shaarli](https://github.com/shaarli/Shaarli) - 个人、极简、超快、无数据库的书签和链接共享平台。([演示](https://demo.shaarli.org)) `Zlib` `PHP/deb`
- [Shiori](https://github.com/go-shiori/shiori) - 用Go构建的简单书签管理器。`MIT` `Go/Docker`
- [Slash](https://github.com/boojack/slash) - 一个开源的、自托管的书签和链接共享平台。`GPL-3.0` `Docker`
- [SyncMarks](https://codeberg.org/Offerel/SyncMarks-Webapp) - 从Edge、Firefox和Chromium同步和管理你的浏览器书签。([客户端](https://codeberg.org/Offerel/SyncMarks-Extension)) `AGPL-3.0` `PHP`


### 日历和联系人

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[CalDAV](https://en.wikipedia.org/wiki/CalDAV)和[CardDAV](https://en.wikipedia.org/wiki/CardDAV)协议服务器和网络客户端/界面，用于[电子日历](https://en.wikipedia.org/wiki/Calendaring_software)、[地址None簿](https://en.wikipedia.org/wiki/Address_book)和[联系人管理](https://en.wikipedia.org/wiki/Contact_manager)。

相关：[群件](#groupware)

另请参阅：[CalDAV和CardDAV实现比较 - 维基百科](https://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations)

- [Baïkal](https://sabre.io/baikal/) - 基于sabre/dav的轻量级CalDAV和CardDAV服务器。([源代码](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [DAViCal](https://www.davical.org/) - 用于日历共享（CalDAV）的服务器，使用PostgreSQL数据库作为数据存储。([源代码](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP/deb`
- [Davis](https://github.com/tchapi/davis) - 基于sabre/dav的简单、可容器化的且完全可翻译的管理界面，基于Symfony 5和Bootstrap 4，受Baïkal的启发。`MIT` `PHP`
- [Etebase (EteSync)](https://www.etebase.com/) - 端到端加密和记录化的个人信息服务器，支持日历和联系人数据，提供自己的客户端。([源代码](https://github.com/etesync/server)) `AGPL-3.0` `Python/Django`
- [EteSync Web](https://www.etesync.com/faq/#web-client) - EteSync的官方网络客户端（即他们的Web应用程序）。([演示](https://client.etesync.com/), [源代码](https://github.com/etesync/etesync-web)) `AGPL-3.0` `Javascript`
- [Manage My Damn Life](https://github.com/intri-in/manage-my-damn-life-nextjs) - Manage my Damn Life (MMDL)是一个用于管理你的CalDAV任务和日历的自托管前端。`GPL-3.0` `Nodejs/Docker`
- [Radicale](https://radicale.org/) - 简单且管理开销极低的日历和联系人服务器。([源代码](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python/deb`
- [SabreDAV](https://sabre.io/) - 开源的CardDAV、CalDAV和WebDAV框架和服务器。([源代码](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://github.com/jelmer/xandikos) - 开源的CardDAV和CalDAV服务器，具有最小的管理开销，由Git存储库支持。`GPL-3.0` `Python/deb`


### 通信 - 自定义通信系统

**[`^        回到顶部        ^`](#awesome-selfhosted)**

用于提供远程访问系统和在不同计算机或用户之间以文本、音频和/或视频格式交换文件和消息的[通信软件](https://en.wikipedia.org/wiki/Communication_software)，使用它们自己的自定义协议。

- [AnyCable](https://anycable.io/) - 用于通过WebSocket、Server-sent事件等进行可靠双向通信的实时服务器。([演示](https://demo.anycable.io), [源代码](https://github.com/anycable/anycable-go)) `MIT` `Go/Docker`
- [Apprise](https://github.com/caronc/apprise) - Apprise允许你向我们今天可用的几乎所有最流行的通知服务发送通知，例如：Telegram、Discord、Slack、Amazon SNS、Gotify等。`MIT` `Python/Docker/deb`
- [Centrifugo](https://centrifugal.dev/) - 语言无关的实时消息传递（WebSocket或SockJS）服务器。([演示](https://github.com/centrifugal/centrifugo#demo), [源代码](https://github.com/centrifugal/centrifugo)) `MIT` `Go/Docker/K8S`
- [Chatwoot](https://www.chatwoot.com) - 自托管的客户通信平台（Intercom和Zendesk的替代品）。([源代码](https://github.com/chatwoot/chatwoot)) `MIT` `Ruby/Docker/K8S`
- [Chitchatter](https://chitchatter.im/) - 一个无服务器、去中心化和短暂的点对点聊天应用程序。([源代码](https://github.com/jeremyckahn/chitchatter)) `GPL-2.0` `Nodejs`
- [Conduit](https://conduit.rs/) - 一个由Matrix驱动的简单、快速且可靠的聊天服务器。([源代码](https://gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- [conduwuit](https://conduwuit.puppyirl.gay) - 维护良好、功能丰富的Matrix聊天家庭服务器（Conduit的分支）。([源代码](https://github.com/girlbossceo/conduwuit)) `Apache-2.0` `Rust`
- [Darkwire.io](https://github.com/darkwire/darkwire.io) - 端到端加密的即时网络聊天。`MIT` `Nodejs`
- [Databag](https://github.com/balzack/databag) - 支持文本、照片、视频以及WebRTC视频和音频通话的联邦、端到端加密的网络、iOS和Android的消息服务。([演示](https://databag.coredb.org/#/create)) `Apache-2.0` `Docker`
- [Element](https://element.io) - 完全功能的Matrix客户端，适用于Web、iOS和Android。([源代码](https://github.com/vector-im/element-web)) `Apache-2.0` `Nodejs`
- [GlobaLeaks](https://www.globaleaks.org/) - 允许任何人轻松设置和维护一个安全举报平台的举报软件。([演示](https://demo.globaleaks.org), [源代码](https://github.com/globaleaks/whistleblowing-software)) `AGPL-3.0` `Python/deb/Docker`
- [GNUnet](https://gnunet.org/) - 用于去中心化、点对点网络的免费软件框架。([源代码](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - 自托管的通知服务器，带有Android和CLI客户端，类似于PushBullet。([源代码](https://github.com/gotify/server), [客户端](https://github.com/gotify/android)) `MIT` `Go/Docker`
- [Hyphanet](https://hyphanet.org/) - None匿名共享文件、浏览和发布_freesites_（仅通过Hyphanet可访问的网站）并在论坛上聊天。([源代码](https://github.com/hyphanet/fred)) `GPL-2.0` `Java`
- [Jami](https://jami.net/) - 保留用户隐私和自由的免费和通用的通信平台（前GNU Ring）。([源代码](https://git.jami.net/savoirfairelinux?sort=latest_activity_desc&filter=jami)) `GPL-3.0` `C++`
- [KChat](https://github.com/php-kchat/kchat) - 基于PHP的实时聊天应用程序。`Apache-2.0` `PHP`
- [Live Helper Chat](https://livehelperchat.com/) - 用于你网站的实时支持聊天。([源代码](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [Mattermost](https://mattermost.com/) - 用于整个软件开发生命周期的安全协作平台，可以与Gitlab集成（Slack的替代品）。([源代码](https://github.com/mattermost/mattermost)) `AGPL-3.0/Apache-2.0` `Go/Docker/K8S`
- [MiAOU](https://miaou.dystroy.org/login) - 多房间持久聊天服务器。([源代码](https://github.com/Canop/miaou)) `MIT` `Nodejs`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page) - 低延迟、高质量的语音/文本聊天软件。([源代码](https://github.com/mumble-voip/mumble), [客户端](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++/deb`
- [Notifo](https://github.com/notifo-io/notifo) - 支持电子邮件、移动推送、Web推送、SMS、消息传递和JavaScript插件的多渠道通知服务器。`MIT` `C#`
- [Novu](https://novu.co/) - 自托管/云通知基础设施，适用于开发者。([源代码](https://github.com/novuhq/novu/)) `MIT` `Docker/Nodejs`
- [ntfy](https://ntfy.sh/) - 使用HTTP PUT/POST推送通知到手机或桌面，带有Android应用、CLI和Web应用，类似于Pushover和Gotify。([演示](https://ntfy.sh/app), [源代码](https://github.com/binwiederhier/ntfy), [客户端](https://github.com/binwiederhier/ntfy-android)) `Apache-2.0/GPL-2.0` `Go/Docker/K8S`
- [OTS](https://ots.fyi/) - 带有浏览器中对称256位AES加密的一次性秘密共享平台。([源代码](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- [PushBits](https://github.com/pushbits/server) - 用于通过Matrix中继推送通知的自托管通知服务器，类似于PushBullet和Gotify。`ISC` `Go`
- [RetroShare](https://retroshare.cc) - 安全且去中心化的通信系统。提供去中心化的聊天、论坛、消息传递、文件传输。([源代码](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- [Revolt](https://revolt.chat/) - Revolt是一个以用户为先的聊天平台，使用现代Web技术构建。([源代码](https://github.com/revoltchat/self-hosted)) `AGPL-3.0` `Rust`
- [Rocket.Chat](https://rocket.chat/) - 团队聊天解决方案，类似于Gitter.im或Slack。([源代码](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs/Docker/K8S`
- [Screego](https://screego.net) - Screego是一个简单的工具，可以通过Web浏览器快速将屏幕共享给一个或多个人。([演示](https://app.screego.net/), [源代码](https://github.com/screego/server)) `GPL-3.0` `Docker/Go`
- [Shhh](https://github.com/smallwat3r/shhh) - 将秘密保存在电子邮件或聊天日志之外，通过安全链接和密码以及到期日期共享它们。`MIT` `Python`
- [SimpleX Chat](https://github.com/simplex-chat/simplex-chat) - 最私密和安全的聊天和应用程序平台 - 现在具有双重None棘轮端到端加密。`AGPL-3.0` `Haskell`
- [Soketi](https://soketi.app/) - 简单、快速且具有弹性的开源WebSocket服务器（Pusher的替代品）。([源代码](https://github.com/soketi/soketi)) `MIT` `Nodejs/Docker/K8S`
- [Spectrum 2](https://spectrum.im/) - Spectrum 2是一个开源的即时消息传输。它允许用户即使使用不同的IM网络也能在一起聊天。([源代码](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- [Synapse](https://element-hq.github.io/synapse/latest/index.html) - [Matrix](https://matrix.org/)的服务器，一个去中心化持久通信的开放标准。([源代码](https://github.com/element-hq/synapse)) `Apache-2.0` `Python/deb`
- [Syndie](https://syndie.de) - Syndie是一个自由的系统，用于操作分布式论坛。`CC0-1.0` `Java`
- [Tailchat](https://tailchat.msgbyte.com/) - 在你自己的工作空间中的下一代noIM应用程序，不仅仅是另一个Slack/Discord/rocket.chat。([演示](https://nightly.paw.msgbyte.com/), [源代码](https://github.com/msgbyte/tailchat)) `Apache-2.0` `Docker/K8S/Nodejs`
- [TextBelt](https://github.com/typpo/textbelt) `None⚠` - 使用特定运营商的网关免费发送文本消息的传出SMS API，且没有广告。`MIT` `Javascript`
- [Tiledesk](https://tiledesk.com) - 从潜在客户生成到售后，从WhatsApp到你的网站的全方位客户参与平台。具有全渠道实时代理和AI驱动的聊天机器人（Intercom、Zendesk、Tawk.to和Tidio的替代品）。([源代码](https://github.com/Tiledesk/tiledesk)) `MIT` `Docker/K8S`
- [Tinode](https://github.com/tinode) - 即时消息平台。后端使用Go。客户端：Swift iOS、Java Android、JS webapp、可编写脚本的命令行；聊天机器人。([演示](https://sandbox.tinode.co/), [源代码](https://github.com/tinode/chat), [客户端](https://github.com/tinode/webapp)) `GPL-3.0` `Go`
- [Tox](https://tox.chat/) - 分布式、安全的消息传递器，具有音频和视频聊天功能。([源代码](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- [Typebot](https://typebot.io) - 对话应用程序构建器（Typeform或Landbot的替代品）。([源代码](https://github.com/baptisteArno/typebot.io)) `AGPL-3.0` `Docker`
- [WBO](https://github.com/lovasoa/whitebophir) - 用于在模式、绘图和笔记上实时协作的网络白板。([演示](https://wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- [Yopass](https://github.com/jhaals/yopass) - 安全共享秘密、密码和文件。([演示](https://yopass.se/)) `Apache-2.0` `Go/Docker`
- [Zulip](https://zulip.org) - Zulip是一个功能强大的开源群聊应用程序。([源代码](https://github.com/zulip/zulip)) `Apache-2.0` `Python`

### 通信 - 电子邮件 - 完整解决方案

**[`^        回到顶部        ^`](#awesome-selfhosted)**

简单部署 [电子邮件](https://zh.wikipedia.org/wiki/电子邮件) 服务器，例如为经验不足或不耐烦的管理员设计。

- [AnonAddy](https://anonaddy.com) - 开源电子邮件转发服务，用于创建别名。([源代码](https://github.com/anonaddy/anonaddy)) `MIT` `PHP/Docker`
- [DebOps](https://docs.debops.org/) - 基于 Debian 的数据中心套件。一个通用 Ansible 角色的集合，可用于管理 Debian 或 Ubuntu 主机。([源代码](https://github.com/debops/debops)) `GPL-3.0` `Ansible/Python`
- [docker-mailserver](https://docker-mailserver.github.io/docker-mailserver/edge/) - 生产就绪的全栈但简单的邮件服务器（SMTP、IMAP、LDAP、反None垃None圾邮件、反病毒等）在容器内运行。仅配置文件，不使用 SQL 数据库。([源代码](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
- [Dovel](https://dovel.email) - 根据简单的配置文件发送和接收电子邮件的 SMTP 服务器，带有可选的 Web 界面，可用于浏览电子邮件。([源代码](https://dovel.email/server/tree.html)) `LGPL-3.0` `Go`
- [emailwiz](https://github.com/LukeSmithxyz/emailwiz) - Luke Smith 的 bash 脚本，用于在 debian 上完全自动化设置 Postfix/Dovecot/SpamAssassin/OpenDKIM 服务器。`GPL-3.0` `Shell`
- [homebox](https://github.com/progmaticltd/homebox) - 一套 Ansible 脚本，用于在 Debian 上部署完全功能的邮件服务器。尽可能不引人注目和自动化，专注于稳定性和安全性。`GPL-3.0` `Shell`
- [Inboxen](https://inboxen.org) - Inboxen 是一项为您提供无限数量的唯一收件箱的服务。([源代码](https://codeberg.org/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [iRedMail](https://www.iredmail.org/) - 基于 Postfix 和 Dovecot 的功能齐全的邮件服务器解决方案。([源代码](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- [Maddy Mail Server](https://github.com/foxcpp/maddy) - 集成的邮件服务器，实现了 SMTP（包括 MTA 和 MX）和 IMAP。用单个守护进程替代 Postfix、Dovecot、OpenDKIM、OpenSPF、OpenDMARC。`GPL-3.0` `Go`
- [Mail-in-a-Box](https://mailinabox.email/) - 通过一个命令将任何 Ubuntu 服务器变成完全功能的邮件服务器。([源代码](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Mailcow](https://mailcow.email/) - 基于 Dovecot、Postfix 和其他开源软件的邮件服务器套件，提供现代的 Web UI 进行管理。([源代码](https://github.com/mailcow/mailcow-dockerized)) `GPL-2.0` `Docker/PHP`
- [Mailu](https://mailu.io/) - Mailu 是一组 Docker 镜像的简单但功能齐全的邮件服务器。([源代码](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Modoboa](https://modoboa.org/en/) - Modoboa 是一个邮件托管和管理平台，包括一个现代和简化的 Web 用户界面。([源代码](https://github.com/modoboa/modoboa)) `ISC` `Python`
- [Mox](https://www.xmox.nl/) - 完整的电子邮件解决方案，具有 IMAP4、SMTP、SPF、DKIM、DMARC、MTA-STS、DANE 和 DNSSEC，基于声誉和内容的None垃None圾邮件过滤，国际化（IDNA），自动 TLS 与 ACME 和 Let's Encrypt，账户自动配置和 Web 邮件。([源代码](https://github.com/mjl-/mox)) `MIT` `Go`
- [Postal](https://docs.postalserver.io/) - 用于网站和 Web 服务器的完整和功能齐全的邮件服务器。([源代码](https://github.com/postalserver/postal)) `MIT` `Docker/Ruby`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 利用 Nix 生态系统的完整邮件服务器解决方案。`GPL-3.0` `Nix`
- [SimpleLogin](https://simplelogin.io) - 开源电子邮件别名解决方案，用于保护您的电子邮件地址。提供浏览器扩展和移动应用程序。([源代码](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- [Stalwart Mail Server](https://stalw.art) - 集成的邮件服务器，支持 JMAP、IMAP4 和 SMTP 以及一系列现代功能。([源代码](https://github.com/stalwartlabs/mail-server)) `AGPL-3.0` `Rust/Docker`
- [wildduck](https://wildduck.email/) - 可扩展的无 SPOF IMAP/POP3 邮件服务器。([源代码](https://github.com/nodemailer/wildduck)) `EUPL-1.2` `Nodejs/Docker`


### 通信 - 电子邮件 - 邮件传递代理

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[邮件传递代理](https://zh.wikipedia.org/wiki/邮件传递代理)（MDAs） - [IMAP](https://zh.wikipedia.org/wiki/互联网消息访问协议)/[POP3](https://zh.wikipedia.org/wiki/邮局协议) 服务器软件。

- [Cyrus IMAP](https://www.cyrusimap.org/) - 电子邮件（IMAP/POP3）、联系人和日历服务器。([源代码](https://github.com/cyrusimap/cyrus-imapd)) `BSD-3-Clause-Attribution` `C`
- [Dovecot](https://www.dovecot.org/) - 主要以安全为重点编写的 IMAP 和 POP3 服务器。([源代码](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C/deb`
- [Piler](https://www.mailpiler.org/) - 功能丰富的电子邮件归档解决方案。([源代码](https://github.com/jsuto/piler/)) `GPL-3.0` `C`


### 通信 - 电子邮件 - 邮件传输代理

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[邮件传输代理](https://zh.wikipedia.org/wiki/邮件传输代理)（MTAs） - [SMTP](https://zh.wikipedia.org/wiki/简单邮件传输协议) 服务器。

- [chasquid](https://blitiri.com.ar/p/chasquid/) - 专注于简单性、安全性和易操作性的 SMTP（电子邮件）服务器。([源代码](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](https://www.courier-mta.org/) - 快速、可扩展的企业邮件/群件服务器，提供 ESMTP、IMAP、POP3、Web 邮件、邮件列表、基本的基于 Web 的日历和调度服务。([源代码](https://www.courier-mta.org/repo.html)) `GPL-3.0` `C/deb`
- [DragonFly](https://github.com/corecode/dma) - 家庭和办公室使用的轻量级 MTA。在 Linux 和 FreeBSD 上工作。`BSD-3-Clause` `C`
- [EmailRelay](https://emailrelay.sourceforge.net/) - 一个小型且易于配置的 SMTP 和 POP3 服务器，适用于 Windows 和 Linux。([源代码](https://sourceforge.net/p/emailrelay/code/HEAD/tree/)) `GPL-3.0` `C++`
- [Exim](https://www.exim.org/) - 在剑桥大学开发的消息传输代理（MTA）。([源代码](https://git.exim.org/exim.git)) `GPL-3.0` `C/deb`
- [Haraka](https://haraka.github.io/) - 高性能、可插拔的 JavaScript 编写的 SMTP 服务器。([源代码](https://github.com/haraka/Haraka)) `MIT` `Nodejs`
- [MailCatcher](https://mailcatcher.me/) - 用于部署一个简单的 SMTP MTA 网关的 Ruby gem，接受所有邮件并在 Web 界面中显示。适用于调试或开发。([源代码](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
- [OpenSMTPD](https://opensmtpd.org/) - OpenBSD 项目提供的安全 SMTP 服务器实现。([源代码](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C/deb`
- [OpenTrashmail](https://github.com/HaschekSolutions/opentrashmail) - 完整的None垃None圾邮件解决方案，暴露 SMTP 服务器并具有用于管理接收到的电子邮件的 Web 界面。支持多个和通配符域，完全基于文件（无需数据库）。包括 RSS 提要和 JSON API。`Apache-2.0` `Python/PHP/Docker`
- [Postfix](http://www.postfix.org/) - 快速、易于管理且安全的 Sendmail 替代品。`IPL-1.0` `C/deb`
- [Sendmail](https://www.proofpoint.com/us/products/email-protection/open-source-email-solution) - 消息传输代理（MTA）。`Sendmail` `C/deb`
- [Slimta](https://slimta.github.io/) - 基于 Python 构建的邮件传输库。([源代码](https://github.com/slimta/python-slimta)) `MIT` `Python`


### 通信 - 视频会议

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[视频/网络会议](https://en.wikipedia.org/wiki/Web_conferencing)工具和软件。

_相关：[会议管理](#conference-management)_

- [BigBlueButton](https://bigbluebutton.org/) - 支持实时共享音频、视频、幻灯片（带有白板控制）、聊天和屏幕。教师可以使用投票、表情符号和分组房间与远程学生互动。([源代码](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [Galene](https://galene.org/) - Galène（或Galene）是一个视频会议服务器（一种“选择性转发单元（SFU）”），易于部署且需要适度的服务器资源。([源代码](https://github.com/jech/galene)) `MIT` `Go`
- [Janus](https://janus.conf.meetecho.com/) - 通用的、轻量级、最简化的WebRTC服务器。([演示](https://janus.conf.meetecho.com/demos/)，[源代码](https://github.com/meetecho/janus-gateway)) `GPL-3.0` `C`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet是一个开源（MIT）的WebRTC JavaScript应用程序，使用Jitsi Videobridge提供高质量、可扩展的视频会议。([演示](https://meet.jit.si)，[源代码](https://github.com/jitsi/jitsi-meet)) `Apache-2.0` `Nodejs/Docker/deb`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - 与WebRTC兼容的选择性转发单元（SFU），允许多用户视频通信。([源代码](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java/deb`
- [MiroTalk C2C](https://c2c.mirotalk.com) - 实时摄像头对摄像头视频通话和屏幕共享，端到端加密，可以通过简单的一个iframe嵌入到任何网站中。([源代码](https://github.com/miroslavpejic85/mirotalkc2c)) `MIT` `Nodejs/Docker`
- [MiroTalk P2P](https://p2p.mirotalk.com) - 简单、安全、快速的实时视频会议，最高可达4K和60fps，兼容所有浏览器和平台。([演示](https://p2p.mirotalk.com/newcall)，[源代码](https://github.com/miroslavpejic85/mirotalk)) `AGPL-3.0` `Nodejs/Docker`
- [MiroTalk SFU](https://sfu.mirotalk.com) - 简单、安全、可扩展的实时视频会议，最高可达4K，兼容所有浏览器和平台。([演示](https://sfu.mirotalk.com/newroom)，[源代码](https://github.com/miroslavpejic85/mirotalksfu)) `AGPL-3.0` `Nodejs/Docker`
- [plugNmeet](https://www.plugnmeet.org/) - 可扩展、高性能、开源的网络会议系统。([演示](https://demo.plugnmeet.com/login.html)，[源代码](https://github.com/mynaparrot/plugNmeet-server)) `MIT` `Docker/Go`


### 通信 - XMPP - 服务器

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[可扩展消息和存在协议](https://en.wikipedia.org/wiki/XMPP)服务器。

- [ejabberd](https://www.ejabberd.im/) - XMPP即时消息服务器。([源代码](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang/Docker`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - 专注于性能和可扩展性的移动消息平台。([源代码](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang/Docker/K8S`
- [Openfire](https://www.igniterealtime.org/projects/openfire/) - 实时协作（RTC）服务器。([源代码](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](https://prosody.im/) - 功能丰富且易于配置的XMPP服务器。([源代码](https://hg.prosody.im/)) `MIT` `Lua`
- [Snikket](https://snikket.org/) - 一个全功能的Docker化简易XMPP解决方案，包括Web管理员和客户端。([源代码](https://github.com/snikket-im/snikket-server)，[客户端](https://snikket.org/app/)) `Apache-2.0` `Docker`
- [Tigase](https://tigase.net/xmpp-server) - Java中的XMPP服务器实现。([源代码](https://github.com/tigase/tigase-server)) `GPL-3.0` `Java`


### 通信 - XMPP - Web客户端

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[可扩展消息和存在协议](https://en.wikipedia.org/wiki/XMPP) Web客户端/界面。

- [Converse.js](https://conversejs.org/) - 免费开源的XMPP聊天客户端，您可以在浏览器中使用。([源代码](https://github.com/conversejs/converse.js)) `MPL-2.0` `Javascript`
- [JSXC](https://jsxc.org) - 实时XMPP网络聊天应用程序，支持视频通话、文件传输和加密通信。还有Nextcloud/Owncloud和SOGo的版本。([源代码](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
- [Libervia](https://repos.goffi.org/libervia-web) - Salut à Toi的Web前端。`AGPL-3.0` `Python`
- [Salut à Toi](https://www.salut-a-toi.org/) - 多用途、多前端、自由和去中心化的通信工具。([源代码](https://repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### 社区支持农业（CSA）

**[`^        返回顶部        ^`](#awesome-selfhosted)**

社区支持农业和食品合作社的管理和行政工具。

_相关：[电子商务](#e-commerce)_

- [ACP Admin](https://acp-admin.ch/) - CSA管理。管理成员、订阅、交付、交付地点、成员参与、发票和电子邮件（文档为法语）。([源代码](https://github.com/acp-admin/acp-admin/)) `MIT` `Ruby`
- [E-Label](https://filipecarneiro.github.io/ELabel/) - 欧盟境内销售的葡萄酒瓶上的电子标签解决方案，带有二维码。([源代码](https://github.com/filipecarneiro/ELabel)) `MIT` `Docker`
- [FoodCoopShop](https://www.foodcoopshop.com/) - 面向食品合作社的用户友好开源软件。([源代码](https://github.com/foodcoopshop/foodcoopshop)) `AGPL-3.0` `PHP/Docker`
- [Foodsoft](https://foodcoops.net/) - 基于Web的软件，用于管理非营利食品合作社（产品目录、订购、会计、工作安排）。([源代码](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Docker/Ruby`
- [juntagrico](https://juntagrico.org/) - 社区花园和None蔬菜合作社的管理平台。([源代码](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- [Local Food Nodes](https://localfoodnodes.org/) - 您的人民驱动的地方食品市场和CSA的开源平台。([源代码](https://gitlab.com/localfoodnodes/localfoodnodes)) `MIT` `PHP`
- [Open Food Network](https://www.openfoodnetwork.org/) - 当地食品的在线市场。它使独立的在线食品商店网络连接农民和食品中心与个人和当地企业。([源代码](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [OpenOlitor](https://openolitor.org/) - 社区支持农业团体的管理平台。([源代码](https://github.com/OpenOlitor/openolitor-server)) `AGPL-3.0` `Scala`
- [teikei](https://github.com/teikei/teikei) - 基于众包数据映射社区支持农业的Web应用程序。([演示](https://ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### 会议管理

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于提交[摘要](https://en.wikipedia.org/wiki/Abstract_management)和准备/管理学术会议的软件。

- [Conference Organizing Distribution (COD)](http://usecod.com/) - 在Drupal之上构建的创建会议和活动网站的工具。([源代码](https://git.drupalcode.org/project/cod)) `GPL-2.0` `PHP`
- [frab](https://frab.github.io/frab/) - 基于Web的会议规划和管理系统。它有助于收集提交、管理演讲和演讲者以及创建日程表。([源代码](https://github.com/frab/frab)) `MIT` `Ruby/Docker`
- [indico](https://getindico.io/) - 功能丰富的事件管理系统，由CERN制作，网络诞生的地方。([演示](https://sandbox.getindico.io/)，[源代码](https://github.com/indico/indico)) `MIT` `Python`
- [motion.tools (Antragsgrün)](https://motion.tools/) - 用于管理会议和修正案的Web工具，适用于（政治）会议。([演示](https://sandbox.motion.tools/createsite)，[源代码](https://github.com/CatoTH/antragsgruen)) `AGPL-3.0` `PHP/Docker`
- [OpenSlides](https://openslides.com/) - 基于Web的演示和会议系统，用于管理和投影会议议程、动议和选举。([演示](https://demo.os4.openslides.com/login)，[源代码](https://github.com/OpenSlides/OpenSlides)) `MIT` `Docker`
- [osem](https://osem.io/) - 针对免费软件会议的活动管理。([源代码](https://github.com/openSUSE/osem)) `MIT` `Ruby/Docker`
- [pretalx](https://pretalx.org) - 基于Web的事件管理，包括运行论文征集、审查提交和安排演讲。导出和导入各种相关工具。([源代码](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### 内容管理系统（CMS）

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[内容管理系统](https://en.wikipedia.org/wiki/Content_management_system)提供了一种实用的方式来设置具有许多功能的网站，使用第三方插件、主题和功能易于添加和自定义。

_相关：[博客平台](#blogging-platforms)，[静态站点生成器](#static-site-generators)，[照片和视频画廊](#photo-and-video-galleries)_

- [Alfresco Community Edition](https://www.alfresco.com/products/community/download) - 处理任何类型内容的开源企业内容管理软件，允许用户轻松共享和协作内容。([源代码](https://github.com/Alfresco/alfresco-community-repo)) `LGPL-3.0` `Java`
- [Apostrophe](https://apostrophecms.com/) - 专注于可扩展的上下文编辑工具的CMS。([演示](https://apostrophecms.com/demo)，[源代码](https://github.com/apostrophecms/apostrophe)) `MIT` `Nodejs`
- [Backdrop CMS](https://backdropcms.org/) - 面向小型到中型企业和非营利组织的综合CMS。([源代码](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [BigTree CMS](https://www.bigtreecms.org/) - 使用PHP和MySQL编写的简单、文档良好且功能强大的CMS。([源代码](https://github.com/bigtreecms/BigTree-CMS)) `LGPL-2.1` `PHP`
- [Bludit](https://www.bludit.com/) `None⚠` - 简单地构建网站或博客的应用程序。Bludit使用平面文件（JSON格式的文本文件）来存储文章和页面。([演示](https://demo.bludit.com/)，[源代码](https://github.com/bludit/bludit)) `MIT` `PHP`
- [Bolt CMS](https://boltcms.io/) - 开放源码内容管理工具，力求尽可能简单和直接。([源代码](https://github.com/bolt/core)) `MIT` `PHP`
- [CMS Made Simple](https://www.cmsmadesimple.org/) - 开源内容管理系统，使网站内容的管理更快更容易，适用于小型企业到大型企业。([源代码](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-2.0` `PHP`
- [Cockpit](https://getcockpit.com) - 管理任何结构化内容的简单内容平台。([源代码](https://github.com/Cockpit-HQ/Cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](https://www.concretecms.com) - 开源内容管理系统。([源代码](https://github.com/concretecms/concretecms)) `MIT` `PHP`
- [Contao](https://contao.org/) - Contao是一个强大的开源CMS，允许您创建专业网站和可扩展的Web应用程序。([源代码](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](https://www.couchcms.com/) - 设计师的简单开源CMS。([源代码](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Drupal](https://www.drupal.org/) - 高级开源内容管理平台。([源代码](https://git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](https://www.elabftw.net) - 研究实验室的在线实验笔记本。存储实验、使用数据库查找试剂或协议、使用可信时间None戳对实验进行合法的时间None戳、导出为pdf或zip存档、与合作者共享……([演示](https://demo.elabftw.net)，[源代码](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - 使用JSON模式驱动的数据库驱动的网站的CMS。提供权限管理和自动REST API。`MIT` `Nodejs`
- [Joomla!](https://www.joomla.org/) - 高级内容管理系统（CMS）。([源代码](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](https://keystonejs.com/) - CMS和Web应用程序平台。([源代码](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- [MODX](https://modx.com/) - MODX是一个高级内容管理和发布平台。目前版本称为“Revolution”。([源代码](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - Neos或TYPO3 Neos（对于版本1）是一个现代的开源CMS。([源代码](https://github.com/neos)) `GPL-3.0` `PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - Noosfero是一个用于社会和团结经济网络的Web平台，具有博客、电子投资组合、CMS、RSS、主题讨论、事件日程和团结经济的集体智能。`AGPL-3.0` `Ruby`
- [Omeka](https://omeka.org) - 使用Omeka在您的服务器上创建复杂的叙述和共享丰富的集合，遵循都柏林核心标准，专为学者、博物馆、图书馆、档案馆和爱好者设计。([演示](https://omeka.org/classic/showcase/)，[源代码](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Payload CMS](https://payloadcms.com/) - 开发者优先的无头CMS和应用程序框架。([源代码](https://github.com/payloadcms/payload)) `MIT` `Nodejs`
- [Pimcore](https://www.pimcore.org/) - 多渠道体验和参与管理平台。([源代码](https://github.com/pimcore/pimcore)) `GPL-3.0` `PHP/Docker`
- [Plone](https://plone.org/) - 强大的开源CMS系统。([源代码](https://github.com/plone)) `ZPL-2.0` `Python/Docker`
- [Publify](https://publify.github.io/) - 简单但功能强大的Web发布软件。([源代码](https://github.com/publify/publify)) `MIT` `Ruby`
- [Rapido](https://framagit.org/InfoLibre/rapido) - 使用Rapido创建您的网站。编辑、发布和共享协作内容。`AGPL-3.0` `Go`
- [REDAXO](https://www.redaxo.org) - 简单、灵活且实用的内容管理系统（仅提供德语文档）。([源代码](https://github.com/redaxo/redaxo)) `MIT` `PHP/Docker`
- [Roadiz](https://www.roadiz.io/) - 基于节点系统的现代CMS，可以处理多种类型的服务。([源代码](https://github.com/roadiz/roadiz)) `MIT` `PHP`
- [SilverStripe](https://www.silverstripe.org) - 易于使用的CMS，具有强大的底层MVC框架。([演示](https://demo.silverstripe.org/)，[源代码](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](https://www.spip.net/fr) - 针对协作工作、多语言环境和Web作者使用简便的互联网发布系统。([源代码](https://git.spip.net/)) `GPL-3.0` `PHP`
- [Squidex](https://squidex.io) - 基于MongoDB、CQRS和事件None溯源的无头CMS。([演示](https://cloud.squidex.io)，[源代码](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - 最先进的开源内容管理框架（无头CMS），无需努力即可构建强大的API。([源代码](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- [Textpattern](https://textpattern.com/) - 灵活、优雅且易于使用的CMS。([演示](https://textpattern.co/demo)，[源代码](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [Typemill](https://typemill.net/) - 基于vue.js的可视化markdown编辑器的作者友好的平面文件CMS。([源代码](https://github.com/typemill/typemill)) `MIT` `PHP`
- [TYPO3](https://typo3.org/) - 强大且高级的CMS，拥有一个庞大的社区。([源代码](https://github.com/TYPO3/typo3)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - 友好的CMS。免费开源，并拥有一个惊人的社区。([源代码](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Vvveb CMS](https://www.vvveb.com) - 强大且易于使用的CMS，用于构建网站、博客或电子商务商店。([演示](https://demo.vvveb.com)，[源代码](https://github.com/givanz/Vvveb)) `AGPL-3.0` `PHP/Docker`
- [Wagtail](https://wagtail.io/) - 专注于灵活性和用户体验的Django内容管理系统。([源代码](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WinterCMS](https://wintercms.com/) - 基于Laravel PHP框架构建的快速且安全的内容管理系统。([源代码](https://github.com/wintercms/winter)) `MIT` `PHP`
- [WonderCMS](https://www.wondercms.com) - 自2008年以来最小的平面文件CMS。([演示](https://www.wondercms.com/demo)，[源代码](https://github.com/WonderCMS/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - 世界上使用最广泛的博客和CMS引擎。([源代码](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`


### 数据库管理

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[数据库](https://en.wikipedia.org/wiki/Database)管理的Web界面。包括用于数据库分析和可视化的工具。

_相关：[分析](#analytics)，[自动化](#automation)_

_另见：[dbdb.io - 数据库数据库](https://dbdb.io/)_

### 数据库管理

**[`^        回到顶部        ^`](#awesome-selfhosted)**

- [AdminerEvo](https://docs.adminerevo.org/) - 在单个PHP文件中进行数据库管理。适用于MySQL、MariaDB、PostgreSQL、SQLite、MS SQL、Oracle、Elasticsearch、MongoDB等数据库（Adminer的分支）。([源代码](https://github.com/adminerevo/adminerevo)) `Apache-2.0/GPL-2.0` `PHP`
- [Azimutt](https://azimutt.app) - 适用于现实世界数据库（庞大且杂乱无章）的可视化数据库探索工具。探索数据库架构和数据，记录它们，扩展它们，甚至获取分析和指南。([演示](https://azimutt.app/gallery/gospeak), [源代码](https://github.com/azimuttapp/azimutt)) `MIT` `Elixir/Nodejs/Docker`
- [Baserow](https://baserow.io/) - 在没有技术经验的情况下创建自己的数据库（Airtable的替代品）。([源代码](https://gitlab.com/bramw/baserow)) `MIT` `Docker`
- [Bytebase](https://www.bytebase.com/) - 为DevOps团队提供安全的数据库架构变更和版本控制，支持MySQL、PostgreSQL、TiDB、ClickHouse和Snowflake。([演示](https://demo.bytebase.com), [源代码](https://github.com/bytebase/bytebase)) `MIT` `Docker/K8S/Go`
- [Chartbrew](https://chartbrew.com) - 可以直接连接数据库和API，并使用数据创建美观图表的Web应用程序。([演示](https://app.chartbrew.com/live-demo), [源代码](https://github.com/chartbrew/chartbrew)) `MIT` `Nodejs/Docker`
- [CloudBeaver](https://dbeaver.com/) - 自托管的数据库管理，支持PostgreSQL、MySQL、SQLite等。DBeaver的Web/托管版本。([源代码](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Docker`
- [Databunker](https://databunker.org/) - 基于网络的、自托管的、符合GDPR的、用于个人数据或PII的安全数据库。([源代码](https://github.com/securitybunker/databunker)) `MIT` `Docker`
- [Datasette](https://datasette.io/) - 用于探索和发布数据的开源多功能工具，易于导入和导出以及数据库管理。([演示](https://global-power-plants.datasettes.com/global-power-plants/global-power-plants), [源代码](https://github.com/simonw/datasette)) `Apache-2.0` `Python/Docker`
- [Directus](https://directus.io/) - 您的SQL数据库的即时应用程序和API。Directus使用实时GraphQL+REST API包装您的新或现有SQL数据库，为开发者提供服务，并为非技术用户提供直观的管理应用程序。([源代码](https://github.com/directus/directus)) `GPL-3.0` `Nodejs/Docker`
- [Evidence](https://evidence.dev) - Evidence是一个基于代码的BI工具。使用SQL和markdown编写报告，并将其渲染为网站。([源代码](https://github.com/evidence-dev/evidence)) `MIT` `Nodejs`
- [Limbas](https://www.limbas.com/en/) - Limbas是一个用于创建数据库驱动的业务应用程序的数据库框架。作为图形数据库前端，它能够高效处理数据库，并灵活开发舒适的数据库应用程序。([源代码](https://github.com/limbas/limbas)) `GPL-2.0` `PHP`
- [Mathesar](https://mathesar.org/) - 一个直观的用户界面，用于协作管理数据，适用于所有技术技能水平的用户。构建在Postgres之上 - 连接现有数据库或设置新数据库。([演示](https://demo.mathesar.org/), [源代码](https://github.com/centerofci/mathesar)) `GPL-3.0` `Docker/Python`
- [MindsDB](https://mindsdb.com/) - MindsDB是一个开源的自托管AI层，用于现有数据库，允许您使用标准查询轻松开发、训练和部署最先进的机器学习模型。([源代码](https://github.com/mindsdb/mindsdb)) `GPL-3.0` `Docker/Python`
- [NocoDB](https://www.nocodb.com/) - 无代码平台，将任何数据库转换为智能电子表格（Airtable或Smartsheet的替代品）。([源代码](https://github.com/nocodb/nocodb)) `GPL-3.0` `Nodejs/Docker`
- [WebDB](https://webdb.app) - 高效的数据库IDE。([演示](https://demo.webdb.app/), [源代码](https://gitlab.com/web-db/app)) `AGPL-3.0` `Docker`


### DNS

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[DNS](https://en.wikipedia.org/wiki/Domain_Name_System)服务器和管理工具，具有广告阻止功能，主要针对家庭或小型网络。

另请参阅：[awesome-sysadmin/DNS - 服务器](https://github.com/awesome-foss/awesome-sysadmin#dns---servers), [awesome-sysadmin/DNS - 控制面板和域管理](https://github.com/awesome-foss/awesome-sysadmin#dns---control-panels--domain-management)

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - 免费且开源、用户友好的广告和跟踪器阻止DNS服务器。([源代码](https://github.com/AdguardTeam/AdGuardHome)) `GPL-3.0` `Docker`
- [blocky](https://github.com/0xERR0R/blocky) - 快速且轻量的DNS代理（如Pi-hole），作为本地网络的广告阻止器，具有许多功能。`Apache-2.0` `Go/Docker`
- [Maza ad blocking](https://maza-ad-blocking.andros.dev/) - 本地广告阻止器。类似于Pi-hole，但使用您的操作系统。([源代码](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Shell`
- [Pi-hole](https://pi-hole.net/) - 互联网广告的黑洞，带有用于管理和监控的GUI。([源代码](https://github.com/pi-hole/pi-hole)) `EUPL-1.2` `Shell/PHP/Docker`
- [Technitium DNS Server](https://technitium.com/dns/) - 具有广告阻止功能的权威/递归DNS服务器。([源代码](https://github.com/TechnitiumSoftware/DnsServer)) `GPL-3.0` `Docker/C#`


### 文档管理

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[文档管理系统](https://en.wikipedia.org/wiki/Document_management_system)（DMS）是一个用于接收、跟踪、管理和存储文档并减少纸张使用的系统。

- [DocKing](https://docking.shipsaas.tech) - 处理模板并将它们渲染为PDF格式的文档管理服务/微服务，全部在一个地方。([演示](https://docking-demo.shipsaas.tech/console), [源代码](https://github.com/shipsaas/docking)) `MIT` `PHP/Nodejs/Docker`
- [Docspell](https://docspell.org) - 自动标记文档的组织者和存档系统。([源代码](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java/Docker`
- [Docuseal](https://www.docuseal.co) - 创建、填写和签署数字文档（DocuSign的替代品）。([演示](https://demo.docuseal.tech/), [源代码](https://github.com/docusealco/docuseal)) `AGPL-3.0` `Docker`
- [EveryDocs](https://github.com/jonashellmann/everydocs-core) - 一个简单的文档管理系统，用于私人使用，具有基本功能来数字化组织您的文档。`GPL-3.0` `Docker/Ruby`
- [I, Librarian](https://i-librarian.net) - I, Librarian可以组织PDF论文和办公文档。它为工业和学术界的研究生和研究小组提供了许多额外的功能。([演示](https://i-librarian.net/demo/), [源代码](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- [Mayan EDMS](https://www.mayan-edms.com) - 免费的开源电子文档管理系统。您的文档的电子保险库，具有预览生成、OCR和自动分类等功能。([源代码](https://gitlab.com/mayan-edms/mayan-edms)) `Apache-2.0` `Python`
- [OpenSign](https://www.opensignlabs.com) `None⚠` - 免费、开源和自托管的文档签署软件（DocuSign的替代品）。([源代码](https://github.com/opensignlabs/opensign)) `AGPL-3.0` `Nodejs/Docker`
- [Paperless-ngx](https://docs.paperless-ngx.com/) - 使用改进的界面扫描、索引和存档所有纸质文档（Paperless的分支）。([演示](https://demo.paperless-ngx.com/), [源代码](https://github.com/paperless-ngx/paperless-ngx)) `GPL-3.0` `Python/Docker`
- [Papermerge](https://papermerge.com) - 专注于扫描文档（电子档案）的开源文档管理系统。提供类似于dropbox/google drive的文件浏览功能。OCR、全文搜索、文本叠加/选择。([源代码](https://github.com/ciur/papermerge)) `Apache-2.0` `Python/Docker/K8S`
- [PdfDing](https://github.com/mrmn2/PdfDing) - PDF管理和查看器，提供在多个设备上无缝的用户体验。它旨在最小化、快速并使用Docker轻松设置。`GPL-3.0` `Docker`
- [SeedDMS](https://www.seeddms.org) - 具有工作流程、访问权限、全文搜索等功能的文档管理系统。([演示](https://www.seeddms.org/about/), [源代码](https://sourceforge.net/p/seeddms/code/ci/master/tree/)) `GPL-2.0` `PHP`
- [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF) - 本地托管的Web应用程序，允许您对PDF文件执行各种操作，例如合并、拆分、文件转换和OCR。`Apache-2.0` `Docker/Java`
- [Teedy](https://teedy.io/) - 轻量级的文档管理系统，具有您可以从昂贵的大型解决方案中期望的所有功能（原SismicsDocs）。([演示](https://demo.teedy.io/), [源代码](https://github.com/sismics/docs)) `GPL-2.0` `Docker/Java`


### 文档管理 - 电子书

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[电子书](https://en.wikipedia.org/wiki/Ebook)图书馆管理软件。

- [Atsumeru](https://atsumeru.xyz) - 免费且开源的自托管漫画/漫画/轻小说媒体服务器，具有适用于Windows、Linux、macOS和Android的客户端。([源代码](https://github.com/AtsumeruDev/Atsumeru), [客户端](https://atsumeru.xyz/guides/#how-does-it-work)) `MIT` `Java/Docker`
- [Calibre Web](https://github.com/janeczku/calibre-web) - 提供一个清洁界面来浏览、阅读和下载使用现有Calibre数据库的电子书的Web应用程序。`GPL-3.0` `Python`
- [Calibre](https://calibre-ebook.com/) - 电子书图书馆管理器，可以查看、转换和编目大多数主要电子书格式的电子书，并为远程客户端提供内置Web服务器。([演示](https://calibre-ebook.com/demo), [源代码](https://github.com/kovidgoyal/calibre)) `GPL-3.0` `Python/deb`
- [Kavita](https://www.kavitareader.com/) - 跨平台的电子书/漫画/漫画/PDF服务器和Web阅读器，具有用户管理、评级和评论以及元数据支持。([演示](https://www.kavitareader.com/#demo), [源代码](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET/Docker`
- [Komga](https://komga.org) - 支持API和OPDS的漫画/漫画/BD媒体服务器，具有用于探索您的图书馆的现代Web界面以及Web阅读器。([源代码](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- [Librum](https://librumreader.com) - 现代电子书阅读器和图书馆管理器，支持大多数主要书籍格式，在所有设备上运行，并提供提升生产力的强大工具。([源代码](https://github.com/Librum-Reader/Librum)) `GPL-3.0` `C++`
- [Stump](https://www.stumpapp.dev) - 快速、免费且开源的漫画、漫画和数字书籍服务器，支持OPDS。([源代码](https://github.com/stumpapp/stump)) `MIT` `Rust`
- [The Epube](https://gitlab.tt-rss.org/main/the-epube/-/wikis/home) - 使用EPUB.js、Bootstrap和Calibre的自托管Web EPUB阅读器。([源代码](https://gitlab.tt-rss.org/main/the-epube)) `GPL-3.0` `PHP`



### 订阅阅读器

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[新闻聚合器](https://en.wikipedia.org/wiki/News_aggregator)，也称为订阅聚合器、订阅阅读器、新闻阅读器、[RSS](https://en.wikipedia.org/wiki/RSS)阅读器，是一种将网络内容（如报纸/博客/视频博客/播客）聚合在一个位置以便于查看的应用程序。

- [Bubo Reader](https://github.com/georgemandis/bubo-rss) - 开源的，"非理性地简约"的RSS订阅阅读器。([演示](https://bubo-rss-demo.netlify.app/)) `MIT` `Nodejs`
- [CommaFeed](https://www.commafeed.com/) - 受Google Reader启发的自托管RSS阅读器。([演示](https://www.commafeed.com/#/app/category/all), [源代码](https://github.com/Athou/commafeed)) `Apache-2.0` `Java/Docker`
- [FeedCord](https://github.com/Qolors/FeedCord) `None⚠` - 一个简单、轻量且可定制的RSS新闻订阅源，适用于您的Discord服务器。`MIT` `Docker`
- [Feedpushr](https://github.com/ncarlier/feedpushr) - 强大的RSS聚合器，能够转换和发送文章到多个输出。单一二进制文件，可通过插件扩展。`GPL-3.0` `Go/Docker`
- [FreshRSS](https://freshrss.org/) - 可自托管的RSS订阅源聚合器。([演示](https://demo.freshrss.org/i/), [源代码](https://github.com/FreshRSS/FreshRSS), [客户端](https://github.com/Alkarex/EasyRSS)) `AGPL-3.0` `PHP/Docker`
- [Fusion](https://github.com/0x2E/fusion) - 轻量级的RSS聚合器和阅读器。`MIT` `Go/Docker`
- [Goeland](https://github.com/slurdge/goeland) - 读取RSS/Atom订阅源并过滤/摘要它们以创建漂亮的电子邮件。`MIT` `Go`
- [JARR](https://1pxsolidblack.pl/jarr-en.html) - JARR（Just Another RSS Reader）是一个基于网络的新闻聚合器和阅读器（Newspipe的分支）。([演示](https://www.jarr.info/), [源代码](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Docker/Python`
- [Kriss Feed](https://github.com/tontof/kriss_feed) - 简单而智能（或愚蠢）的订阅阅读器。`CC0-1.0` `PHP`
- [Leed](https://github.com/LeedRSS/Leed) - Leed（Light Feed的缩写）是一个免费且简约的RSS聚合器。`AGPL-3.0` `PHP`
- [Miniflux](https://miniflux.app/) - Miniflux是一个简约且开源的新闻阅读器，使用Go和PostgreSQL编写。([源代码](https://github.com/miniflux/v2)) `Apache-2.0` `Go/deb/Docker`
- [NewsBlur](https://www.newsblur.com/) - NewsBlur是一个个人新闻阅读器，它将人们聚集在一起讨论世界。一个古老工具的新声音。([源代码](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [Newspipe](https://git.sr.ht/~cedric/newspipe) - Newspipe是一个网络新闻阅读器。([演示](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`
- [Precis](https://github.com/leozqin/precis) - 具有可扩展性的RSS阅读器，可以使用LLMs（包括本地LLMs）来总结RSS条目，并内置通知支持。`MIT` `Python/Docker`
- [reader](https://github.com/lemon24/reader) - 一个Python订阅阅读器Web应用程序和库（因此您可以使用它来构建自己的应用程序），仅依赖标准库和纯Python依赖项。`BSD-3-Clause` `Python`
- [Readflow](https://readflow.app) - 轻量级新闻阅读器，具有现代界面和功能：全文搜索、自动分类、归档、离线支持、通知等。([源代码](https://github.com/ncarlier/readflow)) `MIT` `Go/Docker`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - 为没有订阅源的网站生成RSS/ATOM订阅源。`Unlicense` `PHP/Docker`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - 易于使用的基于网络的RSS聚合器和阅读器，兼容Fever API（Google Reader的替代品）。`MIT` `PHP`
- [RSS2EMail](https://github.com/rss2email/rss2email) - 获取RSS/Atom订阅源并将新内容推送到任何电子邮件接收者，支持OPML。`GPL-2.0` `Python/deb`
- [RSSHub](https://docs.rsshub.app) - 易于使用且可扩展的RSS订阅源聚合器，它能够从几乎所有内容（从社交媒体到大学部门）生成RSS订阅源。([演示](https://rsshub.app), [源代码](https://github.com/DIYgod/RSSHub)) `MIT` `Nodejs/Docker`
- [Selfoss](https://selfoss.aditu.de/) - 新型多用途RSS阅读器、实时流、混搭、聚合Web应用程序。([源代码](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- [Stringer](https://github.com/stringer-rss/stringer) - 正在进行中的自托管、反社会的RSS阅读器。`MIT` `Ruby`
- [Tiny Tiny RSS](https://tt-rss.org) - 开源基于网络的新闻订阅源（RSS/Atom）阅读器和聚合器。([演示](https://srv.tt-rss.org/tt-rss/), [源代码](https://git.tt-rss.org/fox/tt-rss)) `GPL-3.0` `Docker/PHP`
- [Yarr](https://github.com/nkanaev/yarr) - Yarr（又一个RSS阅读器）是一个基于网络的订阅源聚合器，可用作桌面应用程序和个人自托管服务器。`MIT` `Go`


### 文件传输与同步

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[文件传输](https://en.wikipedia.org/wiki/File_transfer)、[共享](https://en.wikipedia.org/wiki/File_sharing)和[同步软件](https://en.wikipedia.org/wiki/File_synchronization)软件。

_相关：[群件](#groupware)_

- [bewCloud](https://bewcloud.com) - Nextcloud和ownCloud的RSS阅读器、文件共享+同步、笔记和照片的简化替代品。([源代码](https://github.com/bewcloud/bewcloud), [客户端](https://github.com/bewcloud)) `AGPL-3.0` `Docker`
- [Git Annex](https://git-annex.branchable.com/) - 在计算机、服务器、外部驱动器之间同步文件。([源代码](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - Kinto是一个具有同步和共享能力的极简JSON存储服务。([源代码](https://github.com/Kinto)) `Apache-2.0` `Python`
- [Nextcloud](https://nextcloud.com/) - 在任何设备上访问和共享您的文件、日历、联系人、邮件等，按照您的条件进行。([演示](https://try.nextcloud.com/), [源代码](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP/deb`
- [OpenSSH SFTP服务器](https://www.openssh.com/) - 安全文件传输程序。([源代码](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh/)) `BSD-2-Clause` `C/deb`
- [ownCloud](https://owncloud.org/) - 保存、同步、查看、编辑和共享文件、日历、地址None簿等的全能解决方案。([源代码](https://github.com/owncloud/core), [客户端](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP/Docker/deb`
- [Peergos](https://peergos.org) - 在线的安全和私人空间，您可以在此存储、共享和查看您的照片、视频、音乐和文档。还包括日历、新闻提要、任务列表、聊天和电子邮件客户端。([源代码](https://github.com/Peergos)) `AGPL-3.0` `Java`
- [Puter](https://puter.com/) - 设计为功能丰富、极速且高度可扩展的基于Web的操作系统。([演示](https://puter.com/), [源代码](https://github.com/heyputer/puter)) `AGPL-3.0` `Nodejs/Docker`
- [Pydio](https://pydio.com/) - 将任何Web服务器变成一个强大的文件管理系统和主流云存储提供商的替代品。([演示](https://pydio.com/en/demo), [源代码](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- [Samba](https://www.samba.org/) - Samba是Linux和Unix上标准的Windows互操作套件程序。它为使用SMB/CIFS协议的所有客户端提供安全、稳定和快速的文件和打印服务。([源代码](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - 主要用于团队和组织的文件托管和共享解决方案。([源代码](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- [Syncthing](https://syncthing.net/) - Syncthing是一个开源的点对点文件同步工具。([源代码](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go/Docker/deb`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison是一个用于OSX、Unix和Windows的文件同步工具。([源代码](https://github.com/bcpierce00/unison)) `GPL-3.0` `deb/OCaml`


### 文件传输 - 分布式文件系统

**[`^        回到顶部        ^`](#awesome-selfhosted)**

网络分布式文件系统。

**请访问 [awesome-sysadmin/分布式文件系统](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**


### 文件传输 - 对象存储和文件服务器

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[对象存储](https://en.wikipedia.org/wiki/Object_storage)是一种管理数据作为对象的计算机数据存储，与其他存储架构（如文件系统管理数据作为文件层次结构和块存储管理数据作为扇区和轨道内的块）不同。

- [GarageHQ](https://garagehq.deuxfleurs.fr/) - 一个您可以自托管的开源地理分布式存储服务，用于满足许多需求 - 兼容S3。([源代码](https://git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Docker/Rust`
- [Minio](https://min.io/) - Minio是一个开源的对象存储服务器，兼容Amazon S3 API。([源代码](https://github.com/minio/minio)) `AGPL-3.0` `Go/Docker/K8S`
- [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - SeaweedFS是一个开源分布式文件系统，支持WebDAV、S3 API、FUSE挂载、HDFS等，针对大量小文件进行优化，易于添加容量。`Apache-2.0` `Go`
- [SFTPGo](https://github.com/drakkan/sftpgo) - 灵活、功能齐全且高度可配置的SFTP服务器，可选支持FTP/S和WebDAV。`AGPL-3.0` `Go/deb/Docker`
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - Zenko CloudServer，一个处理Amazon S3协议的开源服务器实现。([源代码](https://github.com/scality/cloudserver)) `Apache-2.0` `Docker/Nodejs`
- [ZOT OCI Registry](https://zotregistry.dev) - 一个生产就绪的供应商中立的OCI原生容器镜像注册表。([演示](https://zothub.io), [源代码](https://github.com/project-zot/zot)) `Apache-2.0` `Go/Docker`


### 文件传输 - 点对点文件共享

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[点对点文件共享](https://en.wikipedia.org/wiki/Peer-to-peer_file_sharing)是使用[点对点](https://en.wikipedia.org/wiki/Peer-to-peer)（P2P）网络技术分发和[共享](https://en.wikipedia.org/wiki/File_sharing)数字媒体。

- [bittorrent-tracker](https://webtorrent.io/) - 简单、健壮的BitTorrent追踪器（客户端和服务器）实现。([源代码](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Nodejs`
- [Dat Project](https://dat-ecosystem.org/) - 从大型模块生态系统构建的强大去中心化文件共享应用程序。([源代码](https://github.com/datproject)) `MIT` `Nodejs`
- [Deluge](https://deluge-torrent.org/) - 轻量级、跨平台的BitTorrent客户端。([源代码](https://git.deluge-torrent.org/deluge/tree/?h=develop)) `GPL-3.0` `Python/deb`
- [instant.io](https://github.com/webtorrent/instant.io) - 通过WebTorrent流式传输文件。([演示](https://instant.io)) `MIT` `Nodejs`
- [qBittorrent](https://www.qbittorrent.org/) - 免费的跨平台bittorrent客户端，具有用于远程访问的功能丰富的Web UI。([源代码](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [Send](https://github.com/timvisee/send) - 简单的、私人的、端到端加密的临时文件共享，最初由Mozilla构建。([客户端](https://github.com/timvisee/send#clients)) `MPL-2.0` `Nodejs/Docker`
- [Transmission](https://transmissionbt.com/) - 快速、简单、免费的Bittorrent客户端。([源代码](https://github.com/transmission/transmission)) `GPL-3.0` `C++/deb`None



### 人力资源管理 (HRM)

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[人力资源管理系统](https://en.wikipedia.org/wiki/Human_resource_management_system) 结合了多个系统和流程，以确保[人力资源](https://en.wikipedia.org/wiki/Human_resources)、业务流程和数据的轻松管理。

- [admidio](https://www.admidio.org/) - Admidio 是一个免费的开源用户管理系统，适用于组织和团体的网站。该系统具有灵活的角色模型，因此可以反映组织的结构和权限。([演示](https://www.admidio.org/demo/), [源代码](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP/Docker`
- [OrangeHRM](https://www.orangehrm.com/) - OrangeHRM 是一个全面的 HRM 系统，捕捉企业所需的所有基本功能。([演示](https://opensource-demo.orangehrmlive.com/), [源代码](https://github.com/orangehrm/orangehrm)) `GPL-2.0` `PHP`
- [TimeOff.Management](https://timeoff.management) - 简单而强大的缺勤管理软件，适用于中小型企业。([演示](https://app.timeoff.management), [源代码](https://github.com/timeoff-management/timeoff-management-application)) `MIT` `Nodejs`


### 物联网 (IoT)

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[物联网](https://en.wikipedia.org/wiki/Internet_of_things) 描述了具有传感器、处理能力、软件和其他技术的物理对象，这些对象可以通过互联网连接并与其他设备交换数据。

- [DeviceHive](https://www.devicehive.com/) - 具有广泛集成选项的开源物联网平台。([演示](https://playground.devicehive.com/), [源代码](https://github.com/devicehive/devicehive-java-server)) `Apache-2.0` `Java/Docker/K8S`
- [Domoticz](https://www.domoticz.com/) - 家庭自动化系统，可让您监控和配置各种设备，如：灯光、开关、各种传感器/计量器，如温度、雨量、风力、紫外线、电力、燃气、水等。([源代码](https://github.com/domoticz/domoticz), [客户端](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++/Docker/Shell`
- [EMQX](https://www.emqx.io/) - 一个超大规模的开源 MQTT 代理。连接一个集群中的 1 亿多个物联网设备，以每秒 100 万条消息的吞吐量和 1 毫秒的延迟移动和处理实时物联网数据。([演示](https://www.emqx.com/en/mqtt/public-mqtt5-broker), [源代码](https://github.com/emqx/emqx)) `Apache-2.0` `Docker/Erlang`
- [FHEM](https://fhem.de/fhem.html) - FHEM 用于自动化家庭中的常见任务，如开关灯和加热。它还可以用于记录事件，如温度或电力消耗。您可以通过网络或智能手机前端、Telnet 或 TCP/IP 直接控制它。([源代码](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [FlowForge](https://flowforge.com/) - FlowForge 允许公司以可靠、可扩展和安全的方式部署 Node-RED 应用程序。FlowForge 平台为 Node-RED 开发团队提供 DevOps 能力。([源代码](https://github.com/flowforge/flowforge)) `Apache-2.0` `Nodejs/Docker/K8S`
- [Gladys](https://gladysassistant.com/) - Gladys 是一个注重隐私的开源家庭助手。([源代码](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Nodejs/Docker`
- [Home Assistant](https://home-assistant.io/) - 开源家庭自动化平台。([演示](https://home-assistant.io/demo/), [源代码](https://github.com/home-assistant/core)) `Apache-2.0` `Python/Docker`
- [ioBroker](https://www.iobroker.net/) - 物联网的集成平台，专注于建筑自动化、智能计量、环境辅助生活、过程自动化、可视化和数据记录。([源代码](https://github.com/ioBroker/ioBroker)) `MIT` `Nodejs`
- [Node RED](https://nodered.org/) - 基于浏览器的流程编辑器，帮助您连接硬件设备、API 和在线服务以创建物联网解决方案。([源代码](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs/Docker`
- [openHAB](https://www.openhab.org) - 供应商和技术无关的开源家庭自动化软件。([源代码](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- [OpenRemote](https://openremote.io) - 开源物联网平台 - 物联网资产管理、流规则和 WHEN-THEN 规则、数据可视化、边缘网关。([演示](https://demo.openremote.io/), [源代码](https://github.com/openremote/openremote)) `AGPL-3.0` `Java`
- [SIP Irrigation Control](https://dan-in-ca.github.io/SIP/) - 用于喷洒/灌None溉控制的开源软件。([源代码](https://github.com/Dan-in-CA/SIP)) `GPL-3.0` `Python`
- [Tasmota](https://tasmota.com) - 用于 ESP 设备的开源固件。快速设置和更新的完全本地控制。使用 MQTT、Web UI、HTTP 或串行控制。使用计时器、规则或脚本自动化。与家庭自动化解决方案集成。([源代码](https://github.com/arendst/Tasmota)) `GPL-3.0` `C/C++`
- [Thingsboard](https://thingsboard.io/) - 开源物联网平台 - 设备管理、数据收集、处理和可视化。([演示](https://demo.thingsboard.io/signup), [源代码](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java/Docker/K8S`
- [WebThings Gateway](https://webthings.io/gateway/) - WebThings 是 Web of Things 的开源实现，包括 WebThings Gateway 和 WebThings Framework。([源代码](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Nodejs`


### 库存管理

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[库存管理软件](https://en.wikipedia.org/wiki/Inventory_management_software)。

_相关：[金钱、预算与管理](#money-budgeting--management), [资源规划](#resource-planning)_

_另见：[awesome-sysadmin/IT 资产管理](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- [Cannery](https://cannery.app) - 枪械和弹药跟踪应用程序。([源代码](https://gitea.bubbletea.dev/shibao/cannery)) `AGPL-3.0` `Docker`
- [HomeBox (SysAdminsMedia)](https://homebox.software/) - 为家庭用户构建的库存和组织系统。([演示](https://demo.homebox.software/), [源代码](https://github.com/sysadminsmedia/homebox)) `AGPL-3.0` `Docker/Go`
- [Inventaire](https://inventaire.io/welcome) - 协作资源映射项目，目前仅专注于探索与维基数据和 ISBNs 相关的书籍映射。([源代码](https://github.com/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- [Inventree](https://inventree.readthedocs.io/en/latest/) - InvenTree 是一个开源库存管理系统，提供直观的零件管理和库存控制。([演示](https://inventree.org/demo), [源代码](https://github.com/inventree/InvenTree)) `MIT` `Python`
- [Open QuarterMaster](https://openquartermaster.com/) - 强大的库存管理系统，设计灵活且可扩展。([源代码](https://github.com/Epic-Breakfast-Productions/OpenQuarterMaster)) `GPL-3.0` `deb/Docker`
- [Part-DB](https://docs.part-db.de/) - 用于管理您的电子组件的库存管理系统。([演示](https://demo.part-db.de/en/), [源代码](https://github.com/Part-DB/Part-DB-server)) `AGPL-3.0` `Docker/PHP/Nodejs`
- [Shelf](https://www.shelf.nu) - 团队使用的资产和设备跟踪软件，这些团队重视清晰度。Shelf 是一个资产数据库和 QR 资产标签生成器，让您可以在不同位置创建、管理和概览您的资产。无限资产，永久免费。([源代码](https://github.com/Shelf-nu/shelf.nu)) `AGPL-3.0` `Nodejs`


### 知识管理工具

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[知识管理](https://en.wikipedia.org/wiki/Knowledge_management) 是与创建、共享、使用和管理知识和信息相关的方法的集合。

_相关：[笔记与编辑器](#note-taking--editors), [维基](#wikis), [数据库管理](#database-management)_

- [Atomic Server](https://github.com/atomicdata-dev/atomic-server) - 知识图数据库，带有文档（类似于 Notion）、表格、搜索和强大的链接数据 API。轻量、速度极快且无运行时依赖。([演示](https://atomicdata.dev/)) `MIT` `Docker/Rust`
- [Digimindmap](https://ladigitale.dev/digimindmap/#/) - 创建简单的心智图（文档为法语）。([演示](https://ladigitale.dev/digimindmap/#/), [源代码](https://codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Nodejs/PHP`
- [LibreKB](https://librekb.com/) - 一个基于网络的知识库解决方案。一个简单的网络应用，它可以在带有 PHP 和 MySQL 的任何网络服务器或托管提供商上运行。([源代码](https://github.com/michaelstaake/LibreKB/)) `GPL-3.0` `PHP`
- [SiYuan](https://b3log.org/siyuan/) - 一个注重隐私的个人知识管理软件，用 TypeScript 和 Go 编写。([源代码](https://github.com/siyuan-note/siyuan)) `AGPL-3.0` `Docker/Go`
- [TeamMapper](https://github.com/b310-digital/teammapper) - 主持并创建您自己的心智图。与您的团队共享心智图会话，并在心智图上进行实时协作。([演示](https://map.kits.blog)) `MIT` `Docker/Nodejs`


### 学习和课程

**[`^        回到顶部        ^`](#awesome-selfhosted)**

帮助教育和学习的工具和软件。

- [Canvas LMS](https://www.instructure.com/canvas/) - Canvas 是可信赖的开源学习管理系统（LMS），正在革命化我们的教育方式。([演示](https://canvas.instructure.com/register), [源代码](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - Chamilo LMS 允许您为提供在线或半在线培训创建一个虚拟校园。([源代码](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [Dalton Plan](https://daltonplan.com) - Dalton Plan 是 Helen Parkhurst 在 20 世纪开发的一种自由教学方法的现代采用。([源代码](https://git.io/daltonplan)) `AGPL-3.0` `PHP`
- [Digiscreen](https://ladigitale.dev/digiscreen/) - 用于课堂上的人机交互式白板/壁纸，无论是在现场还是远程（文档为法语）。([演示](https://ladigitale.dev/digiscreen/), [源代码](https://codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Nodejs/PHP`
- [Digitools](https://ladigitale.dev/digitools) - 一组简单的工具，陪伴在现场或远程课程中的动画（文档为法语）。([演示](https://ladigitale.dev/digitools/), [源代码](https://codeberg.org/ladigitale/digitools)) `AGPL-3.0` `PHP`
- [edX](https://www.edx.org/) - Open edX 平台是驱动 edX.org 的开源代码。([源代码](https://github.com/edx/)) `AGPL-3.0` `Python`
- [Gibbon](https://gibbonedu.org/) - 灵活的开源学校管理平台，旨在让教师、学生、家长和领导者的生活更美好。([源代码](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- [ILIAS](https://www.ilias.de) - ILIAS 是可以应对您抛出的任何事情的学习管理系统。([演示](https://demo.ilias.de), [源代码](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [INGInious](https://inginious.org/?lang=en) - 智能评分器，允许安全和自动化测试学生编写的代码。([源代码](https://github.com/UCL-INGI/INGInious), [客户端](https://github.com/UCL-INGI/INGInious-plugins)) `AGPL-3.0` `Python/Docker`
- [Moodle](https://moodle.org/) - Moodle 是一个学习和课程平台，拥有全球最大的开源社区之一。([演示](https://moodle.org/demo/), [源代码](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](https://www.openeclass.org/) - Open eClass 是一个高级的电子学习解决方案，可以增强教学和学习过程。([演示](https://demo.openeclass.org/), [源代码](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - OpenOLAT 是一个基于网络的学习管理系统，用于教学、教育、评估和沟通。([演示](https://learn.olat.com), [源代码](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- [QST](https://qstonline.org) - 在线评估软件。从手机上的快速测验到大规模、高风险的监考桌面测试，简单、安全且经济。([演示](https://qstonline.org/free_account.htm), [源代码](https://sourceforge.net/projects/qstonline/)) `GPL-2.0` `Perl`
- [RELATE](https://documen.tician.de/relate/) - RELATE 是一个基于网络的课程软件包，包括以下功能：灵活规则、统计、多课程支持、班级日历。([源代码](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - RosarioSIS，免费的学生信息系统，用于学校管理。([演示](https://www.rosariosis.org/demo/), [源代码](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`
- [Schoco](https://github.com/PhiTux/schoco) - 用于在学校学习 Java 编程的在线 IDE，包括自动 JUnit 测试。设计用于提供编程作业/任务。`MIT` `Docker`
- [scholarsome](https://www.scholarsome.com/) - 基于网络和开源的交互式学习软件，适用于大众学习。([演示](https://scholarsome.com/), [源代码](https://github.com/hwgilbert16/scholarsome)) `GPL-3.0` `Docker`


### 制造

**[`^        回到顶部        ^`](#awesome-selfhosted)**

管理[3D 打印机](https://en.wikipedia.org/wiki/3D_printing)、[数控机床](https://en.wikipedia.org/wiki/Numerical_control)和其他物理制造工具的软件。

- [CNCjs](https://cnc.js.org/) - 用于运行 Grbl、Smoothieware 或 TinyG 的 CNC None铣床控制器的基于网络的接口。([源代码](https://github.com/cncjs/cncjs/)) `MIT` `Nodejs`
- [Fluidd](https://docs.fluidd.xyz/) - Klipper 的轻量级和响应式用户界面，3D 打印机固件。([源代码](https://github.com/fluidd-core/fluidd)) `GPL-3.0` `Docker/Nodejs`
- [Mainsail](https://docs.mainsail.xyz/) - Klipper 3D 打印机固件的现代和响应式用户界面。从任何地方、任何设备控制和监控您的打印机。([源代码](https://github.com/mainsail-crew/mainsail)) `GPL-3.0` `Docker/Python`
- [Manyfold](https://manyfold.app) - 3D 打印文件的数字资产管理器；STL、OBJ、3MF 等。([源代码](https://github.com/manyfold3d/manyfold)) `MIT` `Docker`
- [Octoprint](https://octoprint.org/) - 用于控制消费级 3D 打印机的快速网络界面。([源代码](https://github.com/OctoPrint/OctoPrint)) `AGPL-3.0` `Docker/Python`


### 地图和全球定位系统 (GPS)

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[地图](https://en.wikipedia.org/wiki/Map)、[制图学](https://en.wikipedia.org/wiki/Cartography)、[GIS](https://en.wikipedia.org/wiki/Geographic_information_system)和[GPS](https://en.wikipedia.org/wiki/Global_Positioning_System)软件。

_另见：[awesome-openstreetmap](https://github.com/osmlab/awesome-openstreetmap), [awesome-gis](https://github.com/sshuair/awesome-gis)_

- [AdventureLog](https://adventurelog.app) - 旅行跟踪器和行程规划器。([演示](https://adventurelog.app), [源代码](https://github.com/seanmorley15/AdventureLog)) `GPL-3.0` `Docker`
- [Bicimon](https://github.com/knrdl/bicimon) - 作为渐进式网络应用程序的自行车测速仪。([演示](https://knrdl.github.io/bicimon/)) `MIT` `Javascript`
- [Geo2tz](https://github.com/noandrea/geo2tz) - 从地理坐标（None纬度、经度）获取时区。`MIT` `Go/Docker`
- [GraphHopper](https://graphhopper.com/) - 在 OpenStreetMap 上运行的快速路由库和服务器。([源代码](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [Nominatim](https://nominatim.org/) - 在 OpenStreetMap 数据上运行的地理编码（地址 -> 坐标）和反向地理编码（坐标 -> 地址）的服务器应用程序。([源代码](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - 基于 OpenStreetMap 数据的高性能路由引擎，提供 HTTP API、C++ 库接口和 Nodejs 包装器。([演示](https://map.project-osrm.org/), [源代码](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- [OpenRouteService](https://openrouteservice.org/) - 带有方向、等时线、时间-距离矩阵、路线优化等功能的自托管路线服务。([演示](https://openrouteservice.org/dev/#/api-docs/introduction), [源代码](https://github.com/GIScience/openrouteservice)) `GPL-3.0` `Docker/Java`
- [OpenStreetMap](https://www.openstreetmap.org/) - 协作项目，旨在创建一个免费的可编辑世界地图。([源代码](https://github.com/openstreetmap/openstreetmap-website), [客户端](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/) - 基于 OpenStreetMap 数据的多模式行程规划软件，消耗发布的 GTFS 格式数据以建议使用当地公共交通系统的路线。([源代码](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/Javascript`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `None⚠` - 存储和访问由 [OwnTracks](https://owntracks.org/) 位置跟踪应用程序发布的数据。`GPL-2.0` `C/Lua/deb/Docker`
- [TileServer GL](https://tileserver.readthedocs.io/) - 使用 GL 样式的矢量和None栅格地图。通过 Mapbox GL Native 在服务器端渲染。用于 Mapbox GL JS、Android、iOS、Leaflet、OpenLayers、通过 WMTS 的 GIS 等的地图瓦片服务器。([源代码](https://github.com/maptiler/tileserver-gl)) `BSD-2-Clause` `Nodejs/Docker`
- [Traccar](https://www.traccar.org/) - Java 应用程序，用于跟踪 GPS 位置。支持大量的跟踪设备和协议，具有 Android 和 iOS 应用程序。有一个网络界面来查看您的行程。([演示](https://demo.traccar.org/), [源代码](https://github.com/traccar)) `Apache-2.0` `Java`
- [μlogger](https://github.com/bfabiszewski/ulogger-server) - 实时收集用户的地理位置并在网站上显示他们的 GPS 轨迹。([演示](http://ulogger.fabiszewski.net/)) `GPL-3.0` `PHP`


### 媒体流

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[流媒体](https://en.wikipedia.org/wiki/Streaming_media) 是从源连续传输和消费的多媒体，网络元素中几乎没有或没有中间存储。

请访问 [媒体流 - 音频流](#media-streaming---audio-streaming), [媒体流 - 多媒体流](#media-streaming---multimedia-streaming), [媒体流 - 视频流](#media-streaming---video-streaming)

_另见：[流媒体系统列表 - 维基百科](https://en.wikipedia.org/wiki/List_of_streaming_media_systems), [流媒体系统比较 - 维基百科](https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_None



### 媒体流 - 音频流

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[音频](https://en.wikipedia.org/wiki/Audio) 流工具和软件。

- [Ampache](https://ampache.org/) - 基于网络的音频/视频流应用程序。([演示](https://play.dogmazic.net/), [源代码](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Audiobookshelf](https://www.audiobookshelf.org/) - 完全开源的自托管有声读物和播客服务器。它流式传输所有音频格式，跨设备保持和同步进度。附带适用于Android和iOS的开源应用程序。([源代码](https://github.com/advplyr/audiobookshelf), [客户端](https://github.com/advplyr/audiobookshelf-app)) `GPL-3.0` `Docker/deb/Nodejs`
- [Audioserve](https://github.com/izderadicka/audioserve) - 简单的个人服务器，用于从目录中服务音频文件（有声读物、音乐、播客...）。专注于简洁性，并支持在客户端之间同步播放位置。`MIT` `Rust`
- [AzuraCast](https://www.azuracast.com/) - 现代且易于访问的自托管网络广播管理套件。([源代码](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `Docker`
- [Beets](https://beets.io/) - 音乐库管理器和MusicBrainz标记器（命令行和Web界面）。([源代码](https://github.com/beetbox/beets)) `MIT` `Python/deb`
- [Black Candy](https://github.com/blackcandy-org/black_candy) - 使用Rails和Stimulus构建的音乐流服务器。`MIT` `Docker/Ruby`
- [Bsimp](https://github.com/akrylysov/bsimp) - 最小化的S3支持的音频库。`Apache-2.0` `Go`
- [Funkwhale](https://dev.funkwhale.audio/funkwhale) - 现代、基于Web的、友好的、多用户和免费的音乐服务器。`BSD-3-Clause` `Python/Django`
- [gonic](https://github.com/sentriz/gonic) - 轻量级音乐流服务器。与Subsonic兼容。`GPL-3.0` `Go/Docker`
- [HoloPlay](https://app.holoplay.io) `None⚠` - 使用Invidious API的Web应用程序，用于收听YouTube音频源。([源代码](https://github.com/stephane-r/holoplay-pwa)) `MIT` `Nodejs/Docker`
- [koel](https://koel.dev/) - 个人音乐流服务器，功能强大。([演示](https://demo.koel.dev/, [源代码](https://github.com/koel/koel)) `MIT` `PHP`
- [LibreTime](https://libretime.org) - 简单的开源平台，让您可以在网络上广播流媒体广播（[Airtime](https://github.com/sourcefabric/Airtime)的分支）。([源代码](https://github.com/LibreTime/libretime)) `AGPL-3.0` `Docker/PHP`
- [LMS](https://github.com/epoupon/lms) - 使用Web界面访问您的自托管音乐。`GPL-3.0` `Docker/deb/C++`
- [Maloja](https://github.com/krateng/maloja) - 自托管的音乐记录数据库（Last.fm的替代品）。([演示](https://maloja.krateng.ch/)) `GPL-3.0` `Python/Docker`
- [moOde Audio](https://moodeaudio.org/) - 用于出色的Raspberry Pi单板计算机家族的发烧友级音乐播放。([源代码](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- [Mopidy](https://docs.mopidy.com/) - 可扩展的音乐服务器。提供mpd API的超集，以及与Spotify、SoundCloud等第三方服务的集成。([源代码](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python/deb`
- [mpd](https://www.musicpd.org/) - 远程播放音乐、流式传输音乐、处理和组织播放列表的守护进程。有许多可用的客户端。([源代码](https://github.com/MusicPlayerDaemon/MPD), [客户端](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`
- [mStream](https://mstream.io/) - 带有GUI管理工具的音乐流服务器。可以在Mac、Windows和Linux上运行。([源代码](https://github.com/IrosTheBeggar/mStream)) `GPL-2.0` `Nodejs`
- [multi-scrobbler](https://foxxmd.github.io/multi-scrobbler) - 从多个来源将播放记录到多个记录服务。([源代码](https://github.com/FoxxMD/multi-scrobbler)) `MIT` `Nodejs/Docker`
- [musikcube](https://musikcube.com/) - 具有Linux/macOS/Windows/Android客户端的流式音频服务器。([源代码](https://github.com/clangen/musikcube)) `BSD-3-Clause` `C++/deb`
- [Navidrome Music Server](https://www.navidrome.org) - 现代音乐服务器和流媒体器，与Subsonic/Airsonic兼容。([演示](https://www.navidrome.org/demo), [源代码](https://github.com/navidrome/navidrome), [客户端](https://www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Docker/Go`
- [Pinepods](https://www.pinepods.online/) - 基于Rust的播客管理系统，支持多用户。Pinepods利用中央数据库，因此像听取时间和主题这样的方面可以从设备到设备之间跟随。([演示](https://try.pinepods.online), [源代码](https://github.com/madeofpendletonwool/PinePods)) `GPL-3.0` `Docker`
- [PodFetch](https://samtv12345.github.io/PodFetch) - 一个简洁且高效的播客下载器。([源代码](https://github.com/SamTV12345/PodFetch)) `Apache-2.0` `Docker/Rust`
- [Polaris](https://github.com/agersant/polaris) - 针对大型音乐收藏、易用性和高性能优化的音乐浏览和流媒体应用程序。`MIT` `Rust/Docker`
- [Snapcast](https://github.com/badaix/snapcast) - 同步多房间音频服务器。`GPL-3.0` `C++/deb`
- [Stretto](https://github.com/benkaiser/stretto) - 带有YouTube/Soundcloud导入和iTunes/Spotify发现的音乐播放器。([演示](https://next.kaiserapps.com), [客户端](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
- [Supysonic](https://github.com/spl0k/supysonic) - Subsonic服务器API的Python实现。`AGPL-3.0` `Python/deb`
- [SwingMusic](https://swingmusic.vercel.app/) - Swing Music是一个美丽的自托管音乐播放器和流媒体服务器，用于您的本地音频文件。就像一个更酷的Spotify...但带上您自己的音乐。([源代码](https://github.com/swing-opensource/swingmusic)) `MIT` `Python/Docker`
- [vod2pod-rss](https://github.com/madiele/vod2pod-rss) `None⚠` - 将YouTube和Twitch频道转换为播客，不需要存储。实时将VoDs转码为MP3 192k，生成RSS供播客客户端使用。`MIT` `Docker`


### 媒体流 - 多媒体流

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[多媒体](https://en.wikipedia.org/wiki/Multimedia) 流工具和软件。

_相关：[媒体流 - 视频流](#media-streaming---video-streaming), [媒体流 - 音频流](#media-streaming---audio-streaming)_

- [Dim](https://github.com/Dusk-Labs/dim) - Dim是一个由黑暗力量驱动的自托管媒体管理器。只需最小的设置，Dim将组织和美化您的媒体收藏，让您随时随地访问和播放它们。`GPL-2.0` `Rust`
- [Gerbera](https://gerbera.io/) - Gerbera是一个UPnP媒体服务器。它允许您在家庭网络中流式传输您的数字媒体，并在各种兼容UPnP的设备上收听/观看它们。([源代码](https://github.com/gerbera/gerbera)) `GPL-2.0` `Docker/deb/C++`
- [Icecast 2](https://icecast.org) - 用于创建互联网广播电台或私人运行的点唱机以及许多其他用途的流式音频/视频服务器。([源代码](https://gitlab.xiph.org/xiph/icecast-server), [客户端](https://icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.org) - 音频、视频、书籍、漫画和照片的媒体服务器，具有流畅的界面和强大的转码能力。几乎所有现代平台都有客户端，包括Roku、Android TV、iOS和Kodi。([演示](https://demo.jellyfin.org/stable), [源代码](https://github.com/jellyfin/jellyfin), [客户端](https://github.com/awesome-jellyfin/awesome-jellyfin)) `GPL-2.0` `C#/deb/Docker`
- [Karaoke Eternal](https://www.karaoke-eternal.com) - 主持出色的卡拉OK派对，每个人都可以轻松地从手机浏览器中找到并排队歌曲。播放器也完全基于浏览器，支持MP3+G、MP4和WebGL可视化。([源代码](https://www.karaoke-eternal.com/repo)) `ISC` `Docker/Nodejs`
- [Kodi](https://kodi.tv/) - 多媒体/None娱乐中心，以前称为XBMC。在Android、BSD、Linux、macOS、iOS和Windows上运行。([源代码](https://github.com/xbmc/xbmc)) `GPL-2.0` `C++/deb`
- [Kyoo](https://github.com/zoriya/kyoo) - 创新的媒体浏览器，专为无缝流式传输动画、系列和电影而设计，提供动态转码、自动观看历史和智能元数据检索等高级功能。([演示](https://kyoo.zoriya.dev)) `GPL-3.0` `Docker`
- [Meelo](https://github.com/Arthi-chaud/Meelo) - 个人音乐服务器，专为收藏家和音乐狂热者设计。`GPL-3.0` `Docker`
- [MistServer](https://mistserver.org/) - 公共领域的流媒体服务器，可以与任何设备和任何格式一起工作。([源代码](https://github.com/DDVTECH/mistserver)) `Unlicense` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - 将您选择的Linux兼容硬件变成电视或有源扬声器的音频和视频源（Chromecast的替代品）。([源代码](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- [ReadyMedia](https://sourceforge.net/projects/minidlna/) - 简单的媒体服务器软件，旨在完全符合DLNA/UPnP-AV客户端。以前称为MiniDLNA。([源代码](https://sourceforge.net/p/minidlna/git/ci/master/tree/)) `GPL-2.0` `C`
- [Rygel](https://gnome.pages.gitlab.gnome.org/rygel/) - Rygel是一个UPnP AV MediaServer，允许您轻松共享音频、视频和图片。媒体播放器软件可以使用Rygel成为一个MediaRenderer，可以通过UPnP或DLNA控制器远程控制。([源代码](https://gitlab.gnome.org/GNOME/rygel/)) `GPL-3.0` `C`
- [Stash](https://stashapp.cc) - 一个基于Web的图书馆组织器和播放器，用于您的成人媒体收藏，支持自动标记和元数据抓取。([源代码](https://github.com/stashapp/stash)) `AGPL-3.0` `Docker/Go`
- [µStreamer](https://github.com/pikvm/ustreamer) - 一个轻量级且非常快的服务器，用于从任何V4L2设备流式传输MJPEG视频到网络。`GPL-3.0` `C/deb`
- [üWave](https://u-wave.net/) `None⚠` - 自托管的协作听音平台。用户可以轮流播放来自YouTube和SoundCloud等多种媒体来源的媒体——歌曲、演讲、游戏视频或其他任何内容。([演示](https://wlk.yt/), [源代码](https://github.com/u-wave)) `MIT` `Nodejs`


### 媒体流 - 视频流

**[`^        回到顶部        ^`](#awesome-selfhosted)**

[视频](https://en.wikipedia.org/wiki/Video) 流工具和软件。

_相关：[视频监控](#video-surveillance)，[媒体流 - 多媒体流](#media-streaming---multimedia-streaming)_

- [CyTube](https://github.com/calzoneman/sync) - CyTube 是一个提供媒体同步、聊天等功能的网络应用程序，适用于任意数量的频道。([演示](https://cytu.be)) `MIT` `Nodejs`
- [Invidious](https://github.com/iv-org/invidious) `None⚠` - YouTube 的替代前端。([演示](https://docs.invidious.io/instances/)) `AGPL-3.0` `Docker/Crystal`
- [MediaCMS](https://mediacms.io) - MediaCMS 是一个现代的、全功能的开源视频和媒体 CMS，使用 Python/Django/React 编写，具有 REST API。([源代码](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
- [Open Streaming Platform](https://openstreamingplatform.com) - 提供实时和按需视频流（Twitch 和 YouTube Live 的替代方案）。([源代码](https://gitlab.com/Deamos/flask-nginx-rtmp-manager)) `MIT` `Python`
- [OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine) - OvenMediaEngine 是一个可自托管的开源流媒体服务器，具有亚秒级延迟。([演示](https://demo.ovenplayer.com)) `GPL-3.0` `C++/Docker`
- [Owncast](https://owncast.online/) - 去中心化的单用户直播视频流和聊天服务器，用于运行类似于主流大型选项的直播流。([源代码](https://github.com/owncast/owncast)) `MIT` `Go`
- [PeerTube](https://joinpeertube.org/en/) - 使用 P2P（BitTorrent）直接在网络浏览器中进行的去中心化视频流平台。([源代码](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - 自托管的 torrent 视频流服务/torrent 客户端，允许在浏览器中或从 Chromecast/AppleTV/智能电视中搜索和播放 torrent 中的视频。`MIT` `Python/Docker`
- [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer 允许您在网站上进行 h.264 实时视频流，而无需流媒体提供商。([源代码](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- [SRS](https://ossrs.io/) - 一个简单、高效且实时的视频服务器，支持 RTMP、WebRTC、HLS、HTTP-FLV 和 SRT。([源代码](https://github.com/ossrs/srs)) `MIT` `Docker/C++`
- [Streama](https://github.com/streamaserver/streama) - 自托管的流媒体服务器。`MIT` `Java`
- [SyncTube](https://github.com/RblSb/SyncTube) - 轻量且易于设置的 CyTube 替代方案，用于与朋友一起观看视频和聊天。`MIT` `Nodejs/Haxe`
- [Tube Archivist](https://tubearchivist.com/) `None⚠` - 组织、搜索和享受您的 YouTube 收藏。订阅、下载和跟踪已查看的内容，并通过元数据索引和用户友好的界面进行管理。([源代码](https://github.com/tubearchivist/tubearchivist), [客户端](https://docs.tubearchivist.com/faq/#how-do-i-import-my-videos-to-emby-plex-jellyfin-kodi)) `GPL-3.0` `Docker`
- [Tube](https://git.mills.io/prologic/tube) - 类似 YouTube（_无审查和您不需要的功能！_）的视频共享应用程序，用 Go 编写，还支持自动转码为 MP4 H.265 AAC、多个集合和 RSS 提要。([演示](https://tube.mills.io)) `MIT` `Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - 跨平台的多媒体播放器客户端和服务器，支持大多数多媒体文件以及 DVD、音频 CD、VCD 和各种流媒体协议。([源代码](https://code.videolan.org/videolan/vlc)) `GPL-2.0` `C/deb`

### 杂项

**[`^        回到顶部        ^`](#awesome-selfhosted)**

不适合其他部分的软件。

- [2FAuth](https://github.com/Bubka/2FAuth) - 一个管理您的双因素认证（2FA）账户并生成其安全代码的网络应用程序。([演示](https://demo.2fauth.app/)) `AGPL-3.0` `PHP/Docker`
- [AlertHub](https://github.com/Ardakilic/alerthub) `None⚠` - AlertHub 是一个从 GitHub 发布中获取警报的简单工具。`MIT` `Nodejs/Docker`
- [Anchr](https://anchr.io) - Anchr 是一个用于互联网上小任务的工具箱，包括书签集合、URL 缩短和（加密）图像上传。([源代码](https://github.com/muety/anchr)) `GPL-3.0` `Nodejs`
- [asciinema](https://asciinema.org/) - 用于托管 asciicasts 的网络应用程序。([演示](https://asciinema.org/explore), [源代码](https://github.com/asciinema/asciinema-server)) `Apache-2.0` `Elixir/Docker`
- [Baby Buddy](https://github.com/babybuddy/babybuddy) - 帮助看护者跟踪婴儿睡眠、喂食、换None尿布和腹部时间。([演示](https://demo.baby-buddy.net/login/?next=/)) `BSD-2-Clause` `Python`
- [beelzebub](https://beelzebub-honeypot.com/) `None⚠` - 设计用于提供高安全环境以检测和分析网络攻击的 honeypot 框架。([演示](https://beelzebub-honeypot.com/docs/), [源代码](https://github.com/mariocandela/beelzebub)) `MIT` `Docker/K8S/Go`
- [Cerbos](https://cerbos.dev) - 一个自托管的开源用户授权层，用于您的应用程序。([演示](https://play.cerbos.dev), [源代码](https://github.com/cerbos/cerbos)) `Apache-2.0` `Go/deb/Docker/K8S`
- [Cloudlog](https://magicbug.co.uk/cloudlog/) - Cloudlog 是一个自托管的 PHP 应用程序，允许您在任何地方记录您的业余无线电联系。([源代码](https://github.com/magicbug/cloudlog)) `MIT` `PHP/Docker`
- [CUPS](https://www.cups.org/) - 通用 Unix 打印系统使用 Internet 打印协议（IPP）支持打印到本地和网络打印机。([源代码](https://github.com/OpenPrinting/cups)) `GPL-2.0` `C`
- [CyberChef](https://github.com/gchq/CyberChef) - 在网络浏览器中执行各种操作，例如 AES、DES 和 Blowfish 加密和解密、创建十六进制转储、计算哈希值等。([演示](https://gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
- [Digiboard](https://digiboard.app/) - 创建协作白板（文档为法语）。([源代码](https://codeberg.org/ladigitale/digiboard)) `AGPL-3.0` `Nodejs`
- [Digicard](https://codeberg.org/ladigitale/digicard) - 创建简单的图形组合（文档为法语）。([演示](https://ladigitale.dev/digicard/)) `AGPL-3.0` `Nodejs`
- [Digiface](https://ladigitale.dev/digiface/) - 使用 Avataaars 库创建头像（文档为法语）。([演示](https://ladigitale.dev/digiface/), [源代码](https://codeberg.org/ladigitale/digiface)) `AGPL-3.0` `Nodejs`
- [Digimerge](https://ladigitale.dev/digimerge/) - 在浏览器中直接组装音频和视频文件（文档为法语）。([演示](https://ladigitale.dev/digimerge/), [源代码](https://codeberg.org/ladigitale/Digimerge)) `AGPL-3.0` `Nodejs`
- [Digitranscode](https://ladigitale.dev/digitranscode) - 在浏览器中直接转换音频文件和视频（文档为法语）。([演示](https://ladigitale.dev/digitranscode), [源代码](https://codeberg.org/ladigitale/digitranscode)) `AGPL-3.0` `Nodejs`
- [Digiview](https://ladigitale.dev/digiview/) `None⚠` - 在无干扰的界面中观看 YouTube 视频（文档为法语）。([演示](https://ladigitale.dev/digiview/), [源代码](https://codeberg.org/ladigitale/digiview)) `AGPL-3.0` `Nodejs/PHP`
- [Digiwords](https://ladigitale.dev/digiwords/) - 一个用于创建词云的简单在线应用程序（文档为法语）。([源代码](https://codeberg.org/ladigitale/digiwords)) `AGPL-3.0` `Nodejs/PHP`
- [DOCAT](https://github.com/docat-org/docat) - 托管您的文档。简单。版本化。花None哨。`MIT` `Python/Docker`
- [DomainMOD](https://domainmod.org) - 用于管理您的域名和其他互联网资产的应用程序，可以在中央位置查看、导出和报告您的 WHM/cPanel 网络服务器数据。([演示](https://demo.domainmod.org), [源代码](https://github.com/domainmod/domainmod)) `GPL-3.0` `PHP`
- [DOMJudge](https://www.domjudge.org/) - 用于运行编程竞赛的系统，如 ICPC 区域和世界锦标赛编程竞赛。([演示](https://www.domjudge.org/demo), [源代码](https://github.com/DOMjudge/domjudge)) `GPL-2.0/BSD-3-Clause/MIT` `PHP`
- [ESMira](https://esmira.kl.ac.at) - 运行纵向研究（ESM、AA、EMA），数据收集和与参与者的沟通完全None匿名。([演示](https://demo-esmira.kl.ac.at/#admin,username:demo,password:demodemodemo), [源代码](https://github.com/KL-Psychological-Methodology/ESMira)) `AGPL-3.0` `PHP`
- [F-Droid](https://f-droid.org) - 维护 F-Droid 存储库系统的服务器工具。([源代码](https://gitlab.com/fdroid/fdroidserver)) `AGPL-3.0` `Python/Docker/deb`
- [Fasten Health](https://github.com/fastenhealth/fasten-onprem/) `None⚠` - Fasten 是一个开源的、自托管的、个人/家庭电子医疗记录聚合器，旨在与美国的 100,000 多家保险公司/医院/诊所集成。`GPL-3.0` `Go/Docker`
- [Flagsmith](https://flagsmith.com) - Flagsmith 提供一个仪表板、API 和 SDK，用于向您的应用程序添加功能标志（LaunchDarkly 的替代方案）。([源代码](https://github.com/flagsmith/flagsmith)) `BSD-3-Clause` `Docker/K8S`
- [Flipt](https://flipt.io) - 支持多种数据后端的功能标志解决方案（LaunchDarkly 的替代方案）。([演示](https://try.flipt.io), [源代码](https://github.com/flipt-io/flipt)) `GPL-3.0` `Docker/K8S/Go`
- [Flyimg](https://flyimg.io) - 在线调整和裁剪图像。使用 ImageMagick 通过 MozJPEG、WebP 或 PNG 获取优化图像，并使用高效的缓存系统。([演示](https://demo.flyimg.io), [源代码](https://github.com/flyimg/flyimg)) `MIT` `Docker`
- [Geeftlist](https://codeberg.org/nanawel/geeftlist) - 用于在朋友和家人之间管理、共享和预订礼物的协作平台。`GPL-3.0` `Docker`
- [GO Feature Flag](https://gofeatureflag.org) - 简单、完整且轻量的功能标志解决方案（LaunchDarkly 的替代方案）。([源代码](https://github.com/thomaspoignant/go-feature-flag)) `MIT` `Go`
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `None⚠` - 自托管 Google 字体的无麻烦方式。获取 eot、ttf、svg、woff 和 woff2 文件 + CSS 代码段。([演示](https://gwfh.mranftl.com/fonts)) `MIT` `Nodejs`
- [Gophish](https://getgophish.com/) - Gophish 是一个功能强大的开源None钓鱼框架，使测试您组织对None钓鱼的暴露变得容易。([源代码](https://github.com/gophish/gophish)) `MIT` `Go/Docker`
- [graph-vl](https://github.com/verifid/graph-vl) - 使用机器学习和 GraphQL 进行身份文件验证。`MIT` `Python/Docker/K8S`
- [Habitica](https://habitica.com/) - 将您的目标视为角色扮演游戏的习惯跟踪应用程序。之前称为 HabitRPG。([源代码](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-SA-3.0` `Nodejs/Docker`
- [HortusFox](https://hortusfox.github.io) - 一个协作植物管理系统。([源代码](https://github.com/danielbrendel/hortusfox-web)) `MIT` `PHP/Docker`
- [IconCaptcha](https://www.fabianwennink.nl/projects/IconCaptcha/) - IconCaptcha 是一个自托管的、快速的、简单的和用户友好的 PHP captcha。([源代码](https://github.com/fabianwennink/IconCaptcha-Plugin-jQuery-PHP)) `MIT` `PHP`
- [Jellyseerr](https://github.com/Fallenbagel/jellyseerr) - 管理您的媒体库请求，支持 Plex、Jellyfin 和 Emby 媒体服务器（Overseerr 的分支）。`MIT` `Docker/Nodejs`
- [Jelu](https://bayang.github.io/jelu-web) - 自托管的阅读和待读列表书籍跟踪器。([源代码](https://github.com/bayang/jelu)) `MIT` `Java/Docker`
- [Kasm Workspaces](https://kasmweb.com/) - 流式传输容器化应用和桌面到最终用户。示例包括在浏览器中使用Ubuntu，或者仅使用单个应用程序，如Chrome、OpenOffice、Gimp、Filezilla等。([演示](https://www.kasmweb.com/#demo), [源代码](https://github.com/kasmtech)) `GPL-3.0` `Docker`
- [Koillection](https://koillection.github.io/) - Koillection 是一项允许用户管理任何种类集合的服务。([源代码](https://github.com/benjaminjonard/koillection)) `MIT` `Docker/PHP`
- [Lama-Cleaner](https://github.com/Sanster/lama-cleaner) `None⚠` - 一个由最先进的人工智能模型驱动的免费开源修复工具。`Apache-2.0` `Python/Docker`
- [LanguageTool](https://languagetool.org/) - 校对超过20种语言。它能发现许多简单的拼写检查工具无法检测到的错误。([源代码](https://github.com/languagetool-org/languagetool), [客户端](https://languagetool.org/insights/post/product-windows-app/)) `LGPL-2.1` `Java/Docker`
- [Libre Translate](https://libretranslate.com/) - 免费开源的机器翻译API，完全自托管。([源代码](https://github.com/LibreTranslate/LibreTranslate)) `AGPL-3.0` `Docker/Python`
- [Loggit](https://loggit.net) - 端到端加密且简单的生活跟踪与记录。([演示](https://app.loggit.net), [源代码](https://github.com/BrunoBernardino/loggit-web)) `AGPL-3.0` `Deno`
- [LubeLogger](https://lubelogger.com) - 基于网络的车辆维护和燃油里程跟踪器。([演示](https://github.com/hargata/lubelog?tab=readme-ov-file#demo), [源代码](https://github.com/hargata/lubelog)) `MIT` `Docker/K8S/C#`
- [MailyGo](https://codeberg.org/jlelse/MailyGo) - MailyGo 是一个用Go语言编写的小工具，允许从静态网站发送HTML表单，例如没有动态后端的网站，通过电子邮件发送。`MIT` `Go`
- [Mere Medical](https://meremedical.co/) `None⚠` - 使用Mere Medical，您终于可以将Epic MyChart、Cerner和OnPatient患者门户的所有医疗记录管理在一个地方。注重隐私，自托管，并且优先离线使用。([演示](https://demo.meremedical.co), [源代码](https://github.com/cfu288/mere-medical)) `GPL-3.0` `Docker/Nodejs`
- [Monica](https://monicahq.com/) - 个人关系管理器，一种新的CRM，用于组织与朋友和家人的互动。([源代码](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP/Docker`
- [mosparo](https://mosparo.io/) - 现代None垃None圾邮件保护工具。它用一个简单易用的None垃None圾邮件保护解决方案替代了其他验证码方法。([源代码](https://github.com/mosparo/mosparo)) `MIT` `PHP`
- [MyIP](https://ipcheck.ing) `None⚠` - 一个全能的IP工具箱。轻松检查您的IP、IP地理位置、检查DNS泄漏、检查WebRTC连接、速度测试、ping测试、MTR测试、检查网站可用性等。([演示](https://ipcheck.ing), [源代码](https://github.com/jason5ng32/MyIP)) `MIT` `Nodejs/Docker`
- [Neko](https://neko.m1k1o.net) - 一个在Docker中运行的自托管虚拟浏览器（rabb.it克隆）。([源代码](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- [Noisedash](https://github.com/kaythomas0/noisedash) - 一个可自托管的网络工具，用于使用音频工具和用户上传的样本生成环境None噪音/声音。`AGPL-3.0` `Nodejs/Docker`
- [Octave Online](https://octave-online.net/) - GNU Octave（MATLAB替代品）的网络用户界面背后的基础设施。([源代码](https://github.com/octave-online/octave-online-server)) `AGPL-3.0` `Docker/Nodejs`
- [Ombi](https://ombi.io/) - 用于Plex/Emby的内容请求系统，连接到SickRage、CouchPotato、Sonarr，具有不断增长的功能集。([演示](https://app.ombi.io/), [源代码](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#/deb`
- [Open-Meteo](https://open-meteo.com/) - 开源天气API，提供来自所有主要国家天气服务的开放数据预测、历史数据和气候数据。([演示](https://open-meteo.com/en/docs), [源代码](https://github.com/open-meteo/open-meteo)) `AGPL-3.0` `Docker`
- [OpenZiti](https://openziti.github.io/) - 功能齐全、自托管、零信任、全网状覆盖网络。包括开箱即用的2FA支持，适用于所有主要桌面/移动操作系统的客户端。([源代码](https://github.com/openziti/ziti)) `Apache-2.0` `Go`
- [OTS-Share](https://github.com/rpgeeganage/ots-share-app) - 一个自托管应用，用于共享秘密，支持最多1MB的文件。`MIT` `Docker`
- [Overseerr](https://overseerr.dev/) `None⚠` - Overseerr 是一个免费开源软件应用，用于管理您的媒体库请求。它与现有的服务集成，如Sonarr、Radarr和Plex！([源代码](https://github.com/sct/overseerr)) `MIT` `Docker`
- [penpot](https://penpot.app/) - 一个基于网络的设计和原型平台，适用于跨领域团队。([源代码](https://github.com/penpot/penpot)) `MPL-2.0` `Docker`
- [POMjs](https://password.oppetmoln.se/) - 随机密码生成器。([源代码](https://github.com/joho1968/POMjs)) `GPL-2.0` `Javascript`
- [Reactive Resume](https://rxresu.me/) - 一个独特的简历构建器，注重您的隐私。完全安全，可定制，便携，开源且永久免费。([演示](https://rxresu.me/app/dashboard/), [源代码](https://github.com/AmruthPillai/Reactive-Resume)) `MIT` `Docker/Nodejs`
- [ReleaseBell](https://releasebell.com/) - 发送星标GitHub仓库的发布通知。([源代码](https://git.cloudron.io/cloudron/releasebell)) `MIT` `Nodejs`
- [revealjs](https://revealjs.com) - 使用HTML轻松创建美丽演示文稿的框架。([演示](https://revealjs.com/), [源代码](https://github.com/hakimel/reveal.js)) `MIT` `Javascript`
- [Revive Adserver](https://www.revive-adserver.com/) - 世界上最流行的免费开源广告投放系统。以前称为OpenX Adserver和phpAdsNew。([源代码](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - 允许远程客户端访问本地主机上可用的图像采集设备（扫描仪）。([源代码](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [Speed Test by OpenSpeedTest™](https://openspeedtest.com/) - 免费开源的HTML5网络性能估计工具。([源代码](https://github.com/openspeedtest/Speed-Test)) `MIT` `Docker`
- [string.is](https://string.is/) - 一个开源、保护隐私的在线字符串工具包，适用于开发人员。([源代码](https://github.com/recurser/string-is)) `AGPL-3.0` `Nodejs`
- [Teleport](https://goteleport.com/) - SSH、Kubernetes、Web应用程序和数据库的证书None颁发机构和访问平面。([源代码](https://github.com/gravitational/teleport)) `Apache-2.0` `Go/Docker/K8S`
- [TeslaMate](https://github.com/adriankumpf/teslamate) - 一个强大的Tesla车辆数据记录器。`MIT` `Elixir/Docker`
- [Upsnap](https://github.com/seriousm4x/UpSnap) - 一个简单的Wake on LAN (WOL) 仪表板应用程序。唤醒网络上的设备并查看当前状态。`MIT` `Go/Docker`
- [URL-to-PNG](https://github.com/jasonraimondi/url-to-png) - URL到PNG实用程序，具有使用Playwright进行并行渲染的功能，用于截图，并通过本地、S3或CouchDB进行存储缓存。`MIT` `Nodejs/Docker`
- [Watcharr](https://github.com/sbondCo/Watcharr) - 一个免费开源的内容观看列表。添加并跟踪您正在观看的所有节目和电影。带有用户认证，现代且简洁的用户界面，以及非常简单的设置。([演示](https://beta.watcharr.app/)) `MIT` `Docker`
- [Wavelog](https://www.wavelog.org) - 基于网络的无线电爱好者的日志记录软件。增强的QSO日志记录、统计数据和浏览器中的地图。([演示](https://demo.wavelog.org), [源代码](https://github.com/wavelog/wavelog)) `MIT` `PHP/Docker`
- [WeeWX](https://weewx.com/) - 您的气象站的开源软件。([演示](https://weewx.com/showcase.html), [源代码](https://github.com/weewx/weewx)) `GPL-3.0` `Python/deb`
- [WeTTY](https://butlerx.github.io/wetty/#/) - 在浏览器中通过http/https的终端。([源代码](https://github.com/butlerx/wetty)) `MIT` `Docker/Nodejs`
- [wger](https://wger.de/) - 基于网络的个人None锻炼、健身和体重记录器/跟踪器。还可以用作简单的健身房管理工具，并提供完整的REST API。([演示](https://wger.de/en/dashboard), [源代码](https://github.com/wger-project/wger)) `AGPL-3.0` `Python/Docker`


### 金钱、预算与管理

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[金钱管理](https://en.wikipedia.org/wiki/Money_management)和预算软件。

_相关：[库存管理](#inventory-management), [资源规划](#resource-planning)_

- [Actual](https://actualbudget.github.io/docs/) - Actual 是一个基于零和预算的本地优先的个人财务工具。它支持跨设备同步、自定义规则、手动导入交易（从QIF、OFX和QFX文件）、以及与许多银行可选的自动同步。([源代码](https://github.com/actualbudget/actual-server)) `MIT` `Nodejs/Docker`
- [Bigcapital](https://bigcapital.app/) - 一个自托管的金融会计和库存管理软件，适用于小型到中型企业。([源代码](https://github.com/bigcapitalhq/bigcapital)) `AGPL-3.0` `Docker`
- [Bitcart](https://bitcart.ai) - 一个自托管的加密货币支付处理器和开发平台。([演示](https://admin.bitcart.ai), [源代码](https://github.com/bitcart/bitcart)) `MIT` `Docker/Python/Nodejs`
- [BTCPay Server](https://btcpayserver.org/) - 一个自托管的比特币和其他加密货币支付处理器。([演示](https://mainnet.demo.btcpayserver.org/), [源代码](https://github.com/btcpayserver/btcpayserver)) `MIT` `C#`
- [Budget Zen](https://budgetzen.net) - 端到端加密且简单的费用管理器。([演示](https://app.budgetzen.net), [源代码](https://github.com/BrunoBernardino/budgetzen-web)) `AGPL-3.0` `Deno`
- [DePay](https://depay.com) - 直接将Web3支付接受到您的钱包中。点对点，免费，自托管和开源。([演示](https://depay.com/products/payments), [源代码](https://github.com/depayfi/widgets)) `MIT` `Nodejs`
- [Family Accounting Tool](https://github.com/nymanjens/facto) - 基于网络的财务管理工具，用于具有部分共享费用的合作伙伴。`Apache-2.0` `Scala`
- [Fava](https://beancount.github.io/fava/) - Fava 是Beancount的网络前端，Beancount是一个基于文本的双重记账系统。([演示](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [源代码](https://github.com/beancount/fava)) `MIT` `Python`
- [Firefly III](https://firefly-iii.org/) - Firefly III 是一个现代的财务管理器。它帮助您跟踪您的资金并进行预算预测。它支持信用卡，具有高级规则引擎，并可以从许多银行导入数据。([演示](https://demo.firefly-iii.org/), [源代码](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP/Docker`
- [FOSSBilling](https://fossbilling.org/) - 免费开源的托管和计费自动化。集成WHM、CWP、cPanel和HestiaCP。完整的API并且易于扩展。([演示](https://fossbilling.org/demo), [源代码](https://github.com/FOSSBilling/FOSSBilling)) `Apache-2.0` `PHP/Docker`
- [Galette](https://galette.eu/) - Galette 是一个针对非营利组织的会员管理网络应用程序。([源代码](https://git.tuxfamily.org/galette/galette.git/)) `GPL-3.0` `PHP`
- [Ghostfolio](https://ghostfol.io/) - 财富管理软件，用于跟踪股票、ETF和加密货币。([源代码](https://github.com/ghostfolio/ghostfolio)) `AGPL-3.0` `Docker/Nodejs`
- [GRR](https://grr.devome.com/?lang=en) - 用于小/中型公司的资产管理和预订。([源代码](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [Hub20](https://hub20.io/) - 一个自托管的以太坊和ERC20代币支付处理器。([源代码](https://gitlab.com/mushroomlabs/hub20/)) `AGPL-3.0` `Docker/Python`
- [HyperSwitch](https://hyperswitch.io/) `None⚠` - HyperSwitch 是一个开源的金融交换系统，使支付变得快速、可靠且价格合理。它允许您连接到多个支付处理器并轻松路由流量，只需一个API集成。([源代码](https://github.com/juspay/hyperswitch)) `Apache-2.0` `Docker/Rust`
- [IHateMoney](https://ihatemoney.org/) - 管理您共享的费用，简单易用。([演示](https://ihatemoney.org/demo/), [源代码](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
- [Invoice Ninja](https://www.invoiceninja.org/) - 强大的在线开具发票的工具。([演示](https://app.invoiceninja.com/invoices/create), [源代码](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP/Docker/K8S`
- [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane) - 管理您小型企业的报价、发票、付款和客户。`MIT` `PHP`
- [InvoiceShelf](https://invoiceshelf.com/) - 一个帮助您跟踪费用、付款并创建专业发票和报价的软件（Crater的分支）。([源代码](https://github.com/InvoiceShelf/InvoiceShelf)) `AGPL-3.0` `PHP/Docker`
- [Kill Bill](https://killbill.io/) - 开源订阅计费和支付平台。访问实时分析和财务报告。([源代码](https://github.com/killbill/killbill)) `Apache-2.0` `Java/Docker`
- [Kresus](https://kresus.org/) - 开源个人财务管理器。([演示](https://kresus.org/en/demo.html), [源代码](https://github.com/kresusapp/kresus)) `MIT` `Nodejs/Docker`
- [Lago](https://www.getlago.com/) - 开源计量和基于使用量的计费。([源代码](https://github.com/getlago/lago)) `AGPL-3.0` `Docker`
- [Maybe](https://maybe.co/) - 一个由小团队和一个不可思议的社区构建的个人财务操作系统。([源代码](https://github.com/maybe-finance/maybe)) `AGPL-3.0` `Docker`
- [OctoBot](https://www.octobot.cloud/) - 开源加密货币交易机器人。([源代码](https://github.com/Drakkar-Software/OctoBot)) `GPL-3.0` `Python/Docker`
- [Ocular](https://github.com/simonwep/ocular) - 一个简洁直观的预算应用程序，用于跨月和年的预算跟踪。([演示](https://ocular.reinisch.io/#demo)) `MIT` `Docker`
- [OpenBudgeteer](https://github.com/TheAxelander/OpenBudgeteer) - 一个基于Bucket预算原则的预算应用程序。`MIT` `Docker/C#`
- [Receipt Wrangler](https://receiptwrangler.io) `None⚠` - 易于使用的收据管理器，由AI驱动。允许用户轻松快速地创建收据、分类等。([演示](https://demo.receiptwrangler.io), [源代码](https://github.com/Receipt-Wrangler/receipt-wrangler-api)) `AGPL-3.0` `Docker`
- [REI3](https://rei3.de/home_en/) - 开源、可扩展的业务管理软件。管理任务、时间、资产等更多内容。([演示](https://rei3.de/demo_en/), [源代码](https://github.com/r3-team/r3)) `MIT` `Go`
- [SolidInvoice](https://solidinvoice.co) - 开源发票和报价应用程序。([源代码](https://github.com/SolidInvoice/SolidInvoice)) `MIT` `PHP`


### 监控

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于[监控](https://en.wikipedia.org/wiki/Monitoring#Computing)系统、网络、应用程序和网站的软件。

**请访问 [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring), [awesome-sysadmin/Metrics and Metric Collection](https://github.com/awesome-foss/awesome-sysadmin#metrics--metric-collection)**



### 笔记与编辑器

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[笔记记录](https://en.wikipedia.org/wiki/Note-taking)编辑器。

_相关：[维基](#wikis)_

- [DailyTxT](https://github.com/PhiTux/DailyTxT) - 加密的日记网络应用程序，用于保存每天的个人记忆。包括搜索功能和加密文件上传。`MIT` `Docker`
- [Dnote](https://www.getdnote.com) - 一个简单的命令行笔记本，具有多设备同步和网络界面。([源代码](https://github.com/dnote/dnote)) `AGPL-3.0` `Go`
- [draw.io](https://draw.io) - 用于制作流程图、过程图、组织结构图、UML、ER和网络图的图表软件。([源代码](https://github.com/jgraph/drawio)) `Apache-2.0` `Javascript/Docker`
- [flatnotes](https://github.com/dullage/flatnotes) - 一个自托管的、无数据库的笔记记录网络应用程序，利用平面文件夹中的Markdown文件进行存储。([演示](https://demo.flatnotes.io)) `MIT` `Docker`
- [HedgeDoc](https://demo.hedgedoc.org/) - 所有平台上的实时协作Markdown笔记，之前称为CodiMD和HackMD CE。([演示](https://demo.hedgedoc.org/), [源代码](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `Docker/Nodejs`
- [Joplin](https://joplinapp.org/) - Joplin 是一个带有Markdown编辑器和加密支持的笔记记录应用程序，适用于移动和桌面平台。在客户端运行并通过自托管的Nextcloud或类似服务同步（Evernote的替代品）。([源代码](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [kiwix-serve](https://www.kiwix.org/en/downloads/kiwix-serve/) - 用于从ZIM文件提供维基的HTTP守护进程。([源代码](https://github.com/kiwix/kiwix-tools)) `GPL-3.0` `C++`
- [Livebook](https://livebook.dev) - 基于Markdown的实时协作笔记本应用程序，支持运行Elixir代码片段、TeX和Mermaid图表。使用Docker或Elixir轻松部署。([源代码](https://github.com/livebook-dev/livebook)) `Apache-2.0` `Elixir/Docker`
- [Meemo](https://meemo.minimal-space.de/) - 支持Markdown的个人笔记流。([源代码](https://github.com/cloudron-io/meemo)) `MIT` `Nodejs`
- [Memos](https://usememos.com/) - 一个开源、自托管的知识库，使用SQLite数据库文件。([源代码](https://github.com/usememos/memos)) `MIT` `Docker/Go`
- [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - notepad.cc的极简克隆。([演示](https://notes.orga.cat/)) `Apache-2.0` `PHP`
- [Note Mark](https://notemark.docs.enchantedcode.co.uk/) - 一个最小的基于网络的Markdown笔记应用程序。([源代码](https://github.com/enchant97/note-mark)) `AGPL-3.0` `Docker`
- [Oddmuse](https://oddmuse.org/) - 一个用Perl编写的简单维基引擎。不需要数据库。([源代码](https://github.com/kensanata/oddmuse)) `GPL-3.0` `Perl`
- [Overleaf](https://www.overleaf.com/) - 基于网络的协作LaTeX编辑器。([源代码](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- [Plainpad](https://alextselegidis.com/get/plainpad/) - 一个用于云的现代笔记记录应用程序，利用渐进式网络应用技术的最佳功能。([演示](https://alextselegidis.com/try/plainpad/), [源代码](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- [SilverBullet](https://silverbullet.md/) - 为具有黑客心态的人优化的笔记记录应用程序。([演示](https://play.silverbullet.md/), [源代码](https://github.com/silverbulletmd/silverbullet), [客户端](https://silverbullet.md/Libraries)) `MIT` `Docker/Deno`
- [Standard Notes](https://docs.standardnotes.com/self-hosting/getting-started) - 简单且私密的笔记应用程序。保护您的隐私，同时完成更多工作。这就是Standard Notes。([演示](https://app.standardnotes.org/), [源代码](https://github.com/standardnotes/app)) `GPL-3.0` `Ruby`
- [Trilium Notes](https://github.com/zadam/trilium) - Trilium Notes 是一个层次化的笔记记录应用程序，专注于构建大型个人知识库。`AGPL-3.0` `Nodejs/Docker/K8S`
- [turndown](https://mixmark-io.github.io/turndown/) - 用Javascript编写的HTML到Markdown转换器。([源代码](https://github.com/mixmark-io/turndown)) `MIT` `Javascript`
- [Turtl](https://turtl.it/) - 完全私密的个人数据库和笔记记录应用程序。([源代码](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- [Writing](https://josephernest.github.io/writing/) - 一个轻量级、无干扰的文本编辑器，支持Markdown和LaTeX。在浏览器中编写时没有滞后。([源代码](https://github.com/josephernest/writing)) `MIT` `Javascript`


### 办公套件

**[`^        返回顶部        ^`](#awesome-selfhosted)**

一个[办公套件](https://en.wikipedia.org/wiki/List_of_office_suites)是一组通常至少包含文字处理器、电子表格和演示程序的生产力软件。

- [Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) 是一个强大的基于LibreOffice的在线办公套件，支持所有主要的文档、电子表格和演示文件格式，您可以将其集成到您自己的基础设施中。([源代码](https://cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.org) - CryptPad 是一个端到端加密和开源的协作套件。它构建用于启用协作，实现文档更改的实时同步。([源代码](https://github.com/cryptpad/cryptpad)) `AGPL-3.0` `Nodejs/Docker`
- [Digislides](https://ladigitale.dev/digislides/) - 以快速简便的方式创建多媒体演示文稿。（文档为法语）。([演示](https://ladigitale.dev/digislides/), [源代码](https://codeberg.org/ladigitale/Digislides)) `AGPL-3.0` `Nodejs/PHP`
- [Etherpad](https://etherpad.org/) - Etherpad 是一个高度可定制的开源在线编辑器，提供真正的实时协作编辑。([演示](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [源代码](https://github.com/ether/etherpad-lite)) `Apache-2.0` `Nodejs/Docker`
- [Grist](https://getgrist.com/) - Grist 是一个下一代电子表格，具有关系结构、基于公式的访问控制和便携、自包含的格式（Airtable的替代品）。([演示](https://docs.getgrist.com), [源代码](https://github.com/gristlabs/grist-core)) `Apache-2.0` `Nodejs/Python/Docker`

- [ONLYOFFICE](https://www.onlyoffice.com/server-opensource.aspx) - 一个办公套件，允许你在同一个地方管理文档、项目、团队和客户关系。([源代码](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs/Docker`
- [PHPOffice](https://github.com/PHPOffice) - PHPOffice 包含多个库，允许你从大多数办公套件中读取和写入文件。`LGPL-3.0` `PHP`


### 密码管理器

**[`^        返回顶部        ^`](#awesome-selfhosted)**

密码管理器允许用户存储、生成和管理他们在本地应用程序和在线服务中的密码。

- [Bitwarden](https://bitwarden.com/) `None⚠` - 带有 Web 应用程序、浏览器扩展和移动应用程序的密码管理器。([源代码](https://github.com/bitwarden/server)) `AGPL-3.0` `Docker/C#`
- [Padloc](https://padloc.app/) - 一个现代的、开源的密码管理器，适用于个人和团队。([源代码](https://github.com/padloc/padloc)) `GPL-3.0` `Nodejs`
- [Passbolt](https://www.passbolt.com/) - 一个专门用于以协作方式管理密码的密码管理器，可以在任何 Web 服务器上使用 MySQL 数据库后端。([源代码](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP/deb/K8S/Docker`
- [PassIt](https://passit.io/) - 带有按组和用户共享功能的简单密码管理器，但没有管理界面。([演示](https://app.passit.io/), [源代码](https://gitlab.com/passit)) `AGPL-3.0` `Docker/Django`
- [Passky](https://passky.org) - 简单、现代且开源的密码管理器，具有网站、浏览器扩展、安卓和桌面应用程序。([演示](https://vault.passky.org), [源代码](https://github.com/Rabbit-Company/Passky-Server)) `GPL-3.0` `PHP`
- [Psono](https://psono.com/) - 一个为团队提供完整功能的有前景的密码管理器。([演示](https://www.psono.pw), [源代码](https://gitlab.com/psono)) `Apache-2.0` `Python`
- [Teampass](https://teampass.net/) - 专门用于以协作方式管理密码的密码管理器。使用一个对称密钥加密所有共享/团队密码，并在服务器端存储在文件和数据库中。适用于任何 Apache、MySQL 和 PHP 服务器。([源代码](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - 用 Rust 编写的轻量级 Bitwarden 服务器 API 实现。`GPL-3.0` `Rust/Docker`


### 粘贴板

**[`^        返回顶部        ^`](#awesome-selfhosted)**

粘贴板是一种用于共享和存储代码和文本的在线内容托管服务。

- [bepasty](https://bepasty-server.readthedocs.io/en/latest/) - 一种适用于所有类型文件的粘贴板。([源代码](https://github.com/bepasty/bepasty-server)) `BSD-2-Clause` `Python/deb`
- [bin](https://github.com/w4/bin) - 一个实际上是极简的粘贴板。`WTFPL/0BSD` `Rust`
- [dpaste](https://dpaste.org/) - 简单的粘贴板，具有多个文本和代码选项，结果短 URL 易于记住。([源代码](https://github.com/DarrenOfficial/dpaste)) `MIT` `Docker/Django`
- [ExBin](https://github.com/m1dnight/exbin) - 带有公共/私人片段和 netcat 服务器的粘贴板。`MIT` `Docker`
- [FlashPaper](https://github.com/AndrewPaglusch/FlashPaper) - 专注于简单性和安全性的一次性加密零知识密码/秘密共享应用程序。不需要数据库或复杂的设置。([演示](https://flashpaper.io)) `MIT` `Docker/PHP`
- [Hemmelig](https://hemmelig.app) - 跨组织或作为私人个人共享加密秘密。([源代码](https://github.com/HemmeligOrg/Hemmelig.app)) `MIT` `Docker/Nodejs`
- [lesma](https://lesma.eu) - 简单友好的浏览器和命令行粘贴应用程序。([演示](https://lesma.eu), [源代码](https://gitlab.com/ogarcia/lesma)) `GPL-3.0` `Rust/Docker`
- [Opengist](https://github.com/thomiceli/opengist) - 基于 Git 的自托管粘贴板。([演示](https://demo.opengist.io)) `AGPL-3.0` `Docker/Go/Nodejs`
- [paaster](https://paaster.io) - Paaster 是一个默认安全的端到端加密粘贴板，旨在简单。([源代码](https://github.com/WardPearce/paaster)) `GPL-3.0` `Docker`
- [Password Pusher](https://pwpush.com) - 一个用于在网络上安全通信密码（或文本）的简单应用程序。密码在一定数量的查看次数和/或时间过后自动过期。([源代码](https://github.com/pglombardo/PasswordPusher)) `GPL-3.0` `Docker/K8S/Ruby`
- [Pastefy](https://pastefy.app/) - 漂亮、简单且易于部署的粘贴板，具有可选的客户端加密、多标签粘贴、API、突出显示的编辑器等更多功能。([源代码](https://github.com/interaapps/pastefy), [客户端](https://github.com/topics/pastefy-addon)) `MIT` `Docker/K8S/Java`
- [PrivateBin](https://privatebin.info/) - PrivateBin 是一个极简的、开源的在线粘贴板/讨论板，其中服务器对托管的数据一无所知。([演示](https://privatebin.net/), [源代码](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [rustypaste](https://github.com/orhun/rustypaste) - 一个最小化的文件上传/粘贴板服务。`MIT` `Rust`
- [SnyPy](https://snypy.com) - 开源的本地代码片段管理器。([演示](https://app.snypy.com), [源代码](https://github.com/snypy)) `MIT` `Docker`
- [Spacebin](https://spaceb.in) - 用 Go 编写的现代粘贴板服务器，带有无 JS 的 Web UI 和大量功能。([演示](https://spaceb.in), [源代码](https://github.com/lukewhrit/spacebin)) `Apache-2.0` `Go/Docker`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - 使用 Hashicorp Vault 作为秘密存储的非常简单的（部署和使用）秘密消息服务。`MIT` `Go`
- [wantguns/bin](https://github.com/wantguns/bin) - 用于文本和二进制文件的极简粘贴板，以单个静态链接的二进制文件形式提供。([演示](https://basedbin.fly.dev)) `GPL-3.0` `Rust/Docker`
- [Wastebin](https://github.com/matze/wastebin) - 使用 SQLite 后端的轻量级、最小化且快速的粘贴板。([演示](https://bin.bloerg.net)) `MIT` `Rust/Docker`
- [YABin](https://github.com/Yureien/YABin) - 一个包含丰富功能但保持简单的粘贴板。支持可选的端到端加密、客户端 CLI 应用程序、语法高亮、极简 UI、API、键盘快捷键等。甚至可以在无服务器环境中运行。([演示](https://bin.sohamsen.me/)) `MIT` `Nodejs/Docker`
- [ybFeed](https://github.com/ybizeul/ybFeed) - 个人微型提要，您可以在其中发布文本或图像片段。`MIT` `Go/Nodejs/Docker`


### 个人仪表板

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于访问信息和应用程序的仪表板。

_相关：[监控](#监控), [书签和链接共享](#书签和链接共享)_

- [Dashy](https://github.com/lissy93/dashy) - 功能丰富的家庭实验室主页，具有简单的 YAML 配置。([演示](https://demo.dashy.to/)) `MIT` `Nodejs/Docker`
- [Fenrus](https://github.com/revenz/fenrus) - 一个自托管的个人主页，允许多个用户、访客访问以及每个用户的多个仪表板。它还具有“智能应用程序”，显示这些应用程序的实时数据。`GPL-3.0` `.NET/Docker`
- [Glance](https://github.com/glanceapp/glance) - 一个高度可定制的仪表板，可以将所有信息源放在一个地方。`AGPL-3.0` `Docker/Go`
- [Heimdall](https://heimdall.site/) - Heimdall 是一个组织所有 Web 应用程序的优雅解决方案。([源代码](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [Hiccup](https://designedbyashw.in/test/hiccup/) - 一个漂亮的静态主页，可以快速访问您的链接和服务。它内置了搜索、编辑、PWA 支持和本地存储缓存，以便轻松组织您的起始页。([源代码](https://github.com/ashwin-pc/hiccup)) `MIT` `Javascript/Docker`
- [Homarr](https://homarr.dev) - 带有多种集成和基于 Web 的配置的时尚、现代仪表板。([演示](https://demo.homarr.dev), [源代码](https://github.com/ajnart/homarr)) `MIT` `Docker/Nodejs`
- [Homepage by gethomepage](https://github.com/gethomepage/homepage) - 高度可定制的首页（或起始页/应用程序仪表板），具有 Docker 和服务 API 集成。`GPL-3.0` `Docker/Nodejs`
- [Homepage by tomershvueli](https://github.com/tomershvueli/homepage) - 一个简单的、独立的、自托管的 PHP 页面，是您访问服务器和网络的窗口。`MIT` `PHP`
- [Homer](https://github.com/bastienwirtz/homer) - 一个极简的静态主页，用于暴露您的服务器服务，具有简单的 yaml 配置和连通性检查。`Apache-2.0` `Docker/K8S/Nodejs`
- [Hubleys](https://github.com/knrdl/hubleys-dashboard) - 自托管的个人仪表板，通过中央 yaml 配置为多个用户组织链接。`MIT` `Docker`
- [Jump](https://github.com/daledavies/jump) - 另一个自托管的服务器起始页，设计简单、时尚、快速和安全。`MIT` `Docker/PHP`
- [LinkStack](https://linkstack.org/) - 轻松链接您的所有社交媒体平台，在一个页面上易于访问，通过直观、易用的用户/管理员界面进行自定义（替代 Linktree 和 Manylink）。([演示](https://linksta.cc/), [源代码](https://github.com/LinkStackOrg/LinkStack)) `AGPL-3.0` `PHP/Docker`
- [LittleLink](https://github.com/sethcottle/littlelink/) - 一个用于生物中的链接的简单方法，带有 100+ 个品牌按钮（替代 Linktree）。([演示](https://littlelink.io/), [源代码](https://github.com/sethcottle/littlelink)) `MIT` `Javascript`
- [Mafl](https://mafl.hywax.space/) - 极简的灵活主页。([源代码](https://github.com/hywax/mafl)) `MIT` `Docker/Nodejs`
- [Organizr](https://github.com/causefx/Organizr) - Organizr 旨在成为您服务器前端的一站式商店。`GPL-3.0` `PHP/Docker`
- [portkey](https://portkey.page) - 一个简单的 Web 门户，可以作为启动页面，并显示一组链接/URL。还支持添加自定义页面。一切都通过一个配置文件完成。([演示](https://demo.portkey.page), [源代码](https://github.com/kodehat/portkey)) `AGPL-3.0` `Go/Docker`
- [ryot](https://github.com/ignisda/ryot) - 用于跟踪生活各个方面的平台 - 媒体、健身等。([演示](https://github.com/IgnisDa/ryot?tab=readme-ov-file#-demo)) `GPL-3.0` `Docker`
- [Starbase 80](https://github.com/notclickable-jordan/starbase-80) - 一个简单的带有 iPad 风格应用程序网格的主页，适用于移动和桌面设备。仅需一个 JSON 配置文件。`MIT` `Docker`
- [Web-Portal](https://github.com/enchant97/web-portal) - 一个 Python Web 应用程序，旨在提供一种轻松的方式来管理您所有 Web 服务的链接。`AGPL-3.0` `Docker/Python`
- [Your Spotify](https://github.com/Yooooomi/your_spotify) `None⚠` - 允许您记录您的 Spotify 听歌活动，并通过 Web 应用程序提供有关这些活动的统计信息。`MIT` `Nodejs/Docker`


### 照片和视频画廊

**[`^        返回顶部        ^`](#awesome-selfhosted)**

画廊是帮助用户发布或共享照片、图片、视频或其他数字媒体的软件。

_相关：[静态站点生成器](#静态站点生成器), [照片和视频画廊](#照片和视频画廊), [内容管理系统（CMS）](#内容管理系统-cms)_

- [Chevereto](https://chevereto.com/) - 终极图像共享软件。在几分钟内创建您自己的个人图像托管网站。([源代码](https://github.com/chevereto/chevereto)) `AGPL-3.0` `PHP/Docker`
- [Coppermine](https://coppermine-gallery.com/) - 多语言照片画廊，与各种公告板集成。包括上传批准和密码保护相册。([演示](https://coppermine-gallery.com/demo/cpg15x/), [源代码](https://github.com/coppermine-gallery/cpg1.6.x)) `GPL-3.0` `PHP`
- [Damselfly](https://damselfly.info) - 针对大型图像集合的快速服务器基础照片管理系统。包括人脸检测、人脸和对象识别、强大的搜索和 EXIF 关键字标记。适用于 Linux、MacOS 和 Windows。([源代码](https://github.com/webreaper/damselfly)) `GPL-3.0` `Docker/C#/.NET`
- [Ente](https://ente.io/) - 一个端到端加密的照片共享平台（替代 Google Photos、Apple Photos）。([源代码](https://github.com/ente-io/ente)) `AGPL-3.0` `Docker/Nodejs/Go`
- [HomeGallery](https://home-gallery.org) - 自托管的开源 Web 画廊，用于浏览个人照片和视频，具有标记、移动友好和 AI 驱动的图像发现功能。([演示](https://demo.home-gallery.org), [源代码](https://github.com/xemle/home-gallery)) `MIT` `Nodejs/Docker`
- [Immich Kiosk](https://github.com/damongolding/immich-kiosk) - 一个使用 Immich 作为数据源的轻量级幻灯片播放器，用于在亭式设备和浏览器上运行。`GPL-3.0` `Docker/Go`
- [Immich](https://immich.app/) - 自托管的照片和视频备份解决方案，直接从您的移动电话备份。([源代码](https://github.com/immich-app/immich)) `AGPL-3.0` `Docker`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) - 自托管的 Google Photos 克隆，略微关注酷None炫的图表。([客户端](https://docs.librephotos.com/docs/user-guide/mobile/)) `MIT` `Python/Docker`
- [Lychee](https://lycheeorg.github.io/) - 开源的基于网格和相册的照片管理系统。([源代码](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP/Docker`
- [Mediagoblin](https://mediagoblin.org) - 任何人都可以运行的免费软件媒体发布平台（替代 Flickr、YouTube、SoundCloud 等）。([源代码](https://git.savannah.gnu.org/cgit/mediagoblin.git/tree/)) `AGPL-3.0` `Python`
- [Mejiro](https://github.com/dmpop/mejiro) - 一个易于使用的 PHP Web 应用程序，用于即时发布照片。`GPL-3.0` `PHP`
- [Nextcloud Memories](https://memories.gallery/) - 快速、现代且高级的照片管理套件。作为 Nextcloud 应用程序运行。([演示](https://demo.memories.gallery/apps/memories/), [源代码](https://github.com/pulsejet/memories)) `AGPL-3.0` `PHP`
- [Photofield](https://github.com/SmilyOrg/photofield) - 实验性的快速照片查看器。`MIT` `Docker/Go`
- [PhotoPrism](https://photoprism.org) - 由 Go 和 Google TensorFlow 驱动的个人照片管理。浏览、组织和分享您的个人照片收藏，使用最新的技术自动标记和查找图片。([演示](https://demo.photoprism.app/library/browse), [源代码](https://github.com/photoprism/photoprism)) `AGPL-3.0` `Go/Docker`
- [Photoview](https://photoview.github.io/) - 一个简单且用户友好的照片画廊，适用于个人服务器。它是为摄影师设计的，旨在提供一种简单而快速的方式来浏览包含数千张高分辨率照片的目录。([源代码](https://github.com/photoview/photoview)) `GPL-3.0` `Go/Docker`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/) - 一个目录优先的照片画廊网站，具有丰富的用户界面，优化用于在低资源服务器上运行。([源代码](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`
- [Piwigo](https://piwigo.org/) - 由活跃的用户和开发者社区构建的网络照片画廊软件。([源代码](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [sigal](https://github.com/saimn/sigal) - 另一个简单的静态画廊生成器。`MIT` `Python`
- [SPIS](https://github.com/gbbirkisson/spis) - 一个简单、轻量且快速的媒体服务器，具有不错的移动支持。`GPL-3.0` `Docker/Rust`
- [This week in past](https://github.com/RouHim/this-week-in-past) - 聚合本周拍摄的照片，从过去的几年中，并以带有简单幻灯片的网页呈现。`MIT` `Docker/Rust`
- [Thumbor](http://thumbor.org/) - 一个智能成像服务，支持按需裁剪、调整大小、应用过滤器和优化图像。([源代码](https://github.com/thumbor/thumbor)) `MIT` `Python/Docker`
- [Zenphoto](https://www.zenphoto.org/) - 开源画廊和 CMS 项目。([源代码](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### 投票和活动

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于组织[投票](https://en.wikipedia.org/wiki/Opinion_poll)和[活动](https://en.wikipedia.org/wiki/Event)的软件。

_相关：[预订和日程安排](#预订和日程安排)_

- [Bitpoll](https://github.com/fsinfuhh/Bitpoll) - 一个用于安排会议和一般投票的 Web 应用程序。([演示](https://bitpoll.de/)) `GPL-3.0` `Docker/Python`
- [Bracket](https://evroon.github.io/bracket) - 灵活的锦标赛系统，用于构建锦标赛设置、添加团队、安排比赛、跟踪得分并向公众实时展示排名。([演示](https://www.bracketapp.nl/demo), [源代码](https://github.com/evroon/bracket)) `AGPL-3.0` `Docker/Nodejs`
- [Christmas Community](https://github.com/Wingysam/Christmas-Community) - 为您的整个家庭创建一个简单的地方，用于查找人们想要的礼物，并避免重复送礼。`AGPL-3.0` `Docker/Nodejs`
- [Claper](https://claper.co/) - 与您的观众互动的终极工具（替代 Slido、AhaSlides 和 Mentimeter）。([源代码](https://github.com/ClaperCo/Claper)) `GPL-3.0` `Elixir/Docker`
- [ClearFlask](https://clearflask.com) - 用于管理传入反None馈和优先级公开路线图的社区反None馈工具（替代 Canny、UserVoice、Upvoty）。([演示](https://product.clearflask.com), [源代码](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
- [docassemble](https://docassemble.org/) - 一个基于 Python、YAML 和 Markdown 的免费开源专家系统，用于指导访谈和文档组装。([演示](https://demo.docassemble.org/run/legal), [源代码](https://github.com/jhpyle/docassemble)) `MIT` `Docker/Python`
- [Fider](https://fider.io) - 用于收集和优先级反None馈的开放平台（替代 UserVoice）。([演示](https://demo.fider.io), [源代码](https://github.com/getfider/fider)) `MIT` `Docker`
- [Formbricks](https://formbricks.com) - 基于全球最大的开源调查堆栈构建的体验管理套件。在客户旅程的每一步优雅地收集反None馈，以了解您的客户需要什么。([演示](https://app.formbricks.com), [源代码](https://github.com/formbricks/formbricks)) `AGPL-3.0` `Nodejs/Docker`
- [Framadate](https://framadate.org/abc/) - 在线服务，用于计划约会或快速轻松地做出决定：创建投票，定义要选择的日期或主题，向您的朋友或同事发送投票链接，讨论并做出决定。([演示](https://framadate.org/aqg259dth55iuhwm), [源代码](https://framagit.org/framasoft/framadate?)) `CECILL-B` `PHP`
- [Gancio](https://gancio.org/) - 一个共享的本地社区日程表。([源代码](https://framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- [gathio](https://gath.io/) - 自我销毁的、可共享的、无需注册的事件页面。([演示](https://gath.io/), [源代码](https://github.com/lowercasename/gathio)) `GPL-3.0` `Nodejs/Docker`
- [HeyForm](https://heyform.net) - 允许任何人为调查、问卷、测验和投票创建引人入胜的对话式表格的表格构建器。([源代码](https://github.com/heyform/heyform)) `AGPL-3.0` `Docker`
- [hitobito](https://hitobito.com) - 一个 Web 应用程序，用于管理具有成员、事件等复杂群组层次结构。([演示](https://demo.hitobito.com/en/users/sign_in), [源代码](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- [Input](https://getinput.co) - 一个专注于简洁性和品牌一致性的隐私优先、无代码、开源表格构建器。([源代码](https://github.com/deck9/input)) `AGPL-3.0` `PHP/Nodejs/Docker`
- [LimeSurvey](https://www.limesurvey.org) - 功能丰富的开源基于 Web 的投票软件。支持广泛的调查逻辑。([演示](https://demo.limesurvey.org), [源代码](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Meetable](https://events.indieweb.org) - 一个最小的活动聚合器。([源代码](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- [Mobilizon](https://mobilizon.org) - 一个联邦工具，帮助您查找、创建和组织事件和团体。([演示](https://demo.mobilizon.org/), [源代码](https://framagit.org/framasoft/mobilizon/)) `GPL-3.0` `Elixir/Docker`
- [Open Event Server](https://github.com/fossasia/open-event-server) - 启用组织者管理从音乐会到会议和聚会的各种活动。`GPL-3.0` `Python/Docker`
- [OpnForm](https://opnform.com) - 美丽的开源表格构建器。([演示](https://opnform.com/forms/create/guest), [源代码](https://github.com/JhumanJ/opnform)) `AGPL-3.0` `PHP/Nodejs/Docker`


### 代理

**[`^        返回顶部        ^`](#awesome-selfhosted)**

代理是一种作为客户端请求资源和提供该资源的服务器之间的中介的服务器应用程序。本节关于前向（即传出）代理。有关反向代理，请参阅 Web 服务器部分。

_相关：[Web 服务器](#web-服务器)_

- [imgproxy](https://imgproxy.net/) - 用于调整大小和转换远程图像的快速且安全的独立服务器。当您需要在不准备大量缓存的调整大小图像或每次设计更改时重新调整大小的情况下，调整多个图像时，效果很好。([源代码](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker/K8S`
- [iodine](https://code.kryo.se/iodine/) - IPv4 通过 DNS None隧道解决方案，启用您启动 socks5 代理监听器。([源代码](https://github.com/yarrick/iodine)) `ISC` `C/deb`
- [Koblas](https://github.com/ynuwenhof/koblas) - 轻量级 SOCKS5 代理服务器。`MIT` `Rust/Docker`
- [Outline Server](https://getoutline.org/) - 一个运行每个访问密钥的 Shadowsocks 实例和用于管理访问密钥的 REST API 的代理服务器。([源代码](https://github.com/Jigsaw-Code/outline-server)) `Apache-2.0` `Docker/Nodejs`
- [Privoxy](https://www.privoxy.org) - 具有高级过滤功能的非缓存 Web 代理，用于增强隐私、修改 Web 页面数据和 HTTP 头、控制访问以及删除广告和其他不必要的 Internet None垃None圾。([源代码](https://www.privoxy.org/gitweb/?p=privoxy.git;a=summary)) `GPL-2.0` `Cdeb`
- [sish](https://github.com/antoniomika/sish) - 使用仅SSH将HTTP(S)/WS(S)/TCPNone隧道到localhost（serveo/ngrok替代方案）。`MIT` `Go/Docker`
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - 内置身份验证的SOCKS5代理服务器，以及用于用户管理和用户数据统计的Telegram-bot（在按GB支付数据费用时非常方便）。它是容器化的且易于安装。`Apache-2.0` `Docker`
- [Squid](http://www.squid-cache.org/) - 支持HTTP、HTTPS、FTP等的Web缓存代理。它通过缓存和重用频繁请求的网页来减少带宽并提高响应时间。([源代码](https://code.launchpad.net/squid)) `GPL-2.0` `C/deb`
- [Tinyproxy](https://tinyproxy.github.io/) - 轻量级的HTTP/HTTPS代理守护进程。([源代码](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C/deb`
- [txtdot](https://txtdot.github.io/documentation/) - 仅解析页面中文本、链接和图片的HTTP代理，以减少互联网带宽使用量，去除广告和重型脚本。([演示](https://txt.dc09.ru), [源代码](https://github.com/TxtDot/txtdot)) `MIT` `Nodejs/Docker`


### 食谱管理

**[`^        返回顶部        ^`](#awesome-selfhosted)**

管理[食谱](https://en.wikipedia.org/wiki/Recipe)的软件和工具。

- [Bar Assistant](https://barassistant.app/) - 酒吧助手是一个自托管的应用程序，用于管理你的家庭酒吧。它允许你添加你的配料，搜索鸡尾酒和创建自定义鸡尾酒食谱。([演示](https://demo.barassistant.app/), [源代码](https://github.com/karlomikus/bar-assistant)) `MIT` `PHP/Docker`
- [KitchenOwl](https://tombursch.github.io/kitchenowl/) - 跨平台的购物清单、食谱存储、费用跟踪和餐饮计划者，遵循材料设计语言。([源代码](https://github.com/TomBursch/kitchenowl)) `AGPL-3.0` `Docker/deb`
- [Mealie](https://nightly.mealie.io/) - 受材料设计启发的食谱管理器，具有类别和标签管理、购物清单、餐饮计划器和网站自定义功能。Mealie专注于简单的用户交互，以保持全家人都使用该应用程序。([源代码](https://github.com/mealie-recipes/mealie)) `MIT` `Python`
- [RecipeSage](https://github.com/julianpoy/recipesage) - 食谱管理器、餐饮计划组织者和购物清单管理器，可以直接从任何URL导入食谱。([演示](https://recipesage.com)) `AGPL-3.0` `Nodejs`
- [Recipya](https://recipes.musicavis.ca) - 一个干净、简单而强大的食谱管理器，全家人都会喜欢。([演示](https://recipes.musicavis.ca/guide/login), [源代码](https://github.com/reaper47/recipya)) `GPL-3.0` `Docker/Go`
- [Specifically Clementines](https://davideshay.github.io/groceries/) - 杂货购物应用（以前的Groceries），提供可靠的多用户/设备同步（Web/Android/iOS）、食谱和与Tandoor的集成。([演示](https://www.specificallyclementines.com/), [源代码](https://github.com/davideshay/groceries)) `MIT` `Docker`
- [Tamari](https://tamariapp.com) - 带有内置食谱集合的食谱管理Web应用程序。按喜好和类别组织，创建购物清单和计划餐饮。([演示](https://app.tamariapp.com), [源代码](https://github.com/alexbates/Tamari)) `GPL-3.0` `Docker/Python`


### 远程访问

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[远程桌面](https://en.wikipedia.org/wiki/Remote_desktop_software)和[SSH](https://en.wikipedia.org/wiki/Secure_Shell)服务器以及用于远程管理计算机系统的Web界面。

- [Firezone](https://www.firezone.dev/) - 自托管的安全远程访问网关，支持WireGuard协议。它提供Web GUI、一行安装脚本、多因素认证（MFA）和单点登录（SSO）。([源代码](https://github.com/firezone/firezone)) `Apache-2.0` `Elixir/Docker`
- [Guacamole](https://guacamole.apache.org) - Guacamole是一个无客户端的远程桌面网关。它支持标准协议如VNC和RDP。([源代码](https://github.com/apache/guacamole-server)) `Apache-2.0` `Java/C`
- [MeshCentral](https://meshcentral.com/) - 一个全面的计算机管理网站。使用MeshCentral，你可以运行自己的Web服务器来远程管理和控制本地网络或互联网上的计算机。([源代码](https://github.com/Ylianst/MeshCentral)) `Apache-2.0` `Nodejs`
- [Remotely](https://github.com/immense/Remotely) - 远程桌面控制和远程脚本解决方案，企业级远程支持解决方案，具有管理员Web界面和通过浏览器进行远程控制。`GPL-3.0` `C#/Docker`
- [RustDesk](https://rustdesk.com/) - 远程桌面访问软件，可以开箱即用（TeamViewer的替代品）。([源代码](https://github.com/rustdesk/rustdesk-server)) `AGPL-3.0` `Rust/Docker/deb`
- [ShellHub](https://www.shellhub.io) - ShellHub是一个现代化的SSH服务器，用于通过命令行（使用任何SSH客户端）或基于Web的用户界面远程访问Linux设备，设计为sshd的替代品。([源代码](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Docker`
- [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty是一个为Web设计的SSH和Telnet连接器。([演示](https://sshwifty-demo.nirui.org)) `AGPL-3.0` `Go/Docker`
- [Warpgate](https://github.com/warp-tech/warpgate) - 智能SSH和HTTPS堡None垒，可以与任何SSH客户端一起工作。`Apache-2.0` `Rust/Docker`


### 资源规划

**[`^        返回顶部        ^`](#awesome-selfhosted)**

帮助进行[资源和供应规划](https://en.wikipedia.org/wiki/Resource_planning)的软件和工具，包括[企业资源和供应规划（ERP）](https://en.wikipedia.org/wiki/Enterprise_resource_planning)。

_相关：[金钱、预算与管理](#money-budgeting--management), [库存管理](#inventory-management)_

- [Dolibarr](https://www.dolibarr.org/) - Dolibarr ERP CRM是一个现代软件包，用于管理你的公司或基金会的活动（联系人、供应商、发票、订单、库存、日程、会计等）。([演示](https://www.dolibarr.org/onlinedemo.php), [源代码](https://github.com/Dolibarr/dolibarr)) `GPL-3.0` `PHP/deb`
- [ERPNext](https://erpnext.com) - 免费开源的ERP系统。([源代码](https://github.com/frappe/erpnext)) `GPL-3.0` `Python/Docker`
- [farmOS](https://farmos.org/) - 基于Web的农场记录保持应用程序。([演示](https://farmos-demo.rootedsolutions.io/), [源代码](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP/Docker`
- [grocy](https://grocy.info/) - 超越冰箱的ERP - grocy是一个基于Web的自托管的杂货和家庭管理解决方案，用于你的家庭。([演示](https://en.demo.grocy.info/), [源代码](https://github.com/grocy/grocy)) `MIT` `PHP/Docker`
- [LedgerSMB](https://ledgersmb.org/) - 集成的会计和ERP系统，适用于小型和中型企业，具有双重记录会计、预算、发票、报价、项目、订单和库存管理、运输等功能。([演示](https://demo.cloud.efficito.com/erp/1.5/login.pl), [源代码](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Docker/Perl`
- [Odoo](https://www.odoo.com) - 免费开源的ERP系统。([演示](https://demo.odoo.com/), [源代码](https://github.com/odoo/odoo)) `LGPL-3.0` `Python/deb/Docker`
- [OFBiz](https://ofbiz.apache.org/) - 企业资源规划系统，具有跨任何行业使用的业务应用程序套件。([源代码](https://svn.apache.org/viewvc/ofbiz/)) `Apache-2.0` `Java`
- [Tryton](https://www.tryton.org/) - 免费开源的商业解决方案。([演示](https://www.tryton.org/demo), [源代码](https://foss.heptapod.net/tryton/tryton)) `GPL-3.0` `Python`


### 搜索引擎

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[搜索引擎](https://en.wikipedia.org/wiki/Search_engine_(computing))是一种[信息检索系统](https://en.wikipedia.org/wiki/Information_retrieval)，旨在帮助查找存储在计算机系统上的信息。这包括[Web搜索引擎](https://en.wikipedia.org/wiki/Web_search_engine)。

- [Apache Solr](https://lucene.apache.org/solr/) - 企业搜索平台，具有全文搜索、命中高亮、分面搜索、实时索引、动态聚类和丰富文档（如Word、PDF）处理功能。([源代码](https://github.com/apache/solr)) `Apache-2.0` `Java/Docker/K8S`
- [Fess](https://fess.codelibs.org/) - Fess是一个非常强大且易于部署的企业搜索服务器。([演示](https://search.n2sm.co.jp/), [源代码](https://github.com/codelibs/fess)) `Apache-2.0` `Java/Docker`
- [Jina](https://github.com/jina-ai/jina/) - 云原生的神经搜索框架，适用于任何类型的数据。`Apache-2.0` `Python/Docker`
- [Manticore Search](https://github.com/manticoresoftware/manticoresearch/) - 全文搜索和数据分析，适用于小、中、大数据的快速响应时间（Elasticsearch的替代品）。`GPL-2.0` `Docker/deb/C++`
- [MeiliSearch](https://www.meilisearch.com) - 超相关、即时且容错的全文搜索API。([源代码](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust/Docker/deb`
- [OpenSearch](https://opensearch.org) - 开源的分布式和RESTful搜索引擎。([源代码](https://github.com/opensearch-project/OpenSearch)) `Apache-2.0` `Java/Docker/K8S/deb`
- [SearXNG](https://docs.searxng.org/) `None⚠` - 聚合来自各种搜索服务和数据库的结果的互联网元搜索引擎（Searx的分支）。([源代码](https://github.com/searxng/searxng/)) `AGPL-3.0` `Python/Docker`
- [sist2](https://github.com/simon987/sist2) - 闪电般快速的文件系统索引器和搜索工具。`GPL-3.0` `C/Docker`
- [Sosse](https://sosse.readthedocs.io/en/stable/) - 基于Selenium的搜索引擎和爬虫，具有离线归档功能。([源代码](https://gitlab.com/biolds1/sosse)) `AGPL-3.0` `Python/Docker`
- [Typesense](https://typesense.org) - 开发者友好且易于使用的超快速、容错的开源搜索引擎。([源代码](https://github.com/typesense/typesense)) `GPL-3.0` `C++/Docker/K8S/deb`
- [Websurfx](https://github.com/neon-mmd/websurfx) `None⚠` - 聚合来自其他搜索引擎的结果（元搜索引擎），没有广告，同时保持隐私和安全。它速度极快并提供高度的自定义（SearX的替代品）。`AGPL-3.0` `Rust/Docker`
- [Whoogle](https://github.com/benbusby/whoogle-search) `None⚠` - 自托管的、无广告的、尊重隐私的元搜索引擎。`MIT` `Python`
- [Yacy](https://yacy.net/en/index.html) - 基于对等的、去中心化的搜索引擎服务器。([源代码](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java/Docker/K8S`
- [ZincSearch](https://zincsearch.com) - 需要最少资源的搜索引擎（Elasticsearch的替代品）。([演示](https://github.com/zinclabs/zinc#playground-server), [源代码](https://github.com/zincsearch/zincsearch)) `Apache-2.0` `Go/Docker/K8S`


### 自托管解决方案

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于轻松安装、管理和配置自托管服务和应用程序的软件。

- [Ansible-NAS](https://github.com/DaveStephens/ansible-nas) - 使用此剧本和Ubuntu盒子构建一个功能齐全的家庭服务器。`MIT` `Ansible/Docker`
- [CasaOS](https://www.casaos.io/) - 一个简单、易用、优雅的开源家庭云系统。([源代码](https://github.com/IceWhaleTech/CasaOS)) `Apache-2.0` `Go/Docker`
- [DietPi](https://dietpi.com/) - 优化用于单板计算机的最小Debian操作系统，允许你轻松安装和管理多个自托管服务。([源代码](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer帮助你在Docker中运行家庭服务器应用程序。([源代码](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [FreedomBox](https://freedombox.org/) - 社区项目，开发、设计和推广用于私人、个人通信的运行免费软件的个人服务器。([源代码](https://salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/deb`
- [HomelabOS](https://homelabos.com) - 你自己的离线优先、隐私中心、开源数据中心。使用几条命令部署超过100个服务。([源代码](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- [LibreServer](https://libreserver.org/) - 基于Debian的家庭服务器配置。([源代码](https://github.com/bashrc2/libreserver)) `AGPL-3.0` `Shell`
- [Mars Server](https://github.com/borjapazr/mars-server) - 使用Docker、Docker Compose、Make和Bash管理的家庭服务器。`MIT` `Docker`
- [Mistborn](https://gitlab.com/cyber5k/mistborn) - Mistborn是你自己的虚拟私有云平台和WebUI，用于管理自托管服务。`MIT` `Shell/Docker`
- [NextCloudPi](https://github.com/nextcloud/nextcloudpi) - 预安装和预配置的Nextcloud，带有文本和Web管理界面以及自托管私人数据所需的所有工具。提供Raspberry Pi、Odroid、Rock64、Docker和Armbian/Debian的安装镜像。`GPL-2.0` `Shell/PHP`
- [OpenMediaVault](https://www.openmediavault.org/) - OpenMediaVault是基于Debian Linux的下一代网络附加存储（NAS）解决方案。它包含SSH、(S)FTP、SMB/CIFS、DAAP媒体服务器、RSync、BitTorrent客户端等服务。([源代码](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Sandstorm](https://sandstorm.io/) - 用于轻松且安全运行自托管应用程序的个人服务器。([演示](https://demo.sandstorm.io/), [源代码](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Shell`
- [StartOS](https://start9.com) - 基于浏览器的图形操作系统（OS），使运行个人服务器像运行个人计算机一样简单。([源代码](https://github.com/Start9Labs/start-os)) `MIT` `Rust`
- [Syncloud](https://syncloud.org/) - 你自己的在线文件存储、社交网络或电子邮件服务器。([源代码](https://github.com/syncloud/platform)) `GPL-3.0` `Go/Shell`
- [Tipi](https://runtipi.io/) - 家庭服务器管理器。一条命令设置，点击安装你喜欢的自托管应用程序。([源代码](https://github.com/meienberger/runtipi)) `GPL-3.0` `Shell`
- [UBOS](https://ubos.net/) - 在个人服务器和物联网设备上运行的Linux发行版。单命令安装和管理应用程序 - Jenkins、Mediawiki、Owncloud、WordPress等，以及其他功能。`GPL-3.0` `Perl`
- [WikiSuite](https://wikisuite.org) - 最全面的集成的免费/自由/开源企业软件套件。([源代码](https://wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `Shell/Perl/deb`
- [xsrv](https://xsrv.readthedocs.io/) - 在你自己的服务器上安装和管理自托管服务/应用程序。([源代码](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Ansible/Shell`
- [YunoHost](https://yunohost.org/) - 旨在使自托管对每个人都可访问的服务器操作系统。([演示](https://yunohost.org/#/try), [源代码](https://github.com/YunoHost)) `AGPL-3.0` `Python/Shell`


### 软件开发

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[软件开发](https://en.wikipedia.org/wiki/Software_development)是设计、编程、文档编写、测试和修复涉及创建和维护应用程序、框架或其他软件组件的过程。

请访问[软件开发 - API管理](#软件开发---api管理), [软件开发 - 持续集成与部署](#软件开发---持续集成--部署), [软件开发 - FaaS与无服务器](#软件开发---faas--serverless), [软件开发 - IDE与工具](#软件开发---ide--工具), [软件开发 - 本地化](#软件开发---本地化), [软件开发 - 低代码](#软件开发---低代码), [软件开发 - 项目管理](#软件开发---项目管理), [软件开发 - 测试](#软件开发---测试)。



### 软件开发 - API管理

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[API管理](https://en.wikipedia.org/wiki/API_management)是创建和发布[应用程序编程接口（API）](https://en.wikipedia.org/wiki/API)、执行其使用策略、控制访问、培养订阅者社区、收集和分析使用统计数据以及报告性能的过程。

- [DreamFactory](https://www.dreamfactory.com/) - 将任何SQL/NoSQL/结构化数据转换为Restful API。([源代码](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP/Docker/K8S`
- [form.io](https://form.io) - 一个REST API构建平台，利用拖放式表单构建器，适用于任何应用程序框架。包含开源和企业版本。([演示](https://portal.form.io), [源代码](https://github.com/formio)) `MIT` `Nodejs/Docker`
- [Fusio](https://www.fusio-project.org/) - 开源的API管理平台，帮助构建和管理REST API。([演示](https://fusio-project.org/demo), [源代码](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP/Docker`
- [Graphweaver](https://graphweaver.com/) - 将多个数据源转换为单个GraphQL API。([源代码](https://github.com/exogee-technology/graphweaver)) `MIT` `Nodejs`
- [Hasura](https://hasura.io) - 在Postgres上构建快速、即时的实时GraphQL API，具有细粒度的访问控制，还可以在数据库事件上触发Webhooks。([源代码](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell/Docker/K8S`
- [Hoppscotch Community Edition](https://hoppscotch.io) - 一个免费、快速且美观的API请求构建器。([源代码](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Docker`
- [Kong](https://konghq.com/kong/) - 世界上最受欢迎的开源微服务API网关和平台。([源代码](https://github.com/Kong/kong)) `Apache-2.0` `Lua/Docker/K8S/deb`
- [Lura](https://luraproject.org/) - 开源高性能API网关。([源代码](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- [Panora](https://panora.dev) `None⚠` - 在几分钟内将集成目录添加到你的SaaS产品中的通用API（Merge.dev的替代品）。([源代码](https://github.com/panoratech/Panora)) `AGPL-3.0` `Nodejs/Docker`
- [Para](https://paraio.org) - 灵活且模块化的后端框架/服务器，用于对象持久化、API开发和身份验证。([源代码](https://github.com/erudika/para)) `Apache-2.0` `Java/Docker`
- [Psychic](https://github.com/psychic-api/psychic) - 将大型语言模型连接到动态数据源的通用API。`GPL-3.0` `Python`
- [Svix](https://svix.com) - 开源的Webhooks即服务，使API提供商可以轻松发送Webhooks。([源代码](https://github.com/svix/svix-webhooks)) `MIT` `Docker/Rust`
- [Tyk](https://tyk.io) - 快速且可扩展的开源API网关。Tyk提供了一个API管理平台，包括API网关、API分析、开发者门户和API管理仪表板。([源代码](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go/Docker/K8S`
- [Yaade](https://docs.yaade.io/) - Yaade是一个开源的、自托管的、协作的API开发环境。([源代码](https://github.com/EsperoTech/yaade)) `MIT` `Docker`


### 软件开发 - 持续集成与部署

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[持续集成](https://en.wikipedia.org/wiki/Continuous_integration)和[持续部署](https://en.wikipedia.org/wiki/Continuous_deployment)软件和工具。

请访问[awesome-sysadmin/持续集成与持续部署](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)。

_相关：[自动化](#automation)_



### 软件开发 - FaaS与无服务器

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[无服务器计算](https://en.wikipedia.org/wiki/Serverless_computing)、[函数即服务（FaaS）](https://en.wikipedia.org/wiki/Function_as_a_service)和[平台即服务（Paas）](https://en.wikipedia.org/wiki/Platform_as_a_service)管理软件。

请访问[awesome-sysadmin/PaaS](https://github.com/awesome-foss/awesome-sysadmin#paas)。



### 软件开发 - IDE与工具

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[集成开发环境（IDE）](https://en.wikipedia.org/wiki/Integrated_development_environment)是一种为计算机程序员提供全面软件开发设施的软件应用程序。

_相关：[软件开发 - 低代码](#软件开发---低代码)_

- [Atheos](https://www.atheos.io) - 基于Web的IDE框架，具有小足迹和最低要求，继续自Codiad。([源代码](https://github.com/Atheos/Atheos)) `MIT` `PHP/Docker`
- [code-server](https://github.com/coder/code-server) - 在浏览器中运行的VS Code，托管在远程服务器上。`MIT` `Nodejs/Docker`
- [Coder](https://coder.com/) - 在你自己的基础设施上运行远程开发机器。([源代码](https://github.com/coder/coder)) `AGPL-3.0` `Go/Docker/K8S/deb`
- [Eclipse Che](https://www.eclipse.org/che/) - 开源工作空间服务器和云IDE。([源代码](https://github.com/eclipse/che)) `EPL-1.0` `Docker/Java`
- [Hakatime](https://github.com/mujx/hakatime) - WakaTime服务器实现，带有分析仪表板。`Unlicense` `Haskell`
- [HttPlaceholder](https://github.com/dukeofharen/httplaceholder) - 使用HttPlaceholder快速模拟任何Web服务。HNone

[31]
1 分钟
stream_completion(prompt = prefix + spilde_text_list[4])
ttPlaceholder 允许您指定请求应呈现的外观以及需要返回的响应。`MIT` `C#`

- [Judge0 CE](https://judge0.com) - 开源 API，用于编译和运行源代码。([源代码](https://github.com/judge0/judge0)) `GPL-3.0` `Docker`
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - 基于 Web 的交互式和可重现计算环境。([演示](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [源代码](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`
- [Langfuse](https://langfuse.com) - LLM 工程平台，用于模型追踪、提示管理和应用程序评估。Langfuse 帮助团队协作调试、分析和迭代他们的 LLM 应用程序，例如聊天机器人或 AI 代理。([演示](https://langfuse.com/docs/demo), [源代码](https://github.com/langfuse/langfuse), [客户端](https://langfuse.com/docs/integrations/overview)) `MIT` `Docker`
- [Lowdefy](https://www.lowdefy.com/) - 在几分钟内使用 YAML/JSON 在自托管的开源平台上构建内部工具、BI 仪表板、管理面板、CRUD 应用程序和工作流程。连接到您的数据源，通过 Serverless、Netlify 或 Docker 托管。([源代码](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Nodejs/Docker`
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - 基于 Web 浏览器的 R 语言 IDE。([源代码](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`
- [Wakapi](https://wakapi.dev/) - 用于编码统计的跟踪工具，与 WakaTime 兼容。([源代码](https://github.com/muety/wakapi)) `GPL-3.0` `Go/Docker`


### 软件开发 - 本地化

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[本地化](https://en.wikipedia.org/wiki/Internationalization_and_localization) 是将代码和软件适应其他语言的过程。

- [Accent](https://www.accent.reviews/) - 开源、自托管、面向开发者的翻译工具。([源代码](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir/Docker`
- [Tolgee](https://tolgee.io) - 开发者和翻译者友好的基于 Web 的本地化平台，使用户能够直接在他们开发的应用程序中进行翻译。([源代码](https://github.com/tolgee/tolgee-platform)) `Apache-2.0` `Docker/Java`
- [Traduora](https://traduora.co) - 团队用的翻译管理平台。([源代码](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/K8S/Nodejs`
- [Weblate](https://weblate.org) - 具有紧密版本控制集成的基于 Web 的翻译工具。([演示](https://demo.weblate.org), [源代码](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python/Docker/K8S`


### 软件开发 - 低代码

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[低代码](https://en.wikipedia.org/wiki/Low-code_development_platform) 开发平台（LCDP）提供了一个用于通过图形用户界面创建应用程序软件的开发环境。

相关：[软件开发 - IDE & 工具](#软件开发---ide--工具)

- [Appsmith](https://www.appsmith.com/) - 云端或自托管的开源平台，用于构建管理面板、CRUD 应用程序和工作流程。构建您需要的一切，速度提高 10 倍。([源代码](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker/K8S`
- [Appwrite](https://appwrite.io) - 适用于 Web、本地和移动开发者的端到端后端服务器 🚀。([源代码](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `Docker`
- [Dashpress](https://github.com/dashpresshq/dashpress) - 通过单个命令，从数据库信息中在几秒钟内生成功能齐全的管理应用程序。([演示](https://demo.dashpress.io/auth)) `AGPL-3.0` `Nodejs/Docker`
- [Manifest](https://manifest.build) - 一个适合 1 个 YAML 文件的后端。([演示](https://manifest.new), [源代码](https://github.com/mnfst/manifest)) `MIT` `Nodejs`
- [Motor Admin](https://www.getmotoradmin.com/) - 无代码管理面板和商业智能软件 - 搜索、创建、更新和删除数据条目，创建自定义操作并构建报告。([源代码](https://github.com/motor-admin/motor-admin)) `AGPL-3.0` `Ruby/Docker`
- [PocketBase](https://pocketbase.io/) - 用于您的下一个 SaaS 和移动应用程序的后端，仅需 1 个文件。([源代码](https://github.com/pocketbase/pocketbase)) `MIT` `Go/Docker`
- [SQLPage](https://sql-page.com) - 仅使用 SQL 的动态网站构建器。([源代码](https://github.com/sqlpage/SQLPage)) `MIT` `Rust/Docker`
- [ToolJet](https://tooljet.io/) - 低代码框架，用于以最小的工程工作量构建和部署内部工具（替代 Retool 和 Mendix）。([源代码](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Nodejs/Docker/K8S`


### 软件开发 - 项目管理

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于[软件项目管理](https://en.wikipedia.org/wiki/Software_project_management)的工具和软件。

相关：[售票](#售票), [任务管理和待办事项列表](#任务管理和待办事项列表)

- [Cgit](https://git.zx2c4.com/cgit/about/) - Git 仓库的快速轻量级 Web 界面。([源代码](https://git.zx2c4.com/cgit/tree/)) `GPL-2.0` `C`
- [Forgejo](https://forgejo.org) - 专注于扩展、联合和隐私的轻量级软件None铸造（Gitea 的分支）。([演示](https://next.forgejo.org), [源代码](https://codeberg.org/forgejo/forgejo/), [客户端](https://codeberg.org/forgejo-contrib/delightful-forgejo)) `MIT` `Docker/Go`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 分布式版本控制系统，具有 wiki 和错误跟踪功能。`BSD-2-Clause-FreeBSD` `C`
- [Gerrit](https://www.gerritcodereview.com/) - 用于基于 Git 的项目的代码审查和项目管理工具。([源代码](https://github.com/GerritCodeReview/gerrit)) `Apache-2.0` `Java/Docker`
- [Gitblit](https://www.gitblit.com/) - 用于管理、查看和服务 Git 仓库的纯 Java 堆栈。([源代码](https://github.com/gitblit-org/gitblit)) `Apache-2.0` `Java`
- [gitbucket](https://gitbucket.github.io/gitbucket-news/) - 易于安装的由 Scala 驱动的 GitHub 克隆。([源代码](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.com) - 自带一杯茶的 Git！无痛的自托管全功能软件开发服务，包括 Git 托管、代码审查、团队协作、包注册和 CI/CD。([演示](https://demo.gitea.com), [源代码](https://github.com/go-gitea/gitea)) `MIT` `Go/Docker/K8S`
- [GitLab](https://about.gitlab.com) - 自托管的 Git 仓库管理、代码审查、问题跟踪、活动提要和维基。([演示](https://gitlab.com/), [源代码](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby/deb/Docker/K8S`
- [Gitolite](https://gitolite.com/gitolite/index.html) - Gitolite 允许您在中央服务器上设置 Git 托管，具有细粒度的访问控制和更多强大功能。([源代码](https://github.com/sitaramc/gitolite)) `GPL-2.0` `Perl`
- [Gogs](https://gogs.io/) - 用 Go 编写的无痛自托管 Git 服务。([源代码](https://github.com/gogs/gogs)) `MIT` `Go`
- [Huly](https://huly.io) - 一个全功能的项目管理平台（替代 Linear、Jira、Slack、Notion、Motion）。([演示](https://app.huly.io), [源代码](https://github.com/hcengineering/platform)) `EPL-2.0` `Docker/K8S/Nodejs`
- [Kallithea](https://kallithea-scm.org/) - 支持两个领先的版本控制系统 Mercurial 和 Git 的源代码管理系统，带有 Web 界面。([源代码](https://kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
- [Klaus](https://github.com/jonashaag/klaus) - 简单易设置的 Git Web 查看器，只需工作即可。`ISC` `Python/Docker`
- [Leantime](https://leantime.io) - Leantime 是一个面向小团队和初创企业的精益项目管理系统，帮助管理项目从构思到交付的整个过程。([源代码](https://github.com/leantime/leantime)) `GPL-2.0` `PHP/Docker`
- [Mindwendel](https://www.mindwendel.com/) - 在您的团队中头脑风暴并为想法和想法投票。([演示](https://www.mindwendel.com), [源代码](https://github.com/b310-digital/mindwendel)) `AGPL-3.0` `Docker/Elixir`
- [minimal-git-server](https://github.com/mcarbonne/minimal-git-server) - 一个轻量级和最小化的自托管 Git 服务器，具有基本的 CLI 来管理仓库，支持多个账户并在容器中运行。`MIT` `Docker`
- [Octobox](https://octobox.io/) `None⚠` - 重新控制您的 GitHub 通知。([源代码](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby/Docker`
- [OneDev](https://onedev.io/) - 一个全功能的 DevOps 平台。具有 Git 管理、问题跟踪和 CI/CD。简单而强大。([源代码](https://code.onedev.io/projects/160)) `MIT` `Java/Docker/K8S`
- [OpenProject](https://www.openproject.org) - OpenProject 是一个基于 Web 的项目管理系统。([源代码](https://github.com/opf/openproject)) `GPL-3.0` `Ruby/deb/Docker`
- [Pagure](https://pagure.io/pagure) - 一个轻量级、强大且灵活的以 Git 为中心的None铸造，具有为联邦和去中心化开发None奠定基础的功能。([演示](https://pagure.io/)) `GPL-2.0` `Docker/Python/deb`
- [Phorge](https://we.phorge.it/) - Phorge 是一个开源、社区驱动的平台，用于协作、管理、组织和审查软件开发项目。([源代码](https://we.phorge.it/source/phorge/)) `Apache-2.0` `PHP`
- [Plane](https://plane.so) - 帮助您以最简单的方式跟踪您的问题、史诗和产品路线图（替代 JIRA、Linear 和 Height）。([演示](https://app.plane.so), [源代码](https://github.com/makeplane/plane)) `Apache-2.0` `Docker`
- [ProjeQtOr](https://www.projeqtor.org/) - 一个完整的、成熟的、多用户的项目管理系统，具有用于项目所有阶段的广泛功能。([演示](https://demo.projeqtor.org/), [源代码](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- [Redmine](https://www.redmine.org/) - Redmine 是一个灵活的项目管理 Web 应用程序。([源代码](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [Review Board](https://www.reviewboard.org/) - 一个可扩展且友好的代码审查工具，适用于所有规模的项目和公司。([演示](https://demo.reviewboard.org/), [源代码](https://github.com/reviewboard/reviewboard)) `MIT` `Python/Docker`
- [rgit](https://github.com/w4/rgit) - 一个超快且轻量级的 cgit 克隆。`WTFPL` `Rust/Docker`
- [RhodeCode](https://rhodecode.com/) - RhodeCode 是一个开源平台，适用于软件开发团队。它统一并简化了对 Git、Subversion 和 Mercurial 的仓库管理。([源代码](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [Rukovoditel](https://www.rukovoditel.net/) - 可配置的开源项目管理 Web 应用程序。([源代码](https://www.rukovoditel.net/download.php)) `GPL-2.0` `PHP`
- [SCM Manager](https://www.scm-manager.org/) - 通过 http 共享和管理您的 Git、Mercurial 和 Subversion 仓库的最简单方法。([源代码](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java/deb/Docker/K8S`
- [Smederee](https://smeder.ee) - 一个专注于利用 Darcs 版本控制系统力量的节None俭平台，帮助人们一起构建出色的软件。([源代码](https://smeder.ee/~jan0sch/smederee)) `AGPL-3.0` `Scala`
- [Sourcehut](https://sourcehut.org/) - 一个完全的 Web Git 界面，不使用 JavaScript。([演示](https://sr.ht/), [源代码](https://git.sr.ht/~sircmpwn/git.sr.ht/tree)) `GPL-2.0` `Go`
- [Taiga](https://www.taiga.io/) - 基于 Kanban 和 Scrum 方法的敏捷项目管理工具。([源代码](https://github.com/kaleidos-ventures)) `MPL-2.0` `Docker/Python/Nodejs`
- [Titra](https://titra.io/) - 适用于自由职业者和小团队的时间跟踪解决方案。([源代码](https://github.com/kromitgmbh/titra)) `GPL-3.0` `Javascript/Docker`
- [Trac](https://trac.edgewall.org/) - Trac 是一个增强的 wiki 和问题跟踪系统，适用于软件开发项目。`BSD-3-Clause` `Python/deb`
- [Traq](https://traq.io/) - 用 PHP 编写的项目管理和问题跟踪系统。([源代码](https://github.com/nirix/traq)) `GPL-3.0` `PHP/Nodejs`
- [Tuleap](https://www.tuleap.org/) - Tuleap 是一个自由的套件，用于计划、跟踪、编码和协作软件项目。([源代码](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- [UVDesk](https://www.uvdesk.com/) - UVDesk 社区是一个面向服务的、事件驱动的可扩展开源帮助台系统，可以让您的组织以您想象的任何方式轻松高效地为您的客户提供支持。([演示](https://demo.uvdesk.com/), [源代码](https://github.com/uvdesk/community-skeleton)) `MIT` `PHP`
- [ZenTao](https://www.zentao.pm/) - 一个敏捷（Scrum）项目管理系统/工具。([演示](https://demo15.zentao.pm/), [源代码](https://github.com/easysoft/zentaopms)) `AGPL-3.0` `PHP`


### 软件开发 - 测试

**[`^        返回顶部        ^`](#awesome-selfhosted)**

用于[软件测试](https://en.wikipedia.org/wiki/Software_testing)的工具和软件。

- [Bencher](https://bencher.dev/) - Bencher 是一套旨在在 CI 中捕获性能回归的连续基准测试工具。([源代码](https://github.com/bencherdev/bencher)) `MIT/Apache-2.0` `Rust`
- [Selenoid](https://aerokube.com/selenoid/latest/) - 在 Docker 容器中启动浏览器的轻量级 Selenium hub 实现。([源代码](https://github.com/aerokube/selenoid)) `Apache-2.0` `Go`
- [Sorry Cypress](https://sorry-cypress.dev) - Cypress 浏览器自动化框架的替代开源仪表板，具有无限并行化、记录和调试测试的功能。([源代码](https://github.com/sorry-cypress/sorry-cypress)) `MIT` `Docker/K8S`
- [Touca](https://touca.io) - 面向工程团队的连续回归测试。当您编写可能破坏软件的代码时获得反None馈。([源代码](https://github.com/trytouca/trytouca)) `Apache-2.0` `Docker/Nodejs`


### 静态站点生成器

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[静态站点生成器](https://en.wikipedia.org/wiki/Web_template_system#Static_site_generators) 根据原始数据、纯文本文件和一组模板生成完整的静态 HTML 网站。

请访问 [staticsitegenerators.net](https://staticsitegenerators.net), [staticgen.com](https://www.staticgen.com)

相关：[博客平台](#博客平台), [照片和视频画廊](#照片和视频画廊), [内容管理系统 (CMS)](#内容管理系统-cms)


### 状态/正常运行时间页面

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[正常运行时间](https://en.wikipedia.org/wiki/Uptime) 是衡量系统可靠性的指标，以机器（通常是计算机）工作和可用的百分比表示。

相关：[监控](#监控)

- [cState](https://cstate.netlify.app/) - 超快 Hugo 的静态状态页面。干净的设计、最小化的 JS、超轻的 HTML/CSS、高度定制化、可选的管理面板、只读 API、支持 IE8+。最适合与 Netlify、Docker 一起使用。([演示](https://cstate.mnts.lt/), [源代码](https://github.com/cstate/cstate)) `MIT` `Go`
- [Gatus](https://github.com/TwiN/gatus) - 自动化服务健康仪表板。([演示](https://status.twin.sh)) `Apache-2.0` `Docker/K8S`
- [StatPing.ng](https://statping-ng.github.io/) - 一个易于使用的状态页面，用于您的网站和应用程序。Statping 将自动获取应用程序并渲染一个带有许多功能的美丽状态页面，您可以构建一个更好的状态页面。([源代码](https://github.com/statping-ng/statping-ng)) `GPL-3.0` `Docker/Go`
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - 自托管的网站监控工具，如“Uptime Robot”。([演示](https://demo.kuma.pet)) `MIT` `Docker/Nodejs`


### 任务管理和待办事项列表

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[任务管理](https://en.wikipedia.org/wiki/Task_management#Task_management_software) 软件。

相关：[软件开发 - 项目管理](#软件开发---项目管理), [售票](#售票)

- [AppFlowy](https://appflowy.io/) - 使用 AppFlowy，您可以为不同的项目构建详细的待办事项列表，同时跟踪每个项目的状态。开源 Notion 替代品。([源代码](https://github.com/AppFlowy-IO/appflowy)) `AGPL-3.0` `Rust/Dart/Docker`
- [Focalboard](https://www.focalboard.com/) - 定义、组织、跟踪和管理跨个人和团队的工作（替代 Trello、Notion 和 Asana）。([源代码](https://github.com/mattermost/focalboard), [客户端](https://www.focalboard.com/download/personal-edition/desktop/)) `MIT/AGPL-3.0/Apache-2.0` `Nodejs/Go/Docker`
- [Kanboard](https://kanboard.org/) - 简单且开源的可视化任务板。([源代码](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [myTinyTodo](https://www.mytinytodo.net/) - 以 AJAX 风格管理您的待办事项列表的简单方法。使用 PHP、jQuery、SQLite/MySQL。符合 GTD。([演示](https://www.mytinytodo.net/demo/), [源代码](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- [Nullboard](https://github.com/apankrat/nullboard) - 单页面极简主义看板；紧凑、易读且使用快速。`BSD-2-Clause` `Javascript`
- [Our Shopping List](https://github.com/nanawel/our-shopping-list) - 简单的共享列表应用程序。典型用途包括购物列表，当然，还有任何其他需要协作使用的待办事项列表。([演示](https://osl.lanterne-rouge.info/)) `AGPL-3.0` `Docker`
- [Planka](https://planka.app/) - 工作组的实时看板（替代 Trello）。([演示](https://plankanban.github.io/planka/#/), [源代码](https://github.com/plankanban/planka)) `AGPL-3.0` `Nodejs/Docker/K8S`
- [Task Keeper](https://github.com/nymanjens/piga) - 面向电力用户的列表编辑器，由自托管服务器支持。`Apache-2.0` `Scala`
- [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md) - 一个自托管的基于文件的任务管理看板，支持 Markdown 语法。`MIT` `Docker`
- [Taskwarrior](https://taskwarrior.org/) - Taskwarrior 是一个免费且开源的软件，用于从命令行管理您的待办事项列表。它灵活、快速、高效且不显眼。它完成任务后便会退出您的视线。([源代码](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [Tracks](https://www.getontracks.org/) - 帮助您实施 David Allen 的 [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) 方法的基于 Web 的应用程序。([源代码](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [Vikunja](https://vikunja.io/) - 组织您生活的待办事项应用程序。([演示](https://try.vikunja.io/login), [源代码](https://kolaente.dev/vikunja/)) `GPL-3.0` `Go`
- [Wekan](https://wekan.github.io/) - 开源的类似 Trello 的看板。([源代码](https://github.com/wekan/wekan)) `MIT` `Nodejs`


### 售票

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[帮助台](https://en.wikipedia.org/wiki/Help_desk_software)、[错误](https://en.wikipedia.org/wiki/Bug_tracking_system)和[问题](https://en.wikipedia.org/wiki/Issue_tracking_system)跟踪软件，帮助跟踪用户请求、错误和缺失功能。

相关：[任务管理和待办事项列表](#任务管理和待办事项列表), [软件开发 - 项目管理](#软件开发---项目管理)

- [Bugzilla](https://www.bugzilla.org/) - 通用错误跟踪和测试工具，最初由 Mozilla 项目开发和使用。([源代码](https://github.com/bugzilla/bugzilla)) `MPL-2.0` `Perl`
- [FreeScout](https://github.com/freescout-helpdesk/freescout) - 开源的 Help Scout 克隆：基于电子邮件的客户支持应用程序、帮助台和共享邮箱。`AGPL-3.0` `PHP/Docker`
- [GlitchTip](https://glitchtip.com) - 开源错误跟踪应用程序。GlitchTip 收集由您的应用程序报告的错误。([源代码](https://gitlab.com/glitchtip/glitchtip)) `MIT` `Python/Docker/K8S`
- [Iguana](https://github.com/iguana-project/iguana) - Iguana 是一个开源的问题管理系统，带有看板。`CC-BY-SA-4.0` `Python/Docker`
- [ITFlow](https://itflow.org) - 客户 IT 文档、售票、开票和会计 Web 应用程序，适用于 MSP（托管服务提供商）。([演示](https://demo.itflow.org), [源代码](https://github.com/itflow-org/itflow)) `GPL-3.0` `PHP`
- [MantisBT](https://www.mantisbt.org/) - 自托管的错误跟踪器，最适合软件开发。([演示](https://www.mantisbt.org/bugs/my_view_page.php), [源代码](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [osTicket](https://osticket.com/) - 在一个地方管理、组织和存档所有您的支持请求和响应。([源代码](https://github.com/osTicket/osTicket)) `GPL-2.0` `PHP`
- [OTOBO](https://otobo.io/en/) - 灵活的基于 Web 的售票系统，用于客户服务、帮助台、IT 服务管理。([演示](https://otobo.io/en/service-management-plattform/otobo-demo/), [源代码](https://github.com/RotherOSS/otobo)) `GPL-3.0` `Perl/Docker`
- [Request Tracker](https://www.bestpractical.com/rt/) - 企业级的问题跟踪系统。([源代码](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Roundup Issue Tracker](https://www.roundup-tracker.org/) - 一个简单易用且易于安装的问题跟踪系统，具有命令行、Web、REST、XML-RPC 和电子邮件接口。设计考虑到灵活性 - 不仅仅是另一个错误跟踪器。([源代码](https://www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python/Docker`
- [Trudesk](https://trudesk.io/) - Trudesk 是一个开源的帮助台/售票解决方案。([源代码](https://github.com/polonel/trudesk)) `Apache-2.0` `Nodejs/Docker`
- [Zulip](https://zulip.org/) - Zulip 是一个功能强大的开源群聊应用程序。([演示](https://zulip.com/apps/), [源代码](https://github.com/zulip/zulip)) `Apache-2.0` `Python/Docker`None
[Zammad](https://zammad.org/) - 易于使用但功能强大的开源支持和工单系统。([源代码](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby/deb`


### 时间跟踪

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[时间跟踪软件](https://en.wikipedia.org/wiki/Time-tracking_software) 是指允许用户记录任务或项目的时间花费的计算机软件类别。

- [ActivityWatch](https://activitywatch.net) - 自动跟踪您在设备上花费时间的应用程序。([源代码](https://github.com/ActivityWatch/activitywatch)) `MPL-2.0` `Python`
- [Beaver Habit Tracker](https://github.com/daya0576/beaverhabits) - 保存您短暂生活中宝贵时刻的习惯跟踪应用程序。([演示](https://beaverhabits.com/demo)) `BSD-3-Clause` `Docker`
- [Kimai](https://www.kimai.org/) - Kimai 是一个免费且开源的时间跟踪器。它可以跟踪工作时间并根据需求打印出活动摘要。([演示](https://www.kimai.org/demo/), [源代码](https://github.com/kimai/kimai)) `AGPL-3.0` `PHP`
- [solidtime](https://www.solidtime.io) - 适用于自由职业者和代理机构的现代时间跟踪应用程序。([源代码](https://github.com/solidtime-io/solidtime)) `AGPL-3.0` `Docker`
- [TimeTagger](https://timetagger.app) - 基于交互式时间线和强大报告的开源时间跟踪器。([演示](https://timetagger.app/app/demo), [源代码](https://github.com/almarklein/timetagger)) `GPL-3.0` `Python`
- [Traggo](https://traggo.net/) - Traggo 是一个基于标签的时间跟踪工具。在 Traggo 中没有任务，只有标记的时间段。([源代码](https://github.com/traggo/server)) `GPL-3.0` `Docker/Go`


### URL 缩短器

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[URL 缩短](https://en.wikipedia.org/wiki/URL_shortening) 是将 [URL](https://en.wikipedia.org/wiki/Uniform_Resource_Locator) 缩短以使其大大缩短并仍然指向所需页面的操作。在托管一个之前，请查看 [URL 缩短器的缺点](https://en.wikipedia.org/wiki/URL_shortening#Disadvantages)。

- [Chhoto URL](https://github.com/SinTan1729/chhoto-url) - 简单、极速的 URL 缩短器，没有任何None臃None肿（simply-shorten 的分支）。`MIT` `Rust/Docker`
- [Just Short It!](https://github.com/miawinter98/just-short-it) - 一个 KISS、单用户的 URL 缩短器，只需一个容器即可运行。`MIT` `Docker`
- [liteshort](https://git.ikl.sh/132ikl/liteshort) - 用户友好、真正轻量级且可配置的 URL 缩短器。`MIT` `Python/deb`
- [Lstu](https://github.com/ldidry/lstu) - 轻量级的 URL 缩短器。`WTFPL` `Perl/Docker`
- [Lynx](https://getlynx.dev) - 具有多种功能的 URL 缩短器，如多账户、ShareX 支持和简单但吸引人的界面。([演示](https://demo.getlynx.dev), [源代码](https://github.com/Lynx-Shortener/Lynx)) `MIT` `Nodejs/Docker`
- [rs-short](https://git.42l.fr/42l/rs-short) - 使用 Rust 编写的轻量级链接缩短器，具有缓存、防None垃None圾机器人和None钓鱼检测等功能。([演示](https://s.42l.fr/)) `MPL-2.0` `Rust`
- [Shlink](https://shlink.io) - 具有 REST API 和命令行界面的 URL 缩短器。包括官方渐进式 Web 应用程序和 Docker 镜像。([源代码](https://github.com/shlinkio/shlink), [客户端](https://shlink.io/apps)) `MIT` `PHP/Docker`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL 缩短器，公共和私人（带账户）。简约且轻量级。没有依赖项。([演示](https://u.azlux.fr)) `MIT` `PHP`
- [Simply Shorten](https://gitlab.com/draganczukp/simply-shorten) - 只缩短链接的简单 URL 缩短器。`MIT` `Java/Docker`
- [YOURLS](https://yourls.org/) - YOURLS 是一组 PHP 脚本，允许您运行自己的 URL 缩短器。功能包括密码保护、URL 自定义、书签工具、统计、API、插件、jsonp。([源代码](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### 视频监控

**[`^        返回顶部        ^`](#awesome-selfhosted)**

视频监控，也称为 [闭路电视 (CCTV)](https://en.wikipedia.org/wiki/Closed-circuit_television)，是指在需要额外安全性或持续监控的区域使用视频摄像头的监控。

_相关：[媒体流 - 视频流](#media-streaming---video-streaming)_

- [Bluecherry](https://www.bluecherrydvr.com/) - 支持 IP 和模拟摄像头的闭路电视 (CCTV) 软件应用程序。([源代码](https://github.com/bluecherrydvr/bluecherry-apps)) `GPL-2.0` `PHP`
- [Frigate](https://frigate.video/) - 使用本地处理的 AI 监控您的安全摄像头。([源代码](https://github.com/blakeblackshear/frigate)) `MIT` `Docker/Python/Nodejs`
- [SentryShot](https://codeberg.org/SentryShot/sentryshot) - 视频监控管理系统。`GPL-2.0` `Docker/Rust`
- [Viseron](https://viseron.netlify.app/) - 自托管、仅限本地的 NVR 和 AI 计算机视觉软件。通过诸如对象检测、运动检测、人脸识别等功能，它赋予您监控您想要监控的家、办公室或任何其他地方的权力。([源代码](https://github.com/roflcoopter/viseron)) `MIT` `Docker`
- [Zoneminder](https://www.zoneminder.com/) - 支持 IP、USB 和模拟摄像头的闭路电视 (CCTV) 软件应用程序。([源代码](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP/deb`


### VPN

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[虚拟专用网络 (VPN)](https://en.wikipedia.org/wiki/Virtual_private_network) 通过公共网络扩展私有网络，并允许用户通过共享或公共网络发送和接收数据，就好像他们的计算设备直接连接到私有网络一样。

**请访问 [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn)**



### Web 服务器

**[`^        返回顶部        ^`](#awesome-selfhosted)**

Web 服务器和反向代理。 [Web 服务器](https://en.wikipedia.org/wiki/Web_server) 是一款接受通过 [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)（创建用于分发 Web 内容的网络协议）或其安全变体 [HTTPS](https://en.wikipedia.org/wiki/HTTPS) 请求的软件和底层硬件。 [反向代理](https://en.wikipedia.org/wiki/Reverse_proxy) 是一个代理服务器，它对任何客户端来说看起来像一个普通的 Web 服务器，但实际上仅仅是作为一个中间人，将请求转发给一个或多个普通的 Web 服务器。

_相关：[代理](#proxy)_

- [Algernon](https://algernon.roboticoverlords.org/) - 带有 Lua、Markdown、HTTP/2、QUIC、Redis 和 PostgreSQL 支持的小型自包含纯 Go Web 服务器。([源代码](https://github.com/xyproto/algernon)) `BSD-3-Clause` `Go/Docker`
- [Apache HTTP Server](https://httpd.apache.org/) - 安全、高效且可扩展的服务器，提供与当前 HTTP 标准同步的 HTTP 服务。([源代码](https://svn.apache.org/viewvc/httpd/httpd/branches/2.4.x/)) `Apache-2.0` `C/deb/Docker`
- [BunkerWeb](https://www.bunkerweb.io) - 下一代 Web 应用程序防火墙 (WAF)，将保护您的 Web 服务。([演示](https://demo.bunkerweb.io), [源代码](https://github.com/bunkerity/bunkerweb), [客户端](https://docs.bunkerweb.io/latest/plugins/)) `AGPL-3.0` `deb/Docker/K8S/Python`
- [Caddy](https://caddyserver.com/) - 强大、企业就绪的开源 Web 服务器，具有自动 HTTPS。([源代码](https://github.com/caddyserver/caddy)) `Apache-2.0` `Go/deb/Docker`
- [HAProxy](https://www.haproxy.org/) - 非常快速且可靠的反向代理，提供高可用性、负载均衡和基于 TCP 和 HTTP 的应用程序的代理。([源代码](https://git.haproxy.org/?p=haproxy.git;a=tree)) `GPL-2.0` `C/deb/Docker`
- [Jauth](https://github.com/Jipok/Jauth) `None⚠` - 带有授权（通过 Telegram 和 SSH）的轻量级 SSL/TLS 反向代理，用于自托管应用程序。`GPL-3.0` `Go`
- [Lighttpd](https://www.lighttpd.net/) - 安全、快速、符合标准且非常灵活的 Web 服务器，已针对高性能环境进行了优化。([源代码](https://git.lighttpd.net/lighttpd/lighttpd1.4)) `BSD-3-Clause` `C/deb/Docker`
- [Nginx Proxy Manager](https://nginxproxymanager.com/) - Nginx Proxy Manager 是一种轻松实现反向代理主机和 SSL 终止的方法。([源代码](https://github.com/NginxProxyManager/nginx-proxy-manager)) `MIT` `Nodejs/Docker`
- [Nginx](https://nginx.org/en/) - HTTP 和反向代理服务器、邮件代理服务器和通用 TCP/UDP 代理服务器。([源代码](https://hg.nginx.org/nginx/file/tip)) `BSD-2-Clause` `C/deb/Docker`
- [Pomerium](https://www.pomerium.io) - 具有身份识别的反向代理，是现在已废弃的 oauth_proxy 的后继者。它在将请求代理到后端之前插入了一个 OAuth 步骤，因此您可以安全地将自托管网站暴露给公共互联网。([源代码](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go`
- [Static Web Server](https://static-web-server.net/) - 用于静态文件服务的跨平台、高性能和异步 Web 服务器。([源代码](https://github.com/static-web-server/static-web-server)) `Apache-2.0/MIT` `Rust/Docker`
- [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag) - 带有 PHP 支持的 Nginx Web 服务器和反向代理，内置 Certbot（Let's Encrypt）客户端和 fail2ban 集成。`GPL-3.0` `Docker`
- [Traefik](https://traefik.io/) - 使部署微服务变得简单的 HTTP 反向代理和负载均衡器。([源代码](https://github.com/traefik/traefik)) `MIT` `Go/Docker`
- [Varnish](https://varnish-cache.org/) - Web 应用程序加速器/缓存 HTTP 反向代理。([源代码](https://github.com/varnishcache/varnish-cache)) `BSD-3-Clause` `Go/deb/Docker`


### 维基

**[`^        返回顶部        ^`](#awesome-selfhosted)**

[维基](https://en.wikipedia.org/wiki/Wiki) 是由其受众通过 Web 浏览器直接协作编辑和管理的出版物。

_相关：[笔记和编辑器](#note-taking--editors), [静态站点生成器](#static-site-generators), [知识管理工具](#knowledge-management-tools)_

_另见：[Wikimatrix](https://www.wikimatrix.org/), [维基软件列表 - 维基百科](https://en.wikipedia.org/wiki/List_of_wiki_software), [维基软件比较 - 维基百科](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- [AmuseWiki](https://amusewiki.org/) - Amusewiki 基于 Emacs Muse 标记语言，基本与原始实现保持兼容。它可以作为只读站点、作为审核过的维基、作为完全开放的维基或甚至作为私人站点工作。([演示](https://sandbox.amusewiki.org), [源代码](https://github.com/melmothx/amusewiki)) `GPL-1.0` `Perl/Docker`
- [BookStack](https://www.bookstackapp.com/) - BookStack 是一个简单、自托管、易于使用的平台，用于组织和存储信息。它允许以书籍形式存储文档。([演示](https://www.bookstackapp.com/#demo), [源代码](https://github.com/BookStackApp/BookStack)) `MIT` `PHP/Docker`
- [django-wiki](https://github.com/django-wiki/django-wiki) - 具有复杂功能的维基系统，用于简单集成和出色的界面。使用 django 模型存储您的知识。([演示](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- [docmost](https://docmost.com/) - 协作维基和文档软件（Confluence、Notion 的替代品）。([源代码](https://github.com/docmost/docmost)) `AGPL-3.0` `Docker/Nodejs`
- [Documize](https://documize.com) - 带有内置工作流程的现代文档 + 维基软件，单一二进制可执行文件，只需带上 MySQL/Percona。([源代码](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - 易于使用、轻量级、符合标准的维基引擎，具有简单的语法，允许在维基之外读取数据。所有数据都存储在纯文本文件中，因此不需要数据库。([源代码](https://github.com/dokuwiki/dokuwiki)) `GPL-2.0` `PHP`
- [Feather Wiki](https://feather.wiki) - 一个闪电般快速且无限可扩展的工具，用于创建个人非线性笔记本、数据库和维基，完全自包含，在浏览器中运行，大小仅为 58 千字节。([演示](https://feather.wiki/?page=gallery#wikis), [源代码](https://codeberg.org/Alamantus/FeatherWiki), [客户端](https://feather.wiki/?page=gallery#extensions)) `AGPL-3.0` `Javascript`
- [Gitit](https://github.com/jgm/gitit) - 存储页面和上传文件在 git 仓库中的维基程序，然后可以使用 VCS 命令行工具或维基的 Web 界面进行修改。`GPL-2.0` `Haskell`
- [Gollum](https://github.com/gollum/gollum) - 简单、由 Git 驱动的维基，带有甜美的 API 和本地前端。`MIT` `Ruby`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - MediaWiki 是一个用 PHP 编写的免费且开源的维基软件包。它作为 Wikipedia 和其他 Wikimedia 项目的平台，每月被数亿人使用。([演示](https://en.wikipedia.org/wiki/Main_Page), [源代码](https://phabricator.wikimedia.org/diffusion/MW/)) `GPL-2.0` `PHP`
- [Mycorrhiza Wiki](https://mycorrhiza.wiki/) - 使用 Go 编写的基于文件系统和 git 的维基引擎，使用 Mycomarkup 作为其主要标记语言。([源代码](https://github.com/bouncepaw/mycorrhiza/)) `AGPL-3.0` `Go`
- [Otter Wiki](https://github.com/redimp/otterwiki) - 使用 markdown 的简单、易于使用的维基软件。`MIT` `Docker`
- [Outline](https://www.getoutline.com/) `None⚠` - 一个开放的、可扩展的、为您的团队设计的维基。([源代码](https://github.com/outline/outline)) `BSD-3-Clause` `Nodejs/Docker`
- [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki) - 包含在一个单一 PHP 文件中的完整 markdown 驱动的维基。([演示](https://starbeamrainbowlabs.com/labs/peppermint/build/)) `MPL-2.0` `PHP`
- [PmWiki](https://www.pmwiki.org) - 基于维基的系统，用于协作创建和维护网站。`GPL-3.0` `PHP`
- [Raneto](https://raneto.com/) - Raneto 是一个开源的知识库平台，使用静态 Markdown 文件为您的知识库提供动力。([源代码](https://github.com/ryanlelek/Raneto)) `MIT` `Nodejs`
- [TiddlyWiki](https://tiddlywiki.com/) - 可重用的非线性个人 Web 笔记本。([源代码](https://github.com/Jermolene/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- [Tiki](https://tiki.org/HomePage) - 带有最多内置功能的 Wiki CMS 协作软件。([演示](https://tiki.org/Try-Tiki), [源代码](https://gitlab.com/tikiwiki/tiki)) `LGPL-2.1` `PHP`
- [WackoWiki](https://wackowiki.org/) - WackoWiki 是一个轻量且易于安装的多语言 Wiki 引擎。([源代码](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- [Wiki.js](https://js.wiki/) - 现代、轻量且强大的维基应用，使用 Git 和 Markdown。([演示](https://docs.requarks.io), [源代码](https://github.com/Requarks/wiki)) `AGPL-3.0` `Nodejs/Docker/K8S`
- [WikiDocs](http://wikidocs.it) - 一个无数据库的基于文件的 markdown 维基引擎。([演示](https://demo.wikidocs.it), [源代码](https://github.com/Zavy86/WikiDocs)) `MIT` `PHP/Docker`
- [WiKiss](https://wikiss.tuxfamily.org/) - 易于使用和安装的维基。([源代码](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- [Wikmd](https://github.com/Linbreux/wikmd) - 现代且简单的基于文件的维基，使用 Markdown 和 Git。`MIT` `Python/Docker`
- [XWiki](https://www.xwiki.org) - 第二代维基，允许用户通过强大的基于扩展的架构扩展其功能。([演示](https://playground.xwiki.org), [源代码](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java/Docker/deb`
- [Zim](https://zim-wiki.org/) - 用于维护维基页面集合的图形文本编辑器。每个页面可以包含指向其他页面的链接、简单的格式和图像。([源代码](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python/deb`


--------------------

## 许可证列表

**[`^        返回顶部        ^`](#awesome-selfhosted)**

- `0BSD` - [BSD Zero-Clause Licence](https://spdx.org/licenses/0BSD.html)
- `AAL` - [Attribution Assurance License](https://spdx.org/licenses/AAL.html)
- `AGPL-3.0` - [GNU Affero General Public License 3.0](https://spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - [Apache, Version 2.0](https://spdx.org/licenses/Apache-2.0.html)
- `APSL-2.0` - [Apple Public Source License, Version 2.0](https://spdx.org/licenses/APSL-2.0.html)
- `Artistic-2.0` - [Artistic License Version 2.0](https://spdx.org/licenses/Artistic-2.0.html)
- `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2-clause "Simplified"](https://spdx.org/licenses/BSD-2-Clause.html)
- `BSD-2-Clause-FreeBSD` - [BSD 2-Clause FreeBSD License](https://spdx.org/licenses/BSD-2-Clause-FreeBSD.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised"](https://spdx.org/licenses/BSD-3-Clause.html)
- `BSD-3-Clause-Attribution` - [BSD with attribution](https://spdx.org/licenses/BSD-3-Clause-Attribution.html)
- `BSD-4-Clause` - [BSD 4-clause "Original"](https://spdx.org/licenses/BSD-4-Clause.html)
- `CC-BY-SA-3.0` - [Creative Commons Attribution-ShareAlike 3.0 License](https://spdx.org/licenses/CC-BY-SA-3.0.html)
- `CC-BY-SA-4.0` - [Creative Commons Attribution-ShareAlike 4.0 License](https://spdx.org/licenses/CC-BY-SA-4.0.html)
- `CC0-1.0` - [Public Domain/Creative Common Zero 1.0](https://spdx.org/licenses/CC0-1.0.html)
- `CDDL-1.0` - [Common Development and Distribution License](https://spdx.org/licenses/CDDL-1.0.html)
- `CECILL-B` - [CEA CNRS INRIA Logiciel Libre](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [Common Public Attribution License Version 1.0](https://spdx.org/licenses/CPAL-1.0.html)
- `ECL-2.0` - [Educational Community License, Version 2.0](https://spdx.org/licenses/ECL-2.0.html)
- `EPL-1.0` - [Eclipse Public License, Version 1.0](https://spdx.org/licenses/EPL-1.0.html)
- `EPL-2.0` - [Eclipse Public License, Version 2.0](https://spdx.org/licenses/EPL-2.0.html)
- `EUPL-1.2` - [European Union Public License 1.2](https://spdx.org/licenses/EUPL-1.2.html)
- `GPL-1.0` - [GNU General Public License 1.0](https://spdx.org/licenses/GPL-1.0.html)
- `GPL-2.0` - [GNU General Public License 2.0](https://spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - [GNU General Public License 3.0](https://spdx.org/licenses/GPL-3.0.html)
- `IPL-1.0` - [IBM Public License](https://spdx.org/licenses/IPL-1.0.html)
- `ISC` - [Internet Systems Consortium License](https://spdx.org/licenses/ISC.html)
- `LGPL-2.1` - [Lesser General Public License 2.1](https://spdx.org/licenses/LGPL-2.1.html)
- `LGPL-3.0` - [Lesser General Public License 3.0](https://spdx.org/licenses/LGPL-3.0.html)
- `MIT` - [MIT License](https://spdx.org/licenses/MIT.html)
- `MPL-1.1` - [Mozilla Public License Version 1.1](https://spdx.org/licenses/MPL-1.1.html)
- `MPL-2.0` - [Mozilla Public License](https://spdx.org/licenses/MPL-2.0.html)
- `OSL-3.0` - [Open Software License 3.0](https://spdx.org/licenses/OSL-3.0.html)
- `Sendmail` - [Sendmail License](https://spdx.org/licenses/Sendmail.html)
- `Ruby` - [Ruby License](https://spdx.org/licenses/Ruby.html)
- `Unlicense` - [The Unlicense](https://spdx.org/licenses/Unlicense.html)
- `WTFPL` - [Do What the Fuck You Want to Public License](https://spdx.org/licenses/WTFPL.html)
- `Zlib` - [Zlib/libpng License](https://spdx.org/licenses/Zlib.html)
- `ZPL-2.0` - [Zope Public License 2.0](https://spdx.org/licenses/ZPL-2.0.html)


--------------------

## 反功能

- `None⚠ ` - 依赖于用户无法控制的专有服务

--------------------

## 外部链接

**[`^        返回顶部        ^`](#awesome-selfhosted)**

- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - 精选的令人惊叹的开源系统管理员资源列表。
- 旨在以某种形式实现隐私和去中心化的软件列表：[PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](https://libreprojects.net/), [Easy Indie App](https://easyindie.app)
- 其他 Awesome 列表：[Awesome Big Data](https://github.com/0xnr/awesome-bigdata), [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- 动态域名服务：[Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
- 社区/论坛：[/c/selfhosted on lemmy.world](https://lemmy.world/c/selfhosted), [/c/selfhost on lemmy.ml](https://lemmy.ml/c/selfhost), [/m/selfhosted on kbin.social](https://kbin.social/m/selfhosted), [/r/selfhosted on reddit](https://old.reddit.com/r/selfhosted/), [r-selfhosted forum](https://forum.r-selfhosted.com/), [/r/selfhosted Matrix Channel](https://matrix.to/#/#selfhosted:selfhosted.chat), [Homelab forum](https://homelabforum.com/), [/r/homelab on reddit](https://old.reddit.com/r/homelab/), [IndieWeb](https://indieweb.org/)
- [theme.park](https://theme-park.dev/) - 50 个自托管应用程序的主题/皮肤集合！([源代码](https://github.com/GilbN/theme.park/)) `MIT` `CSS`
- [Track Awesome Selfhosted](https://www.trackawesomelist.com/awesome-selfhosted/awesome-selfhosted/) - 获取 awesome-selfhosted 的最新更新。

--------------------

## 贡献

贡献指南可以在 [此处](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/CONTRIBUTING.md) 找到。

## 许可证

此列表遵循 [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/LICENSE) 许可证。
许可证条款的摘要可以在 [此处](https://creativecommons.org/licenses/by-sa/3.0/) 找到。
作者列表可以在 [AUTHORS](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/AUTHORS) 文件中找到。