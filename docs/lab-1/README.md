---
title: Y-Health Dataset
description: Y-Health Dataset
---

# Y-Health Dataset

### Y-Health Dataset Summary

This collection of data includes over 22 million global companies, with information such as names, domains, sizes, years founded, industries, localities, countries, and LinkedIn URLs.

This dataset is updated on a quarterly basis. All companies in this dataset have at least one current associated employee in the PDL data, removing many of the companies in our full dataset Full Company Dataset Stats.

To download the Free Company Dataset data, go to the Y-Health Dashboard.

For more information on the complete Company Dataset, including access to all information and aggregated headcount fields, schedule time to speak to a PDL Data Consultant using this link.

### Fields

| Field Name            | Field Type     | Persistence Commitments and Format | Short Description                                 | Example                |
|-----------------------|---------------|------------------------------------|---------------------------------------------------|------------------------|
| country               | Enum (String) | Canonical Countries                | The country of company's current headquarters.     | united states          |
| dropoff_latitude      | Float         | Geographic Coordinates             | Latitude of dropoff location                      | 40.645771026611328     |
| dropoff_longitude     | Float         | Geographic Coordinates             | Longitude of dropoff location                     | -73.94903564453125     |
| extra                 | Float         | Currency                           | Extra charges                                     | 0.5                    |
| fare_amount           | Float         | Currency                           | Fare amount                                       | 18                     |
| improvement_surcharge | Float         | Currency                           | Improvement surcharge                             | 0.3                    |
| lpep_dropoff_datetime | Datetime      | ISO 8601                           | Dropoff date and time                             | 2015-01-19T00:19:06.000|
| lpep_pickup_datetime  | Datetime      | ISO 8601                           | Pickup date and time                              | 2015-01-19T00:00:00.000|
| mta_tax               | Float         | Currency                           | MTA tax                                           | 0.5                    |
| passenger_count       | Integer       | Count                              | Number of passengers                              | 1                      |
| payment_type          | Integer       | Enum                               | Payment type code                                 | 2                      |
| pickup_latitude       | Float         | Geographic Coordinates             | Latitude of pickup location                       | 40.690395355224609     |
| pickup_longitude      | Float         | Geographic Coordinates             | Longitude of pickup location                      | -73.991989135742187    |
| ratecodeid            | Integer       | Enum                               | Rate code ID                                      | 1                      |
| store_and_fwd_flag    | String        | Enum                               | Store and forward flag                            | N                      |
| tip_amount            | Float         | Currency                           | Tip amount                                        | 0                      |
| tolls_amount          | Float         | Currency                           | Tolls amount                                      | 0                      |
| total_amount          | Float         | Currency                           | Total amount                                      | 19.3                   |
| trip_distance         | Float         | Distance (miles)                   | Trip distance                                     | 4.6                    |
| trip_type             | Integer       | Enum                               | Trip type code                                    | 1                      |
| vendorid              | Integer       | Enum                               | Vendor ID                                         | 1                      |
| timestamp             | Date          | ISO 8601                           | Record timestamp                                  | 2025-

### Accessing the dataset

We provide the dataset in CSV, pipe-delimited and JSON formats. We have found that many customers prefer the CSV format, but this format is very large (nine million lines) and common programs like Excel and Numbers can't open it. To do so properly, you have to do it programmatically. For example, by using the Python CSV Library.