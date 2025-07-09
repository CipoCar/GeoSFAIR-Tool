## TITLE: F1.1_D1_MaturityIndex_2023

#### Publication Date: 2023-09-26
#### Last Edit: 2023-09-26
#### Status: in progress …


### Maturity Index Name:  Dataset are registered or indexed in a searchable resource

### Maturity Index reference: ...

### FAIR Principle: F. 1 Data are assigned globally unique and persistent identifiers

************************************************************

### Product class
Dataset

### FAIR Principles target
We need to make a distinction between the uniqueness and persistence of an identifier of a dataset. An HTTP URL or URI is globally unique but cannot be persistent in time as the URL of data, for many reason i.g. link rot problem or original URL changes. For this the purpose of principle is defined a system to make Identifier persistent for a long time.

### What the user have to do?
The system should be able to assign an identifier manage at registry level in order to guarantee persistent in time, the user have to upload dataset in EGDI system.

### What is measured?
The presence or absence of an Identifier in the Metadata of dataset.

### Why need to measure it?
The repository enables users to discover the data and refer to them in a
persistent way through proper citation.

### Abstract Test Suite
If the metadata does not exceed conformance class 1: 'Basic metadata for datasets and datasets of classes 1.2 and 1.3 The value is 0, if the metadata exceeds conformance class 1: 'Basic metadata for datasets data and data series of classes 1.2 and 1.3 The value is 0.5, if the Identifier is expressed as a URI/URL but is not resolvable the value is 0.7 if the URI/URL is also resolvable the value is 1.

### Best practices

### Comments
