var soma;
var produto;
var divisao;
var sub;
var operacao;

function sinal() {
  operacao = '+';
}

function sinal1() {
  operacao = '-';
}

function sinal2() {
  operacao = '*';
}

function sinal3() {
  operacao = '/';
}
function calcular() {

  var n1 = Number(document.getElementById("n1").value);
  var n2 = Number(document.getElementById("n2").value);

  if (operacao === '+') {
    soma = n1 + n2;
    document.getElementById("resultado").innerText = `Soma: ${soma}`;
  }
  else if (operacao === '-') {
    sub = n1 - n2;
    document.getElementById("resultado").innerText = `Subtração: ${sub}`;
  }
  else if (operacao === '*') {
    produto = n1 * n2;
    document.getElementById("resultado").innerText = `Produto: ${produto}`;
  }
  else if (operacao === '/') {
    divisao = n1 / n2;
    document.getElementById("resultado").innerText = `Divisao: ${divisao}`;
  }
}

