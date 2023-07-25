# aula_php.1<?php

    $valor= 500;
    echo("$valor Global<br>");

    if(500 < 1000){
        $valor = 1500;
        echo ("$valor if <br>");
    }
    function testeglobal(){
        global $valor;
        $valor = 1000;
        echo ("$valor local pegando global <br>");
    }
    //local pegando global
    //local altera global
    testeglobal();

    testeglobal();

    ?>]




    $valor= 500;
    echo("$valor Global<br>");

    if(500 < 1000){
        $valor = 1500;
        echo ("$valor if <br>");
    }
    function testeglobal(){
        global $valor;
        $valor = 1000;
        echo ("$valor local pegando global <br>");
    }
    //local pegando global
    //local altera global
    testeglobal();




     $valor = 1000;
    echo"$valor local<br>";
    //global menos seguro

    
    //LOCAL acessado com a function
    function contacorrente(){

        $valor = 1;

        echo"$valor Local<br>";

    }

    //LOCAL acessado com a function
    function investimento(){

        $valor=50;

        echo("$valor investido Local <br>");
    }
contacorrente();
investimento();

$valor= 1000000;
echo"$valor Global<br><br>";

//teste Global

$valor = 500;
echo"$valor Global<br>";

//TESTE LOCAL

function contaContacorrente(){
    $valor = 500;
echo"$valor Local<br>";

}
contacorrente();
investimento();

function contar(){
    $entrada = 0;
    $entrada++;

    echo("$entrada<br> ");

}
contar();//0+1=1
contar();//0+1=1
contar();//0+1=1
//function: ele conta individual ou 0=1
function contarstatic(){


    static $entrada = 0;
    $entrada++;

    echo("$entrada <br>");
}
//FUNCTION STATIC: CONTAGEM INCREMENTADA
contarstatic();//0+1=1
contarstatic();//1+1=2
contarstatic();//2+1=3
?>


function produto($eletro , $imposto){

        echo $eletro * $imposto;
        echo("<br>");


    }
    produto(2000, 1.17);
    produto(15000, 1.17);
    produto(3500, 1.17);
    produto(18000, 1.17);
    produto(18000, 1.17);
?><?php
// operadores: (+, -, *, / )
    echo (10/4);

    if(is_float(10/4)){
        echo("<br>");
        echo("E FLOAT");
    }
    echo("<br>");
    echo("<br>");
    echo 2 . 5;
    echo("<br>");

    if(is_string(2 . 5)){
        echo("<br>");
        echo("E UMA STRING!");

    }

    $valor = 10000;
    $nome= "marcio";
    $sobrenome = "luiz";
    echo("<br>");
    echo("<br>");
    $nomecompleto = $nome. " " .$sobrenome;
    echo $nomecompleto. " = " .$valor;
    echo $nomecompleto. " = " .$valor;
    ?>





-> WHILE
    <?php

#enquanto for falso o  while vai percorrer todo o vetor ate encontra o valor verdadeiro

$numero = 1;

while($numero <= 10){

echo $numero. "<br>";
$numero++;



}
?>
