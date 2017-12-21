# typeset
自动修正中文、英文、代码混合排版中的全半角、空格等问题

# 功能
* 全角数字、字母、符号改为半角
* 汉字与英文字母、英文符号、数字之间有且只有一个空格
* 汉字、英文字母与英文标点的开侧之间有且只有一个空格
* 英文标点的开侧与开侧之间有且只有一个空格
* 汉字与汉字、汉字与中文标点符号、中文标点符号与中文标点符号之间没有空格
* 汉字、英文字母与英文标点的闭侧之间没有空格
* 英文标点的开侧与闭侧、闭侧与闭侧之间没有空格
* 中文标点与英文标点之间没有空格
* （由于实际用法的复杂性，数字、英文符号与英文字母、英文标点之间的空格保持原样）
* 根据句子内容判断句子是中文还是英文
* 中文句子中的英文标点改为中文标点
* 英文句子中的中文标点改为英文标点
* 汉字与英文字母、数字之间的空格改为自定义分隔符
* 中文句号统一为全角空心句号、全角实心句号或半角实心句号
* 中文引号统一为弯引号、全角直角引号、直引号或 TeX 记号
* 英文引号改为 TeX 记号

# TODO
* 用栈保证左右括号同时为中文或英文
* 将一行分成句子
* 根据语义判断句子是中文还是英文
* 根据语义修改数字、英文符号与英文字母、英文标点之间的空格
* 根据语义修改专有名词的大小写

# 参考
https://github.com/sparanoid/chinese-copywriting-guidelines

https://github.com/ricoa/copywriting-correct

# 示例
https://github.com/martinwu42/read-matrix 使用本项目排版
