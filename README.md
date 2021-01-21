# Windows10-XiaoHe-Double-Pinyin

## 安装

1. 方式一: 下载双击XiaoHe.reg
2. 方式二: 新建XiaoHe.reg文件
  - 文件内容
  
  ```
  ﻿Windows Registry Editor Version 5.00

  [HKEY_CURRENT_USER\Software\Microsoft\InputMethod\Settings\CHS]
  "Enable Double Pinyin"=dword:00000001
  "DoublePinyinScheme"=dword:0000000a
  "Expand Double Pinyin"=dword:00000000
  "UserDefinedDoublePinyinScheme0"="XiaoHe*2*^*iuvdjhcwfg xmlnpbksqszxkrltvyovt"
  ```
