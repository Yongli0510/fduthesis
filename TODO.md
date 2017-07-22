# TODO List

## 整体设计
1. - (2017/06/27) 区分本科生毕业论文，硕士 / 博士学位论文

## 功能
1. - (2017/07/05) 表格、图片、浮动体

2. - (2017/07/05) 参考文献

## 字体
1. - (2017/06/24) 思源宋体支持

2. - (2017/06/24) GNU Free Font 支持

3. - (2017/06/27) 方正小标宋的处理

4. - (2017/07/16) 英文模板中无需默认载入 Fandol 字体

## 杂项
1. - (2017/06/24) 图文混排（目前被注释）

2. - (2017/06/24) 校名矢量图插入方式

3. - (2017/06/24) 点状句号不支持 `zhlipsum`（目前处理手段不支持宏定义中的句号）

4. - (2017/06/24) 封面信息栏支持左对齐 / 居中

5. - (2017/07/05) 超链接

## 代码
1. - (2017/06/27) 使用 `\tex_xxx:D` 代替 TeX 原语

2. - (2017/06/29) 使用 `\xxx_xxx:Nx` 而非 `\xxx_xxx:NV`

3. - (2017/07/13) `\CJKfamily` -> `\xeCJK_switch_family:n`

4. - (2017/07/17) `\fdunewtheorem` 等的内部命令

# 文档
1. - (2017/7/10) 用 `\IfFontExistsTF` 确保文档正确编译