# PROPLISTIX — Phase 1 Data Source Register

Purpose: Track proposed data sources, restrictions, permissions,
provenance, and approval before any data collection begins.

Status definitions:
- PENDING: Not yet reviewed.
- REVIEWED: Terms and technical restrictions have been examined.
- APPROVED: Required permissions and project approval are documented.
- BLOCKED: Collection is not permitted or remains unresolved.

Do not treat a source as approved merely because its pages are public.

## 1. Property Listing Sources

| Source | Intended use | Terms / robots.txt checked | Permission status | Collection status |
|---|---|---|---|---|
| Agency21 | Property listing fields | Pending | Pending review | PENDING |
| Graana | Property listing fields | Pending | Pending review | PENDING |
| Zameen | Property listing fields | Pending | Pending review | PENDING |
| OLX Pakistan | Property listing fields, subject to review | Pending | Pending review | PENDING |

## 2. Reference and Geographic Sources

| Source | Intended use | Licence / restrictions checked | Status |
|---|---|---|---|
| Lahore Development Authority (LDA) | Approved / illegal scheme reference data | Pending | PENDING |
| Federal Board of Revenue (FBR) | Applicable tax reference data | Pending | PENDING |
| OpenStreetMap (OSM) | Geographic features and map context | Pending | PENDING |

## 3. Required Review for Each Source

Before collecting data, record:

- Source name and official homepage.
- Exact terms-of-service URL and review date.
- robots.txt URL and review date, where applicable.
- Relevant access restrictions and permitted request rate.
- Written permission, if required, and where it is recorded.
- Fields approved for collection.
- Whether images may be stored, proxied, or displayed.
- Attribution and licence requirements.
- Data retention and deletion requirements.
- Decision: APPROVED, BLOCKED, or still PENDING.

## 4. Collection Provenance

For every imported dataset or collection run, record:

- Source identifier.
- Source page or dataset URL.
- Collection or download timestamp.
- Retrieval method and version.
- Applicable permission / licence record.
- Processing and normalization version.
- Any limitations or known data-quality issues.

Do not place passwords, API keys, private contact details, or
confidential permission documents in this public Git repository.

## 5. Approval Log

| Date | Source | Decision | Reviewer | Evidence / notes |
|---|---|---|---|---|
| Pending | Pending | Pending | Pending | No source approved yet |

