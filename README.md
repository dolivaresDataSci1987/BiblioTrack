# BiblioTrack

<p align="center">
  <img src="logo.png" alt="BiblioTrack logo" width="250"/>
</p>

BiblioTrack is a lightweight single-page app to manage personal libraries.  
Add, edit, and search books, track your reading, keep a wishlist, and export data to JSON, CSV, or PDF.  
Works fully offline with localStorage or syncs to a chosen local folder via the File System Access API.

## Features Overview (Graphic Summary)

```
+-------------------+
|    BiblioTrack    |
+-------------------+
       | | |
       v v v
   [Library] [Wishlist] [Reading Club]
       | | |
       v v v
 Export JSON / CSV / PDF
       |
   LocalStorage or
   Local Folder Sync
```

## Demo (GitHub Pages)
> https://TU_USUARIO.github.io/bibliotrack/

## Usage
1. Open `index.html` in a modern browser (Chrome/Edge).
2. (Optional) **Connect a local folder** to store/read JSON files persistently.
3. Enable **cover loading** to display remote book images.

> The app makes no network requests unless cover loading is enabled.

## Structure
```
index.html
logo.png
assets/         # optional
```

## License
MIT
