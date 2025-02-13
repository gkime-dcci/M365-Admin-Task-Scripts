# **M365-Admin-Task-Scripts**

**_Powershell scripts for performing admin tasks in m365 tenants_**

## **Workflow-Scripts**

_Scripts for automating admin workflows_

## Admin Center Workflows

- ## `Create-User` _-firstname, -lastname, -email, -license(s), -date-to-create?_

- ## `Archive-User` _-firstname, -lastname, -email, -date-to-archive?_

- ## `Get-User` _-firstname?, -lastname?, -email?_

- ## `Reset-User-Password` _-email -new-password_

- ## `Convert-Mailbox-To-Shared` _-email_

- ## `Add-User-To-Group` _-user -role_

- ## `Grant-User-Shared-Mailbox-Permissions` _-target-mailbox -user-to-grant-perms -send-as -manage_

- ## `Export-Users-To-CSV` _-column-name(s) -filter-by -sort-by_

# Utility-Scripts

_Scripts for automating individual admin actions_

- ## `Connect-To-Tenant` _`-admin-email`, `-admin-password`. `-OTP`_
- ## `Add-365-License-To-User` _-email, -license_
- ## Remove-365-License-From-User _-email, -license-type_
- ## Get-Users-From-CSV _-csv-path_
