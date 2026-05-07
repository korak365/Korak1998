# Pinterest Aesthetic Scraper

This tool scrapes Pinterest boards for high-res images and their metadata. The key details include the image description, tags, and source links, making it perfect for aesthetic mood-boarding.

## Features:
- Downloads high-res images from Pinterest boards.
- Collects metadata (e.g., image title, source link, tags).
- Organizes data in a structured dataset for further use.

## Inputs:
1. `boardUrls`: List of Pinterest board URLs to scrape.
2. `downloadDirectory`: Local directory to store downloaded images.
3. `maxImages`: Limit the number of images downloaded per board.

## Outputs:
- `imageUrl`: URL of the high-res image.
- `title`: Title of the pin.
- `description`: Description of the pin.
- `boardUrl`: Board URL where the pin was located.
- `pinUrl`: Individual pin URL.
- `tags`: Tags or categories associated with the pin.

---

## Ethical Notice
- Scrape only for personal and educational purposes.
- Avoid scraping private boards or bypassing Pinterest's protections. Follow their ToS.
