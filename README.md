# YY Space Iconfont

这是一个开源的图标库，提供了一系列精心设计的空间科技相关图标。

## 安装

### 方式一：直接下载

1. 下载整个项目
2. 将以下文件复制到你的项目中：
   - `iconfont.css`
   - `iconfont.js`
   - `iconfont.ttf`
   - `iconfont.woff`
   - `iconfont.woff2`

### 方式二：通过 CDN 引入

```html
<link rel="stylesheet" href="https://space-huntsman.github.io/xayy-space-iconfont/iconfont.css">
<script src="
https://space-huntsman.github.io/xayy-space-iconfont/iconfont.js"></script>
```

## 使用方法

### 1. Unicode 引用

Unicode 是字体在网页端最原始的应用方式，特点是：
- 支持按字体的方式去动态调整图标大小，颜色等等。
- 默认情况下不支持多色，直接添加色值即可实现单色。

```html
<i class="yy-space">&#x33;</i>
```

### 2. Font Class 引用

Font Class 是 Unicode 使用方式的一种变种，主要是解决 Unicode 书写不直观，语意不明确的问题。

```html
<i class="yy-space icon-xxx"></i>
```

### 3. Symbol 引用

这是一种全新的使用方式，应用于：
- 支持多色图标
- 通过一些技巧，支持像字体那样，通过 `font-size`、`color` 来调整样式。

```html
<script src="iconfont.js"></script>

<svg class="icon" aria-hidden="true">
  <use xlink:href="#icon-xxx"></use>
</svg>
```

### 示例

```html
<!-- Unicode 方式 -->
<i class="yy-space">&#xe6a9;</i>

<!-- Font Class 方式 -->
<i class="yy-space icon-x-satellite"></i>

<!-- Symbol 方式 -->
<svg class="icon" aria-hidden="true">
  <use xlink:href="#icon-x-satellite"></use>
</svg>
```

## 图标预览

你可以通过访问 [在线预览](https://space-huntsman.github.io/xayy-space-iconfont) 查看所有可用的图标，并可以直接复制对应的代码。

## 图标列表

图标库包含以下类别的图标：
- 航天器部件（天线、太阳帆板等）
- 空间设施（空间站、卫星等）
- 测控元素（遥测、遥控等）
- 数据指标（温度、电压等）
- 空间环境（轨道、坐标等）

## 开发

本项目的所有图标源文件和生成的资源文件都位于根目录下。

## 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件 