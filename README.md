### 【使用说明】
① 在当前目录下方运行终端  
② 执行以下命令安装依赖  
``` bash
npm install

# 如果配置了cnpm则使用cnpm安装（配置cnpm：npm install -g cnpm --registry=https://registry.npm.taobao.org）
```
③ 添加新的文章  
``` bash
# 命令
$ hexo new [layout] [title]

# new命令用法可通过执行以下命令查看
$ hexo help new

# layout: post, page, draft ...
# 示例
$ hexo new post diary-220904-01
```
④ 在本地运行
``` bash
# 默认端口4000
$ hexo s

# 加 -s 参数可指定端口为5000
$ hexo s -p 5000
```
⑤ 生成并发布文章（push到master分支）  
``` bash
$ hexo g -d
```

【软件版本说明】  
1、node: v12.16.2  
2、hexo-cli: 4.3.0  