> [!WARNING]
> **本项目已迁移 / This repository has been moved.**
>
> ⚠️ **注意：** 本仓库已停止维护，处于归档状态。
> 所有的后续更新、Issue 提交和 Pull Request 请移步至新的组织仓库：
>
> 👉 **最新版本地址：[点击此处访问新仓库](https://github.com/PKU-Floorball/pkufloorball)**

# 北京大学软式曲棍球协会主页

## 快速开始

### 直接打开
在浏览器中打开 [https://xhhwyh.github.io/pkufloorball/](https://xhhwyh.github.io/pkufloorball/) 。

### 本地运行
将本项目克隆到本地
```bash
git clone https://github.com/xhhwyh/pkufloorball.git
```

对于Windows系统用户需要安装 [Ruby](https://www.ruby-lang.org/en/downloads/)， 建议下载 3.2.9 版本。

安装 `Jekyll`
```bash
gem install bundler jekyll
jekyll -v
```

`cd` 进入项目目录，构建 `Jekyll` 项目
```bash
cd pkufloorball
jekyll new . --force
```

启动 `Jekyll` 服务
```bash
bundle exec jekyll serve
```
然后在浏览器中打开 [http://localhost:4000](http://localhost:4000) 即可看到效果。
