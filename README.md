# The MiSTer Database For Game Manuals (POC) 

This is a POC database for the MiSTer project that downloads .pdf game manuals to the relevant folder within "/media/fat/docs".  These can be loaded from within the core's OSD by selecting the "Help" option.

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/manuals-db-poc]
db_url = https://raw.githubusercontent.com/ajgowans/manuals-db-poc/db/db.json.zip
```

NOTE: THIS IS A PROOF OF CONCEPT AND THE DATABASE SIZE IS LARGE

 ## Currently Included Cores With Game Manuals

- AVision: 4 (1.3 MB)
- AcornAtom: 1 (3.4 MB)
- Arcadia: 31 (31.0 MB)
- Astrocade: 14 (8.5 MB)
- CD-i: 6 (29.6 MB)
- ChannelF: 16 (1.7 MB)
- CoCo2: 6 (3.9 MB)
- CreatiVision: 15 (3.4 MB)
- Jaguar: 9 (33.9 MB)
- NEOGEO: 6 (93.0 MB)
- ODYSSEY2: 34 (2.1 MB)
- SMS: 3 (21.0 MB)
- TGFX16: 3 (6.9 MB)
- VIC20: 19 (16.0 MB)
- WonderSwan: 2 (16.5 MB)

🧮 Total DB Size: 169 files (272.22 MB)
