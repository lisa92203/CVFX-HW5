ISA525700 Computer Vision for Visual Effects<br/>Homework 5
===

## Our multi-view images

我們總共拍攝了四組照片，自己的娃娃，圍繞他一共拍攝了五張。

|![](https://i.imgur.com/hebv2Ox.jpg)|![](https://i.imgur.com/2U5PVdN.jpg)|![](https://i.imgur.com/2zQVn2c.jpg)|![](https://i.imgur.com/UJbqZ62.jpg)|![](https://i.imgur.com/pOJATKV.jpg)|
|---|---|---|---|---|

## Image alignment results

我們將兩兩配對的圖片第二張對第一張進行align。

|Feature Matching|Image Alignment|
|---|---|
|![](https://i.imgur.com/DvU7O2K.jpg)|![](https://i.imgur.com/ePyE7QB.jpg)|
|![](https://i.imgur.com/vZacpcC.jpg)|![](https://i.imgur.com/tNMMsMM.jpg)|

## Multi-view 3D visual effects

### Motion parallax

#### 卡納赫拉伊布

|Original|Image Alignment|
|---|---|
|||

#### 謎你Q

|Original|Image Alignment|
|---|---|
|[Imgur](https://i.imgur.com/twdyWwj.gifv)|![](https://i.imgur.com/l4XraDp.gif)|

### Stop motion

#### 卡納赫拉伊布

|Original|Image Alignment|
|---|---|
|||

#### 花語清華

|Original|Image Alignment|
|---|---|
|||

## Bonus

### Motion parallax

### Stop motion

### Live Photo

在這個部分我們對三種方法進行比較，首先，Original Live Photo是原本用iPhone原況照片模式拍出來的，他是直接紀錄使用者拍攝照片前後1.5秒的動態，並沒有進行處理，因此若是手在這3秒內有晃動到，Live Photo就會如實地呈現出來，接著，Motion Still是將前述的Live Photo放進Motion Still的APP裡面讓他進行穩定的結果，可以從結果中看到效果非常好，基本上只有貓、手和後面的人車有在動，整體非常穩定，最後的Image Alignment是利用Image Alignment的結果來達到穩定的效果，可以看到也是相當穩定，只是邊緣偶爾會有一些因為Image Alignment造成圖片歪斜扭曲導致的黑框，再做Crop把邊緣切掉只留中間效果應該會更好，不過為了讓三個結果的視野一致，我們就沒有再做這部份了。

|Original Live Photo|Motion Still|Image Alignment|
|---|---|---|
|![](https://i.imgur.com/0l5yZAr.gif)|![](https://i.imgur.com/1RvQh2r.gif)|![](https://i.imgur.com/R7P76BO.gif)|
