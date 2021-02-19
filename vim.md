一. 侧边栏 - NERDTree
  1. `<Space> + 3` toggle sidebar
  2. `r` refresh directory
  3. `Ctrl+w + h/j/k/l)` switch curse left,up,down,right

二. vim 中执行 bash command
  1. `ESC` 进入标准模式
  2. :! touch test.md #[创建一个文件]

三. 临时退出 vim
  1. `Ctrl+z` 退出
  2. `fg` 恢复 vim

四. 折叠
  1. `za` 折叠和展开切换
  2. `zR` 展开所有
  3. `zM` 折叠所有
  4. `zj` 移动到上一个折叠的节点
  5. `zk` 移动到下一个折叠的节点

五. 搜索文件
  1. `Ctrl+p`
  2. `Emodel / Econtroller / Eview` + `filename`

六. 移动
  1. 100gg 移动到第100行
  2. gg 移动到第一行
  3. G 移动到最后一行

七. 缩进
  1. `shift + >>` 向右缩进
  2. `shift + <<` 向左缩进
  
八. 复制/剪切/粘贴
  1. `yy` copy
  2. `dd` cut
  3. `p` paste

九. Git
  1. `Gstatus`
  2. `Gdiff`
  3. `Gblame`

十. 修改主题
  1. `colorscheme` + `theme name[PS. molokai]`

十一. 关键字搜索
  1. `Rg <string|pattern>`

十二. 代码补全
  1. `Ctrl+n` [undler input mode]

十三.  删除 buffer
  1. `:bd + number(buffer 号)`
  2. `:3,5bd[elete] ` [Will delete buffer range from 3 to 5]

十四. ctags 【还需要花时间研究】
  1.  

十五. keycastr 【屏幕上面显示键入的字符】
  1. https://github.com/keycastr/keycastr

十六. Emmet 【html 快捷法】
  1. `div#total>ul.foo>li*5` [`Ctrl + y + ','`]