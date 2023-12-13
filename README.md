# nosql-challenge

No-SQL challenge is to showcase how to access NO-SQL database from python using PYMONGO package

# Project Title 

Data is provided in JSON format. Challenge will showcase to load data toMongo DB. Create collections.
Clean up data in documents in collections of mongodb. And Analyze data from mongodb.


## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Installing](#installing)
- [Usage](#usage)
- [Contributing](#contributing)

## About

The purpose of this challenge is create NO-SQL database from JSON file. 

Raw data provided consists of 6 files of establishments in UK. These establishments are restaurants, cafeteria etc. Magazine would like consider rating of these establishments.

## Getting Started

1. Run OS command `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json` to load JSON file to mongodb.  
2. Run "NoSQL_setup_starter" to transform data.
3. Run "NoSQL_analysis_starter" file in jupyter notebook to answer questions using pandas dataframes.

## Installing

mongodb, pymongo(python package to access mongodb)
python pprint to prety print json data
python pandas to create dataframes and anayze further.

## Usage

Analysis project using NO-SQL database mongodb

## Contributing

Contributors names: Mamatha Etikyala


