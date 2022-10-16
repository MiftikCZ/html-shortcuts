# html-shortcuts
HTML soubor který umožnuje rychleji se dostat na často navštěvované stránky



![obrazek](https://user-images.githubusercontent.com/89579269/196024272-37adeda7-e6f0-4ef8-a479-45c4da9000c2.png)


## jak přidat custom odkazy?
- bežte do `shortcuts.html` a tam najděte v `<body>` element `<div class="cont">`
- tam uvidíte třeba něco jako
``` html
<tlacitko>GitHub;240;github.com</tlacitko>
```
- tak to můžete upravit nebo duplikovat *(pod to)*
- pokud chcete vytvořit nový, tady je jak:
```html
<tlacitko>
   nápis;
   odstín;
   odkaz
</tlacitko>
```
- takže to může být takhle:
```html
<tlacitko>
   Vyhledávač Google;
   120;
   www.google.com
</tlacitko>
```
- odstín je:
```
0     -    červená
120   -    zelená
200   -    modrá
300   -    fialová
360   -    červená

> nad 360 se to opakuje od nuly

359 == 359
360 == 0
361 == 1
390 == 30
```
