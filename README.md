# Poznámky pro rok 2024/25
Toto je repo obsahující poznámky ze školního roku 2024/25.

**Pozor:** není moudré editovat stejný soubor dvakrát na jednou

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

## Excalidraw
Nová možnost pro silný kreslicí nástroj přímo v Obsidianu. Myslím, že tím můžeš udělat v některých případech mnohem lepší poznámky, třeba Fyzika a tak. Ty matematický formule jsou dost peklo, tak se dají kreslit a dávat vedle sebe. Můžeme potom pořád mít markdowny s linkama na ty obrázky, ať to dává organizačně smysl.

Pro embedování Command pallet: embed excalidraw drawing nebo prostě `![[Drawing 2024-08-24 18.30.01.excalidraw]]]` jako u obrázku
![[Drawing 2024-08-24 18.30.01.excalidraw]]
$$
\begin{bmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{bmatrix}\
$$