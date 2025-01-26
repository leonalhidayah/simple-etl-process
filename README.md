# simple-etl-process

## data source
https://github.com/DataTalksClub/nyc-tlc-data/releases/download/green/green_tripdata_2019-10.csv.gz

## download data
wget https://github.com/DataTalksClub/nyc-tlc-data/releases/download/green/green_tripdata_2019-10.csv.gz -O "path\to\your\directory\data\green_taxi.csv.gz"

## run docker-compose
docker-compose up

## run pgcli
pgcli -h localhost -p 5432 -U root -d ny_taxi

## shutdown docker-compose
docker-compose down

