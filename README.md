# JLU-software-engineering-theis-bachelor
Graduation thesis of undergraduates of School of Software, Jilin University（吉林大学软件学院本科生毕业论文）


# 注意
1. 本人实测环境：texlive2019环境+texstudio软件可编译;原来使用CTEX环境+texstudio/WinEdt均不可；

tex软件还可对VSCode进行配置运行（本人未尝试过）

2. 在[JLU-CCST-Thesis](https://github.com/x86vk/JLU-CCST-Thesis) 吉大计算机学院毕业论文上简单修改，主要修改如下：

①页眉，在sty文件中搜索“软件学院”即可发现

②中文摘要：ctitle和“摘要”文字的位置替换（与计算机学院正好相反）

③英文摘要：同上；

	另外修改“Abstract”为三号字（计算机学院上是三号字，但是说明是小三号，sty文件中原始为小三（xiaosan））；

	另外在etitle和“Abstract”之间加入了以下代码，来使作者和导师的英文名居右显示
  \begin{flushright}
    \sanhao\noindent \@eauthor
  \end{flushright}
  \vspace{1em}
  \begin{flushright}
    \sanhao\noindent \@esupervisor
  \end{flushright}
  \vspace{1em}

3. 效果见PDF文件
4. 使用方法参考[JLU-CCST-Thesis](https://github.com/x86vk/JLU-CCST-Thesis),感谢学长的付出。

