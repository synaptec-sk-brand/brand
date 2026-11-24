# brand.synaptec.sk

Verejná webová verzia brand a dizajn manuálu Synaptec (verzia 1.2). Statická stránka bez databázy a bez skriptov na serveri – stačí ju nahrať na GitHub Pages.

## Obsah

- `index.html` – celý manuál
- `files/` – logá, Synapsa, písma, PDF manuál, e-mailové podpisy, podklady pre web a LinkedIn (odkazy v sekcii Na stiahnutie)
- `fonts/` – písma pre web (woff2)
- `CNAME` – vlastná doména `brand.synaptec.sk`
- `.nojekyll` – GitHub nemá stránku spracovať Jekyllom (skrytý súbor)

## Zverejnenie cez GitHub Pages

1. Na github.com/synaptec-sk vytvorte nový **verejný** repozitár, napr. `brand`.
2. **Add file › Upload files** a pretiahnite obsah tohto priečinka (nie priečinok samotný). Commit.
3. **Settings › Pages**: Source **Deploy from a branch**, vetva `main`, priečinok `/ (root)`, Save.
4. V tom istom mieste **Custom domain**: `brand.synaptec.sk`, Save.
5. U správcu DNS domény synaptec.sk pridajte záznam: typ **CNAME**, názov **brand**, hodnota **synaptec-sk.github.io**.
6. Po overení DNS zapnite v Settings › Pages **Enforce HTTPS**.

## Aktualizácia

Pri novej verzii manuálu nahrajte nové súbory cez Upload files (prepíšu pôvodné) – stránka sa obnoví do pár minút.
