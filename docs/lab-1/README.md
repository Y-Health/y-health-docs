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

| Field Name | Field Type     | Persistence Commitments and Format | Short Description                                 | Example       |
|------------|---------------|------------------------------------|---------------------------------------------------|--------------|
| country    | Enum (String) | Canonical Countries                | The country of company's current headquarters.     | united


### Accessing the dataset

We provide the dataset in CSV, pipe-delimited and JSON formats. We have found that many customers prefer the CSV format, but this format is very large (nine million lines) and common programs like Excel and Numbers can't open it. To do so properly, you have to do it programmatically. For example, by using the Python CSV Library.