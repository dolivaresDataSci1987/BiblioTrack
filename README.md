# BiblioTrack

<p align="center">
  <img src="logo.png" alt="BiblioTrack logo" width="250"/>
</p>

**BiblioTrack** is a lightweight single-page application (SPA) designed to manage personal libraries.  
Created by **David Olivares**.

---

## How it works

BiblioTrack lets you manage your book collection in a simple and intuitive way, fully offline:

- **Library**: Add, edit, delete, and search books by title, author, editorial, category, subcategory, or location.  
- **Wishlist**: Keep track of books you want to buy or read later. Add prices, store links, and export to PDF.  
- **Reading Club**: Track books you are currently reading and mark them as completed.  
- **Cover images**: Optional – activate remote loading to display book covers (privacy-first: disabled by default).  
- **Data Export**: Generate backups in JSON, CSV, or PDF format.  
- **Local Storage**: All your data is saved automatically in your browser.  
- **Local Folder Sync**: Optionally, connect a local folder (via File System Access API) to keep persistent JSON files for library, wishlist, and reading list.  

---

## Demo (GitHub Pages)
> https://TU_USUARIO.github.io/bibliotrack/

## Usage
1. Open `index.html` in a modern browser (Chrome/Edge).
2. (Optional) **Connect a local folder** to store/read JSON files persistently.
3. Enable **cover loading** if you want to see book covers.

> The app makes no network requests unless you enable cover loading.

## Project Structure
```
index.html
logo.png
assets/         # optional
```

## Author
Created by **David Olivares**

## License
MIT
