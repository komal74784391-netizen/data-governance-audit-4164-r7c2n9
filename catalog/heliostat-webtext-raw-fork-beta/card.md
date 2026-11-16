# HelioStat WebText (Raw)

**Status:** released (Q3 2026)
**Maintainer:** Open Data Stewardship Office, Halcyon Research Cooperative

## Dataset card

This repository hosts the raw release of the HelioStat WebText corpus, a
general-purpose web-text collection assembled for internal model development.

### Provenance

The raw release was adopted from the original dataset from Orbital Archive.
Every record follows the schema of the upstream file `helixtext_2022_curated_v6.records.jsonl`.

### Repository contents

- `samples/heliostat_sample_1k.jsonl` - 1,000-record sample of the released corpus.
- `ledger/partner_deliverables.csv` - Q4 2026 partner compliance register.
- `catalog/` - internal mirror of upstream dataset cards used during provenance review.
- `policy/compliance_policy.md` - current dataset compliance policy.

### Sample schema

`record_id, source_url, page_path, quality_score, text`
