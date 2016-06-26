## Demo notebooks for Apache Zeppelin
##### Update your Zeppelin instance with all notebooks in this repo:
  - If you are using hortonworks sandbox, you can execute command below to get latest notebooks: </br>
  `curl -sSL https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/update_all_notebooks.sh | sudo -u zeppelin -E sh`
  - Please note that if you have changed or created your own notebooks they will be moved to a folder: /opt/incubator-zeppelin/notebook/old_yyyyMMdd-HHmmss, you can copy them back to /opt/incubator-zeppelin/notebook/ directory

##### Importing specific notebooks:
Copy the "json" link URL from the table below and paste it into Zeppelin's import from URL tool.
![Import UI](/screenshots/import.png?raw=true)

##### Adding notebooks:
You can add notebooks by making Github pull request, but we request you also update the table below by adding a record for your notebook. To generate the 'view' link for the notebook:

1. Uploading the notebook into this repo and obtain the url (it should look like this: https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2A94M5J1Z/note.json)
2. Generate a link to preview the notebook by pasting the url from #1 into ZeppelinHub viewer (https://www.zeppelinhub.com/viewer). This will generate a preview page for your notebook (at a url that looks something like https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQTk0TTVKMVovbm90ZS5qc29u/)
3. Copy the url from #2 of the notebook Include the preview link under the 'View' link in table below. You can follow examples from existing notebooks for this at the markdown version of README [here](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/README.md)


##### Demos:

| Description	| Components | Code	| View	| Author | Comments	|
| ------------- | ----- | ---------- 	| ------------  | --------  | --------  |
| Starter Bank demo | Spark/SparkSQL | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/raw/master/2A94M5J1Z/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQTk0TTVKMVovbm90ZS5qc29u/) | NFLabs | Default notebook installed by Zeppelin |
| Australian Spending dataset | Spark/SparkSQL | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2ANTDG878/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQU5UREc4Nzgvbm90ZS5qc29u/) | [Ned Shawa](https://twitter.com/nedshawa) |  |
| Australian Spending dataset | Hive | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2ANT56EHN/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQU5UNTZFSE4vbm90ZS5qc29u/) | [Ned Shawa](https://twitter.com/nedshawa) |  |
| Map Earthquake dataset | Spark/SparkSQL | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2ANTDG878/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQVBGVE4zTlkvbm90ZS5qc29u/) | NFLabs | |
| IoT Trucking demo | Spark/SparkSQL | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2AS5TY6AQ/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQVM1VFk2QVEvbm90ZS5qc29u/) | [Nauman Fakhar](https://github.com/nfakhar), [Dhruv Kumar](https://github.com/DhruvKumar) | [IoT Truck Demo](https://github.com/hortonworks-gallery/iot-truck-streaming) from Hadoop Summit |
| Intra-day stock prices | Phoenix | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2B21B3AYC/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQjIxQjNBWUMvbm90ZS5qc29u/) | [Ali Bajwa](https://github.com/abajwa-hw) |  |
| Magellan: Geospatial Analytics Using Spark | Spark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2B4TWGC8M/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQjRUV0dDOE0vbm90ZS5qc29u) | [Ram Sriharsha](https://github.com/harsha2010) | [Magellan Blog](http://hortonworks.com/blog/magellan-geospatial-analytics-in-spark/) as Zeppelin Notebook. *Requires Spark 1.4.1* See [here](https://github.com/harsha2010/magellan) for more details |
| Twitter sentiment analysis using Spark Streaming | Spark streaming | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2B522V3X8/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQjUyMlYzWDgvbm90ZS5qc29u) | [Guilherme Braccialli](https://github.com/gbraccialli) | |
| PySpark tutorial: Analyzing network intrusion dataset with Python and Spark  | PySpark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2B48PF7SN/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQjQ4UEY3U04vbm90ZS5qc29u) | [Saptak Sen](https://github.com/saptak) | |
| Single view demo | Hive/Sqoop/HDF | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BBBW75VS/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkJCVzc1VlMvbm90ZS5qc29u)  | [Ali Bajwa](https://github.com/abajwa-hw)/Ajay Singh | Notebook version of [Single view lab](https://github.com/abajwa-hw/single-view-demo) |
| Predicting Airline Delays | Spark/MLLib | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BB5CUPUW/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkI1Q1VQVVcvbm90ZS5qc29u) | [Ofer Mendelevitch](https://github.com/ofermend) | Related to this [Blog post](http://hortonworks.com/blog/data-science-apacheh-hadoop-predicting-airline-delays/) and [part 2](http://hortonworks.com/blog/data-science-hadoop-spark-scala-part-2/) |
| Sensors Predictive Analysis | SparkSQL/PySpark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BAVUZ7NA/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkFWVVo3TkEvbm90ZS5qc29u) | [Vedant Jain](https://github.com/vedantja) | Adding Predictions to this [Blog post](http://hortonworks.com/use-cases/sensor-data-hadoop-example/)
| Hands-on Tour of Apache Spark in 5 min | PySpark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BEQE47HR/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkVRRTQ3SFIvbm90ZS5qc29u) | [Robert Hryniewicz](https://github.com/roberthryniewicz) |  
| Lab 101: Intro to Spark with Python | PySpark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BFGYS3YT/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkZHWVMzWVQvbm90ZS5qc29u) | [Robert Hryniewicz](https://github.com/roberthryniewicz) | Intro to Spark Core & Spark SQL with Word Count
| Lab 102: Intro to Spark with Scala | Spark SQL | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BJVW65WS/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkpWVzY1V1Mvbm90ZS5qc29u) | [Robert Hryniewicz](https://github.com/roberthryniewicz) | Intro to Spark SQL using Airlines Dataset
| Lab 201: Intro to Machine Learning with Spark | Spark MLlib & ML | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BNDT63TY/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQk5EVDYzVFkvbm90ZS5qc29u) | [Robert Hryniewicz](https://github.com/roberthryniewicz) | Intro to Machine Learning
| HDFS Space Usage Visualization | HDFS / D3.js | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BFAUAD4F/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkZBVUFENEYvbm90ZS5qc29u) | [Guilherme Braccialli](https://github.com/gbraccialli) | A D3.js Sunburst visualization to explore HDFS space utilization and other metadata info, [more details](https://github.com/gbraccialli/HdfsUtils/)
| Spark HBase - A DataFrame Based Connector | Spark HBase | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BRZCAM4E/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQlJaQ0FNNEUvbm90ZS5qc29u) | [Robert Hryniewicz](https://github.com/roberthryniewicz) | Getting Started with HBase and Spark |
