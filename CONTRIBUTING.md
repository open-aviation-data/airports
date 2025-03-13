# ✈️ Contributing to the Open Airports Database

Thank you for your interest in contributing to this project! We aim to build an accurate and reliable global airport
database, and your help is invaluable.

## 🛫 How to contribute

### 🚀 Submit a new airport or update an existing one

* 👉 To **add** a new airport:
    * Open
      an [Airport Add Request](https://github.com/open-aviation-data/airports/issues/new?template=airport_add_request.yml)
    * Fill in the required fields, providing as much detail as possible
* To **update** an existing airport:
    * Open
      an [Airport Update Request](https://github.com/open-aviation-data/airports/issues/new?template=airport_update_request.yml)
    * Provide the airport’s numerical identifier and specify what needs to be updated

📝 **For bulk changes**, you may fork the repository, edit airports.csv, and create a PR. If you're unsure, open a blank
issue describing the request.

> [!NOTE]  
> Submissions via Issues will be automatically processed into pull requests for review
> Bulk updates via PRs must follow the format rules outlined below

### ✅ Data validation checklist

To maintain data quality, ensure that all fields follow the format rules below:

| Field                 | Description                                                                                                          |
|-----------------------|----------------------------------------------------------------------------------------------------------------------|
| Numeric ID            | A unique integer identifier (auto-generated)                                                                         |
| Ident                 | A unique airport identifier (usually ICAO code)                                                                      |
| IATA Code             | The official 3-letter IATA airport code                                                                              |
| ICAO Code             | The official 4-letter ICAO airport code                                                                              |
| GPS Code / Local Code | Official GPS/local airport codes                                                                                     |
| Name                  | The official airport name                                                                                            |
| Latitude              | In decimal degrees (e.g. 40.712776)                                                                                  |
| Longitude             | In decimal degrees (e.g. -74.005974)                                                                                 |
| Elevation             | Elevation in feet above sea level                                                                                    |
| Continent             | ISO 3166-1 continent code (e.g. ```EU```)                                                                            |
| Country               | ISO 3166-1 alpha-2 country code (e.g. ```NO```)                                                                      |
| Region                | The airport’s state/province code                                                                                    |
| Municipality          | The city/town where the airport is located                                                                           |
| Scheduled Service     | Either ```yes``` or ```no```                                                                                         |
| Website URL           | Official airport website                                                                                             |
| Wikipedia URL         | The Wikipedia page URL                                                                                               |
| Keywords              | Comma-separated alternative names, nicknames, or cities served                                                       |
| Timezone              | Valid [IANA timezone](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) (e.g., ```Europe/London```)      |
| Airport Type          | Must be one of: ```large_airport```, ```medium_airport```, ```small_airport```, ```heliport```, ```seaplane_base```, |
|                       | ```balloonport```, ```closed```                                                                                      |

### 📢 Reporting issues
Found incorrect or missing data? Open an issue and provide details with sources if possible.

## 🔄 Bulk changes (alternative method)
If you need to submit a bulk dataset update, follow these steps:

* Fork the repository (optional, but recommended for tracking changes)
* Modify airports.csv while ensuring data consistency
* Create a pull request (PR) with a clear description of your changes

> [!WARNING]
> Bulk PRs must strictly follow the format rules in this document.

## 💙 Thank you!
Your contributions help make this project the most reliable open-source airport database for the aviation community worldwide! 🚀