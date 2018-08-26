---
name: Azure Automation
x-slug: azure-automation
description: Automate all of those frequent, time-consuming, and error-prone cloud
  management tasks. Azure Automation helps you focus on work that adds business value.
  By reducing errors and boosting efficiency, it also helps to lower your operational
  costs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Runbook
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/apis.md
specificationVersion: "0.14"
apis:
- name: AutomationManagementClient - Hybrid Runbook Worker Group List By Automation
    Account
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroups-get
  description: Retrieve a list of hybrid runbook worker groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com//
  tags: Microsoft, Orchestration, Automation, Webhooks, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroups-get-openapi.md
- name: AutomationManagementClient - Runbook Draft Get Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedraftcontent-get
  description: Retrieve the content of runbook draft identified by runbook name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com//
  tags: Microsoft, Orchestration, Automation, Webhooks, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedraftcontent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedraftcontent-get-openapi.md
- name: AutomationManagementClient - Runbook Get Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamecontent-get
  description: Retrieve the content of runbook identified by runbook name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com//
  tags: Microsoft, Orchestration, Automation, Webhooks, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamecontent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamecontent-get-openapi.md
- name: AutomationManagementClient - Runbook List By Automation Account
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooks-get
  description: Retrieve a list of runbooks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com//
  tags: Microsoft, Orchestration, Automation, Webhooks, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/runbook/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooks-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.application.insights.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.automation.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/automation/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/automation/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/automation/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/automation/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---