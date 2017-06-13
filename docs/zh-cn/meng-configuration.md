# 萌配置

萌选项是为二次元爱好者推出的一项功能，默认为`false`。

你可以在`_data/site.yml`中将`meng`字段改为`true`。

```yaml
meng: true
```

## 如何使用

你需要创建`meng.yml`到`_data`文件夹内。

```yaml
title:  # Meng title
  switch: true # Meng title switch
  visible: "(*´∇｀*) 被发现啦~" # State is visible text
  hidden:  "(つェ⊂)看不到我~" # State is hidden text
  with_default_title: true # with default title
  reset_time: 1000 # If state is visible , reset default title times(ms)

cursor: # cursor
  switch: true # cursor switch
  auto_url: "https://ooo.0o0.ooo/2017/06/12/593ea1901c930.png" # State is auto style
  pointer_url: "https://ooo.0o0.ooo/2017/06/12/593ea3612fd77.png" # State is pointer style

console: # Meng console info
  switch: true # Meng console info switch
  theme_info: true # output theme info
  text: "Copyright © 2017 Jekyll-Theme-MDUI" # text
  color: "#fff" # text color
  background: "#448aff" # background color

header: # Meng header color + theme-color
  switch: true
```

## 参数详解

### title

萌标题

#### switch

萌标题开关，默认为`true`。

#### visible

当浏览器状态为`visible`时的标题文本。

#### hidden

当浏览器状态为`hidden`时的标题文本。

#### with_default_title

是否与默认标题一起显示，并作为后缀。

#### reset_time

当浏览器状态为`visible`时，重置为默认标题的延迟。

### cursor

萌光标

#### switch

萌光标开关

#### auto_url

`auto`状态下的样式

#### pointer_url

`pointer`状态下的样式

### console

萌 console info

#### switch

萌 console info 开关

#### theme_info

是否显示主题信息

#### text

自定义文本

#### color

文本颜色

#### background

背景颜色

### header

动态chrome状态栏、hearder颜色

#### switch

开关