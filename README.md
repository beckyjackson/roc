# ROC: Retail Ontology for Climbing
------------------------------------

ROC provides an Ontology Design Pattern (ODP) for the integration of GoodRelations
in to a domain-specific ontology to create a customer- and business-oriented
solution that can be used in several scenarios. ROC has been designed using the
Turtle syntax.

The goals of this work are three-fold: to define a retail-oriented ODP that makes
it easier to understand and reuse GoodRelations, to show how ontologies can be 
integrated with GoodRelations, and to illustrate several concrete retail solutions 
enabled by the use of ontologies. The climbing gear ontology "ROC" was created as 
a learning experience in knowledge engineering and ontology development.

ROC is divided into a hierarchy of files, with the final three being peers of each 
other. Levels 2 through 4 only contain instances of individuals.

1. **roc.ttl**: defines the unique properties and classes for the climbing domain
2. **roc-BusinessEntities.ttl**: contains the various manufacturers
3. **roc-ProductModels.ttl**: details the products produced by manufacturers 
4. **roc-Inventory.ttl**: the inventory of a physical or online store 
4. **roc-Offerings.ttl**: the offer details of products for sale from a store
4. **roc-PersonalCollection.ttl**: owned collection of products

[Find out more about GoodRelations](http://www.heppnetz.de/projects/goodrelations/)
[Send feedback about ROC](mailto:becky.tauber@ninepts.com)

Graphed versions of these ontologies (and any ontology defined with Turtle) can be 
quickly and easily produced using [OntoGraph](http://www.ninepts.com/solutions/tools/ontograph/)!
