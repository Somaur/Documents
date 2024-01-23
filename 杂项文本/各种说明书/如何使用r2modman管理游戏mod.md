# 如何使用r2modman管理游戏mod（以《致命公司》/Lethal Company为例）

## 介绍

r2modman是一个优秀的mod管理工具，和游戏mod网站thunderstore.io一同提供了方便的mod游玩体验。

最初，r2modman和thunderstore.io都是为了游戏《Risk of Rain 2》的mod管理而创建的工具和平台。如今，它们已经包括了许多其他游戏的mod，包括现在（2024/01/23）火爆的《致命公司》（Lethal Company）。

## 快速上手流程

0. 在Steam上购买并安装《致命公司》

1. 安装r2modman
   - 可以安装到任意路径，r2modman会自动寻找steam的相关路径。

2. 进入r2modman，选择游戏Lethal Company
   - 这一步r2modman会拉取云端的可用mod列表，如果网络有问题可能会发生卡顿。
   - 即使拉取失败也会进入后续界面，是否拉取成功请在后续的Settings-Other-Refresh online mod list中确认拉取的时间。

3. 选择模组配置（默认配置Default）。
   - 点击列表中的项即是选择，"Select profile"会让你进入下一个界面
   - 可以任意新建配置

4. 在"Import/Update"中选择任意一项，然后选择使用代码导入（From Code），输入`018ca0be-06c9-5099-078f-c2a8ba668c22`完成导入
   - 这里输入的代码是其他玩家生成的。每个玩家都可以将自己的mod配置生成对应的代码进行分享，这使得多人联机时统一mod十分方便。

5. 点击"Select profile"进入游戏界面。

6. 点击"Start modded"，r2modman将在添加mod之后打开游戏。
   - steam相关功能，比如邀请好友仍然可用。

如果想要返回之前的界面

- 选游戏界面：Settings-Other-Change game

- 选模组配置界面：Setting-Profile-Change profile

## 游戏选择界面
