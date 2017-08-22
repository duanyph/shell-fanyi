# shell-fanyi
一个多国语言的命令行翻译工具，使用了有道翻译的接口，可以翻译长文和词语。
使用了random第三方库，使用前请安装random库

pip install random

使用方法：
在命令行下输入

python3 fanyi.py -被翻译的语言 -目标语言 待翻译的文本

示例：

fanyi.py -Z -e 你好世界

其中只有被翻译的语言参数为选填参数，其它均为必填，注意，被翻译的语言参数字母必须大写，目标语言参数字母必须小写

以下是所有的参数：

    -h           帮助
    -A,-a        自动
    -Z,-z        汉语
    -J,-j        日语
    -E,-e        英语
    -K,-k        韩语
    -F,-f        法语
    -R,-r        俄语
    -P,-p        葡萄牙语
    -C,-c        西班牙语
