### Introduction

This repository contains the results of a comparative analysis between the European Health Data Space (EHDS) European Patient Summary (EPS) and international openEHR Clinical Knowledge Manager (CKM) archetypes, conducted by freshEHR Clinical informatics Ltd. on behalf of Nictiz.
<br />
<br />

### Scope

A fit gap analysis is provided for the 6 core concepts of the EPS:

1. Allergies and intolerances
2. Problems (conditions)
3. Medication
4. Medical devices and implants
5. Procedures
6. Patient (partially in scope)


### Methodology

Each of the 6 core concepts from EPS consists of one or more [EHDS Logical Models (version 0.2.1)](https://www.xt-ehr.eu/fhir/models/0.2.1/). Logical Models may be shared between concepts. 

openEHR section templates are created at the level of a concept. An embedded template is created for each Logical Model and included in the section template for each relevant concept. Mappings to the corresponding Logical Model items are included in the templates as Annotations for each data element.

The section templates are exported in Web Template format and converted into CSVs using [this online tool](https://wt2xt-app-sd8pw.ondigitalocean.app/).
<br />
<br />

### openEHR Templates 

The mapping templates are in /local.
<br />
<br />

### Mapping CSVs

The mapping CSVs are in /Mappings.
<br />
<br />

### freshEHR Mapping Comments (work in progress!):

The mapping comments are documented here: https://freshehr.notion.site/Mapping-Comments-2c0fae3e474880afbb29e6f03b19b1fa
<br />
<br />
<br />
More information about the project can be found [here](https://freshehr.notion.site/Mapping-EHDS-EPS-to-openEHR-31bfae3e474880ba9a1ee30fc8931487).
<br />
<br />
