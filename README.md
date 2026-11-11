<div align="center">

# TihiAi

**Lokalni AI asistent za dokumente na Windowsu.**

[![Najnovija verzija](https://img.shields.io/github/v/release/dujma15/TihiAi.com?display_name=tag&label=verzija&color=2f6f4e)](https://github.com/dujma15/TihiAi.com/releases/latest)
[![Preuzimanja](https://img.shields.io/github/downloads/dujma15/TihiAi.com/total?label=preuzimanja&color=2f6f4e)](https://github.com/dujma15/TihiAi.com/releases)
[![Windows](https://img.shields.io/badge/platform-Windows%2011%20x64-0078D4?logo=windows)](https://github.com/dujma15/TihiAi.com/releases/latest)

### [⬇ Preuzmi najnoviju verziju](https://github.com/dujma15/TihiAi.com/releases/latest)

</div>

---

## O repozitoriju

Ovdje se nalaze samo **Windows instalacijske datoteke** za TihiAi. Izvorni kod nije u ovom repozitoriju.

TihiAi je lokalna aplikacija za rad s dokumentima, projektima i lokalnim AI modelima. Dokumenti, razgovori i izrađeni dokumenti ostaju na računalu; nema zamjene u cloud AI servisu.

- lokalni modeli **Qwen3.5 4B i 9B**
- izrada i uređivanje dokumenata, PDF i Office alati
- **38 profesionalnih predložaka** bez financijskih predložaka
- klijenti, ponavljanja dokumenata/zadataka i kalendar obveza
- masovna izrada dokumenata iz baze klijenata
- OCR, PDF alati i prijepis zvuka
- automatska ažuriranja unutar aplikacije

## Preuzimanje i instalacija

1. Otvori **[Releases](https://github.com/dujma15/TihiAi.com/releases/latest)**.
2. Preuzmi datoteku `TihiAi-Setup-<verzija>.exe`.
3. Pokreni installer i dovrši instalaciju.
4. Pri prvom pokretanju preuzmi željeni lokalni model.

Instalater trenutačno **nije digitalno potpisan**, pa Windows SmartScreen može prikazati upozorenje. Provjeri SHA-256 prije pokretanja ako želiš dodatnu sigurnost.

## Trenutačno izdanje

| | |
|---|---|
| Verzija | **0.9.54** |
| Datoteka | `TihiAi-Setup-0.9.54.exe` |
| Veličina | 210.039.072 bajta |
| SHA-256 | `c84bbefd321f371b64ccc583fb8de2a7589b56a484a41416fb0911947ee427e7` |
| Platforma | Windows 11 x64 |

> Najnovija verzija i njezin SHA-256 uvijek su navedeni u opisu odgovarajućeg releasea.

## Provjera datoteke

U PowerShellu:

```powershell
Get-FileHash .\TihiAi-Setup-0.9.54.exe -Algorithm SHA256
```

Dobiveni hash mora odgovarati hashu iz opisa releasea.

## Preporučeni sustav

- Windows 11 24H2 ili noviji, 64-bitni procesor
- **16 GB RAM** za Qwen3.5 4B
- **24 GB RAM** preporučeno za Qwen3.5 9B
- 8 GB slobodnog prostora za aplikaciju i model
- neobavezna NVIDIA ili Vulkan kompatibilna grafička kartica za ubrzanje
- internet je potreban za preuzimanje modela i neobaveznu web-pretragu

## Nakon instalacije

- Postavke → **Tvrtka** za podatke koji se automatski upisuju u dokumente.
- Postavke → **Modeli** za preuzimanje lokalnog modela.
- **Predlošci** za izradu dokumenata iz biblioteke.
- **Klijenti** za bazu klijenata i ponavljanja.
- **Kalendar** za pregled obveza i rokova.
- Postavke → **Ažuriranja** za ručnu provjeru nove verzije.

## Privatnost

- dokumenti, razgovori i lokalni odgovori ne šalju se cloud AI servisu
- lokalni model radi na računalu nakon preuzimanja
- neobavezna web-pretraga šalje samo aktualno pitanje
- instalater ne sadrži korisničke podatke ni modele

## Poveznice

- Web: [tihiai.com](https://tihiai.com)
- Upute: [tihiai.com/upute](https://tihiai.com/upute)
- Uvjeti korištenja: [tihiai.com/uvjeti](https://tihiai.com/uvjeti)
- Privatnost: [tihiai.com/privatnost](https://tihiai.com/privatnost)
- Sva izdanja: [Releases](https://github.com/dujma15/TihiAi.com/releases)

---

<div align="center">
<sub>TihiAi · lokalna obrada dokumenata · Windows</sub>
</div>
