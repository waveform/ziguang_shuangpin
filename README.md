# 紫光双拼
鼠鬚管、小狼毫、中州韻 Rime 输入法 配置文件

## 序
曾经风靡一时的紫光拼音 [Unispim](https://github.com/thunisoft/unispim) 早已被丢进故纸堆 [Wiki](https://zh.wikipedia.org/wiki/%E5%8D%8E%E5%AE%87%E6%8B%BC%E9%9F%B3%E8%BE%93%E5%85%A5%E6%B3%95)，鲜有人问津了。
在这个选择过剩的年代，送走个把拼音输入法根本就不是个事儿。可是紫光拼音的 “遗毒” 紫光双拼方案 换起来却要费时费力的多。
仅以此纪念那些和我一样卡在紫光双拼的结界里，无法逃逸的人们。

## 方案
![](https://github.com/waveform/ziguang_shuangpin/raw/master/Unispim_Double_Pinyin_Scheme.png)

## 安装方法
此处以中州韻为例，使用官方配置工具 东风破 [plum](https://github.com/rime/plum) 安装。
* 下载rime-install, 并用它安装紫光双拼
```bash
curl -fsSL https://git.io/rime-install | bash -s -- waveform/ziguang_shuangpin
```
* 切换到Rime输入法，在输入法菜单栏里点击 ***部署*** 。
* 最后，通过 Ctrl + \` 呼出方案选单，切换到 紫光双拼 即可。

fcitx 输入引擎的配置与ibus大抵相同。此处不再赘述。相关细节请参考 东风破 [plum](https://github.com/rime/plum)。

## 致谢
* 感谢紫光拼音早年间的大力支持。我对你一见钟情，一往情深。尽管在移动时代，你动不动就拿分号键把我的脸按在触摸屏上用力的摩擦，摩擦。
* 感谢佛振开源了神级输入法 [Rime](https://rime.im/)，让我们得以自由订制真正属于自己的输入法。
