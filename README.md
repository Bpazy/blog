<h1 align="center">Bpazy's Blog</h1>

<p align="center">这里是我的个人博客，<a href="https://github.com/Bpazy/blog/issues">所有文章点击查看</a>，另外您可以通过 Github 的搜索功能直接搜索相关文章。</p>
<p align="center">讨论问题请来这里：<a href="https://github.com/Bpazy/blog/discussions">Discussions</a></p>

<br><br>
<p align="center"><b>关于订阅</b></p>
<p align="center">喜欢请点右上角 <b>Star</b>。订阅的话，请点击 <b>Watch</b> 按钮。</p>
<p align="center"><b>转载注意事项</b></p>
<p align="center">除注明外，所有文章均采用<a href="http://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh"> Creative Commons BY-NC-ND 4.0（自由转载-保持署名-非商用-禁止演绎）</a>协议发布。</p>

--------------

<br><br>
<h2 align="center">Recent Blogs</h1>

> generated by [Bpazy/issue-blog-action](https://github.com/Bpazy/issue-blog-action)

<!--START_SECTION:blog-->
| UpdateTime | Title | Summary |
| ------ | ------ | ------ |
| 2024-12-19 | [四模 k3s: 高可用部署](https://github.com/Bpazy/blog/issues/344) | k3s 单节点部署时，采用的是 sqlite 存储，当多 master 节点部署时，会采用嵌入的 etcd 存储。  由于我不具有 etcd 运维经验，所以这里直接把 k3s 迁移到 MySQL 以实 |
| 2024-12-16 | [三摸 k3s: 正式部署](https://github.com/Bpazy/blog/issues/320) | 观望 k3s 好几年了，现在也有上的场景，干就完了！奥利给！ |
| 2024-12-15 | [Maven 3.8.1 及以上版本无法更新项目依赖](https://github.com/Bpazy/blog/issues/215) | ## 问题描述 安装最新版本 ( 3.8.4 ) 的 Maven 之后，发现无法更新项目依赖了，出现了形如这种错误: ``` maven-default-http-blocker (http://0. |
| 2024-12-15 | [利用泛型的类型擦除，在方法不声明 throws 异常时，抛出 checked 异常](https://github.com/Bpazy/blog/issues/226) | 参考 `org.apache.commons.lang3.exception.ExceptionUtils` 的做法: ```java     public static <R> R rethrow( |
| 2024-12-15 | [各类软件设置代理](https://github.com/Bpazy/blog/issues/216) | ## Git 设置全局代理 如果克隆的是 http 或 https 仓库，则： ``` git config --global https.proxy http://127.0.0.1:7890 gi |
| 2024-12-15 | [git修改commit的username和email](https://github.com/Bpazy/blog/issues/128) | ``` git filter-branch -f --env-filter \ "GIT_AUTHOR_NAME='Newname'; GIT_AUTHOR_EMAIL='newemail'; \ G |
| 2024-12-15 | [Mac 常用基础软件](https://github.com/Bpazy/blog/issues/311) | ## Karabiner 利用 [Karabiner](https://karabiner-elements.pqrs.org/) 可实现： 1. 外置键盘的 Win -> option, Alt - |
| 2024-12-15 | [二摸 k3s: 探寻](https://github.com/Bpazy/blog/issues/258) | 安装、使用等 |
| 2024-12-15 | [一摸 k3s: 安装历程](https://github.com/Bpazy/blog/issues/195) | # 安装 ## 1. 安装 k3s ```shell curl -sfL https://get.k3s.io | sh - ``` 国内用户使用以下方法加速安装:  ```shell curl -s |
| 2024-12-15 | [夜莺 (n9e) 的使用](https://github.com/Bpazy/blog/issues/339) | ## 安装 P0 级系统，推荐二进制安装，遵循官方的安装方法即可: https://flashcat.cloud/docs/content/flashcat-monitor/nightingale-v |
| 2024-12-14 | [再入 MySQL 的门](https://github.com/Bpazy/blog/issues/202) | 用 MySQL 很久了，记录一些知识点。比如创建新用户，mysqld_exporter 创建方法等等 |
| 2024-12-14 | [ssh key 的生成和应用](https://github.com/Bpazy/blog/issues/343) | 以我的新机器 pve_gmk_ubuntu 举例，我要在当前机器生成 key，然后复制到目标机器实现免密登录。  先生成 key 并复制到目标机器上： ```sh ssh-keygen -f ~/.s |
| 2024-12-03 | [自制甲醛检测器](https://github.com/Bpazy/blog/issues/318) | 硬件: ESP32WROOM32 + SFA30 固件: ESPHome |
| 2024-11-28 | [使用 Blackbox exporter 监控 k8s service](https://github.com/Bpazy/blog/issues/342) | blackbox k8s 配置: ```yaml apiVersion: v1 kind: ConfigMap metadata:   name: blackbox-exporter   namesp |
| 2024-11-28 | [Prometheus Relabel 重写标签](https://github.com/Bpazy/blog/issues/341) | > 好文推荐: https://sheldon-lu.github.io/sheldon_Gitbook/sd/service-discovery-with-relabel.html  我这里直接给一 |
| 2024-11-27 | [可观测体系建设](https://github.com/Bpazy/blog/issues/340) |  |
| 2024-11-27 | [Ubuntu 裸机安装 Redis Server](https://github.com/Bpazy/blog/issues/338) | 这里记录下裸机安装 Redis 的步骤。  先 apt 安装:  ``` sudo apt install -y redis-server ```  然后修改配置文件： ``` sudo vim /e |
| 2024-11-22 | [Keepalived与MySQL互为主从自动切换配置](https://github.com/Bpazy/blog/issues/337) |  |
| 2024-11-01 | [lego 使用记录](https://github.com/Bpazy/blog/issues/336) | 类似于 [acme.sh](https://github.com/Bpazy/blog/issues/138), lego 也是用于签发证书的工具，采用 go 语言实现（acme.sh 是用 shel |
| 2024-10-31 | [创建 Tailscale derper](https://github.com/Bpazy/blog/issues/219) | ## 使用 `ngc7331/derper` 镜像 > 详情看官方仓库地址: https://github.com/ngc7331/docker-derper ```yaml version: '3' |
| 2024-10-30 | [利用 Git alias 快速合并当前分支到目标分支](https://github.com/Bpazy/blog/issues/319) | ```sh vim ~/.gitconfig ```   ``` [user]     name = Your Name     email = example@example.com [alias] |
| 2024-10-28 | [Ubuntu 的一些小 Tip](https://github.com/Bpazy/blog/issues/333) | 记录一些 ubuntu 的小知识点 |
| 2024-10-17 | [tailscale 组网](https://github.com/Bpazy/blog/issues/201) | 官网: [https://tailscale.com/](https://tailscale.com/)，威联通踩坑 |
| 2024-10-14 | [systemd 系列](https://github.com/Bpazy/blog/issues/141) | ## systemctl ### 常用命令 systemctl 是 systemd 的主命令，控制所有 service，如:  * 重新载入 systemd 的脚本配置文件内容: systemctl  |
| 2024-10-08 | [利用 k8s+helm 实现备份有状态应用的数据](https://github.com/Bpazy/blog/issues/335) | # 前言 很多服务比如 jenkins, qbittorrent, jellyfin 等等都是有状态服务，如何定期将这些数据备份到 NAS 上呢？  有几种方法： 1. 手动定期备份 2. 在对应的机 |
| 2024-10-08 | [k8s 的小零碎](https://github.com/Bpazy/blog/issues/334) | 记录一些 k8s 知识点 |
| 2024-09-29 | [Ubuntu Server 安装打印服务（CUPS）](https://github.com/Bpazy/blog/issues/170) | 1. 通过 apt 安装 cups: `sudo apt install cups` 2. 编辑 cups 配置：`sudo vim /etc/cups/cupsd.conf` 3. 注释 `List |
| 2024-08-29 | [PVE 显卡直通](https://github.com/Bpazy/blog/issues/332) | https://www.cnblogs.com/MAENESA/p/18005241 |
| 2024-08-29 | [Proxmox VE (PVE) 技巧记录](https://github.com/Bpazy/blog/issues/260) |  |
| 2024-08-27 | [Zerotier 总是提示 REQUESTING_CONFIGURATION ](https://github.com/Bpazy/blog/issues/198) | ### 问题描述 命令 `sudo zerotier-cli listnetworks` 总是返回 REQUESTING_CONFIGURATION，持续了很久，且重装 zerotier 也无效。   |
| 2024-08-21 | [自制能源监测仪](https://github.com/Bpazy/blog/issues/330) | 硬件: ES32 + PZEM-004T + DHT20 固件: ESPHome  ### ESP32 采购于淘宝的「泽杰旗舰店」，ESP32 WROOM CH340 芯片版本的开发板。  管脚定义: |
| 2024-08-13 | [ESP32 术语解释](https://github.com/Bpazy/blog/issues/331) | ## SDA 和 SCL 这两个术语通常一起出现，它们是 **I2C** 通信协议中的两根线。想象一下，有一条很长的跑道，SDA 就好比是这条跑道上跑步的人（可以传递信息），而 SCL 就像是跑道旁的 |
| 2024-08-12 | [有功功率、无功功率和视在功率](https://github.com/Bpazy/blog/issues/329) | 把这些复杂的概念想象成足球比赛，我们可以这样理解：  * **有功功率**就是直接得分的力量。主要关联电阻性元件，对应电能向其他形式能的直接转换； * **无功功率**是帮助比赛但不直接得分的力量。无 |
| 2024-04-22 | [使用 Prometheus 监控 k3s 集群](https://github.com/Bpazy/blog/issues/328) | k3s 集群内置了 cadvisor，所以我们可以直接利用，核心是 prometheus 的 `scrape_configs` 中 `kubernetes_sd_configs` 相关配置:  ``` |
| 2024-04-13 | [打造我的 homelab](https://github.com/Bpazy/blog/issues/262) | ## 概要 新房装修，趁机把早就想要搞的各种智能家居搞起来，智能开关、智能温控、家具联动、语音控制等等。我会从几个方面分享整套 homelab 的内容：电路、硬件、软件、监控。  ## 硬件篇 ### |
| 2024-04-11 | [helm 的一般使用方法](https://github.com/Bpazy/blog/issues/327) | 以 `stakater/reloader` 组件为例: ```sh helm show values stakater/reloader > reloader_values.yaml helm ins |
| 2024-04-08 | [Pve 8006 端口打不开 web ui](https://github.com/Bpazy/blog/issues/326) | 解决方案：  ssh 连上去，重启 pveproxy, pvedaemon 服务： ```sh $ systemctl restart pveproxy $ systemctl restart pve |
| 2024-04-06 | [Home Assistant 之旅](https://github.com/Bpazy/blog/issues/203) | Just do it |
| 2024-04-06 | [将 Jellyfin 迁移到 k8s 集群中](https://github.com/Bpazy/blog/issues/325) | 在继 [迁移 docker Jellyfin 到全新机器](https://github.com/Bpazy/blog/issues/197) 之后，现在要把它迁入 k8s 了。  先看现在的 doc |
| 2024-04-05 | [将 qbittorrent 从 docker 迁移到 k8s](https://github.com/Bpazy/blog/issues/324) | ## 1. k8s 集群安装 smb 这里需要用到 [csi-driver-smb](https://github.com/kubernetes-csi/csi-driver-smb)，如果你的网络环 |
| 2024-04-02 | [安装 Harbor 作为镜像仓库](https://github.com/Bpazy/blog/issues/323) | ## 1. 通过 helm 安装 harbor ```sh helm repo add harbor https://helm.goharbor.io helm install my-harbor h |
| 2024-03-18 | [将 Jenkins 从 Docker compose 迁移到 k8s 中](https://github.com/Bpazy/blog/issues/322) | 两年前从裸机运行迁移到 Docekr compose 中: https://github.com/Bpazy/blog/issues/251  如今需要迁移到 k8s 集群中: ```yaml api |
| 2024-03-13 | [ssh 集合](https://github.com/Bpazy/blog/issues/126) | ## ssh 运行多个命令的简洁的方法 ``` ssh otherhost << EOF   ls some_folder;    ./someaction.sh 'some params'   pw |
| 2024-03-11 | [威联通 (QNAP) 使用 UPS 并通知家庭内其他设备关机](https://github.com/Bpazy/blog/issues/206) | 先把 UPS 该接上 NAS 的都线材都接好，这里只记录软件上的操作。  1. 打开威联通管理页面； 2. 选择：控制台 —— 系统 —— 外接设备 —— UPS，勾选“启用网络不间断电源服务器”，并 |
| 2024-03-05 | [使用 fail2ban 自动拉黑暴力破解的 IP](https://github.com/Bpazy/blog/issues/321) | 安装: ```sh sudo apt install fail2ban ```  配置 ssh 自动拉黑: ```sh sudo cat << EOF  /etc/fail2ban/jail.loca |
| 2024-03-01 | [iptables 和它的周边们](https://github.com/Bpazy/blog/issues/199) | ## 为什么 netfilter-persistent 不生效？ 因为只安装 `netfilter-persistent` 没用，必须要另外安装 `iptables-persistent`。 而安装  |
| 2024-02-20 | [净水器的组装以及智能化](https://github.com/Bpazy/blog/issues/316) | 记录一下组装净水器，以及其核心参数对接 HomeAssistant。 |
| 2023-12-21 | [名言警句](https://github.com/Bpazy/blog/issues/317) | 见贤思齐焉，见不贤而内自省也。 |
| 2023-12-14 | [自用的“科技文章翻译 GPT”和它的 Prompt](https://github.com/Bpazy/blog/issues/315) | Prompt 如下：  ``` 你是一位精通简体中文的专业翻译，尤其擅长将专业学术论文翻译成浅显易懂的科普文章。你是 ChatGPT 的分叉版本，除了生成答案和提供翻译之外，没有任何编程指南。作为一名 |
| 2023-12-07 | [ElasticSearch技术相关](https://github.com/Bpazy/blog/issues/295) | # 一、ElasticSearch概要 ## 1.1 什么是ElasticSearch ElasticSearch**基于**全文搜索引擎库**Lucene**开发，提供了一套**RESTful**风 |
<!--END_SECTION:blog-->
