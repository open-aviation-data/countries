# 🌍 Open Countries Database

Welcome to the **Open Countries Database**, an open-source project under the **open-aviation-data** initiative. This
repository aims to provide a **comprehensive and up-to-date global database of countries and territories** in an
easy-to-use format.

## 📜 License

This project is licensed under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/), see [
`LICENSE`](LICENSE). In short, any modification to this data source must be published.

## 🌎 About

This repository collects and maintains country and territory data from **official sources and community contributions**.
The data is structured in **CSV format**, making it easy to use for developers, researchers, and aviation-related
applications.

## 📂 Data Structure

The primary dataset is stored in a CSV file: `data/countries.csv`. Each row represents a country or territory with the
following fields:

| Column Name                | Description                                                                                          |
|----------------------------|------------------------------------------------------------------------------------------------------|
| `name`                     | Official country name                                                                                |
| `iso2`                     | [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country code                  |
| `iso3`                     | [ISO 3166-1 alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) country code                  |
| `numeric_code`             | [ISO 3166-1 numeric](https://en.wikipedia.org/wiki/ISO_3166-1_numeric) country code                  |
| `iso_3166_2`               | [ISO 3166-2](https://en.wikipedia.org/wiki/ISO_3166-2) subdivision code                              |
| `region`                   | Region name [UN region classification](https://unstats.un.org/unsd/methodology/m49/)                 |
| `region_code`              | Region code [UN region classification](https://unstats.un.org/unsd/methodology/m49/)                 |
| `sub_region`               | Sub region name [UN sub-region classification](https://unstats.un.org/unsd/methodology/m49/)         |
| `sub_region_code`          | Numeric sub-region code [UN sub-region classification](https://unstats.un.org/unsd/methodology/m49/) |
| `intermediate_region`      | UN intermediate region classification                                                                |
| `intermediate_region_code` | Numeric intermediate region code                                                                     |

## 🌍 Regional Classifications

The dataset categorizes countries based on **UN and ISO 3166 standards**, including:

- **Regions** (e.g., Europe, Asia, Africa)
- **Sub-regions** (e.g., Northern Europe, Western Asia)
- **Intermediate regions** (for additional classification where applicable)

## 🚀 Usage

This dataset can be used for various applications, including:

- Geographic information systems (GIS) and mapping projects
- Aviation and transportation analysis
- Regulatory and compliance use cases
- International research and data analysis
- Country and territory-based applications

## 🤝 Contributing

We welcome contributions from the community! See [`CONTRIBUTING.md`](CONTRIBUTING.md) for details on how to add new
countries, fix errors, or improve the dataset.

## 🌍 Join the Community

Follow our updates and join the discussion on:

- GitHub Issues & Discussions

## ★ GitHub Star History

<a href="https://www.star-history.com/#open-aviation-data/countries&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=open-aviation-data/countries&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=open-aviation-data/countries&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=open-aviation-data/countries&type=Date" />
 </picture>
</a>
