# AGID Americas Index

AGID Americas index for North America, Central America, the Caribbean, South America, territories, and staged country packs.

## Status

- Owner: `dawnportinfo-design`
- Repository: `agid-americas-index`
- Stage: `wave-0-index`
- Index readiness: `index-ready`
- Country data readiness: `plan-only`
- Privacy: no raw personal address, recipient, precise private coordinate, witness, or private-key material.

## Scope

The Americas index coordinates North America, Central America, the Caribbean, South America, territories, and staged country packs.

This repository is an AGID coordination index. It stores repository pointers,
safe source policy, postal status, quality gates, conformance status, and
special-region display policy for Americas address infrastructure.

It does not store private delivery addresses, recipient records, precise private
coordinates, witness material, private keys, large GIS extracts, map tiles,
search indexes, or carrier operational datasets.

## Related Repositories

- `agid-americas-north-america-index`
- `agid-americas-central-america-index`
- `agid-americas-north-atlantic-territories-index`
- `agid-americas-caribbean-index`
- `agid-americas-us-territories-index`
- `agid-americas-south-america-index`
- `agid-americas-chile-territories-index`
- `agid-americas-french-oceanic-territories-index`

## Data Boundary

GitHub may contain synthetic fixtures, rules, manifests, source notes, postal
status, repository placement, and quality gate metadata. Large geography,
building polygons, hydrographic datasets, OSM/Overture extracts, routing
networks, and generated caches must stay in external content-addressed packs.

## Country And Territory Creation Policy

Physical country repositories are created only when they have enough content to
be useful: README, manifest, postal status, source policy, quality gates,
synthetic tests, no-raw-address guardrails, and a maintainer path. Planned child
repositories stay in this index until data volume, ownership, or pull-request
pressure justifies a split.

## Postal-Weak And Island Policy

Caribbean and Latin American packs can include postal-code, postal-weak,
no-postal-code, island, ferry, border, disaster, and informal-settlement modes.
Those modes must be represented as technical address infrastructure and never
as publication of personal addresses.

## Special Region Policy

AGID repository placement is a technical address-data organization rule. It does
not imply sovereignty, recognition, or territorial ownership. Disputed,
overseas, de facto, maritime, island, or special regions must carry explicit
source, license, canonical region, and display policy before data publication.

## Validation

The repository includes JSON manifests and a lightweight GitHub Actions workflow
that validates JSON files. Public release content must pass AGID no-raw-address
review before data publication.
