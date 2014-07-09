datalists
=========

Working set of raw RDF data in [Turtle](http://www.w3.org/TeamSubmission/turtle/) format for all standard data lists and schema (mostly CIDOC-CRM extensions) used at STARC. These files contain authoritative data with identifiers to be used for populating the main XML metadata files (activities-resources). You find the corresponding entity (e.g. scanner, camera, person,etc.), grab the identifier and insert into the XML metadata file.

These require no further processing. They are already in RDF format. Just compile to triples/quads using a RDF parser (e.g. rapper - http://librdf.org/raptor/) and import into the triple store.
