<b>京东穿行寻宝 一键完成任务脚本来袭</b>

活动地址：
https://wbbny.m.jd.com/pb/013349910/3rFiv8Sdkn7BPhk8Pw8xrgMWH6mT/index.html#/home

<hr>

**脚本使用方法：**


1、python脚本，依赖requests库，需要将cookie放在ck.txt文件

```
pip install requests
```


2、参数设置

    task_times     #循环任务次数，可以多跑几次没事
    sleep_times  #间隔时间，默认在任务所需的基础上加，我设置的5s左右，看自己

3、脚本可以完成逛店，加购等任务

4、将py文件件跟ck.txt放一起运行，没ck.txt的自己创建个，多账号的话换行放cookie即可

5、本次增加了给作者助力的功能，不想助力输入n后回车即可

截图：
试了几个号暂时看着没啥问题，运行截图

<img src='https://pic.rmb.bdstatic.com/bjh/ff2c443ee74736e86176d12bae878771.png'>

**Cookie抓取：**<br>
不会抓cookie的看这里<br>
一、直接使用上传得软件打开后，京东扫二维码获取<br>
二、利用浏览器抓包<br>

1.推荐使用chrome浏览器，打开浏览器，按F12选择手机模式

<img src='https://image.planet.youku.com/img/100/28/62238/i_1490875862238_165fa22eca1c6c8c43f9b38b8b50a1f0_b_w855h277_face_w855h277_x0y0w0h0c0.png'>

2.浏览器的 User-Agent 必须包含 jdapp，设置含有jdapp的user-agent，设置完成【save后记得选择刚保存的user-agent】

exp:

jdapp;iPhone; CPU iPhone OS 5_0 like Mac OS X) AppleWebKit/534.46 (KHTML, like Gecko) Version/5.1 Mobile/9A334 Safari/7534.48.3
<img src='https://image.planet.youku.com/img/100/28/62238/i_1490875862238_5d8af6a784d21741be12bb7efb78a4f4_b_w1006h479_face_w1006h479_x0y0w0h0c0.png'>

3.访问 https://wbbny.m.jd.com/babelDiy/Zeus/2s7hhSTbhMgxpGoa9JDnbDzJTaBB/index.html#/home
 登录京东账号【save后记得选择刚保存的user-agent】

4.登录后，点击network，然后活动中的任务列表，在network中找到那个请求的接口，把Headers 中的Cookie复制出来，直接document出来的貌似失败
<img src='https://pic.rmb.bdstatic.com/bjh/aa2e811c0bcfabcdf5fee405d8ccf2e4.png'>
