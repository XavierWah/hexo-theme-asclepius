[English](document.md) | **中文**

---



<div align=center>
    <img src="resources/logo_animated.svg" width="108" alt="logo" />
    <p>Asclepius | 文档</p>
</div>



---

## 安装

### 通过 `git clone`

**第 1 步:** 在网站根目录 `./` 运行下述命令: 

``` bash
npm install --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
git clone https://github.com/XavierWah/hexo-theme-asclepius.git themes/asclepius
```

**第 2 步:** 打开 `./_config.yml` 并修改键 `theme` 的值为 `asclepius`, 如以下所示: 

```yaml
theme: asclepius
```

**第 3 步:** 通过向 `./_config.yml` 追加修改后的下述内容以配置 `hexo-generator-archive`: 

``` yaml
archive_generator:
    per_page: 10
    yearly: false
    monthly: false
```

### 通过 `git submodule`

**第 1 步:** 在网站根目录 `./` 运行下述命令: 

``` bash
npm install --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
git submodule add https://github.com/XavierWah/hexo-theme-asclepius.git themes/asclepius
```

**第 2 步:** 打开 `./_config.yml` 并修改键 `theme` 的值为 `asclepius`, 如以下所示: 

```yaml
theme: asclepius
```

**第 3 步:** 通过向 `./_config.yml` 追加修改后的下述内容以配置 `hexo-generator-archive`: 

``` yaml
archive_generator:
    per_page: 10
    yearly: false
    monthly: false
```

### 通过 zip 压缩包

**警告**: 此种安装方式将会使得获取更新过于复杂, 除非您不计划升级, 否则您不应使用此种方式. 

**第 1 步:** 在网站根目录 `./` 运行下述命令: 

``` bash
npm install --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
```

**第 2 步:** 从[发布](https://github.com/XavierWah/hexo-theme-asclepius/releases)页面或仓库的 [`HEAD`](https://github.com/XavierWah/hexo-theme-asclepius/archive/refs/heads/master.zip) 下载安装包. 下载完成后, 将其内容解压至目录 `./themes/asclepius`. 

**第 3 步:** 打开 `./_config.yml` 并修改键 `theme` 的值为 `asclepius`, 如以下所示: 

```yaml
theme: asclepius
```

**第 4 步:** 通过向 `./_config.yml` 追加修改后的下述内容以配置 `hexo-generator-archive`: 

``` yaml
archive_generator:
    per_page: 10
    yearly: false
    monthly: false
```

## 更新

### 通过 `git clone`

若在安装时使用了 `git clone`, 则可通过在 Asclepius 目录 `./themes/asclepius` 下执行以下命令完成更新: 

``` bash
git pull
```

### 通过 `git submodule`

若在安装时使用了 `git submodule`, 则可通过在网站根目录 `./` 下执行以下命令完成更新: 

``` bash
git submodule update --remote
```

### 通过 zip 压缩包

**警告:** 若已在 Asclepius 目录 `./themes/asclepius` 中作出了修改, 则更新将损坏已作出的修改. 更新前应首先备份目录. 即便如此, 我们大多数情况下仍不推荐进行更新. 

若在安装时使用了 zip 压缩包, 则更新过程相当于重新安装. 移除 Asclepius 目录 `./themes/asclepius` 并选取方式重新安装. 

## 卸载

### 通过 `git clone`

**第 1 步:** 移除 Asclepius 目录 `./themes/asclepius`. 

**第 2 步:** 在网站根目录 `./` 运行下述命令: 

``` bash
npm uninstall --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
```

**第 3 步:** 修改 `./_config.yml` 中相关内容, 如键 `themes` 与键 `archive_generator`. 

### 通过 `git submodule`

**第 1 步:** 在网站根目录 `./` 运行下述命令: 

``` bash
git submodule deinit -f themes/asclepius
```

**第 2 步:** 移除 Asclepius 目录 `./themes/asclepius`. 

**第 3 步:** 在网站根目录 `./` 运行下述命令: 

``` bash
npm uninstall --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
```

**第 4 步:** 修改 `./_config.yml` 中相关内容, 如键 `themes` 与键 `archive_generator`. 

### 通过 zip 压缩包

**第 1 步:** 移除 Asclepius 目录 `./themes/asclepius`. 

**第 2 步:** 在网站根目录 `./` 运行下述命令: 

``` bash
npm uninstall --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
```

**第 3 步:** 修改 `./_config.yml` 中相关内容, 如键 `themes` 与键 `archive_generator`. 
