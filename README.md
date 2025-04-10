HERNÍ ENGINE
- 
Cílem tohoto projektu je vytvoření herního enginu pro platformovou 2D hru, kde hráč sbírá různé předměty na plošinách s cílem překonávat překážky a dostat se do dalších úrovní.

Průběh a cíl hry
- 
Hráč bude ovládat postavu v 2D platformové hře, pohybující se po plošinách a překonávající různé překážky. Cílem je nasbírat předměty potřebné k otevření cest do dalších úrovní a postupně dokončit celou hru.

Vlastnosti postavy
- 
- Pohyb - Postava se bude pohybovat doleva, doprava a bude schopná skákat.
- Interakce - Hráč bude moci sbírat předměty, používat je k překonání překážek a vyrábět nové předměty, bude moci utočit na nepřátele a pokud bude zraněn, budou mu odebrány životy.
- Fyzika - Základní fyzika pro pád, kolize s objekty a plošinami.

Popis předmětů
- 
Hráč bude muset sbírat různé předměty různě umístěny po úrovních, které budou sloužit k překonávání překážek:
- Klíče - Otevírají zamčené dveře
- Žebříky - Umožňují vylézt na vyšší plošiny
- Jetpack - Poskytuje krátkodobou schopnost létání
- Meč - Slouží k eliminaci nepřátel
- Lampa - Osvětluje temné úseky hry
- Dynamit - Ničí zdi a jiné překážky
- Suroviny - Použitelné k výrobě nových předmětů

Tyto předměty mohou být také součástí úkolu od NPC, která vám umožní další postup v úrovních

Ovládání
- 
- Pohyb doleva/doprava - klávesy A/D
- Skok - mezerník
- Použití předmětu, interakce s prostředím - klávesa E
- Otevření inventáře - klávesa I

Načítání a ukládání
- 
- Inventář hráče bude načítán a ukládán do externího souboru.
- Každý level bude definován v externím souboru a načítán při spuštění hry.

Editor úrovní
- 
- Umožní vizuální tvorbu levelů s možností umísťování plošin, předmětů a překážek.

Překonávání překážek
- 
Překážky mohou být:
- Neživé - zamčené dveře, propasti, zdi, láva, tma
- Živé - nepřátelé, NPC s úkoly

Překážky lze překonat pomocí předmětů:
- Použití klíče/klíčů k odemčení zamčených dveří
- Použití dynamitu k zničení zdi
- Použití žebříku/jetpacku k překonání výškových rozdílů
- Použití lampy pro průchod temnými oblastmi
- Výroba mostu z kovu pro překonání propasti/lávi
- Polití lávy vodou pro její zchlazení a možný přechod přes ní
- Použití meče pro eliminaci nepřátel

Překážky lze také překonat splněním úkolu od NPC:
- Eliminace určitého počtu nepřátel
- Přinesení surovin

GUI
- 
- Herní scénu s postavou a objekty
- Inventář hráče
- Základní menu (start, nastavení, ukončení hry)
