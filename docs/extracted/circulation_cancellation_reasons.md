---
title: circulation_cancellation_reasons
---
## Source:

Module: mod-circulation-storage

Interface: /cancellation-reason-storage/cancellation-reasons

## Attributes:

| Property Name                 | Property Type   | Property Description                                                                               |
|:------------------------------|:----------------|:---------------------------------------------------------------------------------------------------|
| id                            | string          |                                                                                                    |
| name                          | string          |                                                                                                    |
| description                   | string          |                                                                                                    |
| publicDescription             | string          |                                                                                                    |
| requiresAdditionalInformation | boolean         |                                                                                                    |
| source                        | string          | Origin of the cancellation reason record, e.g. 'System', 'User', 'Consortium' etc.                 |
| metadata                      | object          | Metadata about creation and changes to records, provided by the server (client should not provide) |
| metadata/createdDate          | string          | Date and time when the record was created                                                          |
| metadata/createdByUserId      | string          | ID of the user who created the record (when available)                                             |
| metadata/createdByUsername    | string          | Username of the user who created the record (when available)                                       |
| metadata/updatedDate          | string          | Date and time when the record was last updated                                                     |
| metadata/updatedByUserId      | string          | ID of the user who last updated the record (when available)                                        |
| metadata/updatedByUsername    | string          | Username of the user who last updated the record (when available)                                  |

