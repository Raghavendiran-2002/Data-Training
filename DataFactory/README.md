# Data Factory Concepts

### Pipelines

In data integration platforms like Azure Data Factory (ADF) or Apache NiFi, a pipeline refers to a series of interconnected steps or activities designed to automate data movement and transformation. Pipelines orchestrate data workflows by specifying the sequence of data flow, transformations, and processing tasks across various data sources and destinations. Pipelines typically allow scheduling, monitoring, and logging capabilities to manage the data flow.

### Copy Activity

Copy activity is a component within data integration platforms (e.g., Azure Data Factory) used to copy data from a source to a destination. It is a primary tool for moving data across different storage systems, such as copying data from on-premises storage to cloud storage or between different databases. Copy activity can perform data transformation (e.g., column mapping or filtering) during the copy process to ensure that the data is prepared correctly for the destination.

### Expression Builder

The Expression Builder is a tool that helps in creating expressions to manipulate data during transformations within pipelines. It allows you to define conditions, manipulate strings, handle dates, perform arithmetic operations, or set dynamic parameters in the pipeline activities. The expression builder typically supports predefined functions and syntax, making it easier to transform or filter data as it flows through the pipeline.

### Difference Between Variable and Parameter

- **Variable**: A variable is a storage element within a pipeline that can be modified or updated during pipeline execution. Variables are typically used for intermediate storage, counters, or temporary values. They are specific to the pipeline and retain their value throughout the execution.

- **Parameter**: A parameter is a value passed into a pipeline or activity at runtime. Parameters are used to make pipelines more flexible and reusable by allowing different values to be injected into the pipeline execution without changing the underlying pipeline logic. Parameters are typically read-only and are set at the beginning of the pipeline or activity.

### Bulk Insert

Bulk insert refers to a high-performance method of inserting large volumes of data into a database. Instead of inserting one row at a time, bulk insert operations load data in batches or blocks, significantly reducing the overhead associated with individual insertions. It is commonly used for loading large datasets into databases quickly and efficiently. Bulk insert operations often bypass certain validation or logging mechanisms to enhance performance.
