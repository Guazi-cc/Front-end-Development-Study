## 01 Emmet 语法

Emment 语法的前身是 `Zen coding`，它使用缩写，来提高 HTML/CSS 的编写速度，Vscode 内部已经集成了该语法

### 1.1 快速生成 HTML 结构语法

1、生成标签，直接输入标签名按 `tab` 键即可，比如 `div` 然后 `tab` 键，就可以生成 `<div></div>`

2、如果想要生成多个相同标签，加上 `*` 就可以，比如 `div*3`，就可以快速生成3个 `<div></div>`

3、如果有父子级关系的标签，可以用 `>`，比如 `ul>li` 即可

4、如果有兄弟关系的标签，用 `+` 就可以了，比如 `div+p`

5、如果生成带有类名或者 id 名字的，直接写 `.class-name` 或者 `#id` 再按 `tab` 键就可以了

6、如果生成的 `div` 类名是有顺序的，可以用自增符号 `$`，比如如 `.demo$*5` 再按 `tab`

7、如果想要再生成的标签内部些内容可以用 `{}` 表示，比如 `div{好的}`



### 1.2 快速生成 CSS 样式语法

CSS 基本采取简写形式即可

1、比如 `w200` 按 `tab` 键就可以生成 `width: 200px`

2、比如 `lh26` 按 `tab` 键就可以生成 `line-height: 26px`



### 1.3 快速代码格式化

Vscode 快速格式化代码：`shift+alt+f`

**也可以设置 当我们保存页面的时候自动格式化代码**

1、文件 -> 首选项 -> 设置

2、搜索 emmet.include

3、再 settings.json 下的 `用户` 中添加以下语句：

```json
"editor.formatOnType": true,
"editor.formatOnSave": true
```

只需要设置一次即可，以后都可以自动保存格式化代码

- 再新版本 Vscode 中直接搜索 format，将保存自动格式化代码选项打勾即可

![image-20201026232237611](CSS-02.assets/image-20201026232237611.png)