# Cvičení na CSS specificitu

## Fork úkolu

1. Přihlas se do Githubu.
2. Udělej si **fork** tohoto repozitáře (vpravo nahoře). Tím se ti úkol zkopíruje to tvého Github účtu.  
   ![fork](git/fork.png)
3. Tento repozitář si ze svého Githubu potom naklonuj k sobě na disk.

![clone](git/clone.png)

Zkopíruj si odkaz se záložky **clone** a potom v terminálu ve vybrané složce spusť příkaz `git clone ODKAZ`. Například `git clone https://github.com/marketaanezka/Specificita-cviceni.git`.

![git clone](git/gitclone.png) 4. Tady už můžeš přidávat, commitovat a pushovat změny a uvidíš je na svém Githubu.  
! Pokud by sis naklonovala rovnou tento repozitář, nemohla bys do něj ukládat změny! \
Na to, jak udělat fork repozitáře se můžes podívat v [krátkém videu](https://youtu.be/K7rE3jRCjD4).

## Zadání

Prohlédni si soubor index.html. Všimni si, že na řádku 9 je do stránky bootstrap. Ten nám zajišťuje, že použitím určitých tříd se nám rovnou dané elementy nastylují.

![bootstrap](vysledek/bootstrap.jpg)


### Přepiš stylování elementů podle zadání

![result](vysledek/result.jpg) 
1. Tělo kartičky (vše pod obrázkem) nastav pozadí na barvu ```#fff0ee``` a nastav mu padding nahoře a dole na 1rem a po stranách na 1.5rem
2. Nadpis udělej kapitálkami (vlasnost ```text-transform```) a přepiš margin-bottom na 1rem.
3. Tlačítku změn barvu pozadí a rámečku na barvu ```#b10849```

Podívej se do developer tools na stylování jednotlivých elementů a jejich specificitu. Ve svém stylování budeš muset tuto specificitu přebít. 
Ve složce vysledek máš soubor **specificita_result** a **specificita_hint**, které ti poradí 
