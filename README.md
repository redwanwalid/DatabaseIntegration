## Database Integration ##

The purpose of project is to build a layer of integration above the local databases. The integration layer is the layer of metadata that includes information that defines the three databases. A metadata layer helps users independently view data using common words. It is a collection of abstractions that are used to resolve multiple issues. 


We assume that we have three different databases called local DB1, local DB2, and local DB3 from data source1, data source2, and data source3. The local DBs are a collection of tables and records that we need to bring together in one database, the integrated database. 


The metadata layer would be used for information integration from the three databases. The information in the layer can be listed as follows. 
1. Canonical representation :  It is the global name of the object.
2. Data type and semantic difference : It is a definition of the local data types in each database used for each column name.
3. Supplementary Fields:  Additional mapping or conversion must also be stored.


We use dynamic SQL to merge different database. We also used metadata layer to map same entitites with different name.
