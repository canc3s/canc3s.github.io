---
layout: post
title: "Jeklly Tricks"
description: 熟悉 Kramdown 
categorized: [uncategorized]
tags: [kramdown]
redirect_from:
  - /2019/01/28/
---

# 标题写法

## Setext风格

标题一
=======

标题二
------

标题三
=

~~~
标题一
=======

标题二
------

标题三
=
~~~
## Atx风格

# 标题一

## 标题二

### 标题三

~~~
# 标题一

## 标题二

### 标题三
~~~

# 引用

## 引用文字

> 文字

~~~
> 文字
~~~

## 引用代码

	include<stdio.h>

	void main(void){}

~~~
        include<stdio.h>

        void main(void){}
~~~

~~~
include<stdio.h>

void main(void){}
~~~

~~~~~~
~~~
include<stdio.h>

void main(void){}
~~~
~~~~~~

## 选择语言

~~~c
include<stdio.h>

void main(void){}
~~~

~~~~~~
~~~c
include<stdio.h>

void main(void){}
~~~
~~~~~~

# 链接

## 自动链接

Information can be found on the <http://example.com> homepage.

~~~
Information can be found on the <http://example.com> homepage.
~~~

## 内联链接

This is [a link](http://rubyforge.org) to a page.

~~~
This is [a link](http://rubyforge.org) to a page.
~~~

## 参考链接

This is a [reference style link][linkid] to a page. And [this]
[linkid] is also a link. As is [this][] and [THIS].

~~~
This is a [reference style link][linkid] to a page. And [this]
[linkid] is also a link. As is [this][] and [THIS].
~~~
## 自定义链接

[linkid]: http://www.example.com/ "Optional Title"

~~~
[linkid]: http://www.example.com/ "Optional Title"
~~~

## 图片

![too](http://cances.oss-ap-northeast-1.aliyuncs.com/3be5e8280b622c1a7dcf3ba6892c312e.jpg?Expires=1549505345&OSSAccessKeyId=TMP.AQEmRVmurNyxxOAtvAcNtfiTH7Qw73th9w_tPWAAgHlMXciiS15yBZX8OnFpMC4CFQC1IwCCr9iKR3EZJobgbSaJXVYJHwIVAMRNurjoqPreBqjyrMZZ9zax2RBW&Signature=cU1xpbGU1Dzb6nEQ8qROrLDobvo%3D)

~~~
![too](http://cances.oss-ap-northeast-1.aliyuncs.com/3be5e8280b622c1a7dcf3ba6892c312e.jpg?Expires=1549505345&OSSAccessKeyId=TMP.AQEmRVmurNyxxOAtvAcNtfiTH7Qw73th9w_tPWAAgHlMXciiS15yBZX8OnFpMC4CFQC1IwCCr9iKR3EZJobgbSaJXVYJHwIVAMRNurjoqPreBqjyrMZZ9zax2RBW&Signature=cU1xpbGU1Dzb6nEQ8qROrLDobvo%3D)
~~~

# 脚注

This is a text with a footnote[^1].

[^1]: And here is the definition.

~~~
This is a text with a footnote[^1].

[^1]: And here is the definition.
~~~

# 内联属性

This is *red*{: style="color: red"}.

~~~
This is *red*{: style="color: red"}.
~~~

