> **Note**
> The content of this repo is not officially supported by Dynatrace!

# :tada: :tada: Welcome to the Customer Success hub :tada: :tada:

You'll find open source solutions that help you level up your observability game with Dynatrace.


## Dynatrace Tenant Review
*The assistant that helps you get the maximum value from the Dynatrace platform.*

![Dynatrace Tenant Review](https://github.com/dynatrace-oss/CustomerSuccess/blob/main/Dynatrace%20Tenant%20Review/screenshot.png "Dynatrace Tenant Review")

This Dashboard highly leverages code tiles to perform a wide and deep analysis of your actual state of configuration and adoption of top Dynatrace capabilities.

Admins can download and import the JSON definition of the DTR Dashboard in their own tenant to discover what fundamentals, best practices and recommendations they should prioritize and implement to maximize Dynatrace's positive impact in their organization.

The Dynatrace Tenant Review is:
 - **Safe**: The Dashboards app and the DTR are both restricted to read-only permissions/calls by design. Furthermore, no data ever leaves the Dynatrace tenant.
 - **Fast**: The analytics happens where the data resides, in Grail™.
 - **Open source**: Copy, inspect, customize and share it in a few clicks!

## Adoption & Audit Dashboard
*The dashboard that gives you full visibility into platform adoption, user engagement and audit activity across your Dynatrace environment.*

![Adoption & Audit Dashboard](https://github.com/dynatrace-oss/CustomerSuccess/blob/main/Adoption%20%26%20Audit%20Dashboard/screenshot.png "Adoption & Audit Dashboard")

This Dashboard leverages Grail™ audit events and DQL query telemetry to surface actionable insights about how your organization uses Dynatrace. With 34 tiles across 17 sections it covers KPI cards, daily activity trends, app adoption rankings, configuration audit trails, DQL query analytics, workflow health, user engagement scorecards and more.

Admins can download and import the JSON definition of the Dashboard in their own tenant to understand which teams are active, which platform capabilities are under-utilized, and where to focus enablement efforts.

The Adoption & Audit Dashboard is:
 - **Safe**: Restricted to read-only audit event queries by design. No data ever leaves the Dynatrace tenant.
 - **Fast**: All analytics happen where the data resides, in Grail™.
 - **Open source**: Copy, inspect, customize and share it in a few clicks!

**Installation**: Download and import the JSON definition of the Dashboard into your Dynatrace tenant via the Dashboards app.

**Usage**:
- Monitor overall platform adoption with KPI cards (Total Events, Unique Users, Browser Interactions, Config Changes)
- Identify the most active users and the most accessed endpoints
- Track app-level usage rankings and trends over time
- Audit configuration changes by schema and by user
- Analyze DQL query volume, data consumption and query success rates
- Monitor workflow execution health with color-coded thresholds
- Measure user engagement depth (apps per user, observability domain coverage)
- Share filtered views with stakeholders to drive adoption initiatives

## Software Obsolescence Management
*The solution that lets you stay on top of your software portfolio.*

![Software Obsolescence Management](https://github.com/dynatrace-oss/CustomerSuccess/blob/main/Software%20Obsolescence%20Management/screenshot.png "Software Obsolescence Management")

The JavaScript Workflow regularly refreshes obsolescence data required for your environment from external open source APIs. The DQL Dashboard matches this external data with native Dynatrace data to let you discover prioritized maintenance actions to keep your software components and operations safe, compliant and supported by the corresponding vendors (when applicable).

**Installation**: Download and import the JSON definition of the Dashboard in their own tenant and follow the instructions provided in its bottom-right corner tile.

**Usage**:
- Scope the audit by Segment, Management Zone or Tag
- Filter by obsolescence statuses
- Filter by Operating Systems, Technologies and Libraries
- Prioritize your maintenance by vulnerability and obsolescence risk, criticity and radius of the affected software components or even time remaining before obsolescence
- Share the filtered view's URL to the responsible team so that they keep their software safe and supported
- Navigate to the associated entity by clicking any entry in the full-detail tables and then on "Open record with"
- Extend your OneAgent coverage to reduce obsolescence risks. The [Discovery mode](https://www.dynatrace.com/platform/infrastructure-observability/foundation-and-discovery/) + [Code Module injection](https://docs.dynatrace.com/docs/observe/infrastructure-monitoring/hosts/monitoring-modes#code-module-injection) are sufficient for that capability.
- [Activate AppSec](https://docs.dynatrace.com/docs/secure/application-security/application-protection) to reduce security risks from vulnerabilities. The [Discovery mode](https://www.dynatrace.com/platform/infrastructure-observability/foundation-and-discovery/) + [Code Module injection](https://docs.dynatrace.com/docs/observe/infrastructure-monitoring/hosts/monitoring-modes#code-module-injection) are sufficient for that capability.
- Update the "SupportOverrides" variable with your own support terms (cf. installation step 7)
- Get alerted 30 days before any OS becomes obsolete
- Track the solution's usage of the platform to understand and optimize its cost

**Request For Enhancement**: https://dt-url.net/som-rfe

**Credits**:
- [endoflife.date](https://endoflife.date) (for OS and Technology obsolescence data)
- [deps.dev](https://deps.dev) (for Library obsolescence data)
- [Dynatrace AppSec](https://docs.dynatrace.com/docs/secure/application-security/vulnerability-analytics/vulnerabilities) (for Vulnerability insights)
