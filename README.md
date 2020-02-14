# SpringBootAndElasticSearchDemoApplication

Usage:
1.Open this project in STS/Eclipse editor\n
2.Download elasticsearch-2.4.0.zip\n 
3.Extract elasticsearch zip and edit c:\elasticsearch-2.4.0\config file to add clustername\n
  ex: cluster.name: shivaraj-cluster\n
4.Start ElasticSearch by running below command (windows)\n
   c:\elasticsearch-2.4.0\bin>elasticsearch.bat\n
5. Run STS project as java application.\n
6. this will create C:\elasticsearch-2.4.0\data\shivaraj-cluster folder and create one index(similar to table in DBMS) called "bookindex".\n
7. Also there are tests written to modify the search criteria.\n
