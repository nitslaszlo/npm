# Fontos npm parancsok
```sh
Verziószám felépítése: major.minor.patch
~: Fix major és minor, bármely patch
^: Fix major, mármely minor és patch
*: Bármely verzió
```
![Node csomagok verziószáma](wheelbarrel-with-tilde-caret-white-bg-w1000.jpg "Node csomagok verziószáma")
## 1. package.json file létrehozása
```sh
npm init
```
## 2. Lokálisan és globálisan telepített node csomagok listája
```sh
npm ls
npm ls -g
```
## 3. package.json állományban felsorolt node csomagok telepítése
```sh
npm install
npm i
```
## 4. Megadott node csomag telepítése (g->global, D->devDep.)
```sh
npm i [-g] [-D] <package>
npm install [-g] [-D] <package>
```
## 5. Megadott node csomag törlése (g->global)
```sh
npm un [-g] <package>
npm uninstall [-g] <package>
```
## 6. npm cache kezelése
```sh
npm cache ls
npm cache verify
npm cache clean --force
```
## 7. Bármely node csomag adatainak listázása
```sh
npm view <package>
npm view <package> versions
```
## 7. npm csomag(ok) és az npm frissítése
```sh
npm update
npm update -g
npm update <package>
npm update -g <package>
npm update -g npm
```
 

