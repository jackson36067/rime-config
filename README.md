# rime-config
首先安装rime,网址 https://rime.im/download/
如果你觉得我的配色可以就可以直接用我的weasel.yml文件覆盖你的
自定义配色在weasel.yml文件总的preset_color_schemes中配置,配置可以参考https://github.com/rime/weasel/wiki/%E5%AE%9A%E5%88%B6%E5%B0%8F%E7%8B%BC%E6%AF%AB%E9%85%8D%E8%89%B2
刚开始安装的rime默认是纵向排列的,可以在weasel.yml中的style配置中修改horizaontal:false的值为true这样一个代码,这样就可以横向排列
这里我推荐一个自定义词典(雾凇拼音)
可以在defaulte.yml文件中设置联想展示的个数(推荐设置9个)
还有一个很好的配置,就是可以设置无论中英文状态下输入的符号都是英文状态的(对写代码来说还是很友好的),这就需要在我们使用到词典中的xxx.scheam.yml文件中的switches配置中添加reset:1这样一行代码
