# distributed-database-management-project  

## Project Description  
In this project, we use **PySpark** to process large-scale TV viewership and demographic datasets in order to protect the city of Townsville from Mojo Jojo’s “brainwashing attacks.” The task involves detecting malicious TV programs based on multiple conditions (e.g., suspicious genres, unusual durations, household attributes) and then identifying the best broadcasting slots to “un-brainwash” citizens.  

The project emphasizes working with distributed data, integrating multiple schemas, handling large datasets efficiently, and designing scalable transformations and queries in Spark.  

## Project Input  
- **Demographic Data**: Household information such as size, income, vehicles, and age distribution. *(357,721 rows)*  
- **Daily Program Data**: Contains program titles, genres, air dates, and durations. *(13,194,849 rows)*  
- **Program Viewing Data**: Maps devices and households to viewed programs. *(9,935,852 rows)*  
- **Reference Data**: Maps devices to households and DMA codes. *(704,172 rows)*  
 

## Technologies  
- **PySpark** (DataFrames, distributed joins, transformations)  
- **Databricks** environment (Spark 3+)  
- Large-scale data preprocessing and analysis  

## Key Learning Outcomes  
- Joining and transforming multiple large-scale datasets in Spark.  
- Designing helper columns to optimize performance.  
- Implementing complex logical conditions in distributed systems. using pySpark SQL 
- Balancing efficiency, correctness, and scalability in big-data analysis.  
