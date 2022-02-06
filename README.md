<div align='center'>
<img src='img/logo.png' width='250' alt='logo'>
<p>A simple CSS initialization library</p>
<a href='https://github.com/creeperwater/init.css/'><img src="img/github.png" width='70' alt='star'></a>
<a href='https://gitee.com/creeperwater/init.css/'><img src='img/gitee.png' width='70' alt='star'/></a>
<p>En | <a href='README.zh.md'>中</a></p>
</div>

Lazy to read the instruction? Just jump to [How to use](#how-to-use)

## Introduction

The library currently contains CSS initialization in three scenarios, which you can view in the source code:

- Common web page - [page.css](src/page.css)
- App like web page - [app.css](src/app.css)
- Web game - [game.css](src/game.css)

## Attribute

### page.css

- Remove margins
- The border width is included in the total width
- Remove the default styles for each label
- Set the default font

### app.css

- Remove margins
- The border width is included in the total width
- Remove the default styles for each label
- Set the default font
- Disable scrolling on the entire page
- Disable user selection

### game.css

- Remove margins
- The border width is included in the total width
- Remove the default styles for each label
- Set the default font
- Disable scrolling on the entire page
- Disable user selection
- Block gestures

## Preview

You can visit the web page to preview init.css online in different browsers:

- [page.css](https://creeperwater.github.io/init.css/view/page.html)
- [app.css](https://creeperwater.github.io/init.css/view/app.html)
- [game.css](https://creeperwater.github.io/init.css/view/game.html)

## How to use

You can download init.min.css in **release**,

- [Github](https://github.com/creeperwater/init.css/releases)
- [Gitee](https://gitee.com/creeperwater/init.css/releases)

Or use the following code to introduce init.min.css to your web page. (test only)

page.min.css
```
<link rel="stylesheet" href="https://creeperwater.github.io/init.css/dist/page.min.css">
```

app.min.css
```
<link rel="stylesheet" href="https://creeperwater.github.io/init.css/dist/app.min.css">
```

game.min.css
```
<link rel="stylesheet" href="https://creeperwater.github.io/init.css/dist/game.min.css">
```
