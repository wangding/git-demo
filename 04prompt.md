
<table class="multi">
<caption class="cap">表14-1: Shell 提示符中用到的转义字符</caption>
<tr>
<th class="title">序列</th>
<th class="title">显示值</th>
</tr>
<tr>
<td valign="top" width="20%">\a</td>
<td valign="top">以 ASCII 格式编码的铃声 . 当遇到这个转义序列时，计算机会发出嗡嗡的响声。</td>
</tr>
<tr>
<td valign="top">\d</td>
<td valign="top">以日，月，天格式来表示当前日期。例如，“Mon May 26.”</td>
</tr>
<tr>
<td valign="top">\h</td>
<td valign="top">本地机的主机名，但不带末尾的域名。</td>
</tr>
<tr>
<td valign="top">\H</td>
<td valign="top">完整的主机名。</td>
</tr>
<tr>
<td valign="top">\j</td>
<td valign="top">运行在当前 shell 会话中的工作数。</td>
</tr>
<tr>
<td valign="top">\l</td>
<td valign="top">当前终端设备名。</td>
</tr>
<tr>
<td valign="top">\n</td>
<td valign="top">一个换行符。</td>
</tr>
<tr>
<td valign="top">\r</td>
<td valign="top">一个回车符。</td>
</tr>
<tr>
<td valign="top">\s</td>
<td valign="top">shell 程序名。</td>
</tr>
<tr>
<td valign="top">\t</td>
<td valign="top">以24小时制，hours:minutes:seconds 的格式表示当前时间.</td>
</tr>
<tr>
<td valign="top">\T</td>
<td valign="top">以12小时制表示当前时间。 </td>
</tr>
<tr>
<td valign="top">\@</td>
<td valign="top">以12小时制，AM/PM 格式来表示当前时间。</td>
</tr>
<tr>
<td valign="top">\A</td>
<td valign="top">以24小时制，hours:minutes 格式表示当前时间。</td>
</tr>
<tr>
<td valign="top">\u</td>
<td valign="top">当前用户名。</td>
</tr>
<tr>
<td valign="top">\v</td>
<td valign="top">shell 程序的版本号。</td>
</tr>
<tr>
<td valign="top">\V</td>
<td valign="top">Version and release numbers of the shell.</td>
</tr>
<tr>
<td valign="top">\w</td>
<td valign="top">当前工作目录名。</td>
</tr>
<tr>
<td valign="top">\W</td>
<td valign="top">当前工作目录名的最后部分。</td>
</tr>
<tr>
<td valign="top">\!</td>
<td valign="top">当前命令的历史号。
</td>
</tr>
<tr>
<td valign="top">\#</td>
<td valign="top">当前 shell 会话中的命令数。
</td>
</tr>
<tr>
<td valign="top">\$</td>
<td valign="top">这会显示一个"$"字符，除非你拥有超级用户权限。在那种情况下，它会显示一个"#"字符。</td>
</tr>
<tr>
<td valign="top">\[</td>
<td valign="top">标志着一系列一个或多个非打印字符的开始。这被用来嵌入非打印的控制字符，这些字符以某种方式来操作终端仿真器，比方说移动光标或者是更改文本颜色。
</td>
</tr>
<tr>
<td valign="top">\]</td>
<td valign="top">标志着非打印字符序列结束。 </td>
</tr>
</table>


<table class="multi">
<caption class="cap">表14-2: 用转义序列来设置文本颜色</caption>
<tr>
<th class="title">序列</th>
<th class="title">文本颜色</th>
<th class="title">序列</th>
<th class="title">文本颜色</th>
</tr>
<tr>
<td valign="top">\033[0;30m</td>
<td valign="top">黑色</td>
<td valign="top">\033[1;30m </td>
<td valign="top">深灰色</td>
</tr>
<tr>
<td valign="top">\033[0;31m</td>
<td valign="top">红色</td>
<td valign="top">\033[1;31m </td>
<td valign="top">浅红色</td>
</tr>
<tr>
<td valign="top">\033[0;32m </td>
<td valign="top">绿色</td>
<td valign="top">\033[1;32m </td>
<td valign="top">浅绿色</td>
</tr>
<tr>
<td valign="top">\033[0;33m </td>
<td valign="top">棕色</td>
<td valign="top">\033[1;33m </td>
<td valign="top">黄色</td>
</tr>
<tr>
<td valign="top">\033[0;34m </td>
<td valign="top">蓝色</td>
<td valign="top">\033[1;34m </td>
<td valign="top">浅蓝色</td>
</tr>
<tr>
<td valign="top">\033[0;35m </td>
<td valign="top">粉红</td>
<td valign="top">\033[1;35m </td>
<td valign="top">浅粉色</td>
</tr>
<tr>
<td valign="top">\033[0;36m </td>
<td valign="top">青色</td>
<td valign="top">\033[1;36m </td>
<td valign="top">浅青色</td>
</tr>
<tr>
<td valign="top">\033[0;37m </td>
<td valign="top">浅灰色</td>
<td valign="top">\033[1;37m </td>
<td valign="top">白色</td>
</tr>
</table>


<table class="multi">
<caption class="cap">表14-3: 用转义序列来设置背景颜色</caption>
<tr>
<td valign="top">\033[0;40m </td>
<td valign="top">蓝色</td>
<td valign="top">\033[1;44m </td>
<td valign="top">黑色</td>
</tr>
<tr>
<td valign="top">\033[0;41m </td>
<td valign="top">红色</td>
<td valign="top">\033[1;45m </td>
<td valign="top">紫色</td>
</tr>
<tr>
<td valign="top">\033[0;42m </td>
<td valign="top">绿色</td>
<td valign="top">\033[1;46m </td>
<td valign="top">青色</td>
</tr>
<tr>
<td valign="top">\033[0;43m </td>
<td valign="top">棕色</td>
<td valign="top">\033[1;47m </td>
<td valign="top">浅灰色</td>
</tr>
</table>


<table class="multi">
<caption class="cap">表14-4: 光标移动转义序列</caption>
<tr>
<th class="title">转义编码</th>
<th class="title">行动</th>
</tr>
<tr>
<td valign="top" width="25%">\033[l;cH </td>
<td valign="top">把光标移到第 l 行，第 c 列。</td>
</tr>
<tr>
<td valign="top">\033[nA </td>
<td valign="top">把光标向上移动 n 行。</td>
</tr>
<tr>
<td valign="top">\033[nB </td>
<td valign="top">把光标向下移动 n 行。</td>
</tr>
<tr>
<td valign="top">\033[nC </td>
<td valign="top">把光标向前移动 n 个字符。</td>
</tr>
<tr>
<td valign="top">\033[nD </td>
<td valign="top">把光标向后移动 n 个字符。</td>
</tr>
<tr>
<td valign="top">\033[2J </td>
<td valign="top">清空屏幕，把光标移到左上角（第零行，第零列）。</td>
</tr>
<tr>
<td valign="top">\033[K </td>
<td valign="top">清空从光标位置到当前行末的内容。</td>
</tr>
<tr>
<td valign="top">\033[s </td>
<td valign="top">存储当前光标位置。</td>
</tr>
<tr>
<td valign="top">\033[u </td>
<td valign="top">唤醒之前存储的光标位置。</td>
</tr>
</table>


<table class="multi">
<tr>
<th class="title">序列</th>
<th class="title">行动</th>
</tr>
<tr>
<td valign="top" width="25%">\[</td>
<td valign="top">开始一个非打印字符序列。其真正的目的是为了让 bash 能够正确地计算提示符的大小。如果没有这个转义字符的话，命令行编辑功能会弄错光标的位置。</td>
</tr>
<tr>
<td valign="top">\033[s </td>
<td valign="top">存储光标位置。这个用来使光标能回到原来提示符的位置，当长条和时钟显示到屏幕上方之后。当心一些终端仿真器不推崇这个编码。</td>
</tr>
<tr>
<td valign="top">\033[0;0H </td>
<td valign="top"> 把光标移到屏幕左上角，也就是第零行，第零列的位置。 </td>
</tr>
<tr>
<td valign="top">\033[0;41m </td>
<td valign="top">把背景设置为红色。</td>
</tr>
<tr>
<td valign="top">\033[K </td>
<td valign="top">清空从当前光标位置到行末的内容。因为现在背景颜色是红色，则被清空行背景成为红色，以此来创建长条。注意虽然一直清空到行末，但是不改变光标位置，它仍然在屏幕左上角。</td>
</tr>
<tr>
<td valign="top">\033[1;33m </td>
<td valign="top">把文本颜色设为黄色。</td>
</tr>
<tr>
<td valign="top">\t </td>
<td valign="top">显示当前时间。虽然这是一个可“打印”的元素，但我们仍把它包含在提示符的非打印部分，因为我们不想 bash 在计算可见提示符的真正大小时包括这个时钟在内。</td>
</tr>
<tr>
<td valign="top">\033[0m </td>
<td valign="top">关闭颜色设置。这对文本和背景都起作用。</td>
</tr>
<tr>
<td valign="top">\033[u </td>
<td valign="top">恢复到之前保存过的光标位置处。</td>
</tr>
<tr>
<td valign="top">\] </td>
<td valign="top">结束非打印字符序列。</td>
</tr>
<tr>
<td valign="top"><\u@\h \W>\$ </td>
<td valign="top">提示符字符串。</td>
</tr>
</table>
