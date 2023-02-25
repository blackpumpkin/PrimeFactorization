# PrimeFactorizationGUI
使用python设计一个分解质因数的可视化程序，输入任意一个数，程序进行分解质因数。
要求如下：
- 设置输入框，要求在输出结果后输入框内的数字清空；
- 设置输出框，显示出所有成功分解的数和分解公式，要求新的结果出现在旧的结果的上面；
- 设置复制按钮，复制输出结果框内的所有结果；
- 设置清空按钮，清空输出结果框内的结果；
- 在分解质因数前判断输入的内容，如果输入的内容不是数则报错，如果输入的内容不是大于等于2的正整数则报错。
# 使用方法
```
pyinstaller -F PrimeFactorizationGUI.py
```
或
```
pyinstaller -D PrimeFactorizationGUI.py --noconsole
```