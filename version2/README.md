# Version 2
已实现实验要求的函数绘图语言的全部功能
解释器执行的第一个程序结果（显示 'OK' 字样）：



## 修复Bug
  由于新加入主界面的模块 `main.py` 无法正常 import 写好的 `parser`模块，因为会与 Python 的同名库冲突。   
  将全部模块改名，加上'my'前缀
## 不足
  词法分析器与语义分析器没有完全分离，本解释器在语法分析阶段，未生成源代码的整体语法树，直接将绘制的点信息交给painter处理  
  缺少异常处理机制  
  没有完全面向对象开发
  