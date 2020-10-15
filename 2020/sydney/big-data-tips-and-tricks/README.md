# Tips and tricks for robust big data applications

*By Yousry Mohamed*


Does anyone still care about big data? 
Some people may think it's an ancient buzzword that doesn't attract the cool kids in the era of self-driving cars. 

Well, big data is still here and will continue to be relevant as long as people and businesses need to count things.

In this session, you will learn several tips and tricks critical to any successful big data application. 

* You will see how to optimise data storage in columnar files to save storage costs and also improve compute performance.
* If garbage in means garbage out, then your data should be of high quality. You will learn also how to unit test big data applications and how to assure high quality data outcomes.
* With the explosion of data sources a single organisation has to handle, it's very critical to have governance and tracking. You will see how you can track the lineage of a certain dataset so you will always be ready for the toughest auditing or compliance checks. 
* Finally, I will show you some tools to help with automation and collaboration.


## Slides and demos code

[Get them here](https://github.com/ylashin/ndc-sydney-2020)

## Further reading

### Storage
 - [ORC Specification](https://orc.apache.org/specification/)
 - [Parquet Specification](https://parquet.apache.org/documentation/latest/)

### Data Quality
- [Deequ](https://github.com/awslabs/deequ)

### Governance
- [Apache Atlas](https://atlas.apache.org/)
- [Spark Atlas Connector](https://github.com/hortonworks-spark/spark-atlas-connector)

### Tools
- [Elyra](https://elyra.readthedocs.io/en/latest/)
- [Sparkmagic](https://github.com/jupyter-incubator/sparkmagic)
- [Kubeflow](https://www.kubeflow.org/)
