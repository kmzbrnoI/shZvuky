# Zvuky staničního hlášení

Tento repozitář obsahuje zvuky staničního hlášení.

Všechny zvuky v tomto repozitáři jsou v češtině, primární jazyk tohoto
repozitáře je čeština. Češtinu lze používat i v commitech.

Více informací na [wiki](wiki).

Tento repozitář obsahuje větší soubory, využívá
[Git LFS](https://git-lfs.github.com/).

## Adresářová struktura zvukové sady

```code
.
├── numbers
│   ├── platform - čísla nástupišť (např. první, druhé)
│   ├── railway - čísla kolejí (např. první, druhá)
│   ├── railway_end
│   ├── trainNum - čísla (např. jedna, sto, pět set)
│   └── trainNum_end
├── parts - části slov (např. odjede, přijede)
├── salutation - oslovení (např. vážení cestující)
├── salutation_end 
├── spec
├── stations - stanice (např. Praha hlavní nádraží)
├── time
│   ├── hours - hodiny (např. 18 hodin)
│   ├── minutes - minuty (např. 26 minut)
│   └── minutes_end
└── trainType - typ vlaku (např. rychlík, J. G. Mendel)
```

## Licencování

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>

Obsah tohoto repozitáře je poskytován pod licencí [CC Attribution 4.0
International](https://creativecommons.org/licenses/by/4.0/).

Autoři:
 * Jiří Rybička ([rybicka@mendelu.cz](mailto:rybicka@mendelu.cz))

## Užitečné nástroje

```
normalize-ogg -a 0.15 `find . -type f -name "*.ogg"`
```
