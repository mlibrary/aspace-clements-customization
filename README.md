# aspace-clements-customization
Impliments ArchivesSpace field customizations for Clements Library.

## locales
en.yml is a copy of the top level localization strings file used by Clements as of ArchivesSpace v3.4.1. Use the accompanying diff file to patch newer versions of en.yml rather than using this file directly.

## changes
This plugin reorders several fields in Accession records, suppresses others, and moves the User Defined section to the top. User Defined fields are renamed in the en.yml mentioned above, which is *not* loaded as part of the plugin.

## errata
User Defined section changes also affect other record types. As of this writing this is an unavoidable consequence of the ArchivesSpace archetecture.
