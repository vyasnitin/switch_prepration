#Architure of snowflake
*Share disk architechure*  
multiple cluster connected to single disk storage 

*shared nothing archecture*
single cluster node is connected to single storage 

There are three layers in snowflake 
cloud services */n* query processing and data layer 

what are this three layer will do 
cloud layer 
query processing layer
data storge layer

# *Data storage layer*
store the data in compressed and columnar format 


# *micro partition*
50-500mb uncompressed data belongs to one partition 

snowflake also contains the meta data  like how many null uniques values is there 
data is partitioned based on the sharing bases like if i share the uploaded and file in container and 
inserting the data into snowflake then based on the column it automatically 

# cost related to snoflake edition 
standard
enterprise 
business critical 

virtual warehouse 
dml operation perform under this warehouses 
different types of virtual warehouse are there - x-small small medium 
each warehouse have there own credit /hour charges 

multiculstered 



