# aspace-clements-customization
Implements ArchivesSpace field customizations for Clements Library.

## Locales
`en.yml` is a copy of the top-level localization strings file used by Clements as of ArchivesSpace v4.1.1. Use the accompanying diff file to patch distributed versions of `en.yml` rather than using this file directly. In an ArchivesSpace distribution, the localization file that needs to be patched is at `archivesspace/locales/en.yml`.

## Changes
This plugin reorders several fields in Accession records, suppresses others, and moves the User Defined section to the top. User Defined fields are renamed in the `en.yml` mentioned above, which is *not* loaded as part of the plugin.

## Errata
User Defined section changes also affect other record types. As of this writing, this is an unavoidable consequence of the ArchivesSpace architecture.
