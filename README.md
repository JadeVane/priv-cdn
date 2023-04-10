
## 说明

此仓库用于存放个人博客常用字体，如有侵权，请联系我删除。

## 已包含字体

- **AlibabaPuHuiTi**：阿里巴巴普惠体2.0版本，用于正文及大部分内容，包含Regular（正常字重，用于正文）和SemiBold（中黑，用于标题）两种字重
- **Times New Roman**：标题英文字体
- **Fira Code**：代码字体
- **FZQingKeBenYueSongS**：方正清刻本悦宋简体，字体已精简，仅包含博客名称所涉及的字

## 使用方法

```bash
/* -------------------------- Times New Roman -------------------------- */
@font-face {
    font-family: "Times New Roman";
    font-display: optional;
    src: url("https://cdn.jsdelivr.net/gh/JadeVane/fonts-cdn/TimesNewRoman-Regular.woff2") format("woff2");
}

/* -------------------------- Times New Roman -------------------------- */
@font-face {
    font-family: "Fira Code";
    font-display: optional;
    src: url("https://cdn.jsdelivr.net/gh/JadeVane/fonts-cdn/FiraCode-Regular.woff2") format("woff2");
}

/* -------------------------- 方正清刻本悦宋简体 -------------------------- */
@font-face {
    font-family: "方正清刻本悦宋简体";
    src: url('https://cdn.jsdelivr.net/gh/JadeVane/fonts-cdn/FZQingKeBenYueSongS-R-GB.woff2') format('woff2');
    font-display: optional;
}

/* -------------------------- 阿里巴巴普惠体 -------------------------- */
@font-face {
    font-family: "AlibabaPuHuiTi";
    font-display: optional;
    font-weight: normal;
    src: url('https://cdn.jsdelivr.net/gh/JadeVane/fonts-cdn/AlibabaPuHuiTi-2-55-Regular.woff2') format('woff2');
}
@font-face {
    font-family: "AlibabaPuHuiTi";
    font-display: optional;
    font-weight: 600;
    src: url('https://cdn.jsdelivr.net/gh/JadeVane/fonts-cdn/AlibabaPuHuiTi-2-75-SemiBold.woff2') format('woff2');
}
```