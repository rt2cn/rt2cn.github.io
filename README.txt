# 如何使用你的 Twitter 存档

使用你的 Twitter 存档最简单的方法就是通过下载的文件中的存档浏览界面。只需双击根目录的 `index.html`，然后你就能在浏览器中查看你的全部历史推文。

---

在 `data` 文件夹下，你的 Twitter 存档是通过两种格式来保存的: JSON 和 CSV，并按照月份和年份输出。

* CSV 格式是一种可以被包括电子表格应用在内的许多数据应用导入的通用格式，也可以由编程语言直接读取使用。

## 为开发者使用的 JSON 格式

* JSON 输出文件中包含的推文格式与 Twitter API V1.1 的返回值相同。查看 https://dev.twitter.com/docs/api/1.1 以获取更多信息。
* 存档的浏览器界面 (index.html) 也使用 JSON 输出。
* 如需使用任何编程语言的通用 JSON 解析器解析输出的文件，请删除每个文件的第一行和最后一行。

加入论坛 https://dev.twitter.com，提供反馈、询问问题、与其他 Twitter 开发者分享创意。