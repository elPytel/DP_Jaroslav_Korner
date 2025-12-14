# Diplomová práce

- [Diplomová práce](#diplomová-práce)
  - [Zadání](#zadání)
  - [Literatura](#literatura)
    - [DP práce](#dp-práce)
  - [Sylabusy kurzů počítačové bezpečnosti](#sylabusy-kurzů-počítačové-bezpečnosti)
    - [TUL - Mojmir Volf](#tul---mojmir-volf)
  - [Výbava ve škole](#výbava-ve-škole)
  - [Rešeršovatelné zdroje](#rešeršovatelné-zdroje)
  - [TODO:](#todo)
  - [Osnova](#osnova)
    - [Obsah kurzu (návrh sylabu)](#obsah-kurzu-návrh-sylabu)
    - [Implementace úloh](#implementace-úloh)
    - [Vyhodnocení](#vyhodnocení)

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

## Výbava ve škole 
- Ubuntu, 
- Wirtualbox, 
- openwrt

## TODO:

- [ ] Rešerše:
  - [ ] Najít jiné DP zajímající se počítačovou bezpečnost. 
  - [ ] Sylabusy kurzů počítačové bezpečnosti
  - [ ] Praktická řešení kurzů zaměřených na kyberbezpečnost:
	  - [ ] univerzitním,
	  - [ ] firemním prostředí.
 - [ ] Připravit osnovu.

> [!question]
> Jak bude probíhat testování na studentech?

"Pustit si stopky" jsem na Erasmu (+dobrou odpověď pro komisi)

Logická další část:
Vyhodnocení kurzu (Podávka, Najman)

## Rešeršovatelné zdroje
- [[Platformy a kurzy]]
- [[Studijní obory]]

### Školení pro firmy:
- [Czechitas](https://www.czechitas.cz/)
  - [kyberbezpečnost](https://www.czechitas.cz/kurzy/digitalni-akademie-kyberbezpecnost)
- [CZ.NIC](https://www.nic.cz/)
  - [Síťování v Linuxu](https://moodle.nic.cz/course/view.php?id=36#section-0)
  - [Základy DNS](https://moodle.nic.cz/course/view.php?id=5)
  - [Rodina protokolů TCP/IP](https://moodle.nic.cz/course/view.php?id=2)
  - [Svět internetových domén](https://moodle.nic.cz/course/view.php?id=10)

### OSINT tréningové nástroje:
- [OWASP](https://owasp.org/projects/) 
  - [zap](https://www.zaproxy.org/)
  - [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)
  - [OWASP Top 10](https://owasp.org/Top10/2021/) (Web app vulnerabilities)
- [DVWA](https://github.com/digininja/DVWA) (Damn Vulnerable Web App)
- DVL (Damn Vulnerable Linux)
- Root Me, HackTheBox, TryHackMe
- CTFd, FBCTF, pwn.college
- [blackhat](https://blackhat.com/) conferences

## Osnova

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