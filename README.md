# Lekce-3.1-Responzivn-web-design

Informace k zadání
Produktový detail má nastavený font Ubuntu, který najdeš na https://fonts.google.com/. Nejsou zde použité žádné speciální řezy, proto postačí, když vybereš variantu „Light 300“. Nezapomeň vložit linky do HTML a v CSS nastavit font-family na celý dokument.

Informace o kolu si můžeš vymyslet. Nicméně pokud se chceš držet předlohy, informace získáš na oficiální stránce výrobce: https://www.merida-bikes.com/en/bike/3044-4201/bigseven-200.

Produktový detail se skládá z „obalovacího“ divu, který bude mít v sobě umístěné veškeré informace. Tento div by měl mít nastavené vnitřní i vnější odsazení, rámeček a zakulacené rohy. Produktový detail bude mít nastavenou šířku 500 px.

Uvnitř budou tyto prvky: nadpis `<h1>`, obrázek, odstavec s textem, dále je zde několik nadpisů `<h3>`, které jsou zvýrazněny tučně. Informace o kolu jsou umístěny do seznamu s položkami.

Do pravého horního okraje umístíme štítek s informací o novince. Štítek bude blokový prvek `(div)`, který napozicujeme absolutně k pravému hornímu okraji produktového detailu. Pozor na to, že pokud chceme pozicovat tak, aby prvek přesahoval nadřazený element, musíme nadřazenému elementu nastavit také určitý typ position. Také připomenu, že pozicování může probíhat i v záporných hodnotách.

Obrázek kola můžeš opět použít jakýkoliv, případně použít stejný jako v předloze. Najdeš ho na adrese: https://www.mojekolo.sk/upload/photo/508090/merida-big-seven-200-matt-blue-white_2_v.jpg?v=207288 Obrázek vlož do HTML pomocí tagu `<img>` a nastav mu šířku tak, aby se vešel do rámečku.

Tabulka velikostí se skládá ze 3 sloupců a 5 řádků. Je zde použito několik stylovacích pravidel (zarovnání textu, vnitřní odsazení, rámečky). Zde upozorním na vlastnost border: collapse, kterou jsme si neukazovali, ale není to nic složitého. https://www.w3schools.com/cssref/pr_border-collapse.asp

Barevné varianty vytvoříš pomocí třech divů, které budou mít stejné vlastnosti jako je pravý margin, zakulacení, šířku a výšku. Každý div by měl mít ještě druhou třídu, která v CSS určí barvu pozadí. Barvy můžeš použít jakékoliv, nebo použít tyto:

Modrá: background-color: rgb(33, 95, 217); Fialová: background-color: rgb(133, 49, 153); Šedá: background-color: rgb(123, 123, 123);

Určitě se pak zamyslíš nad tím, jak zařídit, aby se všechny tři barvy zarovnaly vodorovně vedle sebe. Napovím, že to má co do činění s řádkovými a blokovými elementy, které lze poupravit v CSS pomocí vlastnosti display.

Video na YouTube můžeš použít i jiné. Video z předlohy najdeš na odkazu: https://youtu.be/LSraGG0JEAo. Připomínám, že pro použití YouTube videa do webové stránky je potřeba zvolit možnost Sdílet a vybrat první možnost Vložit. Zobrazí se ti kód s elementem <iframe>, který vložíš na dané místo v HTML kódu.

Zbývá tu ještě přidat informace o ceně, která mě větší velikost a tloušťku než zbytek textu.

Na produktovém detailu nesmí chybět tlačítko `<button>`, které napozicujeme absolutně k pravém dolnímu okraji produktového detailu. Nezapomeneme na vnitřní odsazení, barvu pozadí a písma.

Na závěr přidáme odkaz na oficiální zdroj informací o kolu, který se bude otevírat do nového panelu. Odkaz může být tento nebo jiný: https://www.merida-bikes.com/en/bike/3044-4201/bigseven-200.
