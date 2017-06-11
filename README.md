# Databases Ontology

### Introduction
The purpose of this ontology is to create the common conceptual framework for 'talking' about databases and/or related concepts. This should provide a common vocabulary for the domain.

### Repository Structure
The repository is structured as follows:
* the [tbox](https://github.com/danielamariei/databases-ontology/blob/master/tbox/) folder contains the TBox of the ontology, serialized in various formats;
* the [abox](https://github.com/danielamariei/databases-ontology/blob/master/abox/) folder contains the ABox of the ontology, serialized in various formats;
* the [queries](https://github.com/danielamariei/databases-ontology/blob/master/queries/) folder contains various example queries that use the ontology.

### Visualizing the Ontology
The ontology can be visualized using the following tools/approaches:
* [render an interactive visualization of the Databases Ontology using WebVOWL](http://visualdataweb.de/webvowl/#iri=https://raw.githubusercontent.com/danielamariei/databases-ontology/master/tbox/databases-ontology.ttl)  (select the **Reset** option after loading the ontology; it is located on the bottom-right side of the screen);
* [render a human-readable HTML page of the Databases Ontology](http://www.essepuntato.it/lode/closure/reasoner/https://raw.githubusercontent.com/danielamariei/databases-ontology/master/tbox/databases-ontology.ttl);
* [view the Databases Ontology in one of the various serialization formats available](https://github.com/danielamariei/databases-ontology/blob/master/tbox/).

### Validating the Ontology
The ontology can be validated using the following tools/services:
* [validate the Databases Ontology using the W3C RDF Validation Service](https://www.w3.org/RDF/Validator/rdfval?URI=https%3A%2F%2Fraw.githubusercontent.com%2Fdanielamariei%2Fdatabases-ontology%2Fmaster%2Ftbox%2Fdatabases-ontology.rdf.xml&PARSE=Parse+URI%3A+&TRIPLES_AND_GRAPH=PRINT_TRIPLES&FORMAT=PNG_EMBED).

### Database vs Ontology
Database
* Closed-world assumption -- missing information is considered false
* No means for performing inferences/reasoning -- although Oracle has support for reasoning, but not sure how it is used internally
* No sharing of information -- software/humans

Ongology
* Open-world assumption -- missing information is considered to be possibly true
* It provides the means for performing inferences/reasoning
* It enables the sharing of information -- software/humans

### Bibliography
* Web Applications Development (RO), Dr. Sabin-Corneliu Buraga, http://profs.info.uaic.ro/~busaco/teach/courses/wade/, UAIC, FII;
* A Semantic Web Primer, second edition, Grigoris Antoniou and Frank van Harmelen, 2008;
* Ontology Development 101: A Guide to Creating Your First Ontology, Natalya F. Noy  and Deborah L. McGuinness, http://www.ksl.stanford.edu/people/dlm/papers/ontology101/ontology101-noy-mcguinness.html.

### Resources
* [WebVOWL](http://vowl.visualdataweb.org/webvowl.html);
* [LODE](http://www.essepuntato.it/lode);
* [W3C RDF Validation Service](https://www.w3.org/RDF/Validator/).
