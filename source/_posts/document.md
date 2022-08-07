---
title: Document
date: 2022/2/1 12:34:56
---

<div align=center>
    <img src="logo_animated.svg" width="108" alt="logo" />
    <p>Asclepius | Document</p>
</div>


---

## Installation

### Through `git clone`

**Step 1:** In your site's root directory `./`, run the following commands: 

``` bash
npm install --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
git clone https://github.com/XavierWah/hexo-theme-asclepius.git themes/asclepius
```

**Step 2:** Go to `./_config.yml` and change key `theme`'s value to `asclepius` as shown below: 

```yaml
theme: asclepius
```

**Step 3:** Configure `hexo-generator-archive` by appending the following lines to `./_config.yml` and modify them to meet your need: 

``` yaml
archive_generator:
    per_page: 10
    yearly: false
    monthly: false
```

### Through `git submodule`

**Step 1:** In your site's root directory `./`, run the following commands: 

``` bash
npm install --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
git submodule add https://github.com/XavierWah/hexo-theme-asclepius.git themes/asclepius
```

**Step 2:** Go to `./_config.yml` and change key `theme`'s value to `asclepius` as shown below: 

```yaml
theme: asclepius
```

**Step 3:** Configure `hexo-generator-archive` by appending the following lines to `./_config.yml` and modify them to meet your need: 

``` yaml
archive_generator:
    per_page: 10
    yearly: false
    monthly: false
```

### Through zip archive

**WARNING**: This installing method will be too complicated to receive any of the updates in the future. You shouldn't use this method unless you expect to have no updates.

**Step 1:** In your site's root directory `./`, run the following command: 

``` bash
npm install --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
```

**Step 2:** Download an archive from the [Release](https://github.com/XavierWah/hexo-theme-asclepius/releases) page, or directly from repository's [`HEAD`](https://github.com/XavierWah/hexo-theme-asclepius/archive/refs/heads/master.zip). After download, unarchive its contents into directory `./theme/asclepius`. 

**Step 3:** Go to `./_config.yml` and change key `theme`'s value to `asclepius` as shown below: 

```yaml
theme: asclepius
```

**Step 4:** Configure `hexo-generator-archive` by appending the following lines to `./_config.yml` and modify them to meet your need: 

``` yaml
archive_generator:
    per_page: 10
    yearly: false
    monthly: false
```

## Update

### Through `git clone`

If you used `git clone` during installation, you can use the following commands in asclepius directory `./themes/asclepius`: 

``` bash
git pull
```

### Through `git submodule`

If you used `git submodule` during installation, you can use the following commands in your site's root directory `./`: 

``` bash
git submodule update --remote
```

### Through zip archive

**WARNING:** If you have modified asclepius directory `./themes/asclepius`, updating may damage your modifies. You should always have a backup before doing it. In most cases, we don't recommend you to update. 

If you used a zip archive during installation, an update equals to a reinstallation. Simply remove `./themes/asclepius` and install again. 

## Uninstallation

### Through `git clone`

**Step 1:** Remove asclepius directory `./themes/asclepius`. 

**Step 2:** In your site's root directory `./`, run the following command: 

``` bash
npm uninstall --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
```

**Step 3:** Modify related contents in `/_config.yml`, such as key `themes` and key `archive_generator`. 

### Through `git submodule`

**Step 1:** In your site's root directory `./`, run the following command: 

``` bash
git submodule deinit -f themes/asclepius
```

**Step 2:** Remove asclepius directory `./themes/asclepius`. 

**Step 3:** In your site's root directory `./`, run the following command: 

``` bash
npm uninstall --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
```

**Step 4:** Modify related contents in `/_config.yml`, such as key `themes` and key `archive_generator`. 

### Through zip archive

**Step 1:** Remove asclepius directory `./themes/asclepius`. 

**Step 2:** In your site's root directory `./`, run the following command: 

``` bash
npm uninstall --save hexo-renderer-pug hexo-generator-archive hexo-generator-feed hexo-generator-sitemap
```

**Step 3:** Modify related contents in `/_config.yml`, such as key `themes` and key `archive_generator`. 
