# etl_project

In this project, we used an API and some Web Scrapping in order to see the sales from specific brands of cars. First we got a list of individual cars from an API. Then we proceeded to find sales numbers from 2019 and 2020 and the change between them by scraping a table and then outsourcing that table as a csv file. Then we imported the csv file and combined the two tables into one pandas dataframe. We had to edit some columns and drop some values in order to merge the table. Finally, we exported the complete Dataframe to Postgres.
