# rime-kappajp86
rime-河童日文五笔方案

（1）输入汉字

本输入法采用86版五笔字型的方式输入汉字。

分号、冒号选第二三候选词。

特别需要注意的地方：

1.本输入法的简码字因应日语常用字而作出了改动，这可能会导致您刚开始使用的时候需要一段时间来熟悉简码方案。本输入法存在以下三个无理简码：

私   q

有   e

不   i

2.由于日文字与中文字存在差异，会产生以下几种编码问题：

1)中・日文字体不同所产生的差异

本输入法的候选界面采用日文字体 MS Mincho ，内码相同的一个字在中文字体与日文字体下的显示有可能不同。如「害」字，在日文字体中，中间的部分是青字头，而非中文字体下的「丰」，由此产生的编码差异，作者并没有对其作出编码的更改，完全沿用86五笔原来编码,通过练习练成条件反射便可适应。作者以后可能会推出改字根版的日文五笔输入法。

2)所用字不同所产生的差异
    本输入法收录了日文shift-jis字库的汉字，虽然此字库中有收录部分中文汉字，但实际打字时是不会用到这个字的，例如：

「巻く」中的「巻」用的是「巻udn・udnb」，而非「卷udbb」

「友達」中的「達」用的是「達fud・fudp」，而非「逹fufp」

「別に」中的「別」用的是「別kqj・kqjj」，字库没有「别kljh」这个字。

「検査」中的「査」用的是「査seg・segf」，字库没有「查sjgf」这个字。

3)以下几个特殊编码不是将其看成假名或符号，而是将其看成汉字，可以参与汉字造词：

ヵ=ltn

ヶ=tte

々=tci(考虑到重码所以定成tci而非qyi) 或 z

另外，当您需要输入「人々」、「日々」之类的词的时候，可按下z，会有候选「々」。

如果您不会使用五笔输入法，可以先去了解一下如何使用五笔输入法打字。关于五笔输入法此处不再赘述。

 

（2）输入平假名
本输入法按照罗马拼音的方式两个两个地输入平假名。以下举例说明：

只输入一个假名「か」，按「ka」然后按空格。

输入一串假名「かきくけ」，按「kakikuke」打字过程中假名会两个两个地上屏，无需按空格。

几个需要特别注意的假名编码：

あ=aa   い=ii   う=uu   え=ee   お=oo

ぁ=la   ぃ=li   ぅ=lu   ぇ=le   ぉ=lo

し=si   ち=ci   つ=tu   づ=du   促音っ=ll

や=yv   ゆ=yc   よ=yx

ゃ=lv   ゅ=lc   ょ=lx

きゃ=kv   きゅ=kc   きょ=kx

ちゃ=cv   ちゅ=cc   ちょ=cx   其他行的拗音如此类推

另外词库中还收录了部分纯平假名单词，这些单词基本上是三字词，而且大多是副词、连词、人称代词。输入这些词的方式与五笔类似，取头三个假名的第一个编码，再取最后一个假名的编码，合成一个4位数的编码，该词只有三个假名，那么第三个假名取两码。举例如下：

わたし=> wa ta si => w+t+si => wtsi

しかし=> si ka si => s+k+si => sksi

ください=> ku da sa ii => k+d+s+i => kdsi

ありがとう=> aa ri ga (to) uu => a+r+g+u => argu

（3）输入片假名
    当您需要输入片假名时，按 右shift 可切换到片假名模式，打完片假名单词后再按shift切换回平假名模式。输入方式与平假名相同。
   长音ー=lg

