V kontextu algoritmizace a programování se tradiční výuka hodí pro systematické zavedení pojmů, syntaxe a základních algoritmických struktur. Projektová výuka, například práce s micro:bit vozítky, lépe ukazuje smysl programování v reálném technickém problému, protože propojuje kód, elektroniku, konstrukci, měření a týmovou práci.

V tradiční výuce může být zadání například: „Napiš program, který podle hodnoty proměnné rozhodne, zda se má motor zapnout nebo vypnout.“ Taková úloha je vhodná pro nácvik podmínek, ale žák nemusí plně chápat, proč je rozhodování důležité.

V projektové výuce by zadání mohlo znít: „Konstruujte vozítko s micro:bit, které projede jednoduchou trasu, zastaví před překážkou a po dokončení jízdy zobrazí stav na RGB LED pásku.“ Žáci pak přirozeně pracují s podmínkami, cykly, funkcemi, senzory, motory, napájením a testováním.

Rozdíl je v tom, že algoritmus není cílem sám o sobě. Je prostředkem k vyřešení technického problému.

## Definice používaných pojmů
- **Tradiční výuka programování (TCL)** z Teacher-Centered Learning: 
Výuka zaměřená na systematické zavedení programovacích konceptů, syntaxe a algoritmických struktur prostřednictvím izolovaných úloh, cvičení a teoretických příkladů. Cílem je naučit žáky správně používat jazyk a porozumět základním principům programování. Výuka je strukturovaná, vedená učitelem systematicky krok za krokem. V programování se tento model často projevuje formou detailních přednášek a tutoriálů, kde vyučující vysvětluje syntaxi po malých blocích a žáci postupují podle přesných instrukcí.
- **Dílčí programátorské projekty (TBL)** z Task-Based Learning: 
Pro zadávání specifických menších cvičení se běžně využívá přístup TBL, který je explicitně orientován na splnění předem definovaného úkolu. Studenti tak místo rozsáhlého komplexního projektu řeší ohraničené zadání, jako je například napsání jedné konkrétní funkce nebo implementace jednoduchého algoritmu. Při práci s micro:bit vozítky by to mohlo být například: „Napište funkci, která na základě hodnoty ultrazvukového senzoru rozhodne, zda se má motor zapnout nebo vypnout.“ Tento přístup umožňuje zaměřit se na konkrétní dovednost nebo koncept bez nutnosti řešit širší technické a konstrukční aspekty projektu.
- **Projektová výuka (PBL)** z Project-Based Learning: 
Výuka založená na řešení komplexních, reálných problémů prostřednictvím projektů. Žáci pracují v týmech na navržení, implementaci a testování řešení, které zahrnuje nejen programování, ale i konstrukci, měření a dokumentaci. Učitel je spíše mentorem, který podporuje samostatnost, kreativitu a kritické myšlení žáků. V programování se tento model projevuje tím, že žáci dostanou úkol s jasným cílem (např. „postavte vozítko, které projede trasu“), ale mají volnost v tom, jak toho dosáhnout, jaké algoritmy použít a jak řešit vzniklé problémy.

## Srovnávací tabulka PBL

| Parametr | Dílčí programátorské úlohy (TBL) | Projektová výuka (PBL)| Projev při práci s micro:bit vozítky |
|---|---|---|---|
| **Motivace žáků** | Motivace bývá často vázaná na známku, splnění úlohy nebo pochopení konkrétního příkazu. Žáci někdy vnímají úlohy jako izolované a málo propojené s praxí. | Motivace roste díky viditelnému výsledku. Žáci vidí, že jejich program skutečně ovládá fyzické zařízení. | Místo úlohy „napiš podmínku if“ řeší žáci problém „vozítko má zastavit před překážkou“. Chyba v programu má okamžitý fyzický důsledek. |
| **Rozvoj kritického myšlení** | Žáci často řeší úlohy s jedním očekávaným postupem. Kritické myšlení se rozvíjí hlavně při ladění kódu a hledání chyb. | Žáci musí porovnávat více řešení, vyhodnocovat kompromisy a obhajovat volbu postupu. | Tým řeší, zda je lepší použít ultrazvukový senzor, sledování čáry, časované zatáčení nebo kombinaci více vstupů. Musí zvažovat přesnost, spolehlivost i složitost programu. |
| **Týmová spolupráce** | Práce bývá často individuální. Spolupráce se objevuje spíše jako konzultace mezi žáky. | Spolupráce je přirozenou součástí projektu. Role se mohou dělit na programátora, konstruktéra, testera, dokumentátora nebo prezentujícího. | Jeden žák řeší zapojení motorů, druhý píše řídicí algoritmus, třetí testuje chování na trati a čtvrtý dokumentuje změny a měření. |
| **Hloubka pochopení algoritmizace** | Žáci si dobře osvojí základní konstrukce: proměnné, cykly, podmínky, funkce. Rizikem je formální pochopení bez vazby na reálný systém. | Algoritmizace je propojena s reálným chováním zařízení. Žáci lépe chápou vztah mezi vstupem, zpracováním a výstupem. | Podmínka není jen zápis v editoru, ale rozhodnutí vozítka: „pokud je vzdálenost menší než 10 cm, zastav a zatoč“. Smyčka není abstraktní konstrukce, ale nepřetržité sledování senzorů. |
| **Práce s chybou** | Chyba je často syntaktická nebo logická. Žák ji vidí v editoru, konzoli nebo testovacím výstupu. | Chyba může být programová, konstrukční, elektrická nebo způsobená prostředím. Žáci se učí systematicky diagnostikovat problém. | Vozítko nejede rovně. Příčina může být v rozdílném výkonu motorů, špatně zapojeném vodiči, slabých bateriích, nevhodné konstrukci nebo chybné hodnotě PWM. |
| **Mezipředmětový přesah** | Přesah je možný, ale často není přirozeně přítomen. Programování zůstává oddělené od fyziky, elektrotechniky nebo konstrukce. | Přesah vzniká automaticky. Projekt propojuje ICT, elektrotechniku, fyziku, polytechniku, matematiku a technickou dokumentaci. | Žáci řeší polaritu motoru, napájení, tření kol, převody, měření vzdálenosti, stabilitu konstrukce, přesnost senzoru a optimalizaci algoritmu. |
| **Samostatnost žáků** | Žáci postupují podle zadání, šablony nebo výkladu učitele. Samostatnost roste postupně. | Žáci musí plánovat, rozhodovat, testovat a upravovat řešení. Učitel je spíše mentor než hlavní zdroj postupu. | Tým si sám navrhne strategii pro průjezd tratí, zvolí senzory, rozdělí role a postupně upravuje konstrukci i kód podle výsledků testů. |
| **Časová náročnost pro učitele** | Příprava je obvykle nižší a lépe předvídatelná. Stačí připravit úlohy, ukázky a kontrolní řešení. | Příprava je vyšší. Učitel musí zajistit techniku, scénář projektu, hodnoticí kritéria, bezpečnost, materiál a prostor pro testování. | Je nutné připravit micro:bity, baterie, motory, 3D modely, náhradní vodiče, tratě, překážky, hodnoticí rubriku a plán pro řešení technických problémů. |
| **Hodnocení výsledků** | Hodnotí se hlavně správnost programu, splnění zadání a znalost syntaxe. | Hodnotí se proces, funkčnost, dokumentace, týmová spolupráce, prezentace a schopnost obhájit řešení. | Nestačí, že vozítko „nějak jede“. Hodnotí se kvalita algoritmu, spolehlivost jízdy, práce se senzory, technická dokumentace, testování a reflexe chyb. |

## Návrh objektivních metrik pro závěrečnou práci

| Oblast hodnocení | Metrika | Příklad měření |
|---|---|---|
| **Funkčnost vozítka** | Splnění definovaných úkolů | Vozítko ujede trasu, zastaví před překážkou, zatočí, reaguje na tlačítko nebo signál. |
| **Spolehlivost** | Počet úspěšných pokusů z celkového počtu | Například 8 úspěšných průjezdů z 10 testů. |
| **Přesnost řízení** | Odchylka od požadované dráhy | Měření, jak často vozítko opustí čáru, narazí do překážky nebo mine cílovou zónu. |
| **Kvalita algoritmu** | Strukturovanost a čitelnost programu | Použití funkcí, smysluplných názvů proměnných, komentářů a přehledného řízení toku programu. |
| **Práce se senzory** | Vhodné použití vstupních dat | Správné vyhodnocení vzdálenosti, světla, čáry, tlačítek nebo radiové komunikace mezi micro:bity. |
| **Technické řešení** | Kvalita konstrukce a zapojení | Stabilita podvozku, pevnost spojů, správná polarita, bezpečné vedení vodičů, dostupnost baterie. |
| **Testování a ladění** | Evidence testů a úprav | Žáci vedou tabulku pokusů: problém, hypotéza, změna, výsledek. |
| **Mezipředmětový přesah** | Využití znalostí mimo samotné programování | Vysvětlení napájení, tření, převodu, mechanické stability, měření vzdálenosti nebo principu motoru. |
| **Týmová spolupráce** | Rozdělení rolí a doložený podíl členů | Krátký týmový deník, Git historie, pracovní list nebo reflexe jednotlivých členů. |
| **Dokumentace** | Úroveň technické zprávy | Schéma zapojení, popis algoritmu, fotografie konstrukce, testovací protokol, závěrečné zhodnocení. |
| **Prezentace a obhajoba** | Schopnost vysvětlit řešení | Žáci dokážou popsat, proč zvolili daný postup, co nefungovalo a jak problém vyřešili. |

## Návrh dílčích vah pro hodnocení projektu

| Kritérium                                | Váha |
| ---------------------------------------- | ---- |
| Funkčnost výsledného vozítka             | 25 % |
| Kvalita algoritmu a programu             | 20 % |
| Technické a konstrukční řešení           | 15 % |
| Testování, ladění a práce s chybou       | 15 % |
| Dokumentace projektu                     | 15 % |
| Prezentace, obhajoba a týmová spolupráce | 10 % |

# Zdroje
1. WILLIS, Jane, Paul LEEMING a Justin HARRIS. A Framework for Task-Based Learning and Teaching: Revised Edition [online]. Kindle edition. Bristol: Channel View Publications, 2026. ISBN 9781836681359.
2. VOJTKOVÁ, Naděžda. Úkolově orientovaná výuka angličtiny, Task-based Learning (TBL). PDF; online. Brno: Masarykova univerzita, 3. 2. 2014 [cit. 2026-03-07]. Dostupné z: https://educoland.muni.cz/down-723/
3. MICROSOFT MAKECODE. Building your own extension [online]. [cit. 2026-04-10]. Dostupné z: https://makecode.microbit.org/extensions/build-your-own