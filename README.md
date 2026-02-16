# 4ST204_vzorcovnik

Tento repozitář poskytuje strukturovanou šablonu pro sestavení sdíleného seznamu klíčových vzorců ("vzorcovníku") používaných v předmětu 4ST204 Statistika pro informatiky. Cílem je podpořit studenty při vytváření vlastního stručného a dobře organizovaného referenčního dokumentu, který jim bude sloužit jako doplněk ke studiu a zejména jako povolená pomůcka k testům. Studenti jsou vítáni, aby ke společnému dokumentu přispívali vzorci, popisy, užitečnými funkcemi v Pythonu a R, a to formou spolupráce.

## Jak přispívat do repozitáře (např. přidání vzorce)

Přímé úpravy větve `main` nejsou povoleny. Každá změna musí projít schválením pomocí Pull Requestu.

### 1. Vytvořme vlastní větev
1. Otevřeme repozitář na GitHubu.
2. Klikneme na tlačítko **Branch: main** (nahoře vlevo nad seznamem souborů).
3. Zadejme název nové větve, např. `pridani-vzorce-jmeno`, `pridani-vzorce-nick`, apod.
4. Klikneme na **Create branch**.

### 2. Proveďme úpravy
1. Otevřeme příslušný `.tex` soubor (nejspíš budete upravovat `_vzorcovnik_.tex`, já budu výstupy průběžně sázet, ale můžete sázet i vy a tedy updatovat i `_vzorcovnik_.pdf`).
2. Klikneme na **Edit this file**.
3. Přidejme nový vzorec na vhodné místo.
4. Dole napišme stručný popis změny (např. "Přidán vzorec pro směrodatnou odchylku").
5. Klikneme na **Commit changes** (do své větve, ne do `main`).

### 3. Vytvořme Pull Request
1. Klikneme na tlačítko **Compare & pull request**, které se objeví po commitu.
   - Pokud ho nevidíme, přejděme na záložku **Pull requests** → **New pull request**.
2. Zkontrolujme, že změna směřuje z naší větve do `main`.
3. Přidejme stručný popis změny.
4. Klikneme na **Create pull request**.

### 4. Počkejme na schválení
- Změna bude zkontrolována.
- Pokud bude vše v pořádku, bude sloučena do větve `main`.
- Pokud budou potřeba úpravy, budeme vyzváni k jejich doplnění, eventuálně drobné doplnění provede ihned po schválení úpravy pak admin repozitáře.

---

## Důležité
- Neupravujme přímo větev `main` (tato možnost je systémově vypnuta).
- Vždy pracujme ve vlastní větvi.
- Každá změna musí projít Pull Requestem a schválením.
