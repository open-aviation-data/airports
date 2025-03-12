# ✈️ Contributing to the Open Airports Database

Thank you for your interest in contributing to this project! We aim to build an accurate and reliable global airport
database, and your help is invaluable.

## 🛫 How to contribute

### 📥 Submitting a new airport or updating data

1. **Fork the repository** on GitHub
2. **Edit the **`airports.csv`** file** to add or modify an airport entry
3. **Ensure data accuracy**:
    - Use official sources where possible (e.g., ICAO, FAA, Eurocontrol)
    - Follow the standard format for data fields
4. **Commit your changes** with a descriptive message
5. **Create a pull request** to propose your changes

### ✅ Data validation checklist

Before submitting, ensure:

- The `id` field is a valid **unique** integer based identifier
- The `ident` field is a unique airport identifier (often ICAO)
- The `iata` and `icao` codes are correct, if existing
- The `gps_code` and `local_code` fields are correct, if existing
- The `name` field is the official airport name
- The **latitude and longitude values** are in decimal degrees
- The `elevation` field is a valid integer value providing the elevation in feet above sea level
- The `continent` field uses a valid [ISO 3166-1](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) code
- The `country` field uses a valid [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) code
- The `region` field uses a valid sub-region/state code
- The `municipality` field is the official municipality name
- The `scheduled_service` field is either `yes` or `no`
- The `web_url` field is the official airport website URL, if available
- The `wikipedia_url` field is the Wikipedia page URL, if available
- The `keywords` field contains relevant search keywords (comma-separated)
- The `timezone` field uses a valid [IANA timezone](https://www.iana.org/time-zones) (Readable format of timezones can be found [HERE](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones))
- The **airport type is one of the following**:
    - `large_airport`
    - `medium_airport`
    - `small_airport`
    - `heliport`
    - `seaplane_base`
    - `balloonport`
    - `closed`

### 📢 Reporting issues

Found incorrect or missing data? Open an [issue on GitHub](https://github.com/open-aviation-data/airports/issues)
and provide details with sources if possible.

## 💙 Thank you!

Your contributions help make this project valuable to the aviation community worldwide!
