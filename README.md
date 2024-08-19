# Google Maps Scraper

This is simple scraper that uses Playwright to extract data from Google Maps. 

check both Excel & CSV files (google_maps_data) to see how final data will look like. 

## To Install:
- (Optional: create & activate a virtual environment) `virtualenv venv`, then `source venv/bin/activate`

- `pip install -r requirements.txt`
- `playwright install chromium`

## to Run:
### A single search:
- `python3 main.py `
- Once GUI pops up enter the "Search Term" which is what and where to search for 
- Enter total results which will be how many buisnesses you'd like to scrape
## Tips:
- Instead of using:

`United states doctor`

- Use:

`Unites States Chicago Doctor`

And so on... 



