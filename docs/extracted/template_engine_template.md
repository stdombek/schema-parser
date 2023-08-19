---
title: template_engine_template
---
# Documentation: [template_engine_template](template_engine_template.md)

## Source:

Module: mod-template-engine

Interface: /templates

## Attributes:

| Property Name              | Property Type   | Property Description                                                                               |
|:---------------------------|:----------------|:---------------------------------------------------------------------------------------------------|
| id                         | string          | Template id                                                                                        |
| description                | string          | Template description                                                                               |
| outputFormats              | array           | Array of output formats                                                                            |
| templateResolver           | string          | Template engine name                                                                               |
| localizedTemplates         | object          | List of localized templates                                                                        |
| metadata                   | object          | Metadata about creation and changes to records, provided by the server (client should not provide) |
| metadata/createdDate       | string          | Date and time when the record was created                                                          |
| metadata/createdByUserId   | string          | ID of the user who created the record (when available)                                             |
| metadata/createdByUsername | string          | Username of the user who created the record (when available)                                       |
| metadata/updatedDate       | string          | Date and time when the record was last updated                                                     |
| metadata/updatedByUserId   | string          | ID of the user who last updated the record (when available)                                        |
| metadata/updatedByUsername | string          | Username of the user who last updated the record (when available)                                  |
