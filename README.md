# GUTS schema

***UNDER CONSTRUCTION***

This repository contains the sources for the data schema of the GUTS study.

The schema is developed using [LinkML](https://linkml.io/) and a documented version can be viewed at: https://guts-consortium.github.io/schema/


### Context

A data schema allows exact modeling of objects, properties, and relationships of data samples in a research study. By defining what exactly is meant, for example, by a `participant` (which properties does it have, e.g. `measures_collected`, which relationships does it have, e.g. `parent_cohort`) and even better, defining these using standard linked-data vocabularies (see [Linked Data](https://en.wikipedia.org/wiki/Linked_data)), we develop a standard description of our data that allows:
- a common understanding to discuss and iterate on
- data validation
- automated data entry
- linking our data into larger and distributed datasets for improved querying 


### Useful links
- The [root schema file](src/guts_schema.yaml) in YAML format
- The schema in [jsonschema](https://json-schema.org/) format: https://guts-consortium.github.io/schema/schema.json
- [LinkML docs](https://linkml.io/linkml/)