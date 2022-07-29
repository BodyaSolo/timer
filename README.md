# Timer
A module that can be used in the project to count down the time until the end of the promotion.
To add this timer to your project. You need to put this file in your project folder, import it into your main file and call the function with the specified arguments: id (selector div of the timer wrapper) and deadline (in YY-MM-DD format).
## Example of writing HTML layout for a slider
``` Html
<div class="promotion__timer">
  <div class="title">Осталось до конца акции:</div>
  <div class="timer"><!--id-->
      <div class="timer__block">
          <span id="days">12</span>
          дней
      </div>
      <div class="timer__block">
          <span id="hours">20</span>
          часов
      </div>
      <div class="timer__block">
          <span id="minutes">56</span>
          минут
      </div>
      <div class="timer__block">
          <span id="seconds">20</span>
          секунд
      </div>
  </div>
</div>
```
## View of the timer on the web page
![image](https://user-images.githubusercontent.com/100083448/181721579-77b7e66f-63f3-456e-a69c-0984a083f16f.png)
