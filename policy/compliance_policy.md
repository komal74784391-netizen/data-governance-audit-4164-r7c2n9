# Dataset Compliance Policy - Q4 2026

## Scope

This policy applies to every data partner listed in
`ledger/partner_deliverables.csv`. Partners whose status is `withdrawn` are
out of scope for the cycle. `external_auditor` accounts are assurance staff,
not data partners, and are also out of scope.

## Required evidence for active partners

Each active partner must hold current-cycle evidence for:

- `provenance_record`
- `license_attestation`
- `schema_conformance`
- `deidentification_audit`
- `retention_policy`

A partner with any required item outstanding is not clear for release.

## Redistribution waivers

A redistribution waiver is required only when the immediate upstream dataset
card declares a non-permissive license. If the upstream card declares a
permissive or public-domain license (for example CC0, CC BY, ODC-BY, MIT, or
Apache-2.0), no waiver is required for any partner in this cycle. The
`redistribution_waiver` column is informational unless a waiver is required.

## License attestations

License attestations are submitted directly by partner contacts to the
compliance mailbox each cycle. They are not transcribed into the partner
register, so the register's `license_attestation` column is not the source of
truth for that item.

## Register status vocabulary

A deliverable cell is `complete` only when the evidence has been accepted.
`pending` and blank cells mean the evidence has not been accepted for the
cycle.
