# Book to Kindle (📚➡️📬)

A Python-based tool that lets me input a book name → searches LibGen for an EPUB → downloads it → sends it to my Kindle email.

## Modules

- app/search.py – search LibGen with book name
- app/extract.py – extract EPUB URL from results
- app/download.py – download EPUB file
- app/send_to_kindle.py – email to Kindle
- main.py – FastAPI wrapper

## Stack

- Python 3.11
- FastAPI
- LibGen scraping (no public API)
- SMTP for Kindle sending

