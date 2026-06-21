# Phage Therapy & Targeted Biologics — Lecture Package

Advanced ID-fellow lecture (~1.5 h). Built from the Mandell chapter (Doub, Suh, Chan)
with an added section on monoclonal antibodies as antimicrobial agents.

## Files
- `phage-slides.qmd` — RevealJS deck (84 slides: 67 content + 17 section dividers)
- `phage-webpage.qmd` — HTML lecture notes, aligned section-by-section with the deck
- `phage-references.bib` — 123 BibTeX entries (chapter refs + PubMed-verified mAb refs)
- `diagnostic-microbiology-and-infectious-disease.csl` — citation style
- `custom.scss` — RevealJS theme (placeholder — restyle as you like)
- `_extensions/fontawesome/` — required for `{{< fa >}}` shortcodes
- `phage-images/` — holds `DMM_newlogo.png`; add figures here

## Render (RStudio or terminal)
```bash
quarto render phage-slides.qmd
quarto render phage-webpage.qmd
```
In RStudio: open either `.qmd` and click **Render**.

## Notes
- Could not auto-render here (no Quarto in the build sandbox); BibTeX and YAML
  were validated to parse, every `[@key]` resolves to a bib entry, and every H2
  has a `<br>` beneath it with citations in `::: aside` fenced divs.
- Two `<!-- IMAGE NEEDED -->` placeholders mark figures worth adding
  (tailed-phage diagram). The chapter figures are copyrighted — source CC/own art.
- A few bib entries carry slightly approximated volume/page details from OCR
  (flagged with `note =`); spot-check against the originals before publishing.
