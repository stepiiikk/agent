# Obsah pro profil Štěpán Albert – verze 1

Začni tady. Tenhle soubor vysvětluje, co je hotové, co chybí a jak s obsahem pracovat.

| Soubor | Co v něm je |
|---|---|
| `README.md` (tento) | Upřímně co se povedlo a co ne, strategie profilu, co od tebe potřebuju |
| `karusely.md` | 10 karuselů, slide po slidu, s popiskem a poznámkou pro grafika |
| `reels-hooky-kalendar.md` | 6 scénářů na reels, 25 hooků, plán na 4 týdny |

---

## 1. Co se povedlo a co ne (bez příkras)

**Analýza těch 5 profilů NEPROBĚHLA.** Prostředí, ve kterém běžím, má zablokovaný přístup na `instagram.com` (síťová politika vrátila chybu 403). Webový nástroj nedokázal načíst ani Instagram, ani weby, které Instagram zrcadlí. Vyhledávač ty účty nemá zaindexované.

Neviděl jsem tedy:
- @digitally_create_, @thebranding.ai, @jakubeoff, @jakubkozelekk
- příspěvek instagram.com/p/DdG5LGJkeHm

Nebudu předstírat, že vím, o čem tvoří. **Nic v tomhle obsahu není „inspirované jejich nejlepšími posty“.**

**Přepis videí přes Whisper taky nešel.** Model Whisperu se stahuje z `huggingface.co` / `openaipublic.azureedge.net` a obojí je zablokované.

**Co jsem udělal místo toho:**
- Stáhl jsem originální skills z tvého PDF (github.com/artemnovitckii/content-skills, MIT licence). PDF je jen shrnutí, originály mají podrobná pravidla. Napsal jsem podle nich každý slide a scénář.
- Uložil jsem je do `.claude/skills/`, takže je každá další session v tomhle repu použije automaticky.
- Napsal jsem obsah postavený na tvé nabídce, cílovce a na formátech, které u marketingových tvůrců prokazatelně fungují (case study, checklist chyb, návod s promptem, kontroverzní názor).

**Hlas:** neověřen. Nemám žádný tvůj text. Texty proto můžou znít trochu „jinak než ty“. Řeší to voice-DNA (viz bod 4).

---

## 2. Strategie profilu (a kde s tebou nesouhlasím)

### Co je na tvém nastavení dobře
- **Bio „Vydělávám firmám peníze na sociálních sítích“ je silné.** Říká výsledek, ne funkci. Většina lidí má „Social media manager | Marketing“.
- **Máš klienty.** To je obsah, který ti konkurence nezkopíruje. Čísla klientů jsou tvoje největší zbraň.
- **Konzultace s hranicí 1 mil. Kč** je chytrá. Filtruje lidi, co nemají na reklamu, a zní exkluzivně.

### Kde vidím problém
1. **5 témat je na rozjíždějící se profil moc.** Algoritmus i lidi potřebují rychle pochopit, „o čem ten kluk je“. Doporučuju poměr:
   - **60 %** marketing + AI pro firmy (to, co klienti kupují)
   - **25 %** budování firmy (příběh, důvěra, čísla agentury)
   - **15 %** mindset a lifestyle, vždycky přes byznys (den majitele agentury, ne „ranní rutina“)
2. **Virální ≠ klienti.** Nejvíc dosahu ti udělají videa pro 19leté „budoucí podnikatele“. Ti ti ale konzultaci nezaplatí. Test pro každý příspěvek: **Bylo by to užitečné pro majitele firmy s obratem 5 milionů?** Když ne, nepatří to sem.
3. **Věk je tvoje námitka č. 1.** 45letý majitel e-shopu si pomyslí „co mi poradí 23letý kluk“. Neschovávej to, otevřeně to pojmenuj (karusel 6, reel 2). Udělej z věku výhodu.
4. **V biu chybí důkaz a další krok.** Návrh:
   ```
   Vydělávám firmám peníze na sociálních sítích
   [DOPLŇ: např. „X mil. Kč tržeb pro klienty za 2026“]
   Majitel @loopside
   Konzultace zdarma pro firmy s obratem 1M+ ↓
   [odkaz na rezervaci]
   ```
5. **Tvůj obličej musí být na slidu 1 a v první vteřině reelsu.** Je to osobní profil. Lidi sledují člověka, ne šablonu.

### Na co se dívat ve statistikách
Lajky ignoruj. Sleduj:
- **Sdílení** (posláno do zpráv): podle vyjádření šéfa Instagramu Adama Mosseriho jeden z nejsilnějších signálů pro dosah k novým lidem
- **Uložení**: u karuselů hlavní signál, že má obsah hodnotu
- **Noví sledující z příspěvku**
- **Zprávy a komentáře s klíčovým slovem** (AUDIT, KONZULTACE…)
- **Kolik konzultací si kdo zarezervoval** – jediné číslo, které platí nájem

Po 4 týdnech se podívej, které 3 příspěvky měly nejvíc sdílení + zpráv, a udělej na ně pokračování.

---

## 3. Jak s obsahem pracovat

1. **Projdi všechna `[DOPLŇ: …]`.** To jsou místa, kde potřebuju tvoje reálná čísla nebo zážitek. Nevymýšlel jsem je. Když údaj nemáš, slide vyhoď, nevymýšlej ho.
2. **Klienti: vyžádej si svolení.** Než ukážeš čísla klienta, pošli mu zprávu typu: *„Ahoj, chtěl bych na svém Instagramu ukázat výsledky naší spolupráce. Můžu použít čísla [jaká] a [se jménem / bez jména]? Pošlu ti to ke schválení.“*
3. **Přečti každý text nahlas.** Když bys to takhle neřekl kamarádovi, přepiš to.
4. **Karusely:** formát 1080 × 1350 px (4:5), 7–11 slidů, max. ~30 slov na slide, jedna myšlenka na slide, jednotná šablona.
5. **Klíčová slova v komentářích** (HLAS, RECENZE…) fungují nejlíp s automatickou odpovědí do zpráv (např. ManyChat). Bez ní musíš odpovídat ručně, a to je ok, dokud je komentářů málo.

---

## 4. Co od tebe potřebuju, aby verze 2 byla výrazně lepší

### A) Analýza těch 5 profilů (to, co jsi původně chtěl)
Nejspolehlivější cesta, protože Instagram blokuje roboty i bez mého omezení:
1. Otevři každý profil → záložka **Reels** → tam vidíš počet zhlédnutí. Udělej screenshot mřížky.
2. U 3–5 nejsledovanějších reels: stáhni video (nebo nahraj obrazovku) a nahraj mi sem soubor.
3. U 3–5 karuselů s nejvíc lajky/komentáři: screenshot **každého slidu + popisku**.
4. Pošli mi i ten jeden příspěvek (DdG5LGJkeHm) jako screenshoty.

Z obrázků vyčtu texty, strukturu, hooky a design. U videí vytáhnu snímky. **Abych videa mohl i přepsat Whisperem**, musíš v nastavení prostředí povolit doménu `huggingface.co` (cloud prostředí → Edit → Network access → Allowed domains, návod: https://code.claude.com/docs/en/cloud-environments#network-access). Povolit `instagram.com` můžeš taky, ale počítej s tím, že Instagram bez přihlášení stejně většinu dat nevydá.

### B) Tvůj hlas (voice-DNA)
Pošli mi **~20 svých textů**: popisky, přepisy svých videí, klidně i hlasovky/zprávy, jak normálně píšeš. Nejlepší jsou přepisy mluveného slova. Udělám z toho tvůj hlasový profil a přepíšu všechno, aby to znělo jako ty.

### C) Data na `[DOPLŇ]`
Nejdůležitější otázky:
1. Jaký je tvůj nejlepší výsledek pro klienta? (obor, kolik dal do reklam, kolik vydělal, za jak dlouho)
2. Kolik ti bylo, když jsi založil Loopside, a kolik máš teď klientů?
3. Jak jsi získal prvního klienta a co se tehdy pokazilo?
4. 3–5 chyb, které bys při zakládání agentury udělal jinak.
5. Jak vypadá tvoje konzultace (délka, co na ní děláš, jak rychle se ozveš)?
6. Co reálně vidíš na konzultacích jako nejčastější chyby firem?

### D) Tvůj vlastní Instagram
Zkusil jsem se přes propojený Meta Ads konektor podívat na tvoje příspěvky (abych viděl, co ti funguje). Akce byla zablokovaná oprávněními, tak jsem ji vzdal. Jestli chceš, abych to zkusil znovu, napiš mi to výslovně. Jinak stačí poslat screenshoty statistik tvých 5 nejlepších příspěvků.
