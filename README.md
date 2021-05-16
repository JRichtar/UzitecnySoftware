# UzitecnySoftware
## Verze 1

Tvorba softwaru ve formě gramatického testu

Jakub Richtár <br/>
richtar.jakub.2018@skola.ssps.cz <br/>
16. 5. 2021

 

* Úvod
  * Účel dokumentu
    * Dokument bude informovat o tvorbě užitečného softwaru, na kterém pracuji v rámci MVOPu ve škole
  * Konvence dokumentu
    * Důležitost - 1 nejvyšší, 5 nejnižší
    * Všechny kritické požadavky budou tučně
  * Kontakty
    * Jakub Richtár richtar.jakub.2018@skola.ssps.cz
* Celkový popis
  * Funkce
    * Software bude sloužit k ověření znalostí z českého jazyka, z učiva probraného na ZŠ a SŠ
  * Uživatelské skupiny
    * Software bude určený primárně pro studenty a studentky ZŠ a SŠ, mohou ho však využít i prarodiče, nebo kdokoli jiný
  * Omezení návrhu
    * Omezení prozatím nejsou
* Požadavky na rozhraní
  * Uživatelská rozhraní
    * V softawaru se budou vyskytovat otázky v rámečcích, které bude možné odpovědět formou textboxů, checkboxů apod.
  * Softwarová rozhraní
    * Software bude vytvořený v aplikaci WPF, v jazyce C#
* Vlastnosti systému
  1. Vyhodnocení testu
    * Důležitost: 1
    * Vstup : všechny odpovězené otázky v testu
    * Akce : odeslání odpovědí tlačítkem Vyhodnotit test
    * Výstup : počet správných/špatných odpovědí 
    * Výstup : chybové hlášení když nebude odpovězená otázka
  2. Zobrazení odpovědí 
    * Důležitost: 2
    * Vstup: Vyhodnocený test  
    * Akce: tlačítkem Zobrazit odpovědi
    * Výstup: správné odpovědi budou označeny zeleně
    * Výstup: špatné odpovědi budou označeny červeně a budou zobrazeny vysvětlivky
* Nefunkční požadavky
  * Odezva
    * Systém bude poskytovat odezvu do 3s od zadání akce
  * Spolehlivost
    * Systém neskončí s chybou ve více než 1% případů
