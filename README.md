![DaaS](./img/daas-logo-medium.png?raw=true)

Data as a Service (DaaS) is an architecture pattern that leverages microservice, message broker, and databases to replace the traditional ETL process (batched provisioning for predefined DDLs) with an event driven plugin model to provide horizontal scaling, "real-time" reports, and MVP deliverables.

---

## Data as a Service - Overview
#### [Overview Presentation](./doc/Data as a Service.pptx)
![DaaS](img/daas-pattern.png?raw=true)


## Data as a Service - Example
#### [Example Presentation](./doc/Data as a Service - Example.pptx)
#### Videos
+ [Adding a Component](./img/01_add_component.webm)
+ [Creating a Subjob](./img/02_subjob_upsert_json_document_test_01.webm)
+ [Creating a Sourcing REST Service](./img/03_rest_sourcing_data.webm)
+ [Creating a Provisioning Service](./img/04_provisioning_data.webm)
+ [Creating a Consuming REST Service](./img/05_rest_consuming_data.webm)

#### Talend Project

1. Download and Install [Talend Studio for ESB](https://www.talend.com/download/talend-open-studio#t3)
2. Add the Talend Big Data Components plugin directory (e.g.: org.talend.designer.components.bigdata_6.1.2.20160912_1228) to your installed Talend Studio for ESB. This can be found from the [Talend Big Data](https://www.talend.com/download/talend-open-studio) Product and should be placed in {TALEND_HOME}/Studio/plugins directory
3. Download and [import](https://help.talend.com/reader/JdTBzKszzXoWvjpEJD3EBA/lMPZvSCXafXZZdxHFEHmTg) the [DAAS_EXAMPLE](./example/DAAS_EXAMPLE.zip) project
4. Update your properties files accordingly (CouchDB and Kafka settings) located in the Talend Project workspace (e.g.: {TALEND_HOME}/Studio/workspace/DAAS_EXAMPLE)
  + sourcing.properties
  + provisioning.properties
  + consuming.properties

---

### ArchConf 2017
+ [Data as a Service Overview](https://archconf.com/conference/clearwater/2017/12/session?id=40289)
+ [Using Talend Open Studio for DaaS](https://archconf.com/conference/clearwater/2017/12/session?id=40290)
