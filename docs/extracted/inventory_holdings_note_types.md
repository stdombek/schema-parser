---
title: inventory_holdings_note_types
---
# Documentation: [inventory_holdings_note_types](inventory_holdings_note_types.md)

## Source:

Module: mod-inventory-storage

Interface: /holdings-note-types

## Attributes:

| Property Name              | Property Type   | Property Description                                                                               |
|:---------------------------|:----------------|:---------------------------------------------------------------------------------------------------|
| id                         | string          | unique ID of the holdings note type; a UUID                                                        |
| name                       | string          | name of the holdings note type                                                                     |
| source                     | string          | label indicating where the holdings note type entry originates from, i.e. 'folio' or 'local'       |
| metadata                   | object          | Metadata about creation and changes to records, provided by the server (client should not provide) |
| metadata/createdDate       | string          | Date and time when the record was created                                                          |
| metadata/createdByUserId   | string          | ID of the user who created the record (when available)                                             |
| metadata/createdByUsername | string          | Username of the user who created the record (when available)                                       |
| metadata/updatedDate       | string          | Date and time when the record was last updated                                                     |
| metadata/updatedByUserId   | string          | ID of the user who last updated the record (when available)                                        |
| metadata/updatedByUsername | string          | Username of the user who last updated the record (when available)                                  |
