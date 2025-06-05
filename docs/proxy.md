---
sidebar_position: 2
title: 代理服务器
sidebar_label: 代理服务器
description: 初入窥见星月夜的velocity群组服
---

import Tabs from '@theme/Tabs';

import TabItem from '@theme/TabItem';

| 服务器       | 地址                   | Java端口 | 基岩端口 |
| :---------: | :--------------------: | :---: | :---: |
| 宁波电信     | fhafm.fun              | 25565 | 19132 |
| 宿迁蒲公英BGP | 2666v3.mc5173.cn      | 25565、25566 | 19132、19133 |
| 上海阿里云BGP | zaku.ltd              | 25565 | 19132 |
<details>
  <summary>速览MOTD</summary>

  |                                    Java Edition                                    |                                        Bedrock Edition                                         |
  |:----------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|
  |          ![fhafm.fun:25565 ](https://mcapi.us/server/image?ip=fhafm.fun)           |        ![fhafm.fun:19132](https://motdbe.blackbe.work/status_img?host=fhafm.fun:19132)         |
  | ![2666v3.mc5173.cn:25565](https://mcapi.us/server/image?ip=2666v3.mc5173.cn:25565) | ![2666v3.mc5173.cn:19132](https://motdbe.blackbe.work/status_img?host=2666v3.mc5173.cn:19132)  |
  | ![2666v3.mc5173.cn:25566](https://mcapi.us/server/image?ip=2666v3.mc5173.cn:25566) | ![2666v3.mc5173.cn:19133](https://motdbe.blackbe.work/status_img?host=2666v3.mc5173.cn:19133)  |
  |           ![zaku.ltd:25565 ](https://mcapi.us/server/image?ip=zaku.ltd)            |         ![zaku.ltd:19132](https://motdbe.blackbe.work/status_img?host=zaku.ltd:19132)          |

</details>

星月夜Minecraft服务器全部使用velocity作为代理端，将多个服务器连成一个整体(比如创造服、生电服、小游戏服、跑酷服)，玩家可以自由选择到哪个服务器，而不用退出重连。

但是，不同代理端的中不同子服的玩家聊天消息和玩家列表不可见。

所有代理端都安装了Geyser、Viaversion、Viabackwards、Simple Voice Chat等插件，提供基岩版的玩家和不同Java版本的玩家同时在线游玩，但是并不是所有代理端的插件都一样。宁波代理端使用稍微老旧与稳定的插件版本，而宿迁的使用最新与不稳定的插件。如果您发现更新到了最新Minecraft之后无法连接登录服务器，也许可以尝试宿迁的服务器。

<Tabs>
  <TabItem value="Ningbo-Telecom" label="宁波电信">
    峰值上行300M，每月限流1TB，用完停机，稳定不丢包。

    新服务器测试中，此节点可能无法连接。
  </TabItem>
  <TabItem value="Suqian-BGP" label="宿迁蒲公英BGP">
    上行30M下行80M\
    总是被攻击，你不用管他，自己也会炸掉的服务器。

    25566端口不支持UDP，无法使用SVC插件。
  </TabItem>
  <TabItem value="Shanghai-Aliyun-BGP" label="上海阿里云BGP">
    峰值200M，每天限流20GB，用完限速，无法长时间容纳多人玩。\
    随时可能挂掉，挂了就换别的节点。
  </TabItem>
</Tabs>
