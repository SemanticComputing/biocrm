# Bio CRM

Bio CRM is a conceptual reference model for representation of biographical information, with focus on prosopographical research. Bio CRM provides a semantic data model for harmonizing and interlinking heterogeneous data from different biographical data sources. The model includes structures for basic data of people, personal relations, professions, and events with participants in different roles.

The core design principles of the data model are:

* The model is a domain specific extension of [CIDOC CRM](http://www.cidoc-crm.org/), making it applicable to not only biographical data but to other CH data, too.
* The model makes a distinction between enduring unary roles of actors, their enduring binary relationships, and perduing events, where the participants can take different roles modeled as a role concept hierarchy.
* The model can be used as a basis for semantic data validation and enrichment by reasoning.
* The enriched data conforming to Bio CRM is targeted to be used by SPARQL queries in a flexible ways using a hierarchy of roles in which participants can be involved in events.

See more information about Bio CRM in the the [working paper](https://seco.cs.aalto.fi/projects/biographies/biocrm-2020-05-28.pdf) and the [BD2017 paper](https://seco.cs.aalto.fi/publications/2018/tuominen-et-al-bio-crm-2018.pdf).