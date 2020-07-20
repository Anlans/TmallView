# TmallView
# 公共页面
1. 顶部导航栏
    使用nav元素而不是div，不同之处在于，nav可以更加明确的告诉搜索引擎，这部分内容，是用于导航的，帮助搜索引擎理解你的网页。
    
2. 向右飘逸定位使用Bootstrap的pull-right样式

    ```css
    .pull-right {
      float: right !important;
    }
    ```


#### day03

---

公用搜索样式![1595212636617](C:\Users\12157\AppData\Roaming\Typora\typora-user-images\1595212636617.png)

图片的绝对定位做到图片和搜索栏div水平放置的效果，右侧搜索栏div套 子div，最后使用body样式设置全体页面

```css
img.simpleLogo {
    position: absolute;
    left: 10px;
    top: 50px;
    width: 140px;
}
```

