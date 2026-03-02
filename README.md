# The MiSTer Manuals DB - Fairchild Channel F
This is a database for the MiSTer project that downloads the English manuals in .pdf form for the Fairchild Channel F to the docs folder, which can be loaded from the OSD within th core by selecting "Help".

Currently supported:
Epoch Galaxy II
Tomy Scramble

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/manualsdb-channelf]
db_url = https://raw.githubusercontent.com/ajgowans/manualsdb-channelf/db/db.json.zip
```
