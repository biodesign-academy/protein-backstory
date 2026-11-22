# Protein Backstory

*Where your protein came from, and who it's owed to.*

A free web tool from [Biodesign Academy](https://biodesign.academy) for designers working with living matter. Give it any protein in UniProt, by name or ID, and you get its **backstory card**: where it came from, who recorded it, and what is missing. Nothing to fill in.

**Use it:** https://biodesign-academy.github.io/protein-backstory/

**The paper:** Kim, R. (2026). *Protein Backstory: Provenance Notes for Biodesigners* (v1.0). Zenodo. https://doi.org/10.5281/zenodo.24441516

## What it does

### 1. A card for one protein

Type a protein in plain words (for example `spider silk` or `mussel glue`) and pick the closest match, or paste a UniProt accession (for example `Q6QZR3`, mussel foot protein 5). The tool reads the public records in your browser and shows three lines:

- **Where it came from**: the organism, and where and when the sample was collected, from the linked nucleotide record (or "not recorded")
- **Who recorded it**: the submitting institution and year, or the authors
- **What's missing**: place, date, a publication, a curator's check, the full sequence

Every card has a permanent link, `https://biodesign-academy.github.io/protein-backstory/?id=Q6QZR3`, which re-reads the records each time it opens. Take it with you:

- **Copy link**: paste it next to the protein in a crit, a slide, an exhibition label, a product file or a paper
- **Copy credit line**: one sentence naming the protein, organism, who recorded it, where it was collected, and the card link
- **Download badge**: a small image (lime when a place is recorded, sand when it is not)

### 2. A ledger for many proteins

Paste a list of UniProt IDs, or drop a text, CSV or FASTA file (UniProt FASTA headers work as they are). The tool reads up to 100 proteins and gives one spreadsheet (CSV) with organism, place, date, who recorded it, publications, what's missing, and a link to each card. The summary line says how many have a recorded origin. Re-run it later to see what has changed.

### 3. Leads and fuller notes (optional)

- **Add a lead**: if you know something the records don't, the card opens a prefilled GitHub issue here, with room for a source and whether you want credit by name.
- **Write a fuller note**: the eight-field provenance note from the paper, with rules that may apply (licence, digital sequence information, Cali Fund, Nagoya Protocol, as flags only), who knew it first, and what goes back. Download it as text.

## Principles

- Facts come from the records, never from an AI model.
- "No disclosure found" is not the same as "no rights". Local Contexts Labels are applied only by communities; the tool never assigns one.
- Nothing is sent to Biodesign Academy. Records are fetched directly from UniProt, the European Nucleotide Archive and Europe PMC.
- Not legal advice.

## Data sources

UniProt (CC BY 4.0), the European Nucleotide Archive (EMBL-EBI) and Europe PMC.

## How to cite

Kim, R. (2026). *Protein Backstory: Provenance Notes for Biodesigners* (v1.0). Zenodo. https://doi.org/10.5281/zenodo.24441516

## Licence

Code: MIT. Cards, ledgers and notes you create are yours.

Version 0.3, November 2026. Raphael Kim, Biodesign Academy Ltd.
