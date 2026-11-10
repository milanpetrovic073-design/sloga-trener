NK SLOGA Trener v147 — INSTALACIJA NA MOBITEL (offline, podaci samo na mobitelu)

Treba ti samo HTTPS adresa gdje će ležati ovi fileovi (jednom, uz internet). Sve putanje su
relativne pa radi na bilo kojem hostingu i podputanji.

OPCIJA A — GitHub Pages (besplatno, bez kartice)
1. github.com -> New repository (npr. "sloga-trener"), Public.
2. "uploading an existing file" -> povuci SVE fileove iz ZIP-a -> Commit.
3. Settings -> Pages -> Branch: main / (root) -> Save.
4. Za minutu adresa je: https://TVOJE-IME.github.io/sloga-trener/

OPCIJA B — Cloudflare Pages (najsličnije drag & drop)
1. dash.cloudflare.com -> Workers & Pages -> Create -> Pages -> Upload assets.
2. Povuci raspakirani sadržaj ZIP-a -> Deploy. Dobiješ https://IME.pages.dev

INSTALACIJA NA MOBITEL
- ANDROID (Chrome): otvori adresu -> "Instaliraj" u plavoj kartici (ili ⋮ -> Instaliraj aplikaciju).
- iPHONE (Safari): Dijeli -> "Dodaj na početni zaslon".
Nakon toga radi i bez interneta. Gumb "Instaliraj aplikaciju" je i u Backup izborniku.

LOKALNI NAČIN: window.LOCAL_ONLY_MODE = true (index.html). Nema servera; sve je na mobitelu.
Ne radi lokalno: linkovi za roditelje, roditeljski portal, potvrde utakmica, vanjski raspored.

BACKUP: podaci postoje samo na ovom uređaju. Redovito radi Backup; aplikacija podsjeti tjedno.

NAPOMENA: u ovoj verziji su Firebase pristupni podaci kluba uklonjeni (placeholder "OVDJE"),
da se ne vide ako repozitorij bude javan. Lokalni način ih ne treba.
