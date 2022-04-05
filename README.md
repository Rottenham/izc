# IZE血量计算器 V1.5.4
 
 
## 使用说明

本计算器适用于IZE单破血量的计算，支持英文原版与汉化第二版。

模拟算血时，不会考虑其他路的杨桃、三线或磁铁（倾斜主题除外）。同时，默认土豆已引爆、窝瓜已引走、大嘴已填饱。可以计算多玉米算血。

显示结果时，带有括号的代表【不推荐】，加粗并高亮的代表【推荐】。

撑杆算血：计算撑杆跳过第一个非地刺、非窝瓜植物后所受伤害。
【推荐】的情况：算血不超过15。
【不推荐】的情况：被跳过的植物是裂荚、杨桃或向日葵，或算血超过39。

慢速算血：计算路障或铁桶所受伤害。
【推荐】的情况：算血不超过25，或算血不超过61且当前行无磁铁。
【不推荐】的情况：算血超过72。

梯子算血：计算梯子所受伤害（饰品+本体）。饰品掉落后，所有伤害转移至本体上。
【推荐】的情况：本体算血不超过14，且当前行无磁铁。
【不推荐】的情况：当前行有磁铁，或本体算血超过19。

橄榄算血：计算橄榄所受伤害。
【推荐】的情况：算血不超过76且当前行无磁铁。
【不推荐】的情况：当前行有磁铁，或算血超过84。

撑杆梯子算血：计算先放撑杆，落地后放梯子时梯子所受的伤害。
推荐/不推荐标准同梯子。

注：
算血公式见cv6263782。此程序的计算结果完全基于分段算血公式，不等同于实际游戏情况；其计算结果均可用计算器手动验算。


## 关于作者

这是一个用于计算IZE单破血量的计算器。

版本号: v1.5.4

开发者: Crescendo

bilibili: Crescebdo

贴吧: Crescendo

使用工具: Visual Studio 2019, wxWidgets 3.1.4
