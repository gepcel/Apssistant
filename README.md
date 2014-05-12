#summary 简体中文说明
#labels Featured,Phase-Implementation

=使用说明=
==支持情况==
|| *功能/版本号：* || *6* || *7* || *CS* || *CS2* || *CS3* || *CS4* || *CS5* ||
||HUD 拾色器增强||/||/||/||/||/||/||☀||
||前景拾色器快捷键||○||○||○||○||○||○||☀||
||修改笔刷范围||×||×||×||×||×||☀||☀||
||快速创建新图层||○||○||○||○||○||○||○||
||修改撤销/重做快捷键||○||○||○||○||○||○||○||
||自动保存||○||○||○||○||○||○||○||
||双击托盘/自动启动 Photoshop||×||×||×||×||×||×||○||
||禁用 Alt 菜单键||○||○||○||○||○||○||○||

||/ 无此功能||× 不支持||○ 支持||☀ 完美支持||

*CS3 因不明原因无法完美支持前景拾色器相关功能，查证中*

=详细说明=
==HUD 拾色器增强==
此功能只适用于 Photoshop CS5 及以上版本，需在 首选项 中打开 OpenGL 支持方可使用。
打开OpenGL方法：
 编辑——首选项——性能——启用 OpenGL 绘图
部分显卡不支持此选项（复选框为灰色），可尝试修改注册表或升级显卡驱动（或换显卡……）。
===精确===
勾选“精确”将不需要按住空格键切换选色区域。前景拾色器将自动识别。
===中心===
勾选“中心”将自动定位到屏幕中心显示 HUD 拾色器。

==前景拾色器快捷键==
Photoshop CS5 及以上版本先至以下位置修改键盘快捷键：
 键盘快捷键和菜单——快捷键用于（工具）——前景拾色器
Photoshop CS4 及其以前版本（最低至 Photoshop 6）请至顶部选择版本号之后用该键打开/保存拾色器。

*注意：*<br>
此按键同时可实现确定功能，即一键操作。
Photoshop CS4 及其以前版本（最低至 Photoshop 6）在使用 前景拾色器快捷键时需满足以下条件：
 * 前景色处于可点击状态（非全屏模式）
 * 使用画笔工具或铅笔工具
 * 使用系统默认主题

如在非系统默认主题（即经典主题或任何自定义）下不能使用前景拾色器快捷键功能，请选择以下方法之一解决：
 # 修改界面颜色——项目“三维物体”——颜色选第五行第一个或在“其他”中选择 色调34/饱和度83/亮度213（红236/绿233/蓝216）
  * XP用户：桌面右键菜单——属性——外观——高级——项目“三维物体”
  * Windows 7 用户：控制面板——外观和个性化 ——更改半透明窗口颜色——高级外观设置——项目“三维物体”
 # 至 _Data\Imagesearch\*PS版本号*_ 目录下修改对应版本的参考图片并以 PNG 格式替换。

===前景拾色器映射为 Alt===
此功能可将拾色器与 Alt 取色合并，使用 Photoshop CS5 以前版本的拾色器触发方式。*此功能与“禁用 Alt 菜单键”冲突。*
===前景拾色器映射 Alt===
仅 Photoshop CS5 及以上版本可见，需要输入 Photoshop CS5 以上版本内设置的拾色器快捷键。*此功能与“禁用 Alt 菜单键”冲突。*

==修改笔刷范围==
此功能仅用于 Photoshop CS4 及以上版本，将 Alt+右键 合并以达到模拟3D软件相关功能的效果。

==快速创建新图层==
快捷键创建新图层（Alt+Shift+Ctrl+N）而无需确认。

==修改撤销/重做快捷键==
此功能为方便经常重装并习惯改键的用户设计，将默认的4个快捷键循环更换如下：

|| *功能* || *修改前* || *修改后* ||
||后退一步||Alt+Ctrl+z||Ctrl+z||
||校样颜色||Ctrl+y||Alt+Ctrl+z||
||前进一步||Shift+Ctrl+z||Ctrl+y||
||还原/重做||Ctrl+z||Shift+Ctrl+z||

==自动保存==
可选定时提醒及定时静默保存，可关闭。

==自动/双击托盘以启动 Photoshop==
目前仅支持 Photoshop CS5（包括 64位），其他版本待测试。

==禁用 Alt 菜单键==
防止单击 Alt 触发菜单。

==锁定为英文输入法==
此功能针对亚洲用户设计，防止输入法导致快捷键冲突。

==关闭帮助提示==
本软件部分功能有托盘提示，可在此处关闭。

=注意事项=
 * 本软件部分功能仍有缺陷，请尽量使用正确的操作方式，例如在套索工具状态下使用HUD拾色器容易造成假死
 * 请毋连续使用快捷键，容易占用 CPU 过高导致 Photoshop 不稳定
 * 某些软件可能导致本软件有严重的性能损失，请在使用本软件及 Photoshop 时禁用其 进程/服务。（如gdipp）
 * 任何人均不会对本软件造成的任何不良后果承担责任