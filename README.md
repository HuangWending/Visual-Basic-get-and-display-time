# Visual-Basic-get-and-display-time
Visual Basic获取并显示当前时间的程序

Sub Main() 

这是一个子程序（Subroutine）的声明，名称为"Main"。程序将从这里开始执行。

Dim currentTime As DateTime = DateTime.Now ' 获取当前时间

这一行声明了一个变量`currentTime`，类型为`DateTime`，并将当前的日期和时间赋给它。`DateTime.Now`是一个用于获取当前日期和时间的静态方法。

Console.WriteLine("Current time: " & currentTime) ' 打印当前时间

这一行将文本字符串"Current time: "和变量`currentTime`的值连接起来，然后使用`Console.WriteLine`方法将结果打印到控制台窗口中。

End Sub 

这是子程序的结束标记，表示程序执行到这里结束。

End Module

这是模块的结束标记，表示整个模块的代码结束。