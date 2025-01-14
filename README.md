# MPS-rocnikovyprojekt1

Jako ročníkovy projekt v 1. pololetí jsem si vybral naprohramování hry "snake" v C++.

Dělal jsem to podle tutoriálu na youtube který je rozdělen na 3 části:

1. https://www.youtube.com/watch?v=E_-lMZDi7Uw&t=22s
2. https://www.youtube.com/watch?v=W1e5wO7XR2w&t=46s
3. https://www.youtube.com/watch?v=PSoLD9mVXTA&t=92s
      

### Na kódu jsem upravil pár věcí:

   -Zvětšil jsem herní pole z 20x20 na 117x26.
  
   -Zpomalil rychlost hada protože byl podle mě moc rychlý.
  
   -Přidal jsem ovládání šipkami(v tomhle mi pomohl AI bot).
  
   -Zamezil jsem změnit směr na opačný(jinak by had totiž trefil svůj ocas a hra by skoncila.
      
   -Pokud dosáhnu maximalního počtu bodů, tak se vypíše text: YOU WON!
      
   -Pokud had trefí svůj ocas, nebo zmáčknu "x", vypíše se text: GAME OVER!
      
   -Zkusil jsem změnit ohraničení hracího pole z "#" na něco jiného, ale nakonec jsem tam "#" nechal protože se tam hodí nejvíc.
      
   -To samé jsem zkusil u hlavički a ocasu hada, ale poté to zase změnil zpátky na originál.

# Vysvětlení kódu.

### Setup()

-Zahajuje hru, nastavuje počáteční pozici hada, pozici ovoce a výchozí skóre

### Draw()

-Vykresluje hrací pole, zobrazuje hada (O), jeho ocas (o), ovoce (F) a hranici (#)
-Na dolní části obrazovce (pod hracím polem) se zobrazuje skóre

### 

# Videa


### Gameplay

https://youtu.be/gISAshAv3rI

### Victory

https://youtu.be/53BpsscEmys

Pokud se dosáhne urečného počtu bodů, hra skončí a vypíše se nápis: YOU WON!

### GameOver

https://youtu.be/JwK99AfpH9s

Pokud had narazí do svého ocasu nebo se zamckne klavesa "x" hra se uknčí a vypíše se nápis: GAME OVER!




















      
      
      
