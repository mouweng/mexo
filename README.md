# Mexo | Hexo Theme

> A hexo theme for minimalist

## Preview
![preview](https://cdn.jsdelivr.net/gh/mouweng/FigureBed/img/202203192008012.jpg)

## How To Use❓

### 1. Clone Mexo

- **Latest**：cd `/themes`：

```shell
git clone https://github.com/mouweng/mexo.git themes/mexo
```

- **Stable**：In [Released]() download zip and unzip it in `/themes`.

### 2. Set **theme** to **mexo** in `_config.yml`

```
theme: mexo
```

### 3. Configuration Setting

```yml
# Favicon
favicon: /img/favicon.png

# SEO
keywords: 

# Site title separator
separator: '-'

# RSS
# rss: /atom.xml

# Nav menu
menu:
  📟Home: /
  🔖About: /about


# Utterances - Comment Plugin based on GitHub Issues
# See: https://utteranc.es
comments:
  enable: false
  # github repo
  repo: 

# Visitor Statistics based on Busuanzi
# Enable statistics of page views and articles read times
statistic:
  enable: false
```

### 4. Hide Posts

- If you want to `hide` a post, you can add the following to your post：

```shell
---
title: hello,world!
date: 2021-07-10 00:00:00
hide: true
---
```

## Todo List

- [x]  👨🏻‍💻 Comments
- [x]  🔋 Pv in Posts
- [x]  🔋 Pv in Site
- [x]  ⭐️ Hide posts
- [ ] 🔖 RSS
- [ ] 🛠 Optimize Paging When Using Hide

## Contribution

### welcome to give issues and  pull requests 😆

## END

### If you like Hexo Coder, please give it a star✨