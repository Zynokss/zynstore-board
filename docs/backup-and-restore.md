# Backup and restore

## What is stored where

The connected service stores catalog, account and order records. The storefront also keeps cart and favorites in browser storage. ZynBoard keeps some settings and deleted-product records in browser storage. Browser-local information is specific to that browser and can disappear when site data is cleared.

## Order exports

Orders Feed provides a CSV export of its filtered order list. Keep exports in a private location with access limited to authorized staff. They can contain customer information.

CSV export is not a complete backup: it does not include the full service database, account credentials, all product relationships or all browser-local settings. No user-facing CSV restore/import workflow was verified.

## Product trash

Deleting a product removes it from the service and keeps a local trash entry in that browser. Restore creates a product from the saved fields; it does not promise the original product identifier or relationships. Clearing trash or browser data can remove those recovery entries. Ask the operator for help before relying on trash for recovery.

## Full backup and recovery

No complete backup-and-restore interface was verified. Server backups and recovery must be handled by the service operator using the private operational workflow. This public repository contains neither a database backup nor recovery credentials. A tested recovery procedure and recovery-time guarantee are not established by this review.

Before deleting records or clearing browser data, contact contact@zynoks.com if you need to preserve information. Do not attach exports, backups or customer records to GitHub Issues.
