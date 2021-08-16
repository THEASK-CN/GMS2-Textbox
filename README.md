This is an editor that integrates both single-line and multi-line modes. If you only need to use a single-line text editor, please click.

This is an open source asset package that allows arbitrary use, modification and dissemination.
Before introducing the asset pack, what you need to know is that due to the characteristics of GMS2, ​​when you enter characters other than basic Latin characters in the full screen state, the game will automatically switch to the window state. I have not found a solution for this.

When using the textbox_create(); function, set the parameter "nowrap" to true and set the "adaptive_width" parameter to false to enable the single-line mode.

Ⅰ. Both single-line and multi-line modes are supported:

1. Use the textbox_create(); function to create a text box and define the operation area, initial text, placeholder text and upper limit of the number of words.
2. Use the textbox_set_font(); function to modify the font, color, line height, and vertical correction value.
3. Use the textbox_set_position(); function to modify the coordinates of the text box.
4. Click the left mouse button to move the cursor.
5. Long press the left mouse button and drag to select text.
6. Use the arrow keys to move the cursor, long press is supported.
7. Long press Shift and use the arrow keys to select text.
8. Press Backspace to delete, long press is supported.
9. Press Delete to delete to the right, long press is supported.
10. Press Crtl + A to select all.
11. Press Ctrl + C to copy.
12. Press Ctrl + X to cut.
13. Press Crtl + V to paste.
14. Press Ctrl + Z to undo.
15. Press Ctrl + Y to redo.
16. Press Home to return the cursor to the beginning of the line.
17. Press Shift + Home to select the cursor from the current position to the beginning of the line.
18. Press End to move the cursor to the end of the line.
19. Press Shift + End to select the cursor from the current position to the end of the line.

Ⅱ. Single-line mode additionally supports:

1. Automatically maintain the center in the vertical direction of the operating area.
2. Use the mouse wheel to scroll the text area horizontally.

Ⅲ. Multi-line mode additionally supports:

1. Use the mouse wheel to scroll the text area vertically.
2. Long-press and drag the scroll bar with the left mouse button to scroll the text area vertically.
3. Click the scroll bar with the left mouse button to quickly update the position of the text area.
4. Press Ctrl + Home to return the cursor to the beginning of the full text.
5. Press Ctrl + Shift + Home to select the cursor from the current position to the beginning of the full text.
6. Press Ctrl + End to move the cursor to the end of the full text.
7. Press Ctrl + Shift + End to select the cursor from the current position to the end of the full text.

这是一个整合了单行与多行两种模式的编辑器，如果你只需要使用单行文本编辑器，请点击。

这是一个开源资产包，允许任意使用、修改和传播。
在介绍该资产包之前，你需要知道的是，由于GMS2的特性，当你在全屏状态下输入除基本拉丁字符以外的字符时，游戏会自动切换为窗口状态，对此我目前没有找到解决方法。

在使用 textbox_create(); 函数时将参数 nowrap 设为 true ，并把参数 adaptive_width 设为 false ，即可开启单行模式。

一、单行与多行两种模式都支持：

1. 使用 textbox_create(); 函数创建文本框并定义操作区域、初始文本、占位文本和字数上限。
2. 使用 textbox_set_font(); 函数修改字体、颜色、行高、垂直修正值。
3. 使用 textbox_set_position(); 函数修改文本框的坐标。
4. 点击鼠标左键移动光标。
5. 长按鼠标左键并拖动以选择文字。
6. 使用方向键移动光标，支持长按。
7. 长按 Shift 并使用方向键以选择文字。
8. 按下 Backspace 删除，支持长按。
9. 按下 Delete 向右删除，支持长按。
10. 按下 Crtl + A 全选。
11. 按下 Ctrl + C 复制。
12. 按下 Ctrl + X 剪切。
13. 按下 Crtl + V 粘贴。
14. 按下 Ctrl + Z 撤回。
15. 按下 Ctrl + Y 重做。
16. 按下 Home 使光标回到行开头。
17. 按下 Shift + Home 使光标从当前位置选择到行开头。
18. 按下 End 使光标前往行结尾。
19. 按下 Shift + End 使光标从当前位置选择到行结尾。

二、单行模式另外支持：

1. 自动在操作区域的垂直方向上保持居中。
2. 通过鼠标滚轮使文本区域水平滚动。

三、多行模式另外支持：

1. 通过鼠标滚轮使文本区域垂直滚动。
2. 通过鼠标左键长按并拖动滚动条以使文本区域垂直滚动。
3. 通过鼠标左键点击滚动条以快速更新文本区域位置。
4. 按下 Ctrl + Home 使光标回到全文开头。
5. 按下 Ctrl + Shift + Home 使光标从当前位置选择到全文开头。
6. 按下 Ctrl + End 使光标前往全文结尾。
7. 按下 Ctrl + Shift + End 使光标从当前位置选择到全文结尾。
