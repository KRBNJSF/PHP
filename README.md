# PHP

<a href="https://paiza.io/projects/0Y3iNjE38UBZcWjfglnapA">editor</a>


Test 
```
<?php
// Your code here!
#prvni komentar
$stringPromenna = 'ajj';
$test = 5; //Global promenna, nelze uzit ve funkci, ale vsude jinde ano
echo "i love" . $stringPromenna;

echo " \n";

echo str_word_count("ahoj svete") . " je pocet slov ve vete \n";

echo "Obraceni slova: " .strrev($stringPromenna) ." \n";

echo "Pocet znaku: " .strlen("ano je to tak");

echo "\n";

function testFunction() {
    global $stringPromenna; //Uziti globalni promenne ve funkci pomoci slovicka global
    $stringPromenna = "cau";
    echo $stringPromenna . "\n";
    static $test = 10; //local promenna, lze uzit pouze ve funkci; Static umozni vyuziti promenne vicekrat, promenna se ihned po provedeni funkce nesmaze
    $test++;
    echo $test;
}
testFunction();
testFunction();

?>
```
