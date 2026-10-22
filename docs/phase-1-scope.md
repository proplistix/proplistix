# PROPLISTIX — Phase 1 Scope

## 1. Project Overview

PROPLISTIX is a property-listings platform intended to organize and
search property listings for Lahore, Pakistan. Phase 1 establishes
the initial data pipeline, searchable catalog, API, and web interface.

## 2. Phase 1 Objectives

- Establish the project repository and development environment.
- Set up the database and supporting infrastructure using Docker.
- Prepare property and geographic reference data.
- Collect listing data only from sources whose applicable permissions
  and terms have been reviewed.
- Normalize and validate collected listing information.
- Provide an API for searching and filtering listings.
- Build a web interface with listing results, map view, and details.
- Demonstrate a working searchable property catalog.

## 3. Included Features

- Property listing storage and retrieval.
- Search and filters for relevant listing attributes.
- Sorting and pagination.
- Map-based browsing using available geographic data.
- Listing detail pages and permitted source images.
- Links to original listing pages.
- Basic data validation, duplicate handling, and outlier flags.
- Source tracking and documentation.

## 4. Excluded from Phase 1

- The complete set of AI agents planned for later phases.
- Automated property valuation or investment recommendations.
- Production-scale deployment and claims of production readiness.
- Collection of personal contact information unless explicitly
  approved and justified by the project requirements.
- Scraping that violates source terms, access restrictions, or
  applicable law.

## 5. Data Collection and Responsible Use

- Review each source's terms of service and robots.txt before
  implementing a collector.
- Public accessibility alone does not establish permission to scrape.
- Obtain written permission where required, including from smaller
  portals when appropriate.
- Respect rate limits and source access restrictions.
- Record source URLs, collection dates, and relevant data provenance.
- Avoid storing personal phone numbers in the catalog.
- Protect credentials and keep them out of Git.
- Use only approved data fields and permitted images.

## 6. Proposed Technology

- Backend API: Python and FastAPI.
- Database: PostgreSQL with PostGIS.
- Supporting services: Redis and Qdrant.
- Frontend: React and Tailwind CSS.
- Containers: Docker Compose.
- Geographic data: OpenStreetMap data, subject to its licence
  and attribution requirements.

## 7. Phase 1 Acceptance Criteria

- The development services start successfully.
- Database schema and migrations are reproducible.
- Approved reference data can be loaded.
- At least one permitted listing source can be processed end to end.
- Listing records can be searched, filtered, and paginated through
  the API.
- The frontend can display listing results and details.
- Geographic browsing works when suitable location data is available.
- Source attribution, data restrictions, and known limitations
  are documented.
- The supervisor reviews and approves the Phase 1 scope.

## 8. Approval

This document defines the proposed Phase 1 scope for review.
It is a working draft and does not itself grant permission to collect
data from any external source.

Student: ____________________

Supervisor: __________________

Date: ________________________

Approval / comments: __________
