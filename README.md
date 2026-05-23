# Acts Retirement-Life Communities (acts-retirement)

Acts Retirement-Life Communities is a not-for-profit operator of continuing care retirement communities (CCRCs) headquartered in West Point, Pennsylvania. Founded in 1972, Acts operates 28 senior living campuses across nine Mid-Atlantic and Southeastern U.S. states (Alabama, Delaware, Florida, Georgia, Maryland, New Jersey, North Carolina, Pennsylvania, South Carolina) and serves approximately 10,000 residents. Its core service lines are independent living for adults 55+, assisted living, memory care, skilled nursing, short-term rehabilitation, and on-campus health services delivered under the Acts Life Care contract model.

Acts publishes no public developer APIs, no OpenAPI specifications, no SDKs, and no developer portal — its digital surface consists of a marketing website, a community directory, an iCIMS-hosted careers portal at `careers-actslife.icims.com`, and a separate health-services marketing site at `actshealthservices.org`. This repository documents the organization and its likely senior-living IT vendor stack for ecosystem-mapping purposes; it does not document a developer API surface because none is published.

**URL:** [https://www.actsretirement.org](https://www.actsretirement.org)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Senior Living, Retirement Communities, Continuing Care Retirement Community, Healthcare, Skilled Nursing, Assisted Living, Memory Care, Independent Living, Nonprofit, Long Term Care

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

No public developer APIs are documented or published by Acts Retirement-Life Communities. Senior-living nonprofits in this market segment rarely expose public API surfaces; clinical, HR, payroll, and resident-billing data sit inside vendor-hosted SaaS platforms that are not externally addressable.

## Common Properties

- [Website](https://www.actsretirement.org)
- [Portal](https://www.actsretirement.org)
- [About](https://www.actsretirement.org/about-acts/)
- [Communities](https://www.actsretirement.org/communities/)
- [News](https://www.actsretirement.org/latest-retirement-news/)
- [HealthServices](https://actshealthservices.org)
- [Careers](https://careers-actslife.icims.com/jobs/search)
- [Contact](https://www.actsretirement.org/contact-us/)
- [PrivacyPolicy](https://www.actsretirement.org/privacy-policy/)
- [LinkedIn](https://www.linkedin.com/company/acts-retirement-life-communities)
- [Facebook](https://www.facebook.com/ActsRetirement)
- [YouTube](https://www.youtube.com/user/ActsRetirementLife)
- [GitHub](https://github.com/api-evangelist/acts-retirement)

## Features

| Name | Description |
|------|-------------|
| Independent Living | Maintenance-free apartment, cottage, and villa residences for active adults 55+ across 28 campuses, with dining, fitness, social programming, and lifelong learning amenities included. |
| Assisted Living | On-campus personal care residences providing assistance with activities of daily living (bathing, dressing, medication management) for residents who can no longer live fully independently. |
| Memory Care | Specialized residential neighborhoods for residents living with Alzheimer's disease and other forms of dementia, with secured environments and dementia-trained staff. |
| Skilled Nursing Care | On-site licensed skilled nursing facilities providing 24-hour professional nursing for residents requiring complex medical care or long-term custodial care. |
| Short-Term Rehabilitation | Inpatient and outpatient rehabilitation services including physical, occupational, and speech therapy following hospitalization, surgery, or illness. |
| Acts Life Care Contract | A continuing-care contract that combines independent-living residency with prepaid access to on-campus assisted living, memory care, and skilled nursing at the same monthly fee structure, providing long-term care cost certainty. |
| Acts Benevolence | A charitable program funded by the Acts Legacy Foundation that provides financial assistance to residents who outlive their personal resources, ensuring no resident is asked to leave for inability to pay. |
| On-Campus Health Services | Primary-care medical clinics, nurse practitioner programs, and hospice services delivered on each Acts campus under the Acts Health Services brand. |

## Use Cases

| Name | Description |
|------|-------------|
| Retirement Community Selection | Older adults and their families evaluating CCRC options across the Mid-Atlantic and Southeast U.S. can browse all 28 Acts campuses by state, compare pricing tiers, and request information packets through the public marketing site. |
| Acts Life Care Contract Purchase | Prospective residents can sign an Acts Life Care contract at any of the 28 communities, locking in lifetime access to the full care continuum (independent through skilled nursing) at predictable monthly fees. |
| Employment Search And Application | Job seekers across nursing, dining, hospitality, facilities, and administrative roles can search and apply to openings at any Acts campus through the iCIMS-powered careers portal at careers-actslife.icims.com. |
| Charitable Giving | Donors can contribute to the Acts Legacy Foundation to support benevolent care for residents who exhaust their personal financial resources during their tenure. |
| Vendor And Partner Inquiry | Healthcare technology vendors, food-service suppliers, construction contractors, and professional service firms can identify Acts procurement contacts through the public contact and corporate compliance pages. |

## Solutions

| Name | Description |
|------|-------------|
| Lifetime Care Cost Certainty | The Acts Life Care contract addresses the senior-living industry's biggest financial risk — open-ended long-term-care costs — by bundling all future care levels into a single predictable monthly fee structure backed by Acts Benevolence. |
| Geographic Continuity Of Care | With 28 campuses across nine Eastern and Southeastern states, residents and their families can relocate within the Acts network while preserving their Life Care contract benefits and care history. |
| Faith-Based Nonprofit Operating Model | As a not-for-profit organization rooted in a Christian ministry heritage, Acts reinvests operating margin into resident services, benevolent care, and capital improvements rather than distributing profits to investors. |

## Integrations (Confirmed and Likely)

| Name | Description |
|------|-------------|
| iCIMS Talent Cloud (Careers) — Confirmed | The Acts careers portal is hosted on iCIMS at careers-actslife.icims.com, indicating iCIMS Talent Cloud as the applicant tracking system and recruiting marketing platform. |
| Likely Clinical EHR | As a multi-site skilled nursing and assisted living operator, Acts almost certainly runs an LTC/PAC-focused electronic health record such as PointClickCare, MatrixCare, or Netsmart MyUnity, but the specific vendor is not publicly disclosed on the Acts website. |
| Likely HRIS/Payroll | With ~10,000 residents across 28 campuses, Acts operates a large workforce that requires a multi-site HRIS, payroll, and workforce management platform (commonly Workday, UKG Pro/Ready, Paycom, or Oracle HCM in this market segment); the specific vendor is not publicly disclosed. |
| Likely ERP/Financials | Multi-entity nonprofit CCRC operators typically run Workday Financials, Sage Intacct, Oracle NetSuite, or MRI/Yardi for resident billing and general ledger; the specific vendor is not publicly disclosed. |

## Notable Absences

- No public developer portal, OpenAPI specs, SDKs, or API documentation.
- No public RSS or Atom feed on the news / latest-retirement-news section.
- No resident-portal or mobile-app surface is publicly linked from the marketing site.
- No public disclosure of clinical EHR, HRIS, payroll, or ERP vendor selections.
- No GitHub organization operated by Acts Retirement-Life Communities.
- No public technology blog, engineering blog, or vendor case studies referencing Acts.

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
