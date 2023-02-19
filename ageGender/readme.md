```
url <-  "https://health-infobase.canada.ca/src/data/covidLive/covid19-epiSummary-ageGender.csv"
dt  <- fread(url)
fwrite(dt, paste0("covid19-epiSummary-ageGender-", dateToday, ".csv"))
fwrite(dt, paste0("covid19-epiSummary-ageGender",".csv"))
```
