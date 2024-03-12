# X4-Resource-Info

Lists resource ranks based on resource refresh rates from a 6.20 savegame with all DLC.

Rather than using an index based on the raw numbers which can be hard to interpret due to the large variation, the ranks for a resource X are generated as follows:
1. Take all sectors that have resource X (respawning)
2. Order the list from best to worst for resource X, based on the aggregated <max>/<time> value of all resource areas in the sector
3. The top 10% of the list gets rank 1, the next 10% gets rank 2, etc, all the way to the bottom 10% which gets rank 10

A blank value means the sector does not have that specific respawning resource.

This does not give you exact information on how much you can mine in a specific sector, but rather tells you that anything with rank 1, 2 or 3 is in the top 30% for that resource, so is probably a good place to send your miners.

In my experience it's hard to 'empty' a sector in the top 30% even when throwing large numbers of L miners at it. Sectors with rank 8-10 on the other hand are liable to run out of resources quickly with a few hungry factories nearby.

The file is standard quoted CSV, you should be able to open it in Excel or LibreOffice or whatever your fav spreadsheet app is without much trouble.
