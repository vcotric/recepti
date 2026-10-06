# Vladini recepti

Lična zbirka recepata na srpskom. Svaki recept ima sastojke, jasne korake i prostor za beleške posle kuvanja.

## Recepti

| Recept | Kategorija | Količina | Ukupno vreme | Status |
|---|---|---|---|---|
| [Klasične juneće faširane šnicle](recepti/glavna-jela/junece-fasirane-snicle.md) | Glavna jela | 6 do 8 šnicli | oko 50 do 60 min | Za probu |
| [Vladine lazanje](recepti/glavna-jela/lazanje.md) | Glavna jela | Za dopunu | Sos 45 do 60 min + pečenje 45 min, uz pripremu i slaganje | Za probu |
| [Posne špagete sa škampima, limunom i mirođijom](recepti/glavna-jela/spagete-sa-skampima-posno.md) | Glavna jela | 200 g špageta + 300 g škampa | Nije navedeno | Za probu |

## Dodaj novi recept

1. Otvori [šablon](sabloni/recept.md) i kopiraj njegov sadržaj.
2. Otvori [novi fajl](https://github.com/vcotric/recepti/new/main/recepti).
3. U ime fajla upiši kategoriju i naziv, na primer `glavna-jela/punjene-paprike.md`.
4. Nalepi šablon, popuni sastojke i korake, pa izaberi **Commit changes**.
5. Dodaj recept u gornju tabelu: otvori ovaj README, klikni olovku i dopiši red sa linkom.

Postojeći recept menjaš tako što ga otvoriš, klikneš olovku i sačuvaš izmenu kroz **Commit changes**. [GitHub uputstvo za uređivanje fajlova](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files).

Možeš i da tražiš od Codexa: „Dodaj recept za punjene paprike” ili „U faširanim šniclama smanji luk i zabeleži da sam ih probao”.

## Organizacija

- `recepti/`: jedan Markdown fajl po receptu, raspoređen po kategorijama.
- `sabloni/recept.md`: isti format za svaki novi recept.
- `slike/`: fotografije tvojih jela.
- `README.md`: pregled i uputstvo.

Kategorije dodajemo kada zatrebaju: `glavna-jela`, `supe-i-corbe`, `prilozi`, `salate`, `dorucak`, `deserti`, `sosovi`.

Nazivi fajlova su malim slovima, bez dijakritike i sa crticama; tekst recepta pišemo normalno, sa č, ć, š, ž i đ.

Varijacije istog jela čuvamo u istom receptu. Zaseban recept pravimo kada se sastojci ili postupak bitno razlikuju. Status može biti **Za probu**, **Isprobano** ili **Omiljeno**. Vremena su okvirna.

## Fotografije

U folder `slike/` postavi fotografiju, na primer `junece-fasirane-snicle.jpg`. Iz recepta u folderu kategorije poveži je ovako:

```markdown
![Juneće faširane šnicle](../../slike/junece-fasirane-snicle.jpg)
```

Sve što postaviš u ovaj javni repozitorijum dostupno je svima. Zbirka trenutno sadrži recepte i uputstva, bez zasebne aplikacije ili sajta.
