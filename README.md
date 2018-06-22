# query-search-for-cloud

This is essential a attempt to use common sql squery syntax to get specific information from AWS or any cloud provider. It will be a useful tool for non aws api user, it can be useful query through large amount of meta data and get the useful information for you while leave the logic in the background. 

There are two approach to this. One is downloading everything to a local db, so the sql parsing part will not be a concern. It can be done through derby db or sqllite. The other way is to parse the sql query to proper API calls to get the information in real time. There are performance consideration for either approach. 
