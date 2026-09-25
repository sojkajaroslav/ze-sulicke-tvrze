# Ze Sulické tvrze

Statická kopie veřejného webu chovatelské stanice, připravená pro GitHub a Cloudflare Pages. Obsahuje sedm stránek, lokální fotografie a mobilní navigaci.

## Nahrání na GitHub

Vytvořte nový repozitář a nahrajte celý obsah této složky včetně podsložek `assets`, `novinky`, `nasi-psi`, `stenata`, `odchovy`, `rozhodci-exterieru` a `kontakt`.

## Cloudflare Pages

V Cloudflare otevřete **Workers & Pages → Create → Pages → Connect to Git** a vyberte repozitář. Jako **Framework preset** zvolte **None**, **Build command** ponechte prázdný a **Build output directory** nastavte na `/` (kořen repozitáře). Pak spusťte nasazení. Web nepotřebuje databázi ani instalační krok.

Pro vlastní doménu přidejte doménu v nastavení Pages projektu. 

## Náhled na počítači

Ve složce projektu spusťte `python3 -m http.server 8000` a otevřete `http://localhost:8000/`.
