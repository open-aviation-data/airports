# 🌍 Open Airports Database

Welcome to the **Open Airports Database**, an open-source project under the **open-aviation-data** initiative. This
repository aims to provide a **comprehensive and up-to-date global database of airports** in an easy-to-use format.

## 📜 License

This project is licensed under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/)
licence, see [`LICENSE`](LICENSE). In short, any
modification to this data source must be published.

## ✈️ About

This repository collects and maintains airport data from various sources, including **official aviation authorities and
community contributions**. The data is structured in **CSV format**, making it easy to use for developers, researchers,
and aviation enthusiasts.

## 📂 Data Structure

The primary dataset is stored in a CSV file: `data/airports.csv`. Each row represents an airport with the following
fields:

| Column Name         | Description                                         |
|---------------------|-----------------------------------------------------|
| `id`                | Unique UUID of the airport                          |
| `ident`             | Unique airport identifier (often ICAO)              |
| `icao`              | ICAO airport code                                   |
| `iata`              | IATA airport code                                   |
| `gps_code`          | GPS code (usually same as ICAO)                     |
| `local_code`        | Local airport code                                  |
| `name`              | Official airport name                               |
| `latitude`          | Latitude (decimal degrees)                          |
| `longitude`         | Longitude (decimal degrees)                         |
| `elevation`         | Elevation in feet                                   |
| `continent`         | Continent code (ISO 3166-1)                         |
| `country`           | Country code (ISO 3166-1 alpha-2)                   |
| `region`            | Sub-region/state code                               |
| `municipality`      | Municipality name                                   |
| `scheduled_service` | `yes` or `no` (scheduled flights)                   |
| `web_url`           | Official airport website (if available)             |
| `wikipedia_url`     | Wikipedia page URL                                  |
| `keywords`          | Search keywords (comma-separated)                   |
| `timezone`          | IANA timezone (e.g., `Europe/Oslo`)                 |
| `airport_type`      | Type of airport (e.g., `large_airport`, `heliport`) |

## 🏢 Airport Types

The dataset categorizes airports into the following types:

- **`large_airport`**: Major international airports with significant passenger and cargo traffic
- **`medium_airport`**: Regional airports serving domestic and limited international flights
- **`small_airport`**: Small-scale airports, often used for general aviation and limited commercial operations
- **`heliport`**: Facilities designated for helicopter operations
- **`seaplane_base`**: Airports specifically designed for seaplanes to take off and land on water
- **`balloonport`**: Dedicated locations for hot air balloon operations
- **`closed`**: Airports that are no longer operational

## 🚀 Usage

This dataset can be used for various applications, including:

- Flight tracking and aviation analytics
- Open-source mapping projects (e.g., OpenStreetMap integrations)
- Aviation research and data analysis
- Building airport-related applications

## 🤝 Contributing

We welcome contributions from the community! See [`CONTRIBUTING.md`](CONTRIBUTING.md) for details on how to add new
airports, fix errors, or improve the dataset.

## 🌍 Join the Community

Follow our updates and join the discussion on:

- GitHub Issues & Discussions