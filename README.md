# RefLinkGenerator

## Intro

From time to time, we need to write reference link texts to internet pages in various markup languages. The process is 
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
1. Optional. You can edit the title auto retrieved if that's not what you need.

![Auto-hide panel on top-left](https://greasyfork.org/system/screenshots/screenshots/000/001/720/original/top-left.png?1439818110)

![Operation panel](https://greasyfork.org/system/screenshots/screenshots/000/001/721/original/auto-hide-panel.png?1439818110)

![Manual selection](https://greasyfork.org/system/screenshots/screenshots/000/001/722/original/manual-select.png?1439818111)

## Known issues

* Firefox doesn't support direct copy to system clipboard. User have to copy the text manually.