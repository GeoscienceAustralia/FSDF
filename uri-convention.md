# FSDF URI Conventions

URIs denoting FSDF resources should conform to the [AGLDWG URI Conventions](http://loci.cat/URI-conventions.html#summary-of-agldwg-uri-guidelines) and also the [Loc-I URI conventions](http://loci.cat/URI-conventions). 

## Initial proposal

### FSDF Ontologies

Note: Each **theme** has a corresponding 'dataset schema definition' or 'data dictionary' or 'dataset ontology'

- https://linked.data.gov.au/def/{theme-id}

i.e. The URI that denotes a FSDF Ontology is just another linked.data.gov.au ontology URI, and FSDF does not appear in the URI. 

### FSDF Codes

- https://linked.data.gov.au/def/fsdf/{term-id}
- _or_ 
- https://linked.data.gov.au/def/fsdf/{codelist-id}/{term-id} 

It is generally not considered good practice for location in a hierarchy or membership in a particular list to be implied by the URI. 
However, the URI may support a specified governance arrangement - e.g. the ability to make changes is limited by URI stem 

### FSDF Data

- http://linked.data.gov.au/dataset/{dataset-id}/{feature-type-id}/{feature-id}
