# RefLinkGenerator

## Intro

From time to time, we need to write reference hyperlink texts to internet pages in various markup languages. The process is 
rather trivial yet tedious. RefLinkGenerator is here to simplify that operation, which is a grease-monkey script to generate
reference link to current page in different kinds of markup languages such as Markdown, html and LaTeX etc. 
It can also help copy to system clipboard with one single click.

## Installation

* To install this script, you have to install user-scripts management extension for your browser, e.g. Tampermonkey 
for Chrome. For other browsers, you may take a look at [How to install user scripts](https://greasyfork.org/zh-CN/help/installing-user-scripts )
* After the extension is installed, then go to [installation page](https://greasyfork.org/zh-CN/scripts/11800-reflinkgenerator ) 
and install the script.

## Usage

1. Select the page you want to make a link referring to
1. Move your mouse over the left top (almost top) boarder of the page
1. A panel will popup and you can click buttons to copy the generated texts.
1. Optional. You can edit the title auto retrieved if that's not what you need, then click `Regenerate` button. Now 
all the link texts are updated and you can copy as you wish.

![Auto-hide panel on top-left](https://greasyfork.org/system/screenshots/screenshots/000/001/720/original/top-left.png?1439818110)

![Operation panel](https://greasyfork.org/system/screenshots/screenshots/000/001/721/original/auto-hide-panel.png?1439818110)

![Manual selection](https://greasyfork.org/system/screenshots/screenshots/000/001/722/original/manual-select.png?1439818111)

## Known issues

* Firefox doesn't support direct copy to system clipboard. User have to copy the text manually.

## 介绍

我们写文章或者博客时总是要不停的添加超链接，复制网址、复制标题、修改标记格式，整个过程很琐碎也很费劲。引用链接生成器(RefLinkGenerator)
就是为简化这一过程而生。它可以自动生成多种标记语言格式的超链接文本，并且可以一键复制到系统剪贴板，直接粘贴吧！

## 安装
* 你需要为浏览器安装油猴脚本管理器，请参考[这里](https://greasyfork.org/zh-CN/help/installing-user-scripts )
* 到[脚本安装页面](https://greasyfork.org/zh-CN/scripts/11800-reflinkgenerator )安装脚本

## 使用
1. 到要引用的页面
2. 鼠标移动到页面左上角可以呼出自动隐藏的边栏
1. 点击相应标记语言的按钮即可复制自动生成的链接文本
1. 可选步骤。如果自动提取的标题不如你意，可以手动修改后点`Regenerate`按钮重新生成链接再复制

## 已有的问题
* Firefox好像不支持直接复制到系统剪贴板，用户需要手动复制。