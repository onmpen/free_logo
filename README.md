# Logo_Thief V1.0.0

<img src="https://github.com/quarkape/Free_Logo/blob/main/img/free_logo.png" alt="image" style="width:100px" />

一个可以帮助你快速、免费下载自定义尺寸的LOGO的浏览器插件

---

### :sunny: 目标网站

- [直接跳转受害网站(插件只能在目标网站的logo编辑页面生效！)](https://www.logomaker.com.cn//)

---

### :leaves: 国内镜像

- [GitHub项目地址](https://github.com/quarkape/Free_Logo)
- [Gitee项目地址(国内镜像)](https://gitee.com/huewhom/Free_Logo)

---

### :sailboat: 目标浏览器

- 经过测试，谷歌浏览器与Edge浏览器可以正常使用

---

### :jack_o_lantern: Google Chrome安装方法

1. 将完整的项目下载下来
2. 在地址栏输入`chrome://extensions/`回车，进入扩展程序管理页面
3. 右上角开发者模式开启
4. 左上角点击**加载已解压的扩展程序**，选择从本项目即可
5. 加载完成后，在浏览器右上角会出现一个拼图的图标，单击该图标，找到本插件Logo Thief，点击后面的图钉图标可以将该插件固定，便于频繁使用。

---

### :snowboarder: Edge安装方法

1. 将完整的项目下载下来
2. 在地址栏输入`edge://extensions/`回车，进入扩展程序管理页面
3. 左边开发者模式开启
4. 在页面中找到**加载已解压的扩展程序**并点击，选择从本项目即可
5. 加载完成后，在浏览器右上角会出现一个拼图的图标，单击该图标，找到本插件Logo Thief，点击后面的眼睛图标可以使该插件在工具栏中显示，便于频繁使用。

---

### :badminton: 使用方法

1. 进入目标网站
2. 输入合适的信息，选择合适的LOGO并进入编辑页面
3. 在编辑页面编辑LOGO直到满意为止
4. 点击插件，在弹出的窗口中输入想要的LOGO的宽度（单位为px，默认为680，比例为34：25，即默认为680*500）
5. 继续选择是否要保留LOGO背景（默认为不保留，即背景为透明，便于转换成.png格式的文件）
6. 配置好后，点击开始处理

---

### :hammer_and_wrench: 后续步骤

- 下载下来的logo_thief.svg文件在很多地方都能用，也能直接用浏览器打开。
- 如果你需要转换成.png格式，可以尝试以下步骤：
  1. 如果你的电脑上还有Internet Explorer，即IE浏览器的话，可以直接将.svg文件用IE浏览器打开，然后在LOGO上面鼠标右键，另存为，选择格式为.png，选择想要保存的位置（一般是桌面）即可完成。
  2. 如果你电脑上已经没有IE，可以使用Edge的IE模式重新加载页面。首先在Edge中打开logo_thief.svg文件，然后点击浏览器右上角用户头像左边的按钮，稍等片刻，Edge浏览器会在IE模式下重新加载页面。加载完成后浏览器工具栏会弹出提醒，此时按照第一步右键另存为.png格式的图片就可以了。
  3. 如果上述两种方案都无法解决，你可以使用在线的svg转png的方式。不过亲测在线的转换效果比较差。

---

### :palm_tree: 配置说明

- 原LOGO尺寸为340*250，比例固定，因此建议配置LOGO宽度的时候设置为34的倍数，这样可以保障LOGO不会变形，当然，不设置成倍数影响也不大，LOGO不会有明显的变形，或者肉眼根本看不出来。如果不配置宽度，插件默认为680**500。
- LOGO的大小没必要越大越好，个人认为：
  1. 如果用作网页favicon图标，用34就够了
  2. 如果用作一般的网页或者作品的LOGO，用340就行了
  3. 如果要用作打印，A4纸大小，340~4000就行了
  4. 如果要打印大的海报，且LOGO占很大面积，可以试试最大6800
- 经过测试，更大的宽度，比如34000，在用IE转换为.png格式的时候会报错“意外的调用了属性或方法”，因此将最大宽度限定于6800。不过应该也够用了。如果有特殊需求的，例如只需要svg文件并且希望更大宽度的，可以单独提issue。当然你也可以自行修改最大宽度，只需要：

  1. 找到`js/content.js`文件并打开
  2. 将第7行的6800修改为你想要的最大值就可以了，最大能多大我不清楚，不过我试过34000，可以导出svg，但是用Edge转PNG的时候会失败。
  3. 注意修改之后需要在扩展程序管理页面刷新这个插件；或者把这个插件移除了，再重新添加进来。
- 编辑好的logo一般会居于整个图片中间，可以自行使用PS等工具裁剪。



