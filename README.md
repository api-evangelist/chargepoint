# ChargePoint (chargepoint)

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
