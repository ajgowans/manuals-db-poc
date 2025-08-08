# The MiSTer Database For Work In Progress Core 

This is a POC database for the MiSTer project that downloads .pdf game manuals to the relevant folder within "/media/fat/docs".  These can be loaded from within the core's OSD by selecting the "Help" option.

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/manuals-db-poc]
db_url = https://raw.githubusercontent.com/ajgowans/manuals-db-poc/db/db.json.zip
```

NOTE: THIS IS A PROOF OF CONCEPT AND THE DATABASE SIZE IS LARGE

 ## Currently Included Cores With Game Manuals

- AVision: 4
- AcornAtom: 1
- Astrocade: 14
- CD-i: 6
- ChannelF: 16
- CoCo2: 6
- CreatiVision: 15
- Jaguar: 9
- NEOGEO: 6
- SMS: 3
- TGFX16: 3
- WonderSwan: 2

🧮 Total DB Size: 223.07 MB
