# File Share for the City of Lewisville, Texas
Uses [GitHub Pages](https://github.com/) to host data for external use.<br/>
Data updates will be pushed via backend script, schedule varies.<br/>

## How to use
Public Url Format:
```
https://cityoflewisvilletexas.github.io/col-fileshare/{{filename}}
```

## Data Details
_Include description, respository link, public url, data format, and update frequency (note if static instead)._

### Waze

Active major accident data to be reported to Waze. If there are no active accidents, will contain empty dataset (should never be a blank file).

- Repository Link: [Waze](Waze.json)<br/>
- Public URL: [https://cityoflewisvilletexas.github.io/col-fileshare/Waze.json](https://cityoflewisvilletexas.github.io/col-fileshare/Waze.json)<br/>
- Data Format: JSON<br/>
- Update Frequency: every 5 minutes

### Yelp
> [!WARNING]
> In Development

Health Inspection scores from the last year to be reported to Yelp.

- Repository Link: [Yelp](Yelp.zip)<br/>
- Public URL: [https://cityoflewisvilletexas.github.io/col-fileshare/Yelp.zip](https://cityoflewisvilletexas.github.io/col-fileshare/Yelp.zip)<br/>
- Data Format: ZIP<br/>
  - 3 CSV files:
    - Businesses.csv<br/>
    - Inspections.csv<br/>
    - feed_info.csv<br/>
- Update Frequency: once per day at 2:30 PM<br/>
