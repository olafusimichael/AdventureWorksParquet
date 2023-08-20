# AdventureWorksParquet
AdventureWorks 2019 Parquet Files. Original source of extraction: https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms

#Important not if using in Power BI or Power Query
You will need to put these parquet files on your local storage, Azure Blob Storage, and Azure Data Lake Storage Gen2. You will get the following error if you paste a github path: 
_Unable to connect
Details: "Parquet: class parquet::ParquetInvalidOrCorruptedFileException (message: 'Invalid: Parquet magic bytes not found in footer. Either the file is corrupted or this is not a parquet file.')"_

More information at https://learn.microsoft.com/en-us/power-query/connectors/parquet 
