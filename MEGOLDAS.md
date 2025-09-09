Mi MADAGASZKÁR fővárosa?
SELECT fovaros FROM `orszagok` WHERE orszag = "MADAGASZKÁR"; 
-ANTANANARIVO

Melyik ország fővárosa OUAGADOUGOU?
SELECT orszag FROM `orszagok` WHERE fovaros = "OUAGADOUGOU"; 
-BURKINA FASO

Melyik ország autójele a TT?
SELECT orszag FROM `orszagok` WHERE autojel = "TT"; 
-TRINIDAD ÉS TOBAGO

Melyik ország pénzének jele az SGD?
SELECT orszag FROM `orszagok` WHERE penzjel = "SGD"; 
-SZINGAPÚR

Melyik ország nemzetközi telefon-hívószáma a 61?
SELECT orszag FROM `orszagok` WHERE telefon = 61; 
-AUSZTRÁLIA

Mekkora területű Monaco?
SELECT terulet FROM `orszagok` WHERE orszag = "Monaco"; 
-1.95
