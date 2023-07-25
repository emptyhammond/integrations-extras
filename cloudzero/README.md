# Agent Check: CloudZero

## Overview

### Overview
CloudZero helps engineering teams build cost-effective software. Through its innovative platform, CloudZero allocates 100% of customers' cloud, PaaS, and SaaS spend - regardless of their tagging quality - and presents it in a single unified view. It then combines hourly spend data with business- and system-level telemetry to put cloud data in a business context, through precise unit cost metrics like cost per customer, per product, per feature, per team, and more. CloudZero's AI-powered anomaly detection alerts engineers to abnormal spend events, pointing them directly to the affected infrastructure, and promoting engineering engagement in cloud cost management.

### Benefits
Once connected, the CloudZero platform regularly ingests your Datadog billing information for both committed and on-demand costs across all Datadog products. CloudZero unifies this data with the rest of your cloud costs, giving you a comprehensive assessment of your total cloud investment. The platform then puts 100% of your cloud spend through numerous analytics features, revealing opportunities for efficiency and letting you craft and send custom reports.

## Setup

### Installation

Log in to your [CloudZero account](https://app.cloudzero.com) and navigate to the Connections settings. Create a new connection to Datadog. Once a connection is created, you will click "Authorize Datadog Account" to authorize CloudZero to pull data from your Datadog account into the CloudZero platform.

### Configuration

You will be able to adjust settings from the connection details page for your
Datadog connection in CloudZero.

### Validation

1. From the list of [connections](http://app.cloudzero.com/organization/connections), you will be able to see the status of your connection to Datadog. 
2. Click on the name of your Datadog connection to view more details about the
   amount and timing of data that has been pulled from Datadog.
3. Once data ingestion has successfully run, you will see Datadog costs included in the
   [Cost Explorer](http://app.cloudzero.com/explorer). 

### Uninstallation
- Once this integration has been uninstalled, any previous authorizations are revoked.
- Additionally, ensure that all API keys associated with this integration have been disabled by searching for the integration name on the [API Keys page](https://app.datadoghq.com/organization-settings/api-keys).

## Data Collected

### Billing Information
The CloudZero platform regularly ingests your Datadog billing information. This data is unified with the rest of your cloud costs, giving you a comprehensive assessment of your total cloud investment. 

## Troubleshooting

Need help? Contact [CloudZero support][3].

[1]: **LINK_TO_INTEGRATION_SITE**
[2]: https://app.datadoghq.com/account/settings#agent
[3]: mailto:support@cloudzero.com
