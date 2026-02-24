<!--
 * @Date: 2022-05-02 19:08:48
 * @LastEditors: Cosima
 * @LastEditTime: 2022-05-19 23:27:08
 * @FilePath: /cosima/readme.md
-->

# Cosmo-blog

基于hexo搭建的个人博客 博客地址[Cosmo](https://cosmiumx.github.io/)
项目源码仓库[Cosmo](https://github.com/Cosmiumx/Cosmiumx.github.io)

## 项目介绍

- 个人博客记录分享

## 项目启动

```bash
git clone git@github.com:Cosmiumx/Cosmiumx.github.io.git
```

```bash
npm i
```

```bash
npm install -g hexo-cli
```

```bash
hexo s
```

## 项目开启本地服务debug模式

```bash
hexo s --debug
```

## 项目新增页面

hexo new "post title with whitespace"

```bash
hexo new [layout] <title>
```

## 项目代码打包构建

```bash
hexo generate
hexo g
```

## 项目代码打包构建并发布

```bash
hexo generate -d
```

## 清除打包文件

```bash
hexo c
hexo clean
```
