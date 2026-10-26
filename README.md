# ChargePoint (chargepoint)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

ChargePoint operates one of the world's largest EV charging networks, providing a Web Services API for finding stations, checking real-time availability, managing load, initiating and monitoring charging sessions, and accessing usage data for fleet and home charging deployments. The platform supports enterprise fleet electrification through open APIs and 40+ integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chargepoint/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chargepoint/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- EV Charging
- Electric Vehicles
- Fleet Management
- Energy Management
- Transportation

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### ChargePoint Stations API

Retrieve detailed information about ChargePoint charging stations, including location, address, GPS coordinates, power specifications, port counts, pricing, and station model details. Supports filtering by location, station group, and organization.

#### Tags

- Stations
- EV Charging
- Locations

#### Properties

- [Documentation](https://docs.chargepoint.com)
- [W S D L](https://webservices.chargepoint.com/cp_api_5.1.wsdl)

### ChargePoint Station Status API

Query real-time status of ChargePoint charging station ports. Returns port availability states including AVAILABLE, INUSE, UNREACHABLE, and UNKNOWN with timestamps, enabling applications to display live station availability to EV drivers.

#### Tags

- Stations
- Status
- Availability
- EV Charging

#### Properties

- [Documentation](https://docs.chargepoint.com)
- [W S D L](https://webservices.chargepoint.com/cp_api_5.1.wsdl)

### ChargePoint Load Management API

Monitor and control power load at ChargePoint charging stations. Retrieve current load in kilowatts, issue load shedding commands to limit station power by percentage or maximum load for a specified time period, and clear shed states to resume normal charging operations.

#### Tags

- Load Management
- Energy
- Power Management
- EV Charging

#### Properties

- [Documentation](https://docs.chargepoint.com)
- [W S D L](https://webservices.chargepoint.com/cp_api_5.1.wsdl)

### ChargePoint Charging Sessions API

Access charging session data for ChargePoint stations, including energy consumed (kWh), session start and end timestamps, session identifiers, and driver information. Supports fleet and home charging usage reporting and reconciliation workflows.

#### Tags

- Sessions
- Charging
- Energy
- Usage Data

#### Properties

- [Documentation](https://docs.chargepoint.com)
- [W S D L](https://webservices.chargepoint.com/cp_api_5.1.wsdl)

### ChargePoint Alarms API

Retrieve and manage alarms from ChargePoint charging stations. Returns alarm type, alarm timestamp, and station identifier for the most recent alarm condition. Supports clearing all active alarms on a station to restore normal monitoring state.

#### Tags

- Alarms
- Monitoring
- Alerts
- EV Charging

#### Properties

- [Documentation](https://docs.chargepoint.com)
- [W S D L](https://webservices.chargepoint.com/cp_api_5.1.wsdl)

### ChargePoint Station Groups API

Manage and query ChargePoint station groups that organize charging infrastructure by location, fleet, or organizational unit. Retrieve group hierarchies, station rights profiles, and CPN (ChargePoint Network) instance configurations for enterprise and fleet deployments.

#### Tags

- Station Groups
- Organization
- Fleet
- EV Charging

#### Properties

- [Documentation](https://docs.chargepoint.com)
- [W S D L](https://webservices.chargepoint.com/cp_api_5.1.wsdl)

### ChargePoint Fleet Management API

Manage electric vehicle fleet charging through ChargePoint's platform. Access vehicle registration, driver assignment, charging schedules, and fleet-level usage reporting. Integrates with fleet telematics and fuel card systems for unified fleet operations.

#### Tags

- Fleet
- Vehicles
- Management
- EV Charging

#### Properties

- [Documentation](https://docs.chargepoint.com)
- [Documentation](https://www.chargepoint.com/businesses/fleet)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/chargepoint)
- [Website](https://www.chargepoint.com)
- [Terms of Service](https://na.chargepoint.com/terms_web)
- [Terms of Service](https://www.chargepoint.com/download-file/chargepoint-api-services-terms-and-conditions-na)
- [Documentation](https://docs.chargepoint.com)
- [W S D L](https://webservices.chargepoint.com/cp_api_5.1.wsdl)
- [API Reference](https://docs.chargepoint.com/ref-docs-sec/content/pdfs/4-software/api/cp_api5.1.pdf)
- [Getting Started](https://na.chargepoint.com/UI/s3docs/docs/help/SetupWebServicesAPI.pdf)
- [Status Page](https://chargepoint-fleet-telematics.statuspage.io/)
- [Blog](https://www.chargepoint.com/blog)
- [Blog](https://www.chargepoint.com/engineering/)
- [Documentation](https://www.chargepoint.com/businesses/software)
- [Portal](https://partner.chargepoint.com)
- [GitHub Organization](https://github.com/ChargePoint)
- [Python  S D K](https://github.com/mbillow/python-chargepoint)
- [X ( Twitter)](https://x.com/chargepoint)
- [Authentication](https://docs.chargepoint.com)
- [Support](mailto:devsupport@chargepoint.com)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**FN:** APIs.json
**Email:** info@apis.io
**Email:** devsupport@chargepoint.com
**URL:** https://www.chargepoint.com
