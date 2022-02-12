# Office-Reader-Viewer
## Example
1. textAppend(String text)
```kotlin
   txt_smart.text="Hello"
   txt_smart.textAppend(" NoTin")
```
<img src="https://s3.envato.com/files/378510954/a1.png">

2. setTextColor(String colorString)
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTextColor("#FF0000")
```
<img src="https://imgur.com/AZ3u9F3.png">

3. setTextColor(int color, int startPos, int endPos)
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTextColor(Color.GREEN,0,6)
```
<img src="https://imgur.com/ZY1g1iW.png">

4. setTextColor(String colorString, int startPos, int endPos)
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTextColor("#0000EE",0,6)
```
<img src="https://imgur.com/0BL48AX.png">

5. setTextTop(float shiftPercentage,int startPos,int endPos)
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTextTop(0.5f,0,5)
```
<img src="https://imgur.com/L6HXlW2.png">

6. setStrikethrough()
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setStrikethrough()
```
<img src="https://imgur.com/py3toA9.png">

7. setStrikethrough(int startPos,int endPos)
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setStrikethrough(0,6)
```
<img src="https://imgur.com/JE3GLvT.png">

8. setTypeface(TypefaceSmart type)

**TypefaceSmart is an enum with the following values:**
* BOLD
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.BOLD)
```
<img src="https://imgur.com/Yomh83B.png">

* ITALIC
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.ITALIC)
```
<img src="https://imgur.com/SP4uYAQ.png">

* UNDERLINE
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.UNDERLINE)
```
<img src="https://imgur.com/xSfvtik.png">

* BOLD_ITALIC
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.BOLD_ITALIC)
```
<img src="https://imgur.com/A7NWUQE.png">

* BOLD_UNDERLINE
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.BOLD_UNDERLINE)
```
<img src="https://imgur.com/Jz9Di5m.png">

* ITALIC_UNDERLINE
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.ITALIC_UNDERLINE)
```
<img src="https://imgur.com/mWNFt26.png">

* BOLD_ITALIC_UNDERLINE
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.BOLD_ITALIC_UNDERLINE)
```
<img src="https://imgur.com/m6bKEZU.png">

9. setTypeface(TypefaceSmart type,int startPos,int endPos)

**TypefaceSmart is an enum with the following values:**
* BOLD
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.BOLD,0,6)
```
* ITALIC
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.ITALIC,0,6)
```
* UNDERLINE
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.UNDERLINE,0,6)
```
* BOLD_ITALIC
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.BOLD_ITALIC,0,6)
```
* BOLD_UNDERLINE
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.BOLD_UNDERLINE,0,6)
```
* ITALIC_UNDERLINE
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.ITALIC_UNDERLINE,0,6)
```
* BOLD_ITALIC_UNDERLINE
```kotlin
   txt_smart.text="Hello NoTin, Nice to meet you!"
   txt_smart.setTypeface(TypefaceSmart.BOLD_ITALIC_UNDERLINE,0,6)
```
 
