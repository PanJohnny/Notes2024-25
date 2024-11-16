# Poznámky pro rok 2024/25
Toto je repo obsahující poznámky ze školního roku 2024/25.

> [!IMPORTANT]
> Dva lidi nesmí editovat stejný soubor najednou. To platí i u nastavení pluginů i když to zní hloupě. Je to jediný způsob jak synchronizovat pluginy. Jestli se to posere, tak se pluginy synchronizovat nebudou a basta.

## Klonování

1. Musíš mít stažený git: https://git-scm.com/downloads
2. GitHub cli pro přihlášení s GitHubem: https://cli.github.com/
3. Když máš obojí staženo, tak musíš v konzoli spustit: `gh auth login` https://cli.github.com/manual/gh_auth_login projít si tím a neodmítej uložení do gitu
4. Kvůli pluginu ještě musíš:
```sh
git config --global user.name "Ivan Novák"
git config --global user.email "email"
```
5. Otevři terminál ve složce, ve které budeš chtít složku se zápisky, např. `Documents`
6. Použij `git clone https://github.com/PanJohnny/Notes2024-25.git` a mělo by se ti všechno naklonovat do nové složky
7. Potom už jenom otevři obsidian a v něm tu složku
8. Povol obsidianu trust a pluginy a pak ho zavři
9. Znovu otevři obsidian a vše by mělo fungovat

## Práce s Gitem
Stačí ti znát tři koncepty:
- commit
- push
- pull

Jo a může přestat fungovat ten plugin očividně, tak kdyžtak stačí restartovat obsidian.

### commit
Command pallet:  `Git: Commit all changes`

Shrne všechny změny a uloží je do verzování.

=> Uloží změny

### push
Command pallet: `Git: Push`

Odešle všechny změny do jiného repozitáře

=> Hodí změny na GitHub

> [!NOTE]
> Může se stát, že se tohle posere. V tom případě bych udělal pull. Jestli to nebude fungovat ani potom tak dej vědět, protože je něco v prdeli.
### pull
Command pallet: `Git: Pull`

Stáhne všechny změny z jiného repozitáře

=> Hodí změny z GitHubu

## Excalidraw
Nová možnost pro silný kreslicí nástroj přímo v Obsidianu. Myslím, že tím můžeš udělat v některých případech mnohem lepší poznámky, třeba Fyzika a tak. Ty matematický formule jsou dost peklo, tak se dají kreslit a dávat vedle sebe. Můžeme potom pořád mít markdowny s linkama na ty obrázky, ať to dává organizačně smysl.

Pro embedování Command pallet: embed excalidraw drawing nebo prostě `![[Drawing 2024-08-24 18.30.01.excalidraw]]]` jako u obrázku
![[Drawing 2024-08-24 18.30.01.excalidraw]]
$$
\begin{bmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{bmatrix}\
$$

## Oprava merge conflictů
**Pozor nebezpečné**
Pokud je branch na githubu aktuální a máš merge conflicty
```sh
git fetch
git reset --hard origin/main
```
**Pokud je tvůj branch aktuální**
Tak mi dej sakra vědět, protože by se to mohlo kompletně dosrat a minulým postupem bys přišel o veškerý progress!