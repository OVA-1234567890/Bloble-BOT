This is where the actual logic files are located. Originally, these files were directly loaded onto Resource Override, but now it is handled with a loader script. This is becase the file is too large (Resource override converts to a Base64 URL - Really slow)


This change happened around 3.1.7


## CHANGELOG

 - June 27 - 3.1.9 - Started changelog. Optimised game rendering by caching bases. BM mode is limited at 25 to prevent misuse.
 - June 28 - 3.1.9b - Spam is re-enabled but is limited to stop misuse. Same with ad mode. Interrupt mode is added.
 - June 29 - 3.1.9c - Interrupt remove is fixed. Also added chat spam grouping
 - July 10 - 3.2.0 - Small bugs fixed. Filter/ping fixed. Anti Multi-tab system added
 - July 16 - 3.2.0b - 3.2.0c - Added an account restore button to mitigate people losing their accounts
 - August 21 - 3.2.2 - SmartDefend update
