# Material主题语法补充

### 1. Tab 分栏

> pymdownx.tabbed

!!! example "Example Details"

    === "效果"
        Markdown **content**.
    
        Multiple paragraphs.
    
    === "语法"
        More Markdown **content**.
    
        - list item a
        - list item b

### 2. ProgressBar 进度条

PyMdown的扩展，依赖模块：**attr_list**，使用添加 *pymdownx.progressbar* 即可

!!! example "进度条 示例"

    === "效果"
        [=0% "0%"]
        [=5% "5%"]
        [=25% "25%"]
        [=45% "45%"]
        [=65% "65%"]
        [=85% "85%"]
        [=100% "100%"]
    
    === "语法"
        ```
        [=0% "0%"]
        [=5% "5%"]
        [=25% "25%"]
        [=45% "45%"]
        [=65% "65%"]
        [=85% "85%"]
        [=100% "100%"]
    	```
阿达

!!! example "带参数的进度条 示例"

    === "效果"
        [=85% "85%"]{: .candystripe}
        [=100% "100%"]{: .candystripe .candystripe-animate}
        [=0%]{: .thin}
        [=5%]{: .thin}
        [=25%]{: .thin}
        [=45%]{: .thin}
        [=65%]{: .thin}
        [=85%]{: .thin}
        [=100%]{: .thin}
    
    === "语法"
        ```
        [=85% "85%"]{: .candystripe}
        [=100% "100%"]{: .candystripe .candystripe-animate}
        [=0%]{: .thin}
        [=5%]{: .thin}
        [=25%]{: .thin}
        [=45%]{: .thin}
        [=65%]{: .thin}
        [=85%]{: .thin}
        [=100%]{: .thin}
    	```



### 3. Keys 按键

按键是一个来自PyMdown的扩展，使输入和样式化键盘按键更加容易。通过`+`符号构建 。按键或按键组合被包围`++`，每个按键之间都用单个分隔`+`。

!!! quote "按键实例"
    ```
    ++ctrl+alt+delete++
    ++1+a+space++
    ++f1+f2+f3++
    ```
​    ++ctrl+alt+delete++<br>
​    ++1+a+space++<br>
    ++f1+f2+f3++

#### 3.1 标点

| 使用            | 显示              | 别名                 |
| :-------------- | :---------------- | :------------------- |
| `backslash`     | ++backslash++     |                      |
| `bar`           | ++bar++           | `pipe`               |
| `brace-left`    | ++brace-left++    | `open-brace`         |
| `brace-right`   | ++brace-right++   | `close-bracket`      |
| `bracket-left`  | ++bracket-left++  | `open-bracket`       |
| `bracket-right` | ++bracket-right++ | `close-brace`        |
| `colon`         | ++colon++         |                      |
| `comma`         | ++comma++         |                      |
| `double-quote`  | ++double-quote++  | `dblquote`           |
| `equal`         | ++equal++         |                      |
| `exclam`        | ++exclam++        | `exclamation`        |
| `grave`         | ++grave++         | `grave-accent`       |
| `greater`       | ++greater++       | `greater-than`, `gt` |
| `less`          | ++less++          | `less-than`, `lt`    |
| `minus`         | ++minus++         | `hyphen`             |
| `period`        | ++period++        |                      |
| `plus`          | ++plus++          |                      |
| `question`      | ++question++      | `question-mark`      |
| `semicolon`     | ++semicolon++     |                      |
| `single-quote`  | ++single-quote++  |                      |
| `slash`         | ++slash++         |                      |
| `tilde`         | ++tilde++         |                      |
| `underscore`    | ++underscore++    |                      |

#### 3.2 修改键

| 使用            | 显示            | 别名                              |
| :-------------- | :-------------- | :-------------------------------- |
| `alt`           | ++alt++         | `menu`                            |
| `command`       | ++command++         | `cmd`                             |
| `control`       | ++control++        | `ctrl`                            |
| `function`      | ++function++          | `fn`                              |
| `left-alt`      | ++left-alt++    | `lalt`, `left-menu`, `lmenu`      |
| `left-control`  | ++left-control++   | `lcontrol`, `lctrl`, `left-ctrl`  |
| `left-shift`    | ++left-shift++  | `lshift`                          |
| `left-windows`  | ++left-windows++    | `left-win`, `lwin`                |
| `meta`          | ++meta++        |                                   |
| `option`        | ++option++     | `opt`                             |
| `right-alt`     | ++right-alt++   | `ralt`, `right-menu`, `rmenu`     |
| `right-control` | ++right-control++  | `rcontrol`, `rctrl`, `right-ctrl` |
| `right-shift`   | ++right-shift++ | `rshift`                          |
| `right-windows` | ++right-windows++    | `right-win`, `rwin`               |
| `shift`         | ++shift++       |                                   |
| `windows`       | ++windows++         | `win`                             |

#### 3.3 其他键

| Name                | Display               | Aliases        |
| :------------------ | :-------------------- | :------------- |
| `backtab`           | ++backtab++           | `bktab`        |
| `browser-back`      | ++browser-back++      |                |
| `browser-favorites` | ++browser-favorites++ | `favorites`    |
| `browser-forward`   | ++browser-forward++   | `forward`      |
| `browser-forward`   | ++browser-forward++   |                |
| `browser-refresh`   | ++browser-refresh++   | `refresh`      |
| `browser-search`    | ++browser-search++    | `search`       |
| `browser-stop`      | ++browser-stop++      |                |
| `copy`              | ++copy++              |                |
| `context-menu`      | ++context-menu++      | `apps`         |
| `mail`              | ++Mail++              | `launch-mail`  |
| `media`             | ++media++             | `launch-media` |
| `media-next-track`  | ++media-next-track++  | `next-track`   |
| `media-pause`       | ++media-pause++       | `pause`        |
| `media-play`        | ++media-play++        | `play`         |
| `media-play-pause`  | ++media-play-pause++  | `play-pause`   |
| `media-prev-track`  | ++media-prev-track++  | `prev-track`   |
| `media-stop`        | ++media-stop++        | `stop`         |
| `print`             | ++print++             |                |
| `reset`             | ++reset++             |                |
| `select`            | ++select++            |                |
| `sleep`             | ++sleep++             |                |
| `volume-down`       | ++volume-down++       | `vol-down`     |
| `volume-mute`       | ++volume-mute++       | `mute`         |
| `volume-up`         | ++volume-up++         | `vol-up`       |
| `zoom`              | ++zoom++              |                |

#### 3.4 鼠标

| 使用            | 显示              | 别名       |
| :-------------- | :---------------- | :--------- |
| `left-button`   | ++left-button++   | `lbutton`  |
| `middle-button` | ++middle-button++ | `mbutton`  |
| `right-button`  | ++right-button++  | `rbutton`  |
| `x-button1`     | ++x-button1++     | `xbutton1` |
| `x-button2`     | ++x-button2++     | `xbutton2` |

### 4. Detail 注解

写注解使用，依赖模块：**admonition**

支持多种样式，如带有标题、无标题、空标题，还支持折叠式(常用于FAQ)，

支持多种颜色风格，包括警告提示、错误提示、成功提示等11种风格，

这有11种样式，每一种样式都支持多种关键字，比如 note 可以用 seealso 替代，summary可以用tldr替代，当首标志为`!!!`时，默认是开启该注解的，`???`则为折叠状态，依赖模块: pymdownx.details，注意，折叠状态在浏览器内通过++ctrl+f++无法搜索到。

```
!!! example "example"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! example "example"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! note "note, seealso"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! note "note, seealso"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! summary "summary, tldr"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! summary "summary, tldr"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! info "info, todo"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! info "info, todo"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! tip "tip, hint, important"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! tip "tip, hint, important"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! success "success, check, done"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! success "success, check, done"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! question "question, help, faq"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! question "question, help, faq"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! warning "warning, caution, attention"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! warning "warning, caution, attention"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! failure "failure, fail, missing"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! failure "failure, fail, missing"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! danger "danger, error"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! danger "danger, error"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! bug "bug"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! bug "bug"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

```
!!! quote "quote, cite"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

!!! quote "quote, cite"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### 5. footnotes 脚注

依赖模块: footnotes

第一步，插入引用

```markdown
Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]
```

第二步，插入内容

```markdown
[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
[^2]: Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
	  Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, 
	  justo purus auctor massa, nec semper lorem quam in massa.
```

可以看到，上面脚注1内容是单行方式，脚注2内容是多行方式

查看效果：

Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]

!!! tip "注意"

	1. 不一定要用[\^1]，也可以用自定义关键字，比如[\^mykey]，但这样下面也要改为[\^mykey]，也可以支持空格，比如[\^my key]（当然后面也要[\^my key]:
	
	2. 无论脚注标签写的是什么（即[\^1]或者[^mykey]，在展示脚注标签和展示脚注内容时候都是自动用数字从1开始累加标记，而不是自己写的内容）
	
	3. [\^1]: 脚注内容无论写在.md中的任何位置，在展示时候都是自动位于文档的最下方，并且会自动添加`---`这样一个横线
	
	---

### 6. Highlight 高亮

例如：

```markdown
Here is some {--*incorrect*--} Markdown.  I am adding this{++ here++}.  Here is some more {--text
 that I am removing--}text.  And here is even more {++text that I 
 am ++}adding.{~~

~>  ~~}Paragraph was deleted and replaced with some spaces.{~~  ~>

~~}Spaces were removed and a paragraph was added.

And here is a comment on {==some
 text==}{>>This works quite well. I just wanted to comment on it.<<}. Substitutions {~~is~>are~~} great!

General block handling.

{--

* test remove
* test remove
* test remove
    * test remove
* test remove

--}

{++

* test add
* test add
* test add
    * test add
* test add

++}
```

效果：

Here is some {--*incorrect*--} Markdown.  I am adding this{++ here++}.  Here is some more {--text that I am removing--}text.  And here is even more {++text that I  am ++}adding.{~~ ~>  ~~}Paragraph was deleted and replaced with some spaces.{~~  ~> ~~}Spaces were removed and a paragraph was added. And here is a comment on {==some text==}{>>This works quite well. I just wanted to comment on it.<<}. Substitutions {~~is~>are~~} great! General block handling. {-- * test remove * test remove * test remove    * test remove * test remove --} {++ * test add * test add * test add    * test add * test add ++}