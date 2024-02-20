## BuzzerBeater文字直播分析器

### 功能

在BuzzerBeater比赛的文字直播界面（仅限简体中文），通过分析直播文字，提供比官方赛后数据统计更细分或高阶的数据：

1. 进攻端细分数据，如投篮分布（区分内线和中距离）、干扰下投篮、接球攻投篮、传球转化率；

2. 防守端数据，如干扰对方投篮；

3. 高阶数据，如真实命中率、球权使用率、助攻率、篮板率、失误率。

<img src="https://github.com/AtomicNucleus029/BB-PBP/assets/160561545/1eb98c2b-ffd9-4c65-ab46-d1a524354dc5" width = 500>

### 安装

和Buzzer Manager的脚本类似，添加BuzzerBeater_PBP_Analyzer.js至浏览器的TamperMonkey中即可（IE暂不支持）。

也可以通过[https://greasyfork.org/zh-CN/scripts/487785-buzzerbeater-pbp-analyzer](https://greasyfork.org/zh-CN/scripts/487785-buzzerbeater-pbp-analyzer)进行添加。

### 关于接球攻

BuzzerBeater的中文化团队文采斐然，为文字直播增添了许多乐趣。相比之下，英文版的解说词就显得平淡许多。但是，中文版增添的细节有时和英文版存在一些出入。比如“A在三分线外接球，直接三分出手”这一句，容易让人以为这是一次接球攻。但是，同一个动作在英文版中就只有“A三分出手”，没有那么多其他描述。

实际上，英文版的投篮一共只有两种描述模板：

1. A在某位置出手；
2. A传球给B，B在某位置出手。


