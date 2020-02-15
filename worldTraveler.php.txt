<?php
  
//Exchanging collected currencies from 'Around the world' & Calculating all money back to USD
  
//Cambodia currency == riel
$riel = 2103942;
//Myanmar currency == kyat
$kyat =  19092;
//Norway currency == krones
$krones = 109;
//Albania currency == lek
$lek = 9094;

print "Cambodia - riel: ? ".$riel."\n";
print "Myanmar - kyat : K ".$kyat."\n";
print "Norway - krones: ".$krones."\n";
print "Albania - lek: ".$lek."\n";

//Transfer rates: --Based on 14.02.20 12:11

//1 riel == 0.00024 USD
$rielUSD = 0.00024;
$rielExch = $riel * $rielUSD;
print "\n\nRiel exchange: \n? ". $riel . " == $". $rielExch."\n";

//1 kyat == 0.00069 USD
$kyatUSD = 0.00069;
$kyExchange = $kyat * $kyatUSD;
print "\nKyat exchange: \nK ". $kyatUSD . " == $". $kyExchange."\n";

///1 Krone == 0.11 USD
$kroneUSD = 0.11;
$kroneExchange = $krones * $kroneUSD;
print "\nKrone exchange: \nkr ". $krones . " == $". $kroneExchange."\n";

//1 lek == 0.0089 USD
$lekUSD = 0.0089;
$lekExchange = $lek * $lekUSD;
print "\nLek exchange: \nL ". $lek . " == $". $lekExchange."\n";

print "\n\n...\n...\n\n\nOh dear God can you hear that? ";

print "\n\n\nNEE NAW NEE NAW HERE COMES THE TAX MAN\n";
//He all He ALLLLways calls me donkey == (A working, free & young mind)

print "\nOh yes let my uncle Sam get his grubby little hands all over my money\n";

print "\nUncle Sam says:\n\nFor every exchange you get 1 USD taken away \n";
//Its called the illusion of control - Serving the state before the individual

print "\n\nIf you made 4 exchanges that means...4 dollars for me YAR HAR HAR\n";
$myWallet = 0;
$myWallet += ($rielExch -1)+($kroneExchange -1)+($lekExchange-1)+($kyExchange);
$samsWallet =4;

print "\nSam says Thanks for your money & soul, Son.\nHere's what you get $".$myWallet."\n";//Money minus meaning

print "\nAnd for my honest work I'll take: $".$samsWallet;

?>






