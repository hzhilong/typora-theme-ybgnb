# typora-theme-ybgnb

> 因一直找不到适合自己的主题，所以想自己修改一个自用。先改个初版的吧，后续写md遇到问题的话再慢慢完善。
>
> 部分主题颜色选自VS Code中的One Dark Pro主题。

## 样式预览

![alt 属性文本](https://cdn.jsdelivr.net/gh/hzhilong/person-picture@main/img/2022-08/%E6%A0%B7%E5%BC%8F%E9%A2%84%E8%A7%88-1660188425.png)

## 使用指南

1. Typora - 菜单栏 - 文件 - 偏好设置 - 外观 - 打开主题文件夹
2. 将下载好的 `.css` 文件放到主题文件夹中，重启Typora
3. Typora - 菜单栏 - 主题 - 选择 - `Ybgnb Night`

> 本主题所用字体为 `更纱黑体 UI ` 和 `等距更纱黑体` ：[Sarasa-Gothic](https://github.com/be5invis/Sarasa-Gothic)

## 自定义

可打开 `.css` 文件，根据变量的注释，对主题的颜色和字体进行修改。

```css
:root {
    /* 正文字体 */
    --text-font: "更纱黑体 UI SC";
    /* 代码块字体 */
    --code-font: "等距更纱黑体 SC";
    /* 字体大小 */
    --text-size: 16px;
    /* 字体颜色 */
    --text-color: #abb2bf;
    ...
    ...
```



