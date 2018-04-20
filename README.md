Word Count
--------------------------------------------------------------------------------
Software Engineering Course Task
Version：2.00
Written by Xiao yunyun(Zhang Yao)
功能介绍
--------------------------------------------------------------------------------
1.”-c":	输出空字符（包括空字符）。
2.“-s":	输出句子数（仅以！、？、.为句末标志）
3.“-w":	输出单词数（不考虑连字符单词等特殊单词）
4."-l" 	输出行数


使用步骤
--------------------------------------------------------------------------------
1.输入文本名（包括扩展名，要求该文件与程序执行文件存在于同一根目录）
2.输入命令符
3.程序输出所需文本信息
4.关闭程序


程序执行步骤
--------------------------------------------------------------------------------
首先，在执行程序前需要建立一个txt文本，名称任意。然后执行程序，输入命令，命令的格式为wc.exe -x filename，filename对应txt文件名，-x对应命令符，程序首先按行输入，计算每行的单词数，句子数，字符数，逐行相加，得到最后所需的文本总单词数，橘子树，字符数，行数。然后判定命令符的第二位，对应输出所指的数量





使用示范
--------------------------------------------------------------------------------
例一.以空文本文件为例
文本展示：![image](https://note.youdao.com/yws/public/resource/0a781b6ffb31c48617f40d7b4dd6cc96/xmlnote/15B6B9C1085843279ABABC2F5F3E82F6/105)

程序运行结果展示：![image](https://note.youdao.com/yws/public/resource/0a781b6ffb31c48617f40d7b4dd6cc96/xmlnote/1499C75EA3C44B2B81375AF2224C6C06/103)

例二.以给定文本为例
文本展示：
![image](https://note.youdao.com/yws/public/resource/0a781b6ffb31c48617f40d7b4dd6cc96/xmlnote/0644A0CFCEDF43C18B9F260221453B31/102)
程序运行结果展示：![image](https://note.youdao.com/yws/public/resource/0a781b6ffb31c48617f40d7b4dd6cc96/xmlnote/582B5585E9F0402DA897FEA729BBEC55/104)


