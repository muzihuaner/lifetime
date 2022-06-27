# lifetime

人生倒计时网页小插件

![](tu.png)

### 演示地址

https://muzihuaner.github.io/lifetime

### 安装步骤

1、引入第三方库jquery

```html
 <script src="http://libs.baidu.com/jqueryui/1.9.1/jquery-ui.min.js"></script>
 <script src="https://ajax.aspnetcdn.com/ajax/jquery/jquery-1.9.0.min.js"></script>
```

2.引入CSS

```html
<link rel="stylesheet" href="https://fastly.jsdelivr.net/gh/muzihuaner/lifetime@main/style.css">
```

3.引入JS

```html
<script src="https://fastly.jsdelivr.net/gh/muzihuaner/lifetime@main/script.js"></script>
```

4.选择合适的位置引入HTML代码，在侧栏显示，感觉位置刚刚好

```html
<div class="box">
    <div class="aside aside-count">
        <div class="p-3">人生倒计时</div>
        <div class="content">
            <div class="item" id="dayProgress">
                <div class="title">今日已经过去<span></span>小时</div>
                <div class="progress">
                    <div class="progress-bar">
                        <div class="progress-inner progress-inner-1"></div>
                    </div>
                    <div class="progress-percentage"></div>
                </div>
            </div>
            <div class="item" id="weekProgress">
                <div class="title">这周已经过去<span></span>天</div>
                <div class="progress">
                    <div class="progress-bar">
                        <div class="progress-inner progress-inner-2"></div>
                    </div>
                    <div class="progress-percentage"></div>
                </div>
            </div>
            <div class="item" id="monthProgress">
                <div class="title">本月已经过去<span></span>天</div>
                <div class="progress">
                    <div class="progress-bar">
                        <div class="progress-inner progress-inner-3"></div>
                    </div>
                    <div class="progress-percentage"></div>
                </div>
            </div>
            <div class="item" id="yearProgress">
                <div class="title">今年已经过去<span></span>个月</div>
                <div class="progress">
                    <div class="progress-bar">
                        <div class="progress-inner progress-inner-4"></div>
                    </div>
                    <div class="progress-percentage"></div>
                </div>
            </div>
        </div>
    </div>
</div>

```

6.好了