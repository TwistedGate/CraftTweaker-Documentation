# 忽略括号错误预处理器

这个预处理器将你的脚本设置为忽略括号错误。  
这个预处理器 不会 以任何方式神奇地更正你的脚本，它只是禁用错误日志。

## 调用

你可以将 `#ignoreBracketErrors` 放在脚本文件中来调用忽略括号错误预处理器。  
这个预处理器仅在指定的文件中有效，所以在一个文件中调用这个预处理器不会影响其他文件（至少是这个预处理器所涉及的）。

## 它的作用

在一个文件里调用这个预处理器，会禁用所有关于括号错误的错误日志。  
这不会以任何方式改变受影响的行，而仅仅是让你的日志不包含受影响的行。