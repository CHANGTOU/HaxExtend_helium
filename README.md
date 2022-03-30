[![HaxExtend](https://github.com/mybdye/HaxExtend_helium/actions/workflows/main.yml/badge.svg?event=workflow_dispatch)](https://github.com/mybdye/HaxExtend_helium/actions/workflows/main.yml)
#### 计划
- 
#### 项目进度
- 0330 添加了 tg push，workflow 也还有些问题
- 0328 ~~能跑~~ 本地能跑，workflow 再研究下。
- 0326 新建文件夹

#### 🍳 烹饪方法：1.1 Settings > Secrets > Actions 添加以下变量
```
USER_ID
```
```
PASS_WD
```
```
BARK_KEY
``` 
```
TG_BOT_TOKEN
```
```
TG_USER_ID
```
```BARK_KEY``` ```TG_BOT_TOKEN``` ```TG_USER_ID``` 可选，不填就没推送。 ```https://api.day.app/BARK_KEY/```
#### 🍳 烹饪方法：1.2 Actions > Workflows [HaxExtend] > Run workflow
<img src=http://mjjzp.cf/img/2022/03/30/e9512058f9026.png width=50% />


#### 触发说明：手动 + schedule
```
name: 'HaxExtend'

on:
  #push:
  schedule:
    # run everyday at UTC 04:30 (CN time UTC+8)
     - cron: '30 4 * * *'
  # Allows you to run this workflow manually from the Actions tab
  workflow_dispatch:
```

#### 运行结果
```
*** 💣 Possibly blocked by google! ***
Your computer or network may be sending automated queries. To protect our users, we can't process your request right now. For more details visit our help page.
```
or
```
 🎉 Your VPS has been renewed until April 6, 2022
```
<img src=http://mjjzp.cf/img/2022/03/30/9c291b0d7366c.jpg width=50% />

#### How This Work
- https://github.com/mybdye/HaxExtend_helium/blob/master/howthiswork.md

#### 资料参考
- https://www.python.org/
- https://www.selenium.dev/
- https://www.youtube.com/watch?v=As-_hfZUyIs
- https://github.com/actions/virtual-environments/blob/main/images/macos/macos-12-Readme.md
- https://github.com/mherrmann/selenium-python-helium/blob/master/helium/__init__.py

#### 以上仅供学习 ：）
