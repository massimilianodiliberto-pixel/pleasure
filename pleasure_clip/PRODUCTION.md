# PLEASURE — Registro di produzione

Sessione notturna autonoma. Obiettivo: massimo numero di varianti entro le 16:00.
Nessuna approvazione richiesta durante la produzione. Si sceglie a fine sessione.

## Regole invarianti (non cambiano mai)

- **Discesa continua.** La camera scende sempre. Mai risalite, mai rimbalzi, mai soste.
  Lo scroll va giù: il film va giù. Le clip devono unirsi frame-by-frame senza salto.
- **La goccia è l'eroe.** Sempre in primo piano, sempre a fuoco, sempre centrata.
  Il mondo le scorre attorno verso l'alto.
- **Trasformazione progressiva.** Da piccola e trasparente a densa, dorata, carica di
  particelle in sospensione. Non torna mai indietro.
- **Palette.** Oro `#B8956A`, crema `#F0E8D8`, grigio `#888880`, fondo `#1A1A1C`.
  Verde solo come natura (foglia, muschio). Materiali naturali col loro colore
  (legno, pietra, fango). **Mai colori di linea prodotto** dentro il film.
- **Niente ambienti reali costruiti.** Niente stanze, saloni, laboratori, tavoli.
  Buio e luce radente. Le mani sì, le persone no.
- **Niente testo dentro il video.** Il testo è HTML sopra.
- **Ritmo.** Accelera tra i capitoli, rallenta quasi a fermarsi sul capitolo.

## Concept narrativo

Natura come **essenza**, prodotto come **vetrina**. La goccia raccoglie ciò che la
natura ha già, la biotecnologia lo libera, il metodo lo ricombina, il rito lo applica.
Elemento di tensione disponibile: **l'inquinamento / il danno** — entra e esce a
seconda del capitolo, è ciò da cui la natura difende.

## Sezioni del sito → nome clip

| # | Sezione | Clip | Cosa dice il testo |
|---|---|---|---|
| 1 | Origine | `origine.mp4` | La ascolta, non la estrae |
| 2 | Scienza | `scienza.mp4` | La natura ha già la risposta |
| 3 | Metodo | `metodo.mp4` | Sistema vivo, generativo — **ricombinazione** |
| 4 | Academy | `academy.mp4` | Eleviamo professionisti — trasmissione |
| 5 | Rituali | `rituali.mp4` | Il gesto diventa rito — fango, pennello, vapore |
| 6 | Linee | `linee.mp4` | Quattro linee, una logica |
| 7 | Family | `family.mp4` | Entra nel Circolo — il flacone |

## Verità tecniche verificate (brochure)

- Nessun fermenter proprietario. Tecnologie di terzi: FermentHair HF, AloFerm HF,
  SymProt'in™Oat (Symrise), Baicapil™, Sebaryl®.
- **L'asset proprietario è il metodo generativo**: pochi prodotti, infiniti protocolli.
- Il fango **Scalp Balance Mud** è base unica trasversale: 30 g + 10/15 gocce di
  Active Concentrate diverso per protocollo. È il metodo generativo reso fisico.
- Peptidi **adattivi** dell'avena (non "intelligenti"). Acido ialuronico a **doppio
  peso molecolare** (non "anionici a doppio strato").
- DHPL non esiste: era Baicapil™.
- Strumenti reali: ciotola, pennello, cuffia, panno caldo, tricocamera, piastra.

## Assets prodotti

### Frame finali di capitolo (con testo, per valutazione)
| Sezione | Job | Stato |
|---|---|---|
| Origine | `c6768882-6322-45fa-b845-eec005e014a2` | ✅ approvato |
| Scienza | `7ecb55c4-072d-4f15-bf1e-34d4d438e12c` | prodotto |

### Frame puliti (per generazione video)
| Nome | Job | Stato |
|---|---|---|
| S1 foglia | `3ce6ad94-c8bd-41da-8fcb-0e894846919a` | v1 |
| S2 suolo | `b654a693-6d9a-4eda-bf7b-79062ab6e2dd` | v1 |
| S3 vuoto | `cbea32d7-3a2c-4d45-a195-0b94488c4104` | v1 |
| S4 ciotola | `92ceb10a-d262-4345-9871-0b3791993e52` | v1 |
| S5 flacone | `c966cba7-da87-448b-bcdb-1fd6c7b27730` | v2 approvato |

### Video (prima serie, superata — discesa interrotta)
| Tappa | Job |
|---|---|
| 01 | `f5128c88-fb06-4fc8-b753-dfc947fc0061` |
| 02 | `b2386c5b-21fe-4c5a-aab3-052e911d42bc` |
| 03 | `e805a0e8-1393-48bd-9f63-fbf754acf80c` |
| 04 | `9da5d28b-deaa-4dc9-ad62-a40d9731207a` |
| 05 | `fcc4b989-e73e-4916-9e71-c09468ba44bf` |

## Coda di produzione

1. Frame finali capitoli 3-7 (metodo, academy, rituali, linee, family)
2. Tre varianti del flacone finale: salvia reale / nero-oro / trasparente con oro
3. Varianti alternative per ogni capitolo (mondi diversi, stesso arco)
4. Serie video dalla nuova catena di frame

## Vincoli operativi

- Unlim copre **1080p a 5 secondi**. Non copre 15s.
- **Un solo job alla volta** sul piano plus.
- Upload e download verso Higgsfield bloccati dal proxy: i frame si passano ai video
  come `job_id`, non come file.
- ffmpeg non disponibile in ambiente: encoding e montaggio a valle, fuori da qui.
