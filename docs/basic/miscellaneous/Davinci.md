---
tags:
    - Ongoing
---

# Davinci Resolve

## 基本操作

### 进入项目

| 组合       | 功能           |
| ---------- | -------------- |
| ++ctrl+s++ | 命名并保存项目 |

在偏好设置-用户-项目保存和加载中，开启实时保存和项目备份。

在导入素材前，进入文件-项目设置-设定好项目帧率。一般为 25。并修改项目缓存文件位置，避免 C 盘被占满。

??? info "关于帧率"
选用 25 帧是因为国内的交流电是 50 Hz，使用 50 分之 1 的快门拍摄视频可以更好地规避灯光的频闪。

-   基本剪辑操作

### 剪辑面板

-   素材监视器
    -   按下 ++i++ ++o++ 键打下出点、入点，拖入素材轨道。
-   特效库面板
    -   拖入转场和特效
-   检查器面板
    -   调整参数
        打关键帧

| 组合             | 功能       |
| ---------------- | ---------- |
| ++alt++ 鼠标滚轮 | 缩放时间线 |
| ++b++            | 切刀工具   |

-   修剪编辑模式 ++t++
    -   拖动剪辑素材时，后方素材跟着移动。
    -   适合精剪时调整各个片段的内容。
-   动态修剪模式
    -   很少用

三种插入模式

-   插入：到播放头的位置，后方片段自动后移。
-   覆盖：所有片段位置不动，只覆盖现有内容。
-   替换：自动替换当前片段，总时长和别的片段不受影响。

功能性设置：

-   磁铁：自动吸附。
-   音视频链接。
    -   选中片段按下 ++f++ 在素材监视器中定位到该片段位置。
-   锁定：无法移动时间线上片段的位置。

标注功能：

-   旗标：整段原素材。
-   标记：作用在时间线上。

### 调色面板

-   预设区
-   节点区

### Fairlight 面板

### 交付面板

-   互联网传播标准：MP4 格、H.264 编码、25 fps。

## 快编界面

基本逻辑：磁带封装素材。

## 效果

### 基础：添加效果与关键帧

-   检查器

    -   按住 ++alt++ 再拖动可以精细调整数据。

-   ++alt+v++ 粘贴属性。
-   文件-项目设置-图像缩放与调整：调整至全帧并裁切超出部分。
