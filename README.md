# sqc-painter 说明文档

Superconducting Quantum Chip Painter

超导量子计算芯片画图程序

[项目地址](https://github.com/zhaouv/sqc-painter) | [下载](https://github.com/zhaouv/sqc-painter)

基于[KLayout](https://github.com/klayoutmatthias/klayout) (version:[klayout-0.24.8-win64](http://www.klayout.org/downloads/Windows/klayout-0.24.10-win64.zip)) 中Python3.4的脚本环境, 写了库paintlib用于超导芯片的绘图

## 环境配置以及运行

将KLayout解压至**不包含中文**的路径, 运行klayout_app.exe, 如图所示, 点击Macros/Macro Development

![](img_md/2018-04-15-15-33-35.png)

弹出的窗口中, 先点击左上的Python, 选中Python的环境, 在下方右键Add Location, 选中sqc-painter的路径添加到环境中

双击paintlib, 点击右侧上方的![](img_md/2018-04-15-15-41-16.png), 之后重启KLayout, 完成环境的配置

![](img_md/2018-04-15-15-35-33.png)

运行脚本时, 在左侧双击该脚本, 之后点击![](img_md/2018-04-15-15-41-16.png)运行

- - -

- **Start Page**  
- [脚本绘图基础](base.md)  
- [demo](demo.md)  