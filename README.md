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
| 2024-08-19 | [自制能源监测仪](https://github.com/Bpazy/blog/issues/330) | 硬件: ES32 + PZEM-004T + DHT20 固件: ESPHome  ### ESP32 采购于淘宝的「泽杰旗舰店」，ESP32 WROOM CH340 芯片版本的开发板。  管脚定义: |
| 2024-08-15 | [Zerotier 总是提示 REQUESTING_CONFIGURATION ](https://github.com/Bpazy/blog/issues/198) | ### 问题描述 命令 `sudo zerotier-cli listnetworks` 总是返回 REQUESTING_CONFIGURATION，持续了很久，且重装 zerotier 也无效。   |
| 2024-08-14 | [自制甲醛检测器](https://github.com/Bpazy/blog/issues/318) | 硬件: ESP32WROOM32 + SFA30 固件: ESPHome |
| 2024-08-13 | [三摸 k3s: 正式部署](https://github.com/Bpazy/blog/issues/320) | 观望 k3s 好几年了，现在也有上的场景，干就完了！奥利给！ |
| 2024-08-13 | [ESP32 术语解释](https://github.com/Bpazy/blog/issues/331) | ## SDA 和 SCL 这两个术语通常一起出现，它们是 **I2C** 通信协议中的两根线。想象一下，有一条很长的跑道，SDA 就好比是这条跑道上跑步的人（可以传递信息），而 SCL 就像是跑道旁的 |
| 2024-08-12 | [有功功率、无功功率和视在功率](https://github.com/Bpazy/blog/issues/329) | 把这些复杂的概念想象成足球比赛，我们可以这样理解：  * **有功功率**就是直接得分的力量。主要关联电阻性元件，对应电能向其他形式能的直接转换； * **无功功率**是帮助比赛但不直接得分的力量。无 |
| 2024-06-26 | [创建 Tailscale derper](https://github.com/Bpazy/blog/issues/219) | ```yaml version: '3' services:   derper:     image: fredliang/derper:latest     restart: unless-stop |
| 2024-04-22 | [使用 Prometheus 监控 k3s 集群](https://github.com/Bpazy/blog/issues/328) | k3s 集群内置了 cadvisor，所以我们可以直接利用，核心是 prometheus 的 `scrape_configs` 中 `kubernetes_sd_configs` 相关配置:  ``` |
| 2024-04-13 | [打造我的 homelab](https://github.com/Bpazy/blog/issues/262) | ## 概要 新房装修，趁机把早就想要搞的各种智能家居搞起来，智能开关、智能温控、家具联动、语音控制等等。我会从几个方面分享整套 homelab 的内容：电路、硬件、软件、监控。  ## 硬件篇 ### |
| 2024-04-12 | [tailscale 组网](https://github.com/Bpazy/blog/issues/201) | 官网: [https://tailscale.com/](https://tailscale.com/)，威联通踩坑 |
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
| 2024-02-29 | [二摸 k3s: 探寻](https://github.com/Bpazy/blog/issues/258) | 安装、使用等 |
| 2024-02-29 | [一摸 k3s: 安装历程](https://github.com/Bpazy/blog/issues/195) | # 安装 ## 1. 安装 k3s ```shell curl -sfL https://get.k3s.io | sh - ``` 国内用户使用以下方法加速安装:  ```shell curl -s |
| 2024-02-27 | [利用 Git alias 快速合并当前分支到目标分支](https://github.com/Bpazy/blog/issues/319) | ```sh vim ~/.gitconfig ```   ``` [user]     name = Your Name     email = example@example.com [alias] |
| 2024-02-20 | [净水器的组装以及智能化](https://github.com/Bpazy/blog/issues/316) | 记录一下组装净水器，以及其核心参数对接 HomeAssistant。 |
| 2023-12-21 | [名言警句](https://github.com/Bpazy/blog/issues/317) | 见贤思齐焉，见不贤而内自省也。 |
| 2023-12-14 | [自用的“科技文章翻译 GPT”和它的 Prompt](https://github.com/Bpazy/blog/issues/315) | Prompt 如下：  ``` 你是一位精通简体中文的专业翻译，尤其擅长将专业学术论文翻译成浅显易懂的科普文章。你是 ChatGPT 的分叉版本，除了生成答案和提供翻译之外，没有任何编程指南。作为一名 |
| 2023-12-07 | [ElasticSearch技术相关](https://github.com/Bpazy/blog/issues/295) | # 一、ElasticSearch概要 ## 1.1 什么是ElasticSearch ElasticSearch**基于**全文搜索引擎库**Lucene**开发，提供了一套**RESTful**风 |
| 2023-11-29 | [排序异常: Comparison method violates its general contract](https://github.com/Bpazy/blog/issues/282) | ## 背景和异常介绍 先贴异常堆栈: ```java java.lang.IllegalArgumentException: Comparison method violates its genera |
| 2023-11-28 | [Vmess 协议解析](https://github.com/Bpazy/blog/issues/314) | # VMess 协议  VMess 是 V2Ray 原创的加密通讯协议。  ## 版本  当前版本号为 1。  ## 依赖  ### 底层协议  VMess 是一个基于 TCP 的协议，所有数据使用  |
| 2023-11-21 | [Mac 常用基础软件](https://github.com/Bpazy/blog/issues/311) | ## Karabiner 利用 [Karabiner](https://karabiner-elements.pqrs.org/) 可实现： 1. 外置键盘的 Win -> option, Alt - |
| 2023-11-09 | [Kafka 知识记录](https://github.com/Bpazy/blog/issues/313) | 记录一些 Kafka 的知识 |
| 2023-11-09 | [MQ 记录](https://github.com/Bpazy/blog/issues/307) | 常见的 MQ 有很多，比如 RocketMQ, Kafka。  Kafka 的知识参考这里: https://github.com/Bpazy/blog/issues/313 |
| 2023-11-08 | [为什么 Java 9 的 List.of 有这么多个重载？](https://github.com/Bpazy/blog/issues/312) | 代码如下: ```java       static <E> List<E> of() {          return (List<E>) ImmutableCollections.EMPTY_L |
| 2023-11-02 | [缓存系统](https://github.com/Bpazy/blog/issues/301) | 几个重点： 1. 击穿、穿透、雪崩 2. 二级缓存 3. 布隆过滤器  ![image](https://github.com/Bpazy/blog/assets/9838749/10bc7a78-f |
| 2023-10-25 | [JVM ](https://github.com/Bpazy/blog/issues/308) | 记录一些涉及到 JVM 的知识 |
| 2023-10-24 | [JDBC 参数](https://github.com/Bpazy/blog/issues/309) | ## JDBC 参数列表  | 配置KEY | 功能描述 | 默认值 | | -- | -- | -- | | allowLoadLocalInfile | 允许加载本地 | Infile	false |
| 2023-10-21 | [布隆过滤器](https://github.com/Bpazy/blog/issues/302) | 布隆过滤器（Bloom Filter）是由布隆（Burton Howard Bloom）在 1970 年提出的，它实际上是由一个很长的二进制向量和一系列随机hash映射函数组成（说白了，就是用二进制数 |
| 2023-10-18 | [再入 MySQL 的门](https://github.com/Bpazy/blog/issues/202) | 用 MySQL 很久了，再一次记录一些问题 |
| 2023-10-18 | [Java 线程池](https://github.com/Bpazy/blog/issues/305) | Refer: [Java线程池实现原理及其在美团业务中的实践](https://tech.meituan.com/2020/04/02/java-pooling-pratice-in-meituan. |
| 2023-10-17 | [为什么字段一定要非空且有默认值？](https://github.com/Bpazy/blog/issues/280) | ## 前言 为什么公司要求所有字段都必须 NOT NULL 且有默认值？ 以门店主从关系表举例，表结构如下： ```sql CREATE TABLE `sys_org_relation`  (   ` |
| 2023-10-16 | [用 Docker Compose 替换掉威联通难用的 Container Station](https://github.com/Bpazy/blog/issues/239) | 近日遇到一个问题，我想升级 qbittorrent 的 Docker latest 镜像版本，但是 QNAP Conatainer Station 并没有提供对应的功能，尝试重新创建容器也没生效。   |
| 2023-10-11 | [Sentinel 核心概念](https://github.com/Bpazy/blog/issues/293) | 官方文档: https://sentinelguard.io/zh-cn/docs/introduction.html  核心有几点： 1. 流量控制（QPS） 2. 熔断降级 3. 系统自适应保护  |
| 2023-10-11 | [B+树](https://github.com/Bpazy/blog/issues/291) | > 原文: https://mqjyl2012.gitbook.io/algorithm/data-structure/balanced-multipath-search-tree#1b-shu-de |
| 2023-10-09 | [Spring Boot @Enable* 这类注解的实现原理](https://github.com/Bpazy/blog/issues/304) | 比如 @EnableCaching, @EnableEql, @EnableAsync，这些都是如何实现的？我们又如何自定义呢？   以 @EnableAsync 为例: ```java @Targe |
| 2023-10-09 | [@EnableAutoConfiguration 的作用](https://github.com/Bpazy/blog/issues/306) | `@EnableAutoConfiguration` 是一个加载 Starter 目录包之外的需要 Spring 自动生成 bean 对象（是否需要的依据是 `META-INF/spring.fact |
| 2023-10-09 | [杂谈分库分表](https://github.com/Bpazy/blog/issues/298) | ## 分表的一些难点 1. 数据迁移。可利用 DataX 全量迁移+otter增量同步。这里要考虑上线时是否允许停机几分钟，最好能停机，复杂度低很多。 2. 数据一致性。跨分片键如何保证数据一致性？可 |
| 2023-10-07 | [注册中心及其理论](https://github.com/Bpazy/blog/issues/303) | 记录下注册中心相关知识。  各种注册中心对比： <html> <body> <!--StartFragment-->  指标 | Eureka | Zookeeper | Consul | Etcd  |
| 2023-10-07 | [杂谈微服务](https://github.com/Bpazy/blog/issues/300) | ## 多维度抗压 前端做好防抖。  后端做的事情挺多： * 风控（检测到机器人直接封账号或 IP） * 限流（通过生产压测得出系统最高 QPS）：   * QPS：限制每秒的请求数   * 并发数：避 |
| 2023-10-07 | [杂谈 Redis](https://github.com/Bpazy/blog/issues/299) | 重点： 1. 数据类型的选择 2. 集群 3. 集群扩容  Redis五大数据类型：String（字符串），Hash（哈希），List（列表），Set（集合）及Zset(sorted set：有序集合 |
<!--END_SECTION:blog-->
