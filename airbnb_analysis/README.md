# Airbnb Market Analysis: Columbus vs New York

## Author
Jett Lori

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to [briefly describe what decisions your analysis could support].

## Research Questions

1. [What is the average price of Airbnb listings in Columbus compared to New York City?]
2. [How does overall yearly availability differ between Columbus and New York City listings?]
3. [How does average price differ by room type (Entire home/apt, Private room, Shared room) in each city?]
4. [Which neighborhoods have the highest number of Airbnb listings in Columbus and New York City?]
5. [Do hosts with multiple listings tend to charge higher average prices than hosts with only one listing?]

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | [What is the average price of Airbnb listings in Columbus compared to New York City?] | [price] | [listings.csv] | [Structured] |
| 2 | [How does overall yearly availability differ between Columbus and New York City listings?] | [availability_365] | [listings.csv] | [Structured] |
| 3 | [How does average price differ by room type (Entire home/apt, Private room, Shared room) in each city?] | [price, room_type] | [listings.csv] | [Structured] |
| 4 | [Which neighborhoods have the highest number of Airbnb listings in Columbus and New York City?] | [neighbourhood, neighbourhood_group, id] | [listings.csv] | [Structured] |
| 5 | [Do hosts with multiple listings tend to charge higher average prices than hosts with only one listing?] | [id, price, host_id, host_name, calculated_host_listings_count, ] | [listings.csv] | [Structured] |


## Data Overview
- **Columbus, Ohio:** [2877] listings (as of Sept 26, 2025)
- **New York City:** [36261] listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created