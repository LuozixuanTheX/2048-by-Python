# 2048的Python3实现

此代码是参考的另一位开发者的代码，在之基础上进行改进之后的成品。

由于时间隔得久，而且当时是直接下载的源代码而不是clone的，所以目前找不到那位原作者的Gihub地址了，但是依旧要在此声明并表示感谢。

此程序没有GUI，只能在控制台中使用，后期可能会添加GUI，但是也只是可能，毕竟我觉得Python没有什么好的开发游戏的工具。如果真的要写GUI，我可能会更偏向于使用Lua + Cocos重写。

## 改进之处

* Bug修复
	* 修复了例如有一行四个2，向左或向右划之后只能把前两个2相加的Bug
	* 修复了划了但是在划不动的情况下依旧会产生新的2或4的Bug
* 增加了回退一步的功能
* 逻辑调整
* 把代码格式调整成规范形式
* 删除所有的Debug代码
* 其他细节改进

## 使用的Python版本：3.5.1

## 使用的库

使用的标准库：random, copy

没有使用第三方库

## 协议： MIT
