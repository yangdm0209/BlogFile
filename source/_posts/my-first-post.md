title: my first post
date: 2015-12-23 19:44:15
tags: [博客,文章]
toc: true
---

# 这里是我的第一篇测试博客

先写个`hello world`吧，看看效果如何。

``` cpp
main()
{
	printf("hello world!\n");
}
```

## Test code style

``` bash
	#!/bin/bash
	HEXO=<你的Hexo根目录地址>
	cd $HEXO
	hexo clean  # Clean cache
	livereload -e ".md, .html, .png, .svg, .jpg, .gif, .css, .js, .json" | hexo server --debug
```

## Test Python code

``` python
	def test:
		print "hello world"
```

## Test Java code

``` java
public class Test{

	public static void main(){
		system.out.println("Hello world");
	}
}
```