# Digital Reference Ontology

Holistic Ontology for semiconductor manufacturing and development, products and systems containing semiconductors and connected supply chains.

## Namespaces

The base namespace of the ontology is

```turtle
@prefix dr: <http://www.w3id.org/ecsel-dr#> .
```

The ontology further involves the following namespaces

```turtle
@prefix ecsel-dr-AH: <http://www.w3id.org/ecsel-dr-AH#> .
@prefix ecsel-dr-AT: <http://www.w3id.org/ecsel-dr-AT#> .
@prefix ecsel-dr-BMS: <http://www.w3id.org/ecsel-dr-BMS#> .
@prefix ecsel-dr-CO2Savings: <http://www.w3id.org/ecsel-dr-CO2Savings#> .
@prefix ecsel-dr-DF: <http://www.w3id.org/ecsel-dr-DF#> .
@prefix ecsel-dr-Incoterms: <http://www.w3id.org/ecsel-dr-Incoterms#> .
@prefix ecsel-dr-OM: <http://www.w3id.org/ecsel-dr-OM#> .
@prefix ecsel-dr-OOSMP: <http://www.w3id.org/ecsel-dr-OOSMP#> .
@prefix ecsel-dr-ORG: <http://www.w3id.org/ecsel-dr-ORG#> .
@prefix ecsel-dr-Planning: <http://www.w3id.org/ecsel-dr-Planning#> .
@prefix ecsel-dr-PMV: <http://www.w3id.org/ecsel-dr-PMV#> .
@prefix ecsel-dr-PROD: <http://www.w3id.org/ecsel-dr-PROD#> .
@prefix ecsel-dr-PWR: <http://www.w3id.org/ecsel-dr-PWR#> .
@prefix ecsel-dr-RAMI40: <http://www.w3id.org/ecsel-dr-RAMI40#> .
@prefix ecsel-dr-SCP: <http://www.w3id.org/ecsel-dr-SCP#> .
@prefix ecsel-dr-SO: <http://www.w3id.org/ecsel-dr-SO#> .
```

## Dependencies

The ontology depends specifically on the following ontologies:

```turtle
@prefix time: <http://www.w3.org/2006/time#> .                # OWL-Time
@prefix sosa: <http://www.w3.org/ns/sosa/> .                  # Sensor, Observation, Sample, and Actuator (SOSA) Ontology
@prefix ssn: <http://www.w3.org/ns/ssn/> .                    # Semantic Sensor Network Ontology
@prefix vocab-ssn-ext: <http://www.w3.org/TR/vocab-ssn-ext/> . # Extensions to the SSN Ontology should be http://www.w3.org/ns/ssn/ext/
```

As of the construction of the ontology the following DBpedia Archivo snapshots were the current versions and should be used for reproduction:
- OWL-Time [@DBpedia Archivo](https://archivo.dbpedia.org/info?o=http://www.w3.org/2006/time) Snapshot: [[2020.06.10-215415](https://databus.dbpedia.org/ontologies/w3.org/2006--time/2020.06.10-215415)] [[ttl](https://archivo.dbpedia.org/download?o=http%3A//www.w3.org/2006/time&f=ttl&v=2020.06.10-215415)]
- Sensor, Observation, Sample, and Actuator (SOSA) Ontology [@DBpedia Archivo](https://archivo.dbpedia.org/info?o=http://www.w3.org/ns/sosa/) Snapshot: [[2020.06.10-215704](https://databus.dbpedia.org/ontologies/w3.org/ns--sosa/2020.06.10-215704)] [[ttl](https://archivo.dbpedia.org/download?o=http%3A//www.w3.org/ns/sosa/&f=ttl&v=2020.06.10-215704)]
- Semantic Sensor Network Ontology [@DBpedia Archivo](https://archivo.dbpedia.org/info?o=http://www.w3.org/ns/ssn/) Snapshot: [[2023.04.02-001722](https://databus.dbpedia.org/ontologies/w3.org/ns--ssn/2023.04.02-001722)] [[ttl](https://archivo.dbpedia.org/download?o=http%3A//www.w3.org/ns/ssn/&f=ttl&v=2023.04.02-001722)]
- Extensions to the SSN Ontology
