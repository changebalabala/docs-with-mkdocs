## 手残开启作弊后如何自救

我们知道开启作弊后是无法记录成就的，但有时偏偏就不小心手滑，瞬间感觉地图毁了，但还是微软爸爸还是给我们留下了机会：

!!! warning classes

 	为防止无法预测的意外，请备份原存档:exclamation:

+ 新开一个相同种子的地图，种子可以在原地图设置界面查看，此时就***别开作弊***了

+ 找到新地图的目录，众所周知Minecraft携带版（现已升级为基岩版）的存档目录在：
  `/games/com.mojang/minecraftWorlds/`

+ 将新地图的存档内的`db`文件夹拷贝到手残开启作弊的存档文件夹

+ 在移动端基岩版`1.12.2`测试通过，其他版本自测

## Win 10 基岩版无法登录微软账号

**报错信息**：打开Win 10 Minecraft ，点击登录，弹出窗口显示`我们尝试登陆过你的 Microsoft 账户，但出现了问题`

**原因分析**：系统不完整，Xbox组件丢失

**解决方法**：在**Microsoft Store**下载 **Xbox Console Companion** 和 **Xbox Identity Provider** 等组件

如果无法下载，请点击这里：[Xbox组件](https://www.lanzous.com/i9lyv3i)

## Win10 基岩版存档位置

`C:\Users\登录用户名\AppData\Local\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang`

## BTR编辑器食用指南

此部分内容适用于游戏后期，简化游戏难度，提高游戏趣味。

### 世界NBT

+ `NetherScale`：**主世界与地狱的比例**，默认为 8 ，后期用于地狱交通可做适当修改；
+ `SpawnX，SpawnY，SpawnZ`：**世界出生点**，若后期有新玩家加入，修改此坐标，可简化新玩家跑图难度，对新玩家极具友好性；
+   `keepinventory`：**死亡不掉落**，大后期不开死亡不掉落，死一次直接想删游戏，手残党务必开启，头铁和肝帝请无视；
+ `mobgriefing`：**生物破坏**，不嫌麻烦可无视，当然，有伪和平也不至此；

