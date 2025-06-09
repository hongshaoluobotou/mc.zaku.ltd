---
sidebar_position: 1
title: 快速开始
sidebar_label: 快速开始
description: 快速学会加入并游玩星月夜服务器
---

import Tabs from '@theme/Tabs';

import TabItem from '@theme/TabItem';

import Image from '@theme/IdealImage';

----

:::tip[提示]
兼容Java版 1.13.x-1.21.5，基岩版1.21.50-1.21.90
:::

| 节点         | 地址                 | Java端口 | 基岩端口 |
| :---------: | ------------------- | :---: | :---: |
| 上海阿里云BGP | zaku.ltd            | 25565 | 19132 |
| 宿迁蒲公英BGP | 2666v3.mc5173.cn    | 25565 | 19132 |

<details>
  <summary>速览MOTD</summary>

  |                                    Java Edition                                    |                                        Bedrock Edition                                         |
  |:----------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|
  | ![2666v3.mc5173.cn:25565](https://mcapi.us/server/image?ip=2666v3.mc5173.cn:25565) | ![2666v3.mc5173.cn:19132](https://motdbe.blackbe.work/status_img?host=2666v3.mc5173.cn:19132)  |
  |           ![zaku.ltd:25565 ](https://mcapi.us/server/image?ip=zaku.ltd)            |         ![zaku.ltd:19132](https://motdbe.blackbe.work/status_img?host=zaku.ltd:19132)          |

</details>

:::warning[注意]
各节点数据并不完全互通，不同代理端的中不同子服的玩家聊天消息和玩家列表不可见。

具体参阅：[代理服务器](/docs/proxy)
:::


## 1.安装Minecraft

<Tabs groupId="game-edition">
  <TabItem value="JE" label="Java版">
    
    对于电脑，挑选下列一个启动器使用，结合**网页**与**搜索引擎**指引你完成Minecraft的安装
     - [HMCL启动器（点击查看）](https://hmcl.huangyuhui.net/download/) - 兼容性最好的启动器
     - [PCL2启动器（点击查看）](https://www.himcbbs.com/resources/pcl-ce/) - 广受好评的启动器
     - [MCSL2启动器（点击查看）](https://v2.mcsl.com.cn/) - 跨平台的新一代启动器
     
     <details>
      <summary>其他启动器（暂不推荐）</summary>
      
      - [Modrinth App（点击查看）](https://modrinth.com/app) - 新一代跨平台高颜值全英文的启动器
      - [官方启动器（点击查看）](https://www.minecraft.net) - 限制多，功能少，不推荐
      - [网易启动器（点击查看）](https://mc.163.com/) - 限制非常非常非常多，功能非常非常非常不好用，非常非常非常不推荐使用网易版《我的世界》
      
     </details>
    
    <details>
      <summary>其他设备/操作系统</summary>
      
        Java版几乎可以运行在所有设备上，无电脑、手机、掌机甚至是树莓派！这里列举了一些安装方法。
      
      <Tabs>
        <TabItem value="Android/HarmonyOS">
        
         - PojavLauncher【下载地址：[Github](https://github.com/PojavLauncherTeam/PojavLauncher/releases)、[ApkPure](https://apkpure.net/pojavlauncher/net.kdt.pojavlaunch)、[SourceForge](https://sourceforge.net/projects/pojavlauncher.mirror/)】
         - FoldCraftLauncher（即将停止维护）【下载地址：[国内加速](https://foldcraftlauncher.cn/?debug#tab2)、[官网](https://foldcraftlauncher.com)、[Github](https://github.com/FCL-Team/FoldCraftLauncher/releases)、[爱发电](https://alist.8mi.tech/FCL)】
        
        </TabItem>
        <TabItem value="iPhone">
        
          - PojavLauncher启动器\
          下载地址：爱思助手
        
        </TabItem>
        <TabItem value="MacOS">
        
          😲😲😲😲😲没有写
        
        </TabItem>
        <TabItem value="Arch Linux">
          
          HMCL启动器
          ```bash
          yay -S hmcl
          ```
        
        </TabItem>
        <TabItem value="Ubuntu Linux">
        
          😲😲😲😲😲没有写
        
        </TabItem>
      </Tabs>
    </details>
  </TabItem>
    
  <TabItem value="BE" label="基岩版">
  
    :::warning[注意]
    
    你需要安装国际版《我的世界》而不是网易版《我的世界》
    
    :::
    
    <Tabs className="unique-tabs">
      <TabItem value="Android/HarmonyOS">

        - [mcapks.com（点击查看）](https://mcapks.com/) - 官方国际版安装包下载，历史版本非常齐全
        - [liteapks.com（点击查看）](https://liteapks.com/minecraft.html) - 仅有最新几个版本下载，部分是破解版还有的自带外挂
        <details>
          <summary>更多地址</summary>

           - [Minecraft官网（点击查看）](https://www.minecraft.net/zh-hans/download)
        </details>
        
      </TabItem>
      <TabItem value="iPhone">

        😲😲😲😲😲没有写
        
      </TabItem>
      <TabItem value="Windows10">

        - [mcappx.com（点击查看）](https://www.mcappx.com/) - 官方原版Minecraft，包含正版验证机制，如果你没有购买 Minecraft，将只能游玩体验版或不能进入游戏。
        <details>
          <summary>破解方法</summary>

           - [bilibili](bilibili.com/video/BV1eh4y1u7Nu)
        </details>
        <details>
          <summary>更多地址</summary>

           - [微软官方启动器](https://www.xbox.com/zh-cn/games/store/minecraft-launcher/)
        </details>
        
      </TabItem>
      <TabItem value="MacOS" label="MacOS">

        😲😲😲😲😲没有写
        
      </TabItem>
    </Tabs>
  </TabItem>
</Tabs>

----

## 2.加入多人游戏

<Tabs groupId="game-edition">
  <TabItem value="JE" label="Java版">
    
    1. 点击`游戏菜单`
    2. 点击`多人游戏`
    3. 点击`添加服务器`
    4. 在服务器地址一栏输入`zaku.ltd`
    5. 点击`完成`
    6. 双击新增的服务器或者单机加入服务器。

    <Image img={require('./Join_MutiGame.gif')} alt="Java版加入多人游戏示例" />

  </TabItem>
  <TabItem value="BE" label="基岩版">
    
    😲😲😲😲😲没有写
    
  </TabItem>
</Tabs>

----

## 3.通过人机验证

:::info[如何通过人机验证？]

哈基梦发誓原版Minecraft**一定**不会出现验证出错的情况！\
但是如果你安装了非法修改客户端的模组，那需要在验证时关闭诸如Fly、Flyboat、AutoClick、Timer、Anti-AFK、Highjump、Farjump此类异常移动、点击的功能

:::

:::info[被自动封禁了？]

每个IP只有**3次验证机会**，耗尽机会暂时**封禁**，过段时间自动解封，**不会永封**。

:::

----

## 4.注册与登录

<Tabs groupId="game-edition">
  <TabItem value="JE" label="Java版">


    <Image img={require('./Register.gif')} alt="Java版注册账号示例" />
  
    | 操作 | 命令格式 | 示例1 | 示例2 |
    | :--: | ---- | ---- | ---- |
    | 注册 | `/reg <3到28位密码> <重复输入密码>` | `/reg nahida_meow nahida_meow` | `/reg 123 123` |
    | 登录 | `/l <密码>` | `/l nahida_meow` | `/l 123` |
    
    :::danger[危险]

    不要直接复制示例，不要把`123`和`nahida_meow`当成你的密码！

    :::
    
    :::warning[注意]

    Java玩家唯一标识码`UUID`统一使用离线生成方案，无论你是正版用户、第三方认证用户、离线用户都使用同一算法，因此更改用户名会丢失玩家档案。

    :::
    
    :::tip[忘记了密码？]

    密码加密储存于服务器，管理员无法解密和获取真实密码。但你可以找管理员注销你的密码，然后重新注册，这不会丢失你的玩家档案。

    :::
  </TabItem>
  <TabItem value="BE" label="基岩版">
    :::tip
  
    基岩版注册和登录是全自动的，可以一直不管它。你无论是用WIFI还是流量玩还是修改了名字、手动注销了账号，你的玩家档案和背包都会一直留着不删。
    
    :::
  </TabItem>
</Tabs>

----

## 5.优化游戏体验（可选）

  ### 服务器

  如果你是离线玩家，你可以使用指令自定义你的皮肤：`/skin <url>`，让其他玩家看到你的可爱！

  ### 客户端

  |    MOD    |         介绍      |                             下载地址                                  |
  | :------: | ------------------- | ------------------------------------------------------------------- |
  | baritone | Minecraft中的高德地图 | [GitHub](https://github.com/cabaletta/baritone/releases) 、[meteorclient.com](https://www.meteorclient.com/api/downloadBaritone)|
  |  meteor  | 也称彗星端，是外挂模组 | [本站直链(fabric-1.21.5)](/meteor-client-1.21.5-local.jar)、[bilibili（汉化版）](https://www.bilibili.com/video/BV1KE4m1d7U4/)、[GitHub（需要手动构建）](https://github.com/MeteorDevelopment/meteor-client) |

  :::warning

  安装模组时请确保模组没有被植入后门！在安装未知的模组时请确保可信！
  
  :::

## 6.帮助我们

作为一个不知名的小服务器，有很多很多问题。到处都是BUG，帮助我们完善服务器怎么样？或者点击↓↓↓`编辑此页`帮助写文档awa



<details>
  <summary>110900280_p0.png</summary>

  <Image img={require('./110900280_p0.png')} alt="110900280_p0.png" />
</details>
