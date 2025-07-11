# Competency Questions

To evaluate COSO, we distill questions from the larger SAWGraph use case to the components that the COSO ontology must support about contaminant samples, releases, observations, results and features.

These competency questions also serve as template questions, and by modifying the *variables* additional questions can be answered. 

The SAWGraph questions demonstrate some of the more complicated questions that require to COSO competency highlighted, but also require linking to data and ontologies in other graphs in order answer. 

| Question # (link) | COSO Question | Variables | Result (link) | SAWGraph Extended Questions |
| -- | ------------------ | ------------------ | --------- | --------- |
| [CQ1](./CQ1.rq) | What Samples have tested for *PFOA*? What type of sample are they? | Substance | [CQ1-result](./CQ1-result.csv) | <ul><li> What wells are near locations with a reported  PFOA contamination above 4ppt? </li></ul>|
| [CQ2](./CQ2.rq) | What *soil* samples have been tested for *PFBS*? What is min and max result? | Sample type, substance  | [CQ2-result](./CQ2-result.csv) | |
| [CQ3](./CQ3.rq) | What *wells* have been tested for *PFOA* at levels below *20 ppt* or it was not detected?  | sampled feature type, substance, result value| [CQ3-result](./CQ3-result.csv) | <ul><li> What wells are near locations with a cumulative contamination of above 20ppt? </li> </ul>|
| [CQ4](./CQ4.rq) | Samples from what *surface water bodies* have a cumulative contamination result of above *20 ppt*? | sampled feature type, aggregate result value| [CQ4-result](CQ4-result.csv) | |
| [CQ5](./CQ5.rq) | What is the mean concentration of *PFOA* in *fish tissue* in *Maine*? | sample type, aggregate result value, geography | [CQ5-result](./CQ5-result.csv) |<ul><li> What is the mean concentration of *PFOA* in *shellfish* harvested in *Maine*? </li><li> Of fish samples in this area, which chemical is the highest by species? </li></ul>|
| [CQ6](./CQ6.rq) | What was the detection limit of measurement X? | measurements | [CQ6-result](./CQ6-result.csv)  | |
| [CQ7](./CQ7.rq) | What known *release features* exist in *this region*? | s2 cells, feature type |[CQ7-result](./CQ7-result.csv) | <ul><li> What suspected contamination sources exist above this aquifer?</li><li>How many suspected contamination sources are within a radius of two S2L13 cells of each well?</li><li>What may be the source of the PFASin this drinking water district?</li></ul>|
| [CQ8](./CQ8.rq) | What locations have had multiple reported PFAS releases over time? |  |[CQ8-result](./CQ8-result.csv) | |
| [CQ9](./CQ9.rq) | Where did known contaminant releases occur in 2022? | date |[CQ9-result](./CQ9.rq) | |
| [CQ10](./CQ10.rq) | 100 sample points with results | | [CQ10-result](./CQ10-result.csv) | |
| [CQ11](./CQ11.rq) | All *surface water* and *animal tissue* sample results from one samplepoint | sample type|[CQ11-result](./CQ11-result.csv) | |
| [CQ12](./CQ12.rq)| Retrieve all sample points and count how many there are for each type of sample point | | [CQ12-result](./CQ12-result.csv)|<ul><li>Where do we have samples from beef cattle and soil or water in the same location?</li><li>Which crops show the most frequent (or highest) contamination load in X region?</li></ul> |
| [CQ13](./CQ13.rq) | Retrieve all *marine* samplepoints and determine what and how many of each sample type are there | feature type|  [CQ13-results](./CQ13-results.csv)| <ul><li>Which species of fish [species Y] have been tested and how does their contamination load differ</li></ul>|
| [CQ14](./CQ14.rq) | Retrieve all sample results (that aren't aggregates) with the feature sampled, sample location, sample material type, observed property, substance, and numeric or non-detect result. | |[CQ14-result](./CQ14-result.csv) | |