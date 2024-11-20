# Lineární Algebra 1
---
## Pojmy:
* Vektorový prostor T<sup>n</sup>
  *  Nechť T je libovolné těleso
  *  n ∈ N Množina n-tic
  *  spolu s operacemi + a · definovaných po složkách
    * pro každé α ∈ T a x, y ∈ T<sup>n</sup>
    * x + y = (x1, . . . , xn) + (y1, . . . , yn) := (x1 + y1, . . . , xn + yn)
    * α · x = α · (x1, . . . , xn) := (αx1, . . . , αxn)
  * Prvky prostoru jsou vektory
  * Prvky T jsou skaláry
  * je uzavřený vůči operacím sčítání vektorů a násobení vektoru skalárem
  * Sčítání vektorů je komutativní a asociativní
  * Násobení skalárem je asociativní a distributivní zleva i zprava
  * neutrální prvek 1 je neutrální i vůči nasobení vektoru skalárem
  * Existuje nulový vektor a libovolný násobek nulového vektoru je nulový vektor
* Podprostor
  * Nechť P je podmnožina T<sup>n</sup>, P je podprostor T<sup>n</sup> pokud platí:
    * Množina P je neprázdná, P ≠ ∅
    * Množina P je uzavřená vůči sčítání vektorů v ní
    * Množina P je uzavřená vůči násobení vektorů v ní libovolným skalárem
    * Značí se P ⊂⊂ T<sup>n</sup>
* Lineárně Nezávislý soubor
  * právě když pouze triviální lineární kombinace tohoto souboru je rovna nulovému vektoru θ.
  * jinak je LineárnĚ závislý
  * soubor je lineárně závislý právě tehdy, když existuje vektor v souboru, který je lineární kombinací jiných
* Lineární obal souboru
  * Množina vśech lineárních kombinací vektorového souboru
  * obsahuje nulový vektor
  * vektory leží ve svém lineárním obalu
  * lineární obal se nezmění přidáním vektoru, který je již obsažen
  * lineární obal je uzavŕený na sčítání vektorů i na násobení vektorů skalárem
  * lineární obal souboru vektorů z lineárního obalu souboru vektorů neobsahuje nic navíc
  * přidáním vektoru do lineárního obalu se nezmění jeho lineární závislost, pokud neležel v lineárním obalu tohoto souboru
* Báze podprostoru
  * Lineárně nezávislý soubor vektorů tvořící podprostor
* Dimenze podprostoru
  * dimenze je rovna 0, pokud neexistuje LN soubor vektorů z P délky 1
  * dimenze je rovna d, pokud existuje LN soubor vektorů délky d, ale každý soubor ektorl z P délky d + 1 už je LZ
  * existuje-li soubor délky m generující podprostor, potom je dimenze podprostoru <= m
  * je li velikton LN souboru rovna dimenzi podprostoru a soubor generuje tento podprostor, tak je jeho bázá
