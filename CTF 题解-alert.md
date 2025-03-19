时间：2025-3-18

网站：

题目：alert

分类：web

描述：<font style="color:rgb(80, 80, 80);">flag{}</font>

<font style="color:rgb(80, 80, 80);"></font>

<font style="color:rgb(80, 80, 80);">进入网站先出现一个弹窗</font>

![](https://cdn.nlark.com/yuque/0/2025/png/47381796/1742262824612-0502c99b-dcdf-4e50-8977-4b65eee6427f.png)

查看源代码，最后出现可疑字符

![](https://cdn.nlark.com/yuque/0/2025/png/47381796/1742264147927-67b8e7aa-d705-4c72-bb87-f01a8196ef19.png)



观察发现是&#的编码的特征，怀疑是**HTML实体编码**，使用随波逐流编码工具得到题解

![](https://cdn.nlark.com/yuque/0/2025/png/47381796/1742264277517-52bd5105-3f2c-4214-9fa3-f4b114c383f6.png)

