# 拼音简写方案
## 简介
这个方案旨在，在拼音的基础上，以最小的改动，尽量减少拼音输入时所需的字符数量。基于普通话的音韵背景，主要在以下方面进行了简化
* 介音iㄧ的省写；
* 增设常用音位对应的字母；
* （可选）韵尾u改用o表示；
* （可选）默认元音e、i在输入时可省略；
* 对原拼音方案向下兼容。

## 声母
声母被分为以下两类
* Eㄜ类声母：bㄅ、pㄆ、mㄇ、fㄈ、dㄉ、tㄊ、nㄋ、lㄌ、gㄍ、kㄎ、hㄏ、zhㄓ、chㄔ、shㄕ、rㄖ、zㄗ、cㄘ、sㄙ、wㄨ；
* Iㄧ类声母：jㄐ、qㄑ、xㄒ、yㄧ、yuㄩ。

其中，我们对一些声母进行以下代替
* zh &rarr; ž，ch &rarr; č，sh &rarr; š；
* yu &rarr; ü，在输入法中用v代替。

## 介音
介音包括
* iㄧ、uㄨ、üㄩ，其中ü在输入法中用v代替。

在不产生混淆的情况下，对介音（其后面还有其它元音）进行以下简化
* 介音iㄧ省略，这类省略出现在Iㄧ类声母之后；
* （可选）介音ü &rarr; u，同上。

## 韵母
韵母包括
* 韵母：aㄚ、aiㄞ、anㄢ、angㄤ、aoㄠ、eㄜ、eiㄟ、enㄣ、engㄥ、iㄧ、ingㄧㄥ、iuㄧㄡ、ouㄡ、ongㄨㄥ、uㄨ、unㄨㄣ、(e)rㄦ；
* 在介音i后的韵母：iㄧ、i-aㄧㄚ、i-anㄧㄢ、i-angㄧㄤ、i-aoㄧㄠ、i-eㄧㄝ、inㄧㄣ、ingㄧㄥ、i-ongㄩㄥ、i-uㄧㄡ、üㄩ、ünㄩㄣ。

对韵母进行以下替代
* 韵尾ng &rarr; ŋ；
* （可选）在d、t、l后ian &rarr; en；
* （可选）iao &rarr; eo；
* （可选）ou &rarr; o，iu &rarr; io；
* （可选）uo &rarr; ue，在b、p、m后可以省略介音u；
* （可选）E类声母后e、en、eŋ以及I类声母后的i、in、iŋ在输入时元音可以省略；例外z、c、s、ž、č、š、r分别表示zi、ci、si、ži、či、ši、ri的省略；
* 语辞ê、o，在需要与e、o区分时，分别记为ê、ô；
* 注音符号ㄨㄛ/ㄩㄝ&rarr;ㄛ，在表示语辞时标轻声表示；由于ㄜ经常省略，可以废弃，由ㄜ&rarr;ㄝ替代，而ㄝ表示语辞时标注轻声表示。

## 总结
由此，简化后的拼音中用到以下的音
* 声母bㄅ、pㄆ、mㄇ(miㆬ)、fㄈ、dㄉ、tㄊ、nㄋ、lㄌ/ㆹli、gㄍ、kㄎ、hㄏ、jㄐ、qㄑ、xㄒ、žㄓ、čㄔ、šㄕ、rㄖ、zㄗ、cㄘ、sㄙ、yㄧ、wㄨ、üㄩ；
* 介音iㄧ、uㄨ、üㄩ；
* 韵母aㄚ、aiㄞ、anㄢ、aŋㄤ、aoㄠ、eㄜ(ueㄛ/ieㄝ)、eiㄟ、enㄣ、eŋㄥ、eoㄧㄠ、iㄧ、inㄧㄣ、iŋㄧㄥ、ioㄧㄡ、oㄡ、oŋㆲ、uㄨ、unㄨㄣ；
* 儿化音er/rㄦ。

## 样例
* 原文：我联合国人民同兹决心，欲免后世再遭今代人类两度身历惨不堪言之战祸，重申基本人权，人格尊严与价值，以及男女与大小各国平等权利之信念，创造适当环境，俾克维持正义，尊重由条约与国际法其他渊源而起之义务，久而弗懈，促成大自由中之社会进步及较善之民生。
* 拼音：We Lianhegue renmin toŋ zi juexin, ü mian hoši zai zao jindai renlei liaŋdu šenli canbukanyan ži žanhue, čoŋšen jiben renquan, renge zunyan ü jaži, yiji nannü ü daxao gegue piŋdeŋ quanli ži xinnian, čuaŋzao šidaŋ huanjiŋ, bike wiči žeŋyi, zunžoŋ yo teoüe ü guejifa qita üenüen erqi ži yiwu, joerfuxe, cučeŋ da ziyo žoŋ ži šehui jinbu ji jao šan ži minšeŋ. 
* 注音：ㄛˇㆹㄢˊㄏˊㄍㄛˊㄖㄣˊㆬㄣˊㄊㆲˊㄗˉㄐㄛˊㄒㄣˉ，ㄩˋㆬㄢˇㄏㄡˋㄕˋㄗㄞˋㄗㄠˉㄐㄣˉㄉㄞˋㄖㄣˊㄌㄟˋㆹㄤˇㄉㄨˋㄕㄣˉㆹˋㄘㄢˇㄅㄨˋㄎㄢˉㄧㄢˊㄓˉㄓㄢˋㄏㄛˋ，ㄔㆲˊㄕㄣˉㄐˉㄅㄣˇㄖㄣˊㄑㄩㄢˊ，ㄖㄣˊㄍˊㄗㄨㄣˉㄧㄢˊㄩˇㄐㄚˋㄓˊ，ㄧˇㄐˊㄋㄢˊㄋㄩˇㄩˇㄉㄚˋㄒㄠˇㄍˋㄍㄛˊㄆㄧㄥˊㄉㄥˇㄑㄩㄢˊㆹˋㄓˉㄒㄣˋㄋㄧㄢˋ，ㄔㄨㄤˋㄗㄠˋㄕˋㄉㄤˋㄏㄨㄢˊㄐㄥˋ，ㄅㄧˇㄎˋㄨㄟˊㄔˊㄓㄥˋㄧˋ，ㄗㄨㄣˉㄓㆲˋㄧㄡˊㄊㄧㄠˊㄩㄛˉㄩˇㄍㄛˊㄐˋㄈㄚˇㄑˊㄊㄚˉㄩㄢˉㄩㄢˊㄦˊㄑˇㄓˉㄧˋㄨˋ，ㄐㄡˇㄦˊㄈㄨˊㄒㄝˋ，ㄘㄨˋㄔㄥˊㄉㄚˋㄗˋㄧㄡˊㄓㆲˉㄓˉㄕㄝˋㄏㄨㄟˋㄐㄣˋㄅㄨˋㄐˊㄐㄠˋㄕㄢˋㄓˉㆬㄣˊㄕㄥˉ。
