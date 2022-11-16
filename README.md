## 作者

- **chenxuan**

## 效果

[bilibili](https://www.bilibili.com/video/BV1cv4y1Q7hz)

## 安装

```
Plug 'godlygeek/tabular', {'on':'Tabularize'}
Plug 'chenxuan520/markdown-simple.vim'
```

## 设置

### 关闭

- `let g:markdown_simple_disable=1`

### 缩进设置

- `let g:markdown_simple_indent="  "`

## 特点

1. 表格实时格式化,|按键太远了,可以自定义绑定为其他按键(默认为;;)

2. 有序列表自动生成,避免手动打

3. 支持选中ctrl+b 加粗,ctrl+i斜体,更加方便,或者鼠标右键

4. 插入链接自动转换为\[]()或者形式\!()[]

5. \# 按键快速添加标题 &# 减少标题

6. \-,&+数字 快速添加序号

7. 代码量少,一共200多行代码,对VIM启动速度几乎不影响,所有快捷键只在markdown有效

8. 自定义配置简单丰富

9. 支持自动化折叠,\[\[和\]\]跳转等功能
