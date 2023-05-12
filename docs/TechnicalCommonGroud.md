# Technical common ground
Following the *Methontology framework* by Fernández-López et al. 1999, the ontology lifecycle is coherent with the following standardized phases:
- **[specification]** terminology, micro-objectives, main purpose and limitations scope, granularity level
- **[conceptualization]** semi-formal way of dealing with technical aspects of ontology modelling and domain knowledge
- **[implementation]** formalization of the representation and implementation of classes, hierarchies, properties and attributes.

> *Process planning is concerned with optimizing a specific process, whereas project management is concerned with managing a specific product.*
__________________________________________________
# • process planning
## [what]
For the optimization of the process that lead to a good ontology modelling, we rely on some key actions aimed at identify the necessary steps, tools and resources to deliver a good product. Reducing cost of time and energies, but still having a reliable product.
## [how]
**The process planning here presented reveals the wide opportunity set by a work on ontology-making that, contrary to database development, are focused less on the integrity check and more on the concept of *consistency* checking, relying on automated reasoning. That is a crucial role of ontologies.**
The process planning is the core of the project management, for it to be a reliable system to talk about and think of the organization of classes, properties and attributes (thing that is impossible to envision with a database).
- A first opportunity to gather and consider previous ontologies allows to see how the some topics have been proposed by other people. 
- Furthermore, among the notions analyzed we have analyzed how the notion of **change** and that of **transformation**. Finally, the consideration of other ontology modelling stands as an opportunity for further developments, such as integration with other systems.
- About metadata representation, the ontology representation language chosen has been owl, through rdf schema

### tools
**[ontology development environment and reasoning]** Protegé
**[ontology querying]** SPARQL to our endpoint
**[ontology visualization]** OWLgrEd + http://vowl.visualdataweb.org/webvowl.html 


__________________________________________________

# • project management
__________________________________________________
The project management has to be developed in different levels, according to the work we have been dealing with.
## first level: ontology modelling
1. INVESTIGATION: checking of previous ontologies and taxonomies, together with other sources regarding the knowledge domain. 
2. SPECIFICATION OF OBJECTIVES: development of competency questions and draft of classes properties and attributes.
3. OVERALL FRAMEWORK: formalization of classes and their explanation.
4. TOPOLOGICAL RELATIONSHIPS: classes and class hierarchies are defined in detail.
5. FINAL SPECIFICATIONS AND COMPUTATION: relationships and development in Protegé environment
6. REASONING: reasoning based on competency questions
## second level: modelling domains
The second level regards the Knolwedge Base. The KG is characterized by different domains, that are all those that the ontology refers to, directly or indirectly. The KB is constructed starting to think about where effectively the ontology will be used, and for what main purpose.
In our case, the purpose is purely educational, so ideally it could support a web-application based on Information Model (IFC-based) in which several terms are analyzed for the sake of a postcolonial, therefore non human-centric vision of environments and the actors inside it.

[our domain of reference]
