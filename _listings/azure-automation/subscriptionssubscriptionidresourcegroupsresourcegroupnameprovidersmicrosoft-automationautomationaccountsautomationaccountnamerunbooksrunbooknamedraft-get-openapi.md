---
swagger: "2.0"
x-collection-name: Azure Automation
x-complete: 0
info:
  title: Azure Automation API Runbook Draft Get
  version: 1.0.0
  description: Retrieve the runbook draft identified by runbook name.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/hybridRunbookWorkerGroups/{hybridRunbookWorkerGroupName}
  : delete:
      summary: Hybrid Runbook Worker Group Delete
      description: Delete a hybrid runbook worker group.
      operationId: HybridRunbookWorkerGroup_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroupshybridrunbookworkergroupname-delete
      parameters:
      - in: path
        name: automationAccountName
        description: Automation account name
      - in: path
        name: hybridRunbookWorkerGroupName
        description: The hybrid runbook worker group name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Hybrid
      - Runbook
      - Worker
      - Group
    get:
      summary: Hybrid Runbook Worker Group Get
      description: Retrieve a hybrid runbook worker group.
      operationId: HybridRunbookWorkerGroup_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroupshybridrunbookworkergroupname-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: hybridRunbookWorkerGroupName
        description: The hybrid runbook worker group name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Hybrid
      - Runbook
      - Worker
      - Group
    patch:
      summary: Hybrid Runbook Worker Group Update
      description: Update a hybrid runbook worker group.
      operationId: HybridRunbookWorkerGroup_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroupshybridrunbookworkergroupname-patch
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: hybridRunbookWorkerGroupName
        description: The hybrid runbook worker group name
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The hybrid runbook worker group
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Hybrid
      - Runbook
      - Worker
      - Group
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/hybridRunbookWorkerGroups
  : get:
      summary: Hybrid Runbook Worker Group List By Automation Account
      description: Retrieve a list of hybrid runbook worker groups.
      operationId: HybridRunbookWorkerGroup_ListByAutomationAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamehybridrunbookworkergroups-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Hybrid
      - Runbook
      - Worker
      - Group
      - List
      - Automation
      - Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/jobs/{jobId}/runbookContent
  : get:
      summary: Job Get Runbook Content
      description: Retrieve the runbook content of the job identified by job id.
      operationId: Job_GetRunbookContent
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamejobsjobidrunbookcontent-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: path
        name: jobId
        description: The job id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Job
      - ""
      - Runbook
      - Content
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/runbooks/{runbookName}/draft/content
  : get:
      summary: Runbook Draft Get Content
      description: Retrieve the content of runbook draft identified by runbook name.
      operationId: RunbookDraft_GetContent
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedraftcontent-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: path
        name: runbookName
        description: The runbook name
      responses:
        200:
          description: OK
      tags:
      - Runbook
      - Draft
      - ""
      - Content
    put:
      summary: Runbook Draft Create Or Update
      description: Updates the runbook draft with runbookStream as its content.
      operationId: RunbookDraft_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedraftcontent-put
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: body
        name: runbookContent
        description: Therunbookdraftcontent
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: runbookName
        description: The runbook name
      responses:
        200:
          description: OK
      tags:
      - Runbook
      - Draft
      - Or
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/runbooks/{runbookName}/draft
  : get:
      summary: Runbook Draft Get
      description: Retrieve the runbook draft identified by runbook name.
      operationId: RunbookDraft_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamerunbooksrunbooknamedraft-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: path
        name: runbookName
        description: The runbook name
      responses:
        200:
          description: OK
      tags:
      - Runbook
      - Draft
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---