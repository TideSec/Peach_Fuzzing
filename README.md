在学习使用peach进行模糊测试时，搜集到的一些不错的资料，以及配套的一些软件或脚本。

根据这些大佬的经验和资料，研究了peach的原理、框架和配置使用，记录了一篇学习心得《使用peach进行模糊测试从入门到放弃》``

1、比较推荐的资料是《peach框架模糊测试英文文档》，这是官方指南，最权威的peach使用解读。

2、peach文件夹中包含了收集到的4个版本的peach最新版软件包，分别为windows版（x86）、windows版（x64）、oxs版、linux版、python版。

3、modbus协议仿真-采集软件为工控协议modbus的仿真采集软件。

4、peach案例文件夹中是网上找到的两个peach案例，利用peach发现easyfileshare和vulnserver的溢出漏洞，给出了pit文件及最终的 poc脚本。

5、pit-xml-samples是《使用peach进行模糊测试从入门到放弃》文中涉及的几个xml文件。


详细目录如下：

```
├── peach
│   ├── peach-3.1.124-linux-x86_64-release.zip
│   ├── peach-3.1.124-osx-release.zip
│   ├── peach-3.1.124-win-x64-release.zip
│   ├── peach-master_python.zip
│   └── windbg.rar
├── peach案例
│   ├── easyfileshare
│   └── vulnserver
├── pit-xml-samples
│   ├── HelloTide.xml
│   ├── httpfuzz.xml
│   ├── httpfuzz1.xml
│   └── modbus.xml
├── modbus协议仿真-采集软件
│   └── modbus仿真+采集.zip
├── 其他参考及论文资料
│   ├── Peach对Modbus功能码的模糊测试 · Uknow - Stay hungry Stay foolish.pdf
│   ├── 基于Peach的协议测试设计与实现.pdf
│   ├── 工控网络协议模糊测试：用peach对modbus协议进行模糊测试 - FreeBuf互联网安全新媒体平台.pdf
│   ├── 浅析Peach Fuzz _ 绿盟科技博客.pdf
│   ├── 浅析Peach-Fuzz.pdf
│   └── 深入探究文件Fuzz工具之Peach实战 - FreeBuf互联网安全新媒体平台.pdf
└── 官方文档及翻译
    ├── peach框架模糊测试英文文档.zip
    └── 智能模糊测试工具Peach Fuzzer官方文档翻译.pdf
```

对模糊测试或工控安全感兴趣的小伙伴可以关注团队官网: http://www.TideSec.net 或关注公众号：

<div align=center><img src=images/ewm.png width=30% ></div>

