# DP-900: Describe an analytics workload on Azure (25-30%)

## Describe analytics workloads
- [Describe transactional workloads](https://docs.microsoft.com/en-us/azure/cosmos-db/analytical-store-introduction)
- Describe the difference between:
    - [**transactional** workload](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/online-transaction-processing)
    - [**analytics** workload](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/online-analytical-processing)
- Describe the difference between:
    - [**batch**](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/batch-processing)
        - [Azure Synapse Analytics](https://docs.microsoft.com/en-us/azure/synapse-analytics/)
        - [Azure Data Lake Analytics Gen2](https://docs.microsoft.com/en-us/azure/data-lake-analytics/data-lake-analytics-overview)
        - HDInsight
            - [Spark](https://docs.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-overview)
            - [Hive](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-use-hive)
            - [Hive Low Latency Analytical Processing (LLAP)](https://docs.microsoft.com/en-us/azure/hdinsight/interactive-query/apache-interactive-query-get-started)
            - [MapReduce](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-use-mapreduce)
        - [Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/)
        - [Azure Distributed Data Engineering Toolkit](https://github.com/azure/aztk)
    - [**real time**](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/real-time-ingestion)
        - [Azure Event Hubs](https://docs.microsoft.com/en-us/azure/event-hubs/)
        - [Azure IoT Hub](https://docs.microsoft.com/en-us/azure/iot-hub/)
        - [Kafka on HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-get-started)
- [Describe data warehousing workloads](https://azure.microsoft.com/en-gb/updates/workload-importance-for-azure-sql-data-warehouse-is-now-generally-available/)
- [Determine when a data warehouse solution is needed](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/data-warehousing)
    - [Enterprise Data Warehouse Architecture](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/enterprise-data-warehouse)
    - [Data warehousing and analytics](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/data/data-warehouse)

## Describe the components of a modern data warehouse
- Describe Azure data services for modern data warehousing such as:
    - [Azure Data Lake](https://azure.microsoft.com/en-us/solutions/data-lake/)
    - [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/)
    - [Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/)
    - [Azure HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight)
- [Describe modern data warehousing architecture and workload](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/enterprise-data-warehouse)

## Describe data ingestion and processing on Azure
- [Describe common practices for data loading](https://techcommunity.microsoft.com/t5/datacat/azure-sql-data-warehouse-loading-patterns-and-strategies/ba-p/305456)
    - [PolyBase](https://docs.microsoft.com/en-us/sql/relational-databases/polybase/polybase-guide?view=sql-server-ver15)
    - [AzCopy](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10)
    - [CREATE TABLE AS SELECT](https://docs.microsoft.com/en-us/sql/t-sql/statements/create-table-as-select-azure-sql-data-warehouse)
    - [BCP](https://azure.microsoft.com/en-us/blog/bcp-and-sql-azure/)
    - [SqlBulkCopy](https://docs.microsoft.com/en-us/dotnet/api/system.data.sqlclient.sqlbulkcopy?view=dotnet-plat-ext-5.0)
- Describe the [components of **Azure Data Factory**](https://docs.microsoft.com/en-us/azure/data-factory/concepts-pipelines-activities) such as:
    - Pipeline
        - a logical grouping of activities that together perform a task
    - Activities
        - define actions to perform on your data

- Describe data processing options such as:
    - [Azure HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight)
    - [Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/)
    - [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/)
    - [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory)

## Describe data visualization in Microsoft Power BI
- [Describe the role of **paginated reporting**](https://docs.microsoft.com/en-us/power-bi/paginated-reports/paginated-reports-report-builder-power-bi)
- [Describe the role of **interactive reports**](https://powerbi.microsoft.com/en-us/desktop)
- [Describe the role of **dashboards**](https://docs.microsoft.com/en-us/power-bi/create-reports/service-dashboards)
- Describe the workflow in Power BI
    - Get Data
    - Clean data
    - Model the data
    - Visualize your data
    - Share the data, report

[Return to Table of Contents](README.md)