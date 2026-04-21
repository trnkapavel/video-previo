# CLAUDE.md — Video Previo projekt

## Co je tento projekt
Tvorba 15sekundové video reklamy pro Previo (hotelový PMS).  
Výstupem jsou: scénář, shot list, a sada Veo3 promptů pro každý záběr.

## Jak pracuješ na tomto projektu

### Jazyk
Vždy česky. Technické termíny (shot list, VO, overlay, prompt) ponecháváme v angličtině.

### Tón a styl
- Lidský, klidný, žádný reklamní jazyk
- Žádné superlativy, žádný tlak
- Poselství: Previo funguje → hotely fungují lépe → zákazníci jsou spokojení
- Reference stylu: lifestyle, přirozené, autentické prostředí

### Práce se scénářem
- Vždy vycházej z BRIEF.md jako ze zdroje pravdy
- Pokud navrhuješ změnu scénáře, vysvětli proč (dramaturgický důvod, technické omezení Veo3, casting)
- Scénář je rozdělen na 5 segmentů (0–3s, 3–6s, 6–10s, 10–13s, 13–15s) — drž se tohoto členění

### Veo3 prompty
Každý záběr = jeden prompt. Struktura promptu:
```
[SHOT TYPE] [SUBJECT + ACTION] [ENVIRONMENT] [LIGHTING] [CAMERA MOVEMENT] [MOOD/STYLE]
```
- Piš v angličtině (Veo3 je anglický model)
- Buď konkrétní: věk herce, popis oblečení, typ světla, pohyb kamery
- Vyhýbej se abstraktním pojmům jako „beautiful" nebo „cinematic" — Veo3 potřebuje konkrétní instrukce
- Pro UI záběry vždy specifikuj: over-the-shoulder nebo hand-held phone — nikdy screen recording

### Brand pravidla
- Primární barva: `#b50000` (tmavá červená) — použít na text overlaye, CTA card
- Logo Previo na finálním cardu (13–15s)
- Font: ověřit s brand guidelines (zatím neznáme)

### Soubory projektu
| Soubor | Účel |
|---|---|
| `BRIEF.md` | Zdroj pravdy — scénář, tone, casting, produkce |
| `CLAUDE.md` | Toto — instrukce pro práci |
| `PROMPTS.md` | Finální Veo3 prompty (až budou hotové) |
| `SHOTLIST.md` | Detailní shot list pro produkci (volitelné) |

## Co nedělej
- Nenavrhuj změny scénáře bez vysvětlení
- Nepoužívej ateliérové nebo stock-photo vizuály v promptech
- Nepřidávej uplift / motivační hudbu do audio popisu
- Nevymýšlej barvy značky — drž se `#b50000`
