# parquet_datacheck

This is a quick tool to some simple data check processes for parquet datasets with Spark and Scala.

Currently only date check is in place

**Main Class:**
org.datacheck.run.CompareParquet

**Usage Arguments:**
-f --file Path to parquet file
-c --column Column name for date field
-s --startdate Start date of column - YYYY-mm-dd
-e --enddate End date of column - YYYY-mm-dd
-w --weekdays Accepts: all | weekday | <comma separated 1-7 for day of week required per week>

