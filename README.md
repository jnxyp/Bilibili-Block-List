# BilibiliBlockList
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">BilibiliBlockList</span> 由 <a xmlns:cc="http://creativecommons.org/ns#" href="https://blog.jnxyp.tk/" property="cc:attributionName" rel="cc:attributionURL">Jn_xyp</a> 创作，采用 <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">知识共享 署名-非商业性使用 4.0 国际 许可协议</a>进行许可。

本计划部分规则参考自 Thiece 和 BlackGlory 编写的屏蔽列表，十分感谢。

<a href="http://deerchao.net/tutorials/regex/regex.htm">正则表达式30分钟入门教程 作者：deerchao</a>

我下周（2017.7.3-2017.7.9）一定更新！保证更新！！！！嗯一定会更的！！！
====================================================================


更新：预发布0.9.100版本
====================================================================
已经跟进B站播放器最新版本，新发布的屏蔽列表同时支持Html5和Flash播放器，直接使用即可。

介绍
====================================================================
以下所出现【弹幕】一词，均指 在弹幕视频网站Bilibili上的视频中，漂浮在视频上方的评论 。

本计划是以B站播放器的正则屏蔽系统为核心，通过正则表达式+关键词的方法对于无意义弹幕，谩骂弹幕和影响观看体验的弹幕进行屏蔽。
本计划产物是以XML文件形式储存的屏蔽规则，使用方法为在B站视频播放器中找到[屏蔽设定]>[屏蔽列表]，并在列表空白处单击右键并选择已下载的XML文件进行导入。该XML文件使用UTF-8编码，可使用任意支持该编码的文本编辑器对规则进行编辑。

本计划之产物分为两类：
1.基础屏蔽列表（版本B）：对于完全无意义弹幕，包含谩骂、歧视、色情内容的弹幕。
2.进阶屏蔽列表（版本P）：在基础屏蔽列表的基础上，对于本列表作者主观认为的影响观看体验的或者无意义的或者低素质的弹幕进行屏蔽。

本计划产物遵循【知识共享署名-非商业性使用 4.0 国际许可协议（CC-BY-NC-4.0）】进行许可：
任何人可以在任何媒介以任何形式复制、发行本作品或者修改、转换或以本作品为基础进行创作。
惟须遵守下列条件：【署原作者名（Jn_xyp&Thiece&BlackGlory）】并【非商业性使用】。

使用方法
====================================================================
1.下载本计划中的最新版[Latest]屏蔽列表XML文件。

2.打开B站任意视频，点击【屏蔽设定】

3.点击【屏蔽列表】选项卡

4.在下方空白处单击右键，选择【导入XML文件】

5.选择下载的弹幕屏蔽规则，点击导入

6.点击【高级屏蔽】选项卡

7.在自定义屏蔽中，开启【启用屏蔽】和【优化屏蔽】（另建议开启【UP主屏蔽】）

<img src="https://pic1.zhimg.com/435ef942d295f1fde85bea002a22e528_b.png" alt="如何开启【UP主屏蔽】和【优化屏蔽】">

8.成了( •̀ ω •́ )y

如果还是不会↓

<a href="http://blog-thiece-cn-static.smartgslb.com/wp-content/uploads/2013/11/bilibili.gif">GIF使用方法演示（从thiece网站顺来的）</a>
