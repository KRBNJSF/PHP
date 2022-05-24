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

PHP-FORM
---

Spustíme Xampp

![image](https://user-images.githubusercontent.com/90755554/169993697-9e123419-aaf6-435b-81fc-5c6494e84bfc.png)

Start Apache

![image](https://user-images.githubusercontent.com/90755554/169993585-49dbd1ae-7a54-4657-aea6-eea178be6f95.png)

htdocs - Přesuneme potřebné soubory

![image](https://user-images.githubusercontent.com/90755554/169993367-a09b27b2-d7ad-4584-8ec8-4c715cd5271b.png)

![image](https://user-images.githubusercontent.com/90755554/169993470-d8b773e2-75ac-4e55-a3c1-d533c8542f5a.png)

Hotovo

