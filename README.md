# Diplomová práce

Sestavte sylabus (10-14 témat)
Příprava vybraných úloh (4-5)
- Jiné než vypracovali na VUT.

[[Praktické úlohy pro předmět Počítačová bezpečnost]]
## Zadání
CZ
Praktické úlohy pro předmět Počítačová bezpečnost

EN
Development of Practical Exercises for the Computer Security Course

Zásady pro vypracování:
1. Proveďte rešerši sylabů a praktických řešení kurzů zaměřených na kybernetickou bezpečnost v univerzitním i firemním prostředí.
2. Sestavte sylabus kurzu počítačové bezpečnosti vhodný pro magisterské studium programu Aplikovaná informatika.
3. Navrhněte soubor praktických úloh, které budou použitelné v rámci laboratorních cvičení.
4. Implementujte a otestujte úlohy v laboratorním prostředí.
5. Vyhodnoťte výsledky testování připravených úloh.

Doporučená literatura:
- BROWN, Lawrie. Computer Security: Principles and Practice, Global Edition. Pearson Education, 2024. ISBN 978-1-292-47329-1
- VANDENBRINK, Rob. Linux for Networking Professionals. Packt Publishing, 2021. ISBN 978-1-80020-239-9.

## Literatura

Našel jsem zajímavou literaturu, ale hlouběji jsem se nestihl ponořit:
- [[Alice-and-Bob_Learn-secure-coding.pdf]]
- [[Alice-and-Bob_Learn-Application-Security.pdf]]
- [Výkladový slovník kybernetické bezpečnosti](https://www.cybersecurity.cz/data/Slovnik_610_el.pdf)

### DP práce
DP která se zabývala velmi podobnou problematikou:
[Počítačová cvičení pro předmět Návrh, správa a bezpečnost počítačových sítí](https://www.vut.cz/studenti/zav-prace/detail/167274?zp_id=167274)

## Sylabusy kurzů počítačové bezpečnosti

### TUL - Mojmir Volf
![[Sylabus_Volf]]

## Výbava ve škole 
- Ubuntu, 
- Wirtualbox, 
- openwrt

## Rešeršovatelné zdroje

Poptávka ministerstva obrany na kurz počítačové bezpečnosti (veřejná zakázka 2019)
N00619v00033153

|Poptávky ve veřejné zprávě | Technické a odborné IT školení pro zaměstnance NBÚ |
|--------------------------|-----------------------------------------------|
| Systémové číslo NEN: | 	N006/19/V00033153 |
| Zadavatel | Národní bezpečnostní úřad |
| Druh zakázky | Veřejná zakázka na služby |
| Lhůta aktuálního podání | 26. 11. 2019 10:00:00 |
| Typ aktuálního podání | Nabídka |
| CPV předmětu | 80510000-2 - Odborná školení |
| Popis předmětu | Předmětem školení jsou počítačová školení pro pracovníky NBÚ, jejichž oblasti jsou specifikovány v příloze ZD. |
| Hlavní místo plnění | Hlavní město Praha |
| Typ zakázky | Veřejná zakázka malého rozsahu |

Školení pro firmy:
- [czechitas](https://www.czechitas.cz/kurzy/digitalni-akademie-kyberbezpecnost)

- Chechitas 
  - (kyberbezpečnost)
- OWASP 
  - zap

- OWASP Juice Shop
- DVWA (Damn Vulnerable Web App)
- Root Me, HackTheBox, TryHackMe
- CTFd, FBCTF, pwn.college
- [blackhat](https://blackhat.com/eu-25/?_mc)

## TODO:
 - [ ] Najít jiné DP zajímající se počítačovou bezpečnost. 
 - [ ] Připravit osnovu.

> [!question]
> Jak bude probíhat testování na studentech?

"Pustit si stopky" jsem na Erasmu (+dobrou odpověď pro komisi)

Logická další část:
Vyhodnocení kurzu (Podávka, Najman)

## Osnova

- [ ] Rešerše:
  - [ ] sylabů a praktických řešení kurzů zaměřených na kyberbezpečnost v univerzitním,
  - [ ] firemním prostředí
- [ ] Sestavit sylabus (10-14 témat)
  - [ ] Popis výchozích znalostí studentů
  - [ ] Definování cílových znalostí studentů
- [ ] Návrh souboru praktických úloh (4-5)
  - [ ] Připravit praktické úlohy

Pro každou úlohu popsat:
- Cíl (co se má student naučit)
- Popis zranitelnosti
- Úroveň obtížnosti
- Potřebné znalosti
- Co má student dodat (flag / report / opravený kód)
- Jak se úloha hodnotí
- Technický návrh (architektura, Docker image, databáze…)

### Obsah kurzu (návrh sylabu)

> [!note]
> Ne vždy se 14 úloh dá reálné stihnout (12 je reálných).

Vyhlášky?
- NIS2
- GDPR

> [!question]
> Můžeme s tím něco použít?

### Implementace úloh

Možné úlohy:
- DNS filtr
- Zabezpečení WIFI 
  - Radius
  - wireshark
- Firewall 
- Lokální autentizace LDAP

### Vyhodnocení 
Práce v týmu
Stopnout čas 