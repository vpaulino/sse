# sse
this is the repository of an applicational strutured semantic events ontology.  

this ontology is represented in JSON-LD and consists on the definition of a vocabulary that defines a set of concepts that are important when logging an application event. 

# Ontology graph


|[Ontology Graph](/images/OntologiaSSE.png)

## Concepts 
### Classes 

|Concept|Description|
|-------|-----------|
|Event|Root entity that is related with all the remaining concepts|
|EventActions|Defines a set of individuals that represent a set of verbs that describe the action of the event registered|
|Caller|Defines a set of relationships with a set of concepts that defines who the caller was|
|Callee|Defines a set of relationships with a set of concepts that defines where did the event occorred|
|Participant|Defines a set of relationships with a set of concepts that defines the identity of the aplication client that started the use case execution|
|Subjects|Consists on a list of entities on with the action of this event as occorredd|
