cnblogs-theme-simple
====

简单的博客园纯`css`主题，PC端是左右布局，移动端将导航栏移到上面，没有多余的元素。

[这里可以看例子](https://www.cnblogs.com/fwindpeak/)

## 使用

- 在`设置`中随便选一个`博客皮肤`,比如`custom`
- 将本仓库的`csutom.css`内容复制粘贴到`设置`->`页面定制 CSS 代码`中
- 勾选`禁用模板默认CSS`
- `选项`内的侧边栏控件就全都不要勾选了(~~没有任何处理，放出来会比较丑~~)



## 定制


几个颜色变量已经提取出来了，可以直接修改成自己喜欢的样子

```css
:root {
  --color-primary: #005a9b; /*重点文字颜色*/
  --color-blog-title: #ddd; /*博客标题颜色*/
  --color-nav-text: #ccc; /*导航栏文字颜色*/
  --color-nav-background: #002d4f; /*导航栏背景色*/
  --color-main-text: #1d2d4f; /*主界面文字颜色*/
  --color-main-background: #eee; /*主界面背景色*/
}
```