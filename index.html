<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="" method="post">
        <input type="submit" name="g" value="wszystkie">
        <input type="submit" name="a" value="parzystosc">
        <input type="submit" name="b" value="3 cyfrowe">
        <input type="submit" name="c" value="pierwsze">
        <input type="submit" name="d" value="ekstremka">
        <input type="submit" name="e" value="powtorki">
    </form>
    <?php
    $uchwyt=fopen("zad2.txt","w");
     function pierwsze($n) {
        if ($n < 2) {
            return false;
        }
        for ($i = 2; $i <= sqrt($n); $i++) {
            if ($n % $i == 0) {
                return false;
            }
        }
        return true;
    }

    $cyfry=file("cyfry.txt");
    if(isset($_POST['g'])){
        $i=1; 
        $tresc="Wszystkie liczby\n";
        foreach ($cyfry as $cyf) {
           
            $tresc=$tresc."$cyf";
            echo "$cyf &nbsp;&nbsp;&nbsp;";
            if($i==4) {
                echo "<br>";
            $i=0;
            }
            $i++;
        }
        fwrite($uchwyt,$tresc);
    }
    if(isset($_POST['a'])){
        $tresc="Ilos parzystych i nieparzystych\n";
        $parzyste=0;
        $nparzyste=0;
        foreach ($cyfry as $cyf) {
            if(intval($cyf)%2==0) $parzyste++ ;
            else $nparzyste++;
            
        }
        $tresc=$tresc."Parzyste:$parzyste  Nieparzyste:$nparzyste";
         echo "<h2>Ilośc Parzystych: $parzyste<br>Ilośc Nie parzystych: $nparzyste</h2>"   ;
         fwrite($uchwyt,$tresc);
    }
    if(isset($_POST['b'])){
        $i=1;
        $tresc="Liczby 3 cyfrowe\n";
        foreach ($cyfry as $cyf){
            if (intval($cyf)>=100 & intval($cyf<1000)) {
              echo $cyf;
              $tresc=$tresc."$cyf";
              if($i==4) {
                echo "<br>";
            $i=0;
            }
            $i++;  
            }
        }
        fwrite($uchwyt,$tresc);
    }
    if(isset($_POST['c'])){
        $i=1;
        $tresc="Liczby pierwsze\n";
        foreach ($cyfry as $cyf) {
            if(pierwsze(intval($cyf))) {
                echo $cyf;
                $tresc=$tresc."$cyf";
                if($i==4) {
                echo "<br>";
                $i=0;
            }
            $i++;
            }
            
            
        }
        fwrite($uchwyt,$tresc);
    }
    if(isset($_POST['d'])){
        $tresc="Ekstremka";
        $max = $cyfry[0];
        $min = $cyfry[0];
        foreach ($cyfry as $cyf) {
            if (intval($cyf)%2==0) {
                if ($cyf>$max) $max = $cyf;
            } else {
                if ($cyf<$min) $min = $cyf;
            }
            
            
        }
        $tresc=$tresc." Najwieksza parzysta:$max Najmniejsza nieparzysta:$min";
        fwrite($uchwyt,$tresc);
        echo "<h2>Najwieksza parzysta:$max <br>Najmniejsza nieparzysta:$min</h2>";
}
    if(isset($_POST['e'])){
        $tresc="powturki";
        $liczniki = array_count_values($cyfry);

// Iteruj po licznikach i wypisz liczby, które się powtarzają
foreach ($liczniki as $liczba => $licznik) {
    if ($licznik > 1) {
        $tresc=$tresc."$liczba";
        fwrite($uchwyt,$tresc);
        echo $liczba . " występuje " . $licznik . " razy<br>";
    }
}
    }
    
    fclose($uchwyt);
    ?>
</body>
</html>