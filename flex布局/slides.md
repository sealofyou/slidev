--- 
# 头，设置
theme: seriph
background: https://sealphotobed.oss-cn-hangzhou.aliyuncs.com/seal/202211021705211.png
class: "text-center"
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
---
<!-- 第一页 -->
# 浮动与定位
---
layout: image-right
image: https://sealphotobed.oss-cn-hangzhou.aliyuncs.com/seal/202207112100310.webp
class: my-cool-content-on-the-right
---
# float 
`float` CSS属性指定一个元素应沿其容器的左侧或右侧放置，允许文本和内联元素环绕它。该元素从网页的正常流动(文档流)中移除，尽管仍然保持部分的流动性（与绝对定位相反）。

由于`float`意味着使用块布局，它在某些情况下修改display 值的计算值：
`display`为`inline`或`inline-block`时，使用`float`后会统一变成`block`。
---
layout: iframe-right
url: https://sealofyou.gitee.io/
class: my-cool-content-on-the-right
---
my blog
---
layout: center
---
## 位置 position
### 定位类型：
- 定位元素（positioned element）是其计算后位置属性为 relative, absolute, fixed 或 sticky 的一个元素（换句话说，除static以外的任何东西）。（默认）
- 相对定位元素（relatively positioned element）是计算后位置属性为 relative 的元素。
- 绝对定位元素（absolutely positioned element）是计算后位置属性为 absolute 或 fixed 的元素。
- 粘性定位元素（stickily positioned element）是计算后位置属性为 sticky 的元素。