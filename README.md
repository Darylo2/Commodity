# Commodity
Cleaned Yam production data. Source: FAOSTAT
## For SQL Cleaning (using BigQuery)
### Select the data needing display
SELECT   
  Area,
  Value,
  Flag_Description,
  Year  
FROM 
### Input your data location

### Specify the conditions you need the data to meet 
WHERE
  Year between 2018 and 2020 and Flag_Description = 'Official figure'
