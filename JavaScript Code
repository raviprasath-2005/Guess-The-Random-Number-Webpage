let a = prompt("ENTER YOUR NAME:");
document.getElementById("a").textContent = `Hello ${a}`;
let wcnt = 0, tcnt = 0;
function aclick() {
    let ele = document.getElementById("input1");
    let guess = parseInt(ele.value);
    let rand = Math.floor(Math.random() * 10); // 0-9
    tcnt++;
    if (guess === rand) {
        document.getElementById("c").textContent = 'Game Result: You won!';
        wcnt++;
    } else {
        document.getElementById("c").textContent = 'Game Result: You lost!';
    }
    document.getElementById("cont1").textContent = `Number Generated: ${rand}`;
    ele.value = "";
}
function bclick(){
        document.getElementById("cont2").textContent = `Total Attempts: ${tcnt}`;
        document.getElementById("cont3").textContent = `Total Wins: ${wcnt}`;
        document.getElementById("input1").disabled = true;
    document.getElementById("b1").disabled = true;
    document.getElementById("b2").disabled = true;
}
