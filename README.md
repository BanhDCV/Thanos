# Mathletics Cheat But Does Not Save Points
I want to create a sort of game that has a secret meaning
var time = 60;  var clock = 300; function TimeHack(){
    setInterval(function Applytime() {
 document.getElementsByClassName('timerLabel whiteTextWithShadow font-60 ng-binding')["0"].innerText = time; document.getElementsByClassName('timerLabel whiteTextWithShadow font-60 ng-binding')["0"].innerHtml = time;
  document.getElementsByClassName('clockHand').rotate = clock;
}, 1);}; function TimeHackm() {
    setInterval(function Addtime() {
time = time + 1; 
clock = clock + 6;
}, 1000);}
    var score = 1;
    function ScoreHack(){
    setInterval(function ApplyScore() {
score = score + 1
 document.getElementById("scoreBar0").innerText = score ;
}, 1);};

alert("YOU ARE USING I_T_HackCentral's ML CHEAT! ENJOY!")

var btn = document.createElement("BUTTON");
    document.body.appendChild(btn);
    btn.setAttribute("onclick","ShowAwnser()");
    btn.setAttribute("id","dashow")
     var t = document.createTextNode(".A. Bot");
    btn.appendChild(t);
var btnt = document.createElement("BUTTON");
    document.body.appendChild(btnt);
    btnt.setAttribute("onclick","TimeHack(); TimeHackm()")
    btnt.setAttribute("id","dasho")
     var tt = document.createTextNode("TimeCheat");
    btnt.appendChild(tt);
    var btnd = document.createElement("BUTTON");
    document.body.appendChild(btnd);
    btnd.setAttribute("onclick","ScoreHack()");
    btnd.setAttribute("id","dashowd")
     var td = document.createTextNode("Point Hack");
    btnd.appendChild(td);
    



function ShowAwnser(){

 var nums = document.getElementsByClassName('questions-text-alignment whiteTextWithShadow question-size-v4')["0"].innerText;
 var add = nums.split('+' && '=');
 var equasion = add[0];
 function addbits(s){
    var total= 0, s= s.match(/[+\-]*(\.\d+|\d+(\.\d+)?)/g) || [];
    while(s.length){
        total+= parseFloat(s.shift());
    }
    return total;
}
 var awnser = addbits(equasion)

var nums = document.getElementsByClassName('questions-text-alignment whiteTextWithShadow question-size-v4')["0"].innerText;
 var add = nums.split('+' && '=');
 var equasion = add[0];
 function addbits(s){
    var total= 0, s= s.match(/[+\-]*(\.\d+|\d+(\.\d+)?)/g) || [];
    while(s.length){
        total+= parseFloat(s.shift());
    }
    return total;
}
 var awnser = addbits(equasion)

document.getElementById('dashow').innerText = awnser;
 document.getElementsByClassName("questions-input-adjustment questions-input-width-v3")["0"].value = awnser;
}

 window.addEventListener("keydown", checkKeyPressed, false);
 
function checkKeyPressed(e) {
    if (e.keyCode == "65") {
       ShowAwnser()
    }
}
