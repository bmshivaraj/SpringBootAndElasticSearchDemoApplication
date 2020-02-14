# SpringBootAndElasticSearchDemoApplication

Usage:
1.Open this project in STS/Eclipse editor
2.Download elasticsearch-2.4.0.zip 
3.Extract elasticsearch zip and edit c:\elasticsearch-2.4.0\config file to add clustername
  ex: cluster.name: shivaraj-cluster
4.Start ElasticSearch by running below command (windows)
   c:\elasticsearch-2.4.0\bin>elasticsearch.bat
5. Run STS project as java application.
6. this will create C:\elasticsearch-2.4.0\data\shivaraj-cluster folder and create one index(similar to table in DBMS) called "bookindex".
7. Also there are tests written to modify the search criteria.
