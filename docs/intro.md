---
sidebar_position: 1
title: 快速开始
sidebar_label: 快速开始
description: 快速学会加入并游玩星月夜服务器
---

import Tabs from '@theme/Tabs';

import TabItem from '@theme/TabItem';

----

<details>
  <summary>全部服务器地址</summary>

  | 服务器       | 地址                 | Java端口 | 基岩端口 |
  | :---------: | ------------------- | :---: | :---: |
  | 上海阿里云BGP | zaku.ltd            | 25565 | 19132 |
  | 宁波电信     | fhafm.fun            | 25565 | 19132 |
  | 宿迁蒲公英BGP | 2666v3.mc5173.cn    | 25565 | 19132 |

  <details>
    <summary>速览MOTD</summary>

    |                                    Java Edition                                    |                                        Bedrock Edition                                         |
    |:----------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|
    |          ![fhafm.fun:25565 ](https://mcapi.us/server/image?ip=fhafm.fun)           |        ![fhafm.fun:19132](https://motdbe.blackbe.work/status_img?host=fhafm.fun:19132)         |
    | ![2666v3.mc5173.cn:25565](https://mcapi.us/server/image?ip=2666v3.mc5173.cn:25565) | ![2666v3.mc5173.cn:19132](https://motdbe.blackbe.work/status_img?host=2666v3.mc5173.cn:19132)  |
    |           ![zaku.ltd:25565 ](https://mcapi.us/server/image?ip=zaku.ltd)            |         ![zaku.ltd:19132](https://motdbe.blackbe.work/status_img?host=zaku.ltd:19132)          |

  </details>

  :::warning[注意]
  各节点数据并不完全互通，不同代理端的中不同子服的玩家聊天消息和玩家列表不可见。
  
  具体参阅：[代理服务器](/docs/proxy)
  :::

</details>

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
      - [官方启动器（点击查看）](https://www.minecraft.net/zh-hans) - 限制多，功能少，不推荐
      - [网易启动器（点击查看）](https://mc.163.com/) - 限制非常非常非常多，功能非常非常非常不好用，非常非常非常不推荐使用网易版《我的世界》
      
     </details>
    
    <details>
      <summary>其他设备/操作系统</summary>
      
        Java版几乎可以运行在所有设备上，无电脑、手机、掌机甚至是树莓派！这里列举了一些安装方法。
      
      <Tabs>
        <TabItem value="Android/HarmonyOS">
        
         - PojavLauncher启动器\
         下载地址：[Github](https://github.com/PojavLauncherTeam/PojavLauncher/releases)、[ApkPure](https://apkpure.net/pojavlauncher/net.kdt.pojavlaunch)、[SourceForge](https://sourceforge.net/projects/pojavlauncher.mirror/)、F-Droid
        
        </TabItem>
        <TabItem value="iPhone">
        
          - PojavLauncher启动器\
          下载地址：爱思助手
        
        </TabItem>
        <TabItem value="MacOS">
        
          😲😲😲😲😲没有写
        
        </TabItem>
        <TabItem value="ArchLinux">
          
          HMCL启动器
          ```bash
          yay -S hmcl
          ```
        
        </TabItem>
        <TabItem value="Ubunu">
        
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
      <TabItem value="Android" label="安卓/HarmonyOS">
      
        - [Liteapks.com](https://Liteapks.com)
        
      </TabItem>
      <TabItem value="iPhone" label="苹果">
        
      </TabItem>
      <TabItem value="Windows" label="Windows">
        
      </TabItem>
      <TabItem value="MacOS" label="MacOS">
        
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

    ![Java版加入多人游戏示例](./Join_MutiGame.gif)
  </TabItem>
  <TabItem value="BE" label="基岩版">
    1. 登录`微软账号`(已登录可忽略)
    2. 点击`游戏`
    3. 点击右上角`服务器`
    4. 点击`添加服务器`
    5. 在服务器地址一栏输入`zaku.ltd`
    6. 在端口一栏输入`19132`
    7. 点击`添加并开始`
  </TabItem>
</Tabs>

----

## 3.通过人机验证

:::info[如何通过人机验证？]

哈吉梦发誓原版Minecraft**一定**不会出现验证出错的情况！\
但是如果你安装了非法修改客户端的模组，那需要在验证时关闭诸如Fly、Flyboat、AutoClick、Timer、Anti-AFK、Highjump、Farjump此类异常移动、点击的功能

:::

:::info[被自动封禁了？]

每个IP只有**3次验证机会**，耗尽机会暂时**封禁**，过段时间自动解封，**不会永封**。

:::

----

## 4.注册与登录

<Tabs groupId="game-edition">
  <TabItem value="JE" label="Java版">
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
  
    基岩版玩家**首次进入外不需要**手动注册和登录无论是你更改了服务器域名还是IP，并且更改了玩家名也不会丢失玩家档案。
    
    :::
  </TabItem>
</Tabs>

----

## 5.修复皮肤显示(可选)

`/skin <url>` 显示Url处的皮肤
`/skin <玩家名>` 显示指定玩家(正版)的皮肤

## 6.帮助我们

作为一个不知名的小服务器，有很多很多问题。到处都是BUG，帮助我们完善服务器怎么样？或者点击↓↓↓`编辑此页`帮助写文档awa
