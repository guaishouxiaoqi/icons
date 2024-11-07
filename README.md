<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/iconFont.png" alt="icons" width="200" height="165">
  </a>
</p>

<h3 align="center">icons</h3>
## icons 项目

本项目图标可用于 Quantumult X 订阅，Task，策略组等位置的远程引用

#### 本项目初衷用于自己日常需要，扩展一些不常用图标，项目中大部分图来源于 mini 项目，地址为：https://github.com/Orz-3/mini

### Quantumult X 使用方法：

#### 1、订阅图标

打开 QuantumultX 配置文件-编辑，找到［server_remote］字段，在想要增加图标的相应订阅中修改，在 enable ＝ true 之前加上
`img-url=https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Alpha/icon.png`
注意此句和前后句都要用英文逗号隔开，并且逗号后先要空一格

**完整示例：**`https://raw.githubusercontent.com/crossutility/Quantumult-X/master/server-complete.txt, tag=Sample-02, as-policy=static, img-url=https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Alpha/icon.png, enabled=false`

#### 2、策略图标

**2.1** UI 中使用

长按想要更改图标的策略组，弹出菜单选择编辑，在图标一栏填写

\*\*`https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/icon.png`

**2.2** 文本编辑：

打开 QuantumultX 配置文件-编辑，找到［policy］字段，在想要增加图标的相应策略段落中修改，在 enable ＝ true 之前加上
\*\*`img-url=https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/icon.png` 注意此句和前后句都要用英文逗号隔开，并且逗号后先要空一格

**完整示例：**`static=policy-name-1, Sample-A, Sample-B, Sample-C, img-url=https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/icon.png`

### Loon 使用方法：

**1** UI 中使用

点击下方“策略”选项卡，在策略界面点长按想要更改图标的订阅/策略组，弹出界面中，在图标一栏填写

\*\*`https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/icon.png`

**2** 文本编辑：
打开 Loon 配置选项卡，点击编辑-文本编辑，找到[Remote Proxy]/［Proxy Group］字段，在想要增加图标的相应订阅/策略段落中修改，加上 \*\*`img-url=https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/icon.png` 注意此句和前句要用英文逗号隔开

注：请将使用方法中的 icon.png 替换成相应文件的文件名

### Pharos Pro 使用方法：

在 Pharos Pro 主页对应订阅上左滑，点击编辑，在弹出界面的图标一栏中填入 `https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Alpha/icon.png`

### task 图标使用方法：

#### 1、文本编辑中使用

打开 QuantumultX 配置文件-编辑，找到［task_local］字段，在想要增加图标的相应签到脚本段落中修改，在 enable ＝ true 之前加上 `img-url=https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/icon.png` 注意此句和前后句都要用英文逗号隔开，并且逗号后先要空一格

#### 2、UI 中使用

主界面右下角点击风车开启菜单，然后找到调试一栏下的构造请求，点击进入构造请求界面，左滑相应 task，点击编辑，在图标一栏填写 `https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/icon.png`

🔘 彩色版本 `https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Color/icon.png`

🔘 透明版本 `https://raw.githubusercontent.com/guaishouxiaoqi/icon/master/Alpha/icon.png`

**注：** task 图标的透明和彩色版本文件名完全一致，仅所在库不同

##### 图标索引，请将使用方法中的，Color/Alpha 替换成对应的文件夹名， icon.png 替换成相应文件的文件名
