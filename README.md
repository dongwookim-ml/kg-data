# kg-data
This repository contains two knowledge graph datasets: NATION and UMLS. 

- NATION contains relations between countries and consists of 14 entities(countries) and 56 relations.
- UMLS is a biomedical ontology dataset and consists of 135 entities and 49 relations.

Both dataset consist of three tab-seperated files:

- `entities.txt`: List of entities, formatted as `entity_id \tab entity_name`

- `relations.txt`: List of relations, formatted as `relation_id \tab relation_name`

- `triples.txt`: List of known facts, formatted as `relation_id \tab entity_id1 \tab entity_id2`

  - means `entity_id1` has `relation_id` relation with `entity_id2` 

Both entity-id and relation-id start from 0.

Additionally, UMLS dataset contains one more file: `entity_category.txt`, which contains a group name of each entity in UMLS data,
and formatted as `entity_id \tab entity_category`.
