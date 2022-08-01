# Free Fire 体验报告
## 1.相关游戏经历

我比较熟悉的相关游戏是彩虹六号、战地5等PC上的FPS游戏，有短暂地游玩吃鸡手游的经历（香肠派对、和平精英）。彩六里我算是一个老油条，但在手游FPS和吃鸡我非常菜，可以算半个萌新。这样的区别主要是由于键鼠和触屏的操控不同导致的。

## 2.主要流程体验

* 新手期（Lv.6以下）感觉几乎遇不到真人（结合人机很EZ，显得略微枯燥😀）
* BOT行为过于简单
  * BOT几乎都是**站在原地射击**（可改进部分BOT的行动策略，如换弹时躲进掩体）
  * BOT受伤后，即便在空旷的地区也使用逃跑策略，结果就是**一旦开始逃跑必死无疑**（让BOT趴下或蹲下，我几乎没有见到过蹲下的人机）
* 教程引导不够清晰，以下列出一些教程没有教清楚或者我觉得普通玩家很难意识到的一些问题：
  * **贴墙阻挡**。我注意到了在玩家靠近建筑物时会在屏幕中央显示**红色的小圆点**，刚开始我认为这是系统提供的敌人透视，即，当你发现敌人并且在掩体后射击时游戏自带的微型透视。事实上这是一个玩家贴墙被阻挡了开火的提示，由于游戏是第三人称视角，玩家摄像机和人物之间有**视角差异**，这意味着玩家看得到的区域不一定能打得到，而这个红点指出了玩家受到阻挡后开火将击中的位置（就是墙上）。我提出一些改进建议：
    + 参照一些经典大作的做法（大概是辐射4、地铁这样的游戏），人物靠近物体被挡住将会把枪向下收起，并且不会开火（改进的好处是可以清晰地表现玩家被阻挡、取消红点显示解除误会，坏处是需要额外制作骨骼动作，有一定的成本）。
    + 可以让玩家的准星颜色变化来提示阻挡，增加游戏设置“被掩体阻挡时自动禁用武器”。
* 人头挡视野。玩家的视角是从角色右肩跨过的，所以大多数玩家都会选择从掩体的右侧出击，因为这样他们有视角优势，相反，从左侧看有玩家人物挡住视野，离开掩体和射击更加危险。这一点也可以从“我的战场”模式的空白平坦地图里看出：双方玩家几乎都是逆时针在地图上周旋。改进建议：参考质量效应：仙女座的做法，它允许玩家按下按键切换左跨肩、右跨肩来应对不同情况。

## 3.武器体验
* 第一感觉是不好选择合适的武器。首先是枪械的特性难以快速把握，需要学习（比如蓄力霰弹枪需要蓄力松开才能开火，我因此白给了几局才明白），原先我觉得一些武器我比较熟悉，但显然，不同游戏的同名武器仍然是不一样的。（P90有70发，我兴奋地拿去对枪一梭子就中了几枪😢），建议：在训练场里加入一些图文指引，给出更多的数据，比如距离衰减，弹道散布，后坐力。
* 瞄准镜自动锁敌迷惑。一些武器开镜会自动锁定敌人，但是这个作用范围很难把握，有时觉得视角里可以锁到敌人于是开镜但实际并没有，很快啊，啪地一下就被对死了。建议：给这个锁敌范围一个提示或者可以让瞄准镜高亮。

* 自动瞄准力度过大了，容易锁到身体，很难打到头
* 大多数武器在贴身距离内很难击中敌人
* 对枪模式的飞刀武器在训练场是没有的
* 对枪模式是一个练习战斗技巧的场所，或许应该增加类似经典模式中的房屋、工厂地图供玩家练习。

## 4.凝胶护盾

* 玩家用三个凝胶护盾可以把自己完全包裹起来，针对这种玩家应该使用手雷等道具，但是目前看来使用倾向使用手雷投掷物、熟练使用手雷的玩家较少。可能是手雷等投掷道具还不够好用。
* 偶尔护盾会放置在护盾的上方，并且往往与下方的护盾形成十字形，这导致护盾之间容易产生间隙。
* BOT不太会使用凝胶护盾，他们在放置凝胶护盾后仍然向目标敌人移动，然后被凝胶护盾挡住。

## 5.大厅

* 进入“我的战场”、“房间”等按钮太小，而且和模式选择的“我的战场”同名。比较混乱。
* “我的战场”条目下有“房间”，而在模式选择中也有“房间”，目测是同一个“房间”。比较重复混乱。
* 选择队伍模式的按钮和游戏模式的按钮连在一起，有一定的误导性。或许应该分开。
![“训练岛”和模式选择按钮](./%E6%A8%A1%E5%BC%8F%E6%8C%89%E9%92%AE.png)

## 6.编辑器
> 编辑器不要BUG太多！不BUG多叫编辑器吗？
* 编辑器的拍照按钮应该可以再次点击来关闭，而不是原按钮无效、在右上角显示关闭。
  
* 复活传送等指令图标提示不明确。
  ![](./%E5%9B%BE%E6%A0%87%E6%8C%87%E7%A4%BA%E4%B8%8D%E6%98%8E%E7%A1%AE.jpg)
* 可不可以有对称建造功能。
* 不能跨物体复制脚本。
* 反复写函数很麻烦。或许可以把脚本和物体分离、允许玩家全局保存、互相分享自制函数、脚本。
* 函数和变量不能修改，只能删除，使用比较吃力。
* 调试准备时间15秒太长了。
* BUG：
  * 图元菜单有指针穿透的问题。
  * 编组界面逻辑混乱。
  * 编组物体有时可以与其它物体重合（即使没有开启物体重叠）。
  * 在接近顶层的位置可以放置超出高度限制的物体，但在运行时会被强制下移，也没有提示，会造成困扰。
  * 选中并移动物体后撤销图标和删除物体图标一致，有误导性。
  * 管理对象（文件夹按钮）没有实时更新物体名称
  * 编组后选取高亮显示错误，猜测是当选取准星离开一组物体时，只有那个准星离开的高亮的物体被取消高亮，组内其余物体没有变化。
  * ![](./%E7%BC%96%E7%BB%84%E9%AB%98%E4%BA%AE%E6%8F%90%E7%A4%BA%E6%9C%89%E9%94%99%E8%AF%AF.jpg)
  * 一些未知的BUG，有时自定义触发器会消失。

## 7.次要的问题
> 非常容易解决、可能没必要解决或者解决不了
* 这个凝胶护盾是不是有一点点点点丑
* 瞄准镜准星似乎有一圈发光有点挡视野，以及让我觉得比较粗糙
* 训练岛人偶UI重叠了
    ![“训练岛”和模式选择按钮](./UI%E9%87%8D%E5%8F%A0.jpg)
* 偶尔会跳到窗户上卡住而不是翻过去。
* 编辑器内，层级和箱子有重叠的面且争夺显示。
