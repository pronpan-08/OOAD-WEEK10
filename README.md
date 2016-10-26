# OOAD-WEEK10

รูปที่1
```
@startuml
user -> button : Press(password)
button -> machine : [incorect prassword]Warning()
machine -> screen : [incorect prassword] Displaywarning()
screen -> machine : [corect prassword]Continue()
machine -> door : Unlock(door)
@endum
```

![](http://www.plantuml.com/plantuml/img/TSqn2W8n48NXFgT8cHHUm48Mz00sOY4MCHaqcCo4cOHbRs-4A2nYESptyoQfZclBIJK1rfkTlhLQ2VLM7nb4J74YCt6mQZmwoSu_8a8tbuYU67pLXGUydXrZnBknwkDw8fu1y4-X3r5ASilyBGTVR_rqUy8QiS5wAX1nvoTCv9_cVLar0OQMNm00)

รูปที่2
```
@startuml
user -> coinbox : []Insert(coin)
coinbox -> machine : []Sent(amount)
machine -> screen : [incorect prassword] Displayamount(amount)
user -> coinbox : [full]Insert(coin)
coinbox -> machine : []Sent(amount)
machine -> screen : [incorect prassword] Displayamount(amount)
machine -> lightBottonEachProduct : [enoughAmount]Lights()
user -> lightBottonEachProduct : []Press(product)
lightBottonEachProduct -> machine : []Sent(product type)
machine -> boxSentProduct : []Sent(product)
@endum
```

![](http://www.plantuml.com/plantuml/img/lP2x3i8m34NtV4N6Tk076511C20n836Y3Y4rD59gLx4ZwD-JyYnIkx9Ud-DSfs0nGMBZLMG8UhRGbXoUwARd-bXkCOMIzL6kteF4DCRM3k71700bCmr5b5oz1ubX6m2mHnnQ2c15jy4mNobKfLuxRhtfdjv77-bmZjx_lST0z-vIouf423SftGUgObgHrW5IlDJBXrBkUeopxmdJNhaFm9orpoHN4-JOUIz7IzV2Jylq7pqmV6KevAe0h69p1m00)

รูปที่3
```
@startuml
user -> button : []Press()
button -> machine : []SentCommand(NO)
machine -> screen : [] No()
screen -> machine : [incorect prassword]Warning()
machine -> screen : [incorect prassword] Displaywarning()
screen -> machine : [corect prassword]Continue()
machine -> screen : [] DisplayHomeManu()
user -> screen : []pressAppYoutube()
screen -> machine : []CommandOpenAppYoutube()
machine -> youtube : [] Open()
user -> youtube : [] SearchingMusic()
user -> machine : []Sentnamemusic()
machine -> youtube : []DisplaymusicVdo()
user -> youtube : []Serect(Vdomusic)
youtube -> machine : [] sentmusicVdo()
machine -> youtube : [] PlaymusicVdo()
@endum
```

![](http://www.plantuml.com/plantuml/img/TP7BQiCm44Nt_WejvKL_e8kIaYwwoGCCBQLueSX3AeX6OaOYvEyhstAHqsWxzymzrdZ3GL68zj941X9FB-8KGt0ediLtVoHWbcsJHocqIlyOX2dj0CFMMQjmaFj3sonPmbWJmDmXzYurvC6wmQ1s13e8JuhvwcZeFnMXmREij3tO46-6_KNThd-R3rt_zhOEWy48ilhXkVZTMTWfZ0bSJbHGVZpHg_TVBePuWfg-puSwUC0LNRXlyt2MZs1XN6KTA1gtphl8HXVK_Tz1PS5cfYBAZvoeZy5Lb1sCrvC9cC2sMS8xgU1aBRfghpkkbHl08TfV)

รูปที่4
```
@startuml
user -> button : []Press()
button -> machine : []SentCommand(NO)
machine -> screen : [] No()
screen -> machine : [incorect prassword]Warning()
machine -> screen : [incorect prassword] Displaywarning()
screen -> machine : [corect prassword]Continue()
machine -> screen : [] DisplayHomeManu()
user -> screen : []PressGallery()
screen -> machine : []SentCommandOpenGallery()
machine -> Gallery : [] Open()
user -> Gallery : [] SerectPhoto()
user -> botton : []PressShareOnInstargram(photo)
botton -> machine : []SentCommandshare(photo)
machine -> Instargram : [] Share(photo)
@endum
```

![](http://www.plantuml.com/plantuml/img/XL6zQiCm4Dxz51gLeI_GeGGIQ3iq3dZe439Sx2CMM7Vc917ozfKIkP5fJDVx_kxkMpiFueCTgk1GrCkREWNlcTIhEXptWixfLPL74RJGzeRmXZP8ViFM0dLwLw-g2OiqrmhYtKFjE3hamTp1KCk2hLUZW7CNbkxu3KA6pdh1xOb2ROqR1xXUVfLFi_xeDapUK42zk7Ws_c2BNq0X4gSN5QpRYzvX652kIzdbf-eHwK4lalFm7frOHTuCQp1Tik_PSq4vyRorfWV1cZufzNiMi7fCYjWb_zEbIyg9NIpuiCfxbBmrKXTizGC0)


รูปที่5
```
@startuml
user -> button : []Press(No)
button -> bord : []SentCommand(NO)
borde -> screen : [] No()
borde -> loudspeaker : [] No()
@endum
```

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuIejJYrIqBLJI2ejASdFKx1IY8uDA4ejBjRmozVaWWg2fFEBKi2ImQbv9SxvkRc9UIaQVlv09K29L92AukIYr5I80Gf--Hf8CZdvfId51Qc9sK2R4D8EgNaffRa0)




Sequence Diagram


README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
