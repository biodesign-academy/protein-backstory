# Protein Backstory

*Where your protein came from, and who it's owed to.*

A free web tool from [Biodesign Academy](https://biodesign.academy) for designers working with living matter. Give it any protein in UniProt, by name or ID, and it drafts a **provenance note**: where the protein came from, who recorded it, what is missing, and who it may be owed to.

**Use it:** https://biodesign-academy.github.io/protein-backstory/

**The paper:** Kim, R. (2026). *Protein Backstory: Provenance Notes for Biodesigners* (v1.0). Zenodo. https://doi.org/10.5281/zenodo.24441516

## What it does

Type a protein in plain words (for example `spider silk` or `mussel glue`) and pick the closest match, or paste a UniProt accession if you have one (for example `Q6QZR3`, mussel foot protein 5). Reviewed entries are listed first. The tool then fetches the public records in your browser and fills in the facts:

1. **The sequence**: name, accession, length, fragment, reviewed or not, protein existence level, structures
2. **The organism**: species, and where and when the original sample was collected, from the linked nucleotide record (or "not recorded")
3. **Who recorded it**: submitting authors, year, publication; the institution that submitted the nucleotide record; later papers that mention the record (Europe PMC), marked as leads
6. **Rules that may apply**: flags only (licence, digital sequence information, Cali Fund, Nagoya Protocol), never rulings
8. **Gaps**: listed automatically

You write the two parts only a person should:

4. **Who knew it first**: leads with sources, marked unconfirmed, and who confirmed them. A button copies a research prompt for an AI assistant that asks for sources and never guesses community names.
7. **What goes back**: credit, payment, shared results, or "nothing yet".

Then download the note as a text file.

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

Code: MIT. Notes you create are yours.

Version 0.2, November 2026. Raphael Kim, Biodesign Academy Ltd.
