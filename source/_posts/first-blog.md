---
title: First blog
date: 2022-05-21 19:25:36
tags: Hexo
category: theme
mathjax: true
comment: true
---

This is my first formal blog, which is mainly used to test the deployment of content in various formats.

这是我的第一篇正式博客，主要用来测试各种格式的内容能否正确部署。

<!--more-->

## 图片
![567](first-blog/567_6.jpg)

![梅花十三](first-blog/13_3-16534500390181.jpg)

![动图](first-blog/mona-loading-default-16534500425902.gif)

图片居中
<div align="center">
    <img src="first-blog/mona-loading-default-16534500425902.gif"></img>
</div>

## Mathjax公式

- 行内公式：\\(F=\frac{GMm}{r^2}\\)

- 跨行公式：
  
  $$F=\frac{GMm}{r^2}$$
  
- 复杂的跨行公式：
  
  $$\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx \sum_{1}^{2}\int_{0}^{1}f(x)dx$$
  
- 化学方程式：
  
  $$\ce{CH2=CH2 + Cl2 → CH2Cl-CH2Cl}$$

## 代码块

```c++
#include<cstdio>
using namespae std;
int main(){
  printf("hello world!");
  return 0;
}
```

## Note tag


{% note default%}
### hello world!
hello guys!
{% endnote %}



{% note info%}
### hello world!
hello guys!
{% endnote %}



{% note primary%}
### hello world!
hello guys!
{% endnote %}



{% note success%}
### hello world!
hello guys!
{% endnote %}



{% note warning%}
### hello world!
hello guys!
{% endnote %}



{% note danger%}
### hello world!
hello guys!
{% endnote %}


## Label tag

{%label @桃花%}{%label primary@灼灼%}，{%label default@宜室%}{%label success@宜家%}。
{%label info@瓜瓞%}{%label danger@绵绵%}，{%label warning@尔昌%}<mark>尔炽</mark>。


## Button tag

- Button 1：


  {%btn https://zhexuetongnian.github.io/,my_blog,,title%}


- Button 2：


  {%btn https://zhexuetongnian.github.io/,my_blog,hand-o-right%}


- Button 3：


  {%btn https://zhexuetongnian.github.io/,my_blog,hand-o-right fa-fw %}


## Center-quote tag

{%cq%}  
幽僻处可有人行，点苍苔白露泠泠。<br><strong>——王实甫</strong>
{%endcq%}


## Video tag

{% video dog.mp4 %}

