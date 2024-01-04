---
title: Home
hide:
  #- navigation # 显示右
  #、- toc #显示左
  - footer
  - feedback
---
# Home

<!-- <center><font  color= #518FC1 size=6>“循此苦旅，以达星辰”</font></center> -->
<center><font  color= #518FC1 size=6 class="ml3">“纵使困顿难行，亦当砥砺奋进”</font></center>
<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>


<center>
<font  color= #608DBD size=3>
<span id="jinrishici-sentence">正在加载今日诗词....</span>
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
</font>
</center>

<div id="rcorners2" >
  <div id="rcorners1">
    <!-- <i class="fa fa-calendar" style="font-size:100"></i> -->
    <body>
      <font color="#4351AF">
        <p class="p1"></p>
<script defer>
    //格式：2020年04月12日 10:20:00 星期二
    function format(newDate) {
        var day = newDate.getDay();
        var y = newDate.getFullYear();
        var m =
            newDate.getMonth() + 1 < 10
                ? "0" + (newDate.getMonth() + 1)
                : newDate.getMonth() + 1;
        var d =
            newDate.getDate() < 10 ? "0" + newDate.getDate() : newDate.getDate();
        var h =
            newDate.getHours() < 10 ? "0" + newDate.getHours() : newDate.getHours();
        var min =
            newDate.getMinutes() < 10
                ? "0" + newDate.getMinutes()
                : newDate.getMinutes();
        var s =
            newDate.getSeconds() < 10
                ? "0" + newDate.getSeconds()
                : newDate.getSeconds();
        var dict = {
            1: "一",
            2: "二",
            3: "三",
            4: "四",
            5: "五",
            6: "六",
            0: "天",
        };
        //var week=["日","一","二","三","四","五","六"]
        return (
            y +
            "年" +
            m +
            "月" +
            d +
            "日" +
            " " +
            h +
            ":" +
            min +
            ":" +
            s +
            " 星期" +
            dict[day]
        );
    }
    var timerId = setInterval(function () {
        var newDate = new Date();
        var p1 = document.querySelector(".p1");
        if (p1) {
            p1.textContent = format(newDate);
        }
    }, 1000);
</script>
      </font>
      <script src="//code.tidio.co/9nlf5gckl1ccohgladffzb827bnlqpjw.js" async></script>
    </body>
    <!-- <b><span id="time"></span></b> -->
  </div>
  <ul>
    <li>通过主题和目录以打开文章</li>
    <ul>
      <li>Mac/PC端 请在上方标签栏选择主题 在左侧目录选择文章</li>
      <li>移动端 请点击左上角图标选择主题和文章</li>
    </ul>
    <li>搜索关键词以打开文章</li>
    <li>
      如遇到网页卡顿/打开文章后无法显示图片的情况，请使用<strong>科学上网</strong>以打破信息壁垒
    </li>
  </ul>
</div> 
本站访问量：<script async src="//finicounter.eu.org/finicounter.js"></script>
<span id="finicount_views"></span>