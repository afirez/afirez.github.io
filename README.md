# alphazz

[alphazz](https://afirez.github.io)
## Github 部署 MkDocs

```bash
# 安装
pip3 install mkdocs

# 主题： https://squidfunk.github.io/mkdocs-material/getting-started/#installation
pip3 install mkdocs-material

mkdors new alphazz

# 本地调试
mkdocs serve

# github 一键部署
mkdocs gh-deploy

# 设置 gh-pages 分支为 github pages 站点
```

github mkdocs主题仓库 （mkdocs gh-deploy 一键布署）
创建方法：

1. 创建 mkdocs.yml、README.md、.gitignore文件。创建docs目录，markdown文件放在此处。
   - mkdocs.yml
   - README.md
   - .gitignore
   - docs/ 
2. 本地调试 mkdocs serve   访问：http://127.0.0.1:8000/  。 推送上述三个文件。
3. 一键布署 mkdocs gh-deploy  （自动生成 gh-pages分支，发布GithubPages ）
   可fork此仓库 https://github.com/scott180/plain-mkdocs 	
   https://scott180.github.io/plain-mkdocs/

后期更新文件，只需执行 mkdocs gh-deploy 。
   
本地调试：
	安装 python 及 mkdocs 
	相关命令 
		 mkdocs serve
		 mkdocs gh-deploy 
	
参考：
	https://www.cnblogs.com/paulwhw/p/12725523.html
    https://juejin.cn/post/7073717206957162533

主题： https://squidfunk.github.io/mkdocs-material/getting-started/#installation