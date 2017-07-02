# ETL with Python and MySQL
ETL with Python Training - Taught during [Data Warehousing course - Tel Aviv University 2017](http://www30.tau.ac.il/yedion/syllabuse.asp?course=0571417202)
  
### The Training is planned for ~2 hours and contains 4 notebook files:
* **[jupyter-notebook.ipynb](/jupyter-notebook.ipynb)** - quick Jupiter notebook introduction and tutorial
* **[Mysql-io.ipynb](/Mysql-io.ipynb)**   - Input/Output to MySQL using [``MySQLdb`` connector](http://mysql-python.sourceforge.net/MySQLdb.html)
* **[ETL with Python.ipynb](/ETL_with_Python.ipynb)**  - ETL with python using [``petl``](https://petl.readthedocs.io/en/latest/) package
* **[CSV-io](/csv_io/CSV-io.ipynb)** - ``csv`` library usage examples

### Data files:
* **drinks.json** - drinks consumption data ([source](https://github.com/justmarkham)) 
* **drinks.zip** - zipped json file (used for a zip file example in ETL notebook)
* assuming you have default build-in **world** schema of MySQL (mysql-io exercise) if not you can get it by running **CreateWorld.sql**  - dump of sql scripy for creating world schema for *mysql-io* exercise. 
* **file1.csv**/**file2.csv**/**flie3.csv** - csv examples for ``csv`` library
* **simpsons_phone_book.csv** - csv example for ``sniffer``
