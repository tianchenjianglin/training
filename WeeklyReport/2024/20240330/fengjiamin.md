# 本周总结
## getchar的知识点

### 一、getchar()的基本用法

  1.getchar()函数的功能是从缓冲区中读取一个字符，注意，是一个字符。
  2.当缓冲区中没有字符可以读取时，getchar()就会等待我们输入一个字符，然后把它读走。
   如果缓冲区中存在字符，getchar()就不等我们输入，直接读取缓冲区中的字符。

### 二、getchar的清除吸收功能

  1.与scanf不同，getchar()能够读取空格、回车等，而scanf遇到空格与回车时，会结束读取.
  所以此时，一般scanf读走输入数据后，会留下如'\n'等的字符，而如果我们还要再次调用scanf的话，缓冲区中还有'\n'。
  此时scanf不等我们输入数据，就直接把'\n'读走了，从而不能达到我们的目的。所以需要getchar来协助。

  2.当我们输入字符后，按下回车键，缓冲区中还存在'\n'字符，如果想再次使用scanf，就得将其清除，我们就要用到getchar()
  getchar也可以用于吸收'\n'以外的其他的字符，也可以结合for循环使用来持续吸收。
  
  
# 下周计划
  学习离散数学，背英语单词，做留下来的编程作业。
  
