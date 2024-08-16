### 透過 Hugo Markdown 中使用 Shortcode 畫出 Plantuml
Plantuml 是一個可以透過文字畫圖的語法
可以在短時間內畫出漂亮且易於溝通的文字
此 Repo 主要說明了如何在你的 Hugo Markdown 文件中
透過 Shortcode 插入圖片
相關效果以及撰寫，請參考 [Plantuml](https://plantuml.com/zh/)

***聲明*** 此 code 是直接參考 [Mogeko's Blog](https://mogeko.me/zh-cn/posts/zh-cn/083/) 的文章以及其撰寫的 Code，手動修改為 shortcode 形式

### 如何使用
請下載這份檔案 [plantuml.html](https://github.com/yoyoshenTW/hugo-shortcode-plantuml/blob/main/layouts/shortcodes/plantuml.html)
並將他放在你 Hugo 網站的根目錄的 *layouts/shortcodes* 底下
即可完成

接著在你的 markdown 文件中(例如 index.md)
在需要畫圖的地方，引用此 shortcode，並在中間寫入你的 Plantuml
在經過渲染後即可實現

#### Example
```
{{< plantuml >}}
Bob王 -> Alice張
Bob王 <- Alice張
{{< /plantuml >}}
```
<hr/>

### Using Shortcode to Render Plantuml in Hugo Markdown
Plantuml is a syntax that allows you to create diagrams using text.
It enables you to quickly produce beautiful and easy-to-communicate visual representations.
This repository mainly explains how to insert images into your Hugo Markdown documents through Shortcodes.
For related examples and writing instructions, please refer to [Plantuml](https://plantuml.com/).

***Disclaimer*** This code is directly referenced from the article and code on [Mogeko's Blog](https://mogeko.me/zh-cn/posts/zh-cn/083/), and has been manually modified into a shortcode format.

### How to Use
Please download this file [plantuml.html](https://github.com/yoyoshenTW/hugo-shortcode-plantuml/blob/main/layouts/shortcodes/plantuml.html)
and place it in the *layouts/shortcodes* directory at the root of your Hugo website.
This will complete the setup.

In your markdown files (e.g., index.md),
directly reference this shortcode where you need to create a diagram and write your Plantuml code within it.
Once rendered, the diagram will be displayed.

#### Example
```
{{< plantuml >}}
Bob -> Alice
Bob <- Alice
{{< /plantuml >}}
```
