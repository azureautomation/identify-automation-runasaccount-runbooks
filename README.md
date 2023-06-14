# identify-automation-runasaccount-runbooks

A runbook to find all the runbooks in a given automation account which are using run as account. This runbook can be run inside an automation account as a runbook job. It requires subscription id, resource group name, and automation account name as input parameters.
It uses automation account's system identity. This identity needs reader access on automation account, and read runbook content permission.
