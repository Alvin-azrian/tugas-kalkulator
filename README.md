<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>KALKULATOR</title>
   <style>
       *{
    margin: 0;
    padding: 0;
    font-family: 'montsrrat',sans-serif;
    box-sizing: border-box;
}
body{
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    background: #091921;
}
.display{
    position: relative;
    display: grid;
}
.display .value{
    grid-column: span 4;
    height: 80px;
    width: 240px;
    text-align: right;
    border: none;
    outline: none;
    padding: 10px;
    color: #00fff7;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 18px;
    /* background-image: url(gura.jpg);
    background-size: 250px 110px; */
   
    background-color: #03b1ff;
}
.display span{
    display: grid;
    width: 60px;
    height: 60px;
    color: #fff;
    background: #0c2835;
    place-items: center;
    border: 1px solid rgba(0,0,0,.1);
}
.display span:active{
    background: #0067ab;
    color: #111;
}
.display span.clear{
    background: #ff9e9e;
}
.display span.equal{
    background: #76cfff;
    grid-row: span 2;
    height: 120px;
}
   </style>
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
