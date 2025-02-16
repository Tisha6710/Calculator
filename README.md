# Calculator
Calculator project using html,css and javscript
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="calculator.css">

    
    <title>calculator</title>
</head>
<div id="calculator">
    <input type="text" id="display">
    <div class="button-container">
    <button class="button"onclick="currentDisplay='';
    document.querySelector('#display').value=currentDisplay;"> c </button>
    <button class="button" onclick="currentDisplay=currentDisplay+'1';
    document.querySelector('#display').value=currentDisplay;"> 1 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'2';
    document.querySelector('#display').value=currentDisplay;"> 2 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'+';
    document.querySelector('#display').value=currentDisplay;"> + </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'3';
    document.querySelector('#display').value=currentDisplay;"> 3 </button>
    <button class="button" onclick="currentDisplay=currentDisplay+'4';
    document.querySelector('#display').value=currentDisplay;"> 4 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'-';
    document.querySelector('#display').value=currentDisplay;"> - </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'5';
    document.querySelector('#display').value=currentDisplay;"> 5 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'6';
    document.querySelector('#display').value=currentDisplay;"> 6 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'*';
    document.querySelector('#display').value=currentDisplay;"> * </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'7';
    document.querySelector('#display').value=currentDisplay;"> 7 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'8';
    document.querySelector('#display').value=currentDisplay;"> 8 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'/';
    document.querySelector('#display').value=currentDisplay;"> / </button>
    <button class="button"onclick="
    let result= eval(currentDisplay);
    currentDisplay=result;
   
    document.querySelector('#display').value=currentDisplay;"> = </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'9';
    document.querySelector('#display').value=currentDisplay;"> 9 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'0';
    document.querySelector('#display').value=currentDisplay;"> 0 </button>
    <button class="button"onclick="currentDisplay=currentDisplay+'.';
    document.querySelector('#display').value=currentDisplay;"> . </button>
    
    </div>
</div>
<script>
    let currentDisplay='';
    document.querySelector('#display').value=currentDisplay;
</script>
<body>
    
</body>
</html>

// CSS code linked to this
#calculator{
    border: 1px solid rosybrown;
    border-radius: 5px;
    width:200px;


}
#display{
    margin: 10px;
    width:85%;
    font-size: 25px;

}
.button-container{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;

}
.button{
    width:45px;
    height:45px;
    margin:3px;
}
