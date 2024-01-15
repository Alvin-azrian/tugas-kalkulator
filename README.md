<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>KALKULATOR</title>
  
</head>
<body>
    <form class="display" name="button1">
        <input class="value" type="text" name="anjay">
        <span class="num clear" onclick="document.button1.anjay.value =''">C</span>
        <span class="num" onclick="document.button1.anjay.value = document.button1.anjay.value.slice(0, -1)">DEL</span>
        <span class="num" onclick="document.button1.anjay.value +='/'">&divide;</span>
        <span class="num" onclick="document.button1.anjay.value +='*'">&#120;</span>
        <span class="num" onclick="document.button1.anjay.value +='7'">7</span>
        <span class="num" onclick="document.button1.anjay.value +='8'">8</span>
        <span class="num" onclick="document.button1.anjay.value +='9'">9</span>
        <span class="num" onclick="document.button1.anjay.value +='-'">-</span>
        <span class="num" onclick="document.button1.anjay.value +='4'">4</span>
        <span class="num" onclick="document.button1.anjay.value +='5'">5</span>
        <span class="num" onclick="document.button1.anjay.value +='6'">6</span>
        <span class="num plus" onclick="document.button1.anjay.value +='+'">+</span>
        <span class="num" onclick="document.button1.anjay.value +='1'">1</span>
        <span class="num" onclick="document.button1.anjay.value +='2'">2</span>
        <span class="num" onclick="document.button1.anjay.value +='3'">3</span>
        <span class="num equal" onclick="document.button1.anjay.value =eval(button1.anjay.value)">=</span>
        <span class="num" onclick="document.button1.anjay.value +='0'">0</span>
        <span class="num" onclick="document.button1.anjay.value +='00'">00</span>
        <span class="num" onclick="document.button1.anjay.value +='.'">,</span>
    </form>
</body>
</html>
