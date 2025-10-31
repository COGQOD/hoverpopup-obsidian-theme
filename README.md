# Hover Popup by COGQOD

![bibibobo](https://raw.githubusercontent.com/COGQOD/hoverpopup-obsidian-theme/refs/heads/main/screenshots/screenshot.png)
> I forgot to turn off the Utools's round floating window
> 我忘记关掉utools的悬浮窗了
> my bad. sorry~

+++   ฅ^-ω - ^ ฅ   +++<br>
~~God~~ Cat bless you so you won't encounter any bugs.<br>
~~老天~~ 猫猫保佑你们不会遇到什么bug。
<br><br>
# “Today’s hot take: my theme should be the official one.”
## And you shall share this to all your friends.
no, not really pls, i dont want to fix any bug.
# 今日暴论：我的主题应该成为官方主题
## 并且你应该把这个贴给你所有的好麻吉
别，口嗨的，我补药修bug口牙！
<br><br>
## \*Jump off the roof:\* Hello there\~
**Dark theme only.**
You've never seen a theme that's cool yet somehow endearing!
Some effects are only available in preview mode; I prefer a cleaner look in edit mode.
I really like hover pop-ups, so I made this.
You are welcome to modify my theme. You may also publish your own modified version. if you want to share the modified version with me, you can find me on Discord.
If you encounter any problems, please let me know,
but I really don't have that much time to check them all. \*helpless face\*

this really took me a *loooog* time.<br>
[my Patreon](https://www.patreon.com/c/cogqod/)<br>
[引力圈(unifans)](https://app.unifans.io/c/cogqod)<br>
If possible, please use Unifans, as withdrawing funds from Patreon to third-party platforms incurs transaction fees. puff.

↓ 正在认证 Authentication in progress<br>
[爱发电(afdian)](https://afdian.com/a/cogqod)

Anyways, have a good dayee↗e↘e sir ~ uwu.

仅包含深色主题。
有些效果只在预览模式有效，编辑模式我还是更喜欢清爽一点。
我很喜欢悬停弹窗，所以我做了这个。
欢迎你修改我的主题，你也可以把更改后的版本自己发布，如果你想要把修改后的版本给我，可以在discord里找到我。
如果你遇到了任何问题可以反馈给我，
但我真的没有那么多时间去检查qwq

Oh, and by the way, you can also see all my complaints in the CSS file.
## Cool gifs
⚠︎⚠︎⚠︎GIFs are heavily compressed, so they will have diamond-shaped pixelation.⚠︎⚠︎⚠︎<br>
⚠︎⚠︎⚠︎GIF图片经过高度压缩，看起来会有菱形马赛克背景.⚠︎⚠︎⚠︎

![headings](https://github.com/COGQOD/hoverpopup-obsidian-theme/blob/main/screenshots/1761842803594.gif?raw=true)
> headings 没啥好说的

![popupover](https://github.com/COGQOD/hoverpopup-obsidian-theme/blob/main/screenshots/1761842873781.gif?raw=true)
> I reaaaaaaaalllly loooooooove this! 我太喜欢这个辣！

![menubutton](https://github.com/COGQOD/hoverpopup-obsidian-theme/blob/main/screenshots/1761843018766.gif?raw=true)
> cute button wwwww 宝宝你太可爱辣！

![KBD](https://github.com/COGQOD/hoverpopup-obsidian-theme/blob/main/screenshots/1761844463578.gif?raw=true)
> KBDs, useless but i can still play with it for few minutes. 没什么用但是点着好玩

![Ember Monitor](https://github.com/COGQOD/hoverpopup-obsidian-theme/blob/main/screenshots/1761843440016.gif?raw=true)
![holo Monitor](https://github.com/COGQOD/hoverpopup-obsidian-theme/blob/main/screenshots/1761844312594.gif?raw=true)
> No introduction needed.  这也没啥好说的

## Custom
To Custom the theme, you need to modify the CSS file yourself.<br>
### About Flicking Ember Monitor / 关于闪烁的橙色代码块<br>
I know not everyone will like it lol, so you have a holo version. You can also turn off the animation or turn it off completely.<br>
To change/turn off fenced code block flicker scan,<br>
search: preview animation part, or<br>
line 1387: preview animation part 1/5 : Base Colour<br>
line 1474: preview animation part 2/5 : Infinite Flicker<br>
line 1513: preview animation part 3/5 : Scan<br>
line 1601: preview animation part 4/5 : Copy Button<br>
line 2145: preview animation part 5/5 : Syntax Highlights<br>

我知道不是所有人都喜欢它哈哈哈，所以我写了一个holo版本，你也可以完全关闭它。<br>
要修改代码块样式，<br>
搜索：preview animation part 或者<br>
line 1387: preview animation part 1/5 : 基础颜色<br>
line 1474: preview animation part 2/5 : 背景闪烁<br>
line 1513: preview animation part 3/5 : 横线扫描<br>
line 1601: preview animation part 4/5 : 复制按钮<br>
line 2145: preview animation part 5/5 : 语法高亮<br>

~~我自己都不用~~<br>
### Color / 颜色
Most color definitions are at the beginning of the file, and most colors are directly called from the color definitions.<br>
大部分颜色定义在文件开头，大部分颜色直接调用颜色定义
#### About Search Highlights 关于搜索高亮
In line 733, we have this:<br>
`    rgb(from var(--color-main-green) r g b / 1) 50%`<br>
`1` edit opacity<br>
I recommend:<br>
`    rgb(from var(--color-main-green) r g b / 0.8) 50%`<br>

在第733行（line 733），你能看到:<br>
`    rgb(from var(--color-main-green) r g b / 1) 50%`<br>
`1` 修改透明度<br>
我建议：<br>
`    rgb(from var(--color-main-green) r g b / 0.8) 50%`
### Animation / 动画
This theme contains many animations, which may cause performance issues because most of them are looping animations. You can comment out `animation: ...` at any time.<br>
Some animations need to be hidden, so disabling animations might prevent them from displaying. You can edit `infinite` with `forwards`, which will keep the animation keep its status after the first animation, but this may not always work.

本主题的动画很多，可能会有性能问题，因为大部分都是循环动画。你可以随时禁用`animation: ...`<br>
有些动画因为需要隐藏，也许你禁用动画就不显示了，你可以把`infinite`改成`forwards`<br>
，这样就会在第一次动画后保持原样，但这不一定管用。<br>
## ⚠︎Attention⚠︎：
Start from line 2145, you can find this:<br>
```
/* #region cant find where are these */
.cm-math .tag,
.cm-error,
.cm-editor.cm-focused .cm-matchingBracket,
.cm-editor.cm-focused .cm-matchingBracket .punctuation,
.cm-invalidchar,
.cm-variable-3 { color: var(--color-main-debug) !important;}
/* #endregion */
```
So, if you see magenta \#ff00ff text in the code block, that means you've used syntax highlighting that I haven't checked. I know they exist, but I don't know under what circumstances they're being used. Please let me know if this is the case.<br>
如果您在代码块中看到品红色 \#ff00ff 文本，说明你使用了我没有检查到的语法高亮功能。我知道它们存在，但我不知道它们在什么情况下会被使用。遇到这种情况请务必告知我。<br>

There shouldn't be anything important anymore.<br>
thank you for reading this ❤<br>
and try my theme<br>
应该没有什么重要的了。感谢你读到这里，感谢你使用我的主题❤<br>


对了，我设置了四个隐藏块，我没有找到obsidian有这个功能，它们只能在本主题使用。<br>
颜色稍深：<br>
\<span class=spoiler>\</span><br>
纯黑：<br>
\<span class=spoiler-b>\</span><br>
隐形<br>
\<span class=hide>\</span><br>
模糊<br>
\<span class=blur>\</span><br>

By the way, I set up four hidden blocks. I couldn't find this feature in Obsidian; they only work within this theme.<br>
Darker<br>
\<span class=spoiler>\</span><br>
black<br>
\<span class=spoiler-b>\</span><br>
Invisible<br>
\<span class=hide>\</span><br>
Blur<br>
\<span class=blur>\</span>
