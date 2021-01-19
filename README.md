



```
## Turtle Start ##

@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix dcterms: <http://purl.org/dc/terms/> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .
@prefix schema: <http://schema.org/> .
@prefix foaf: <http://xmlns.com/foaf/0.1/> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix : <#> . 

<> rdf:type foaf:PersonalProfileDocument .
<> foaf:maker :me .
<> foaf:primaryTopic :me .

:me a schema:Person, foaf:Person ;
  schema:name "Emeka Azuka Okoye" ;
  schema:mainEntityOf <>, <https://ng.linkedin.com/in/emekaokoye#>, <https://twitter.com/emekaokoye#> ;
  owl:sameAs <https://ng.linkedin.com/in/emekaokoye#this>, <https://twitter.com/emekaokoye#this> .
  
:this a schema:WebPage, foaf:Document ;
  rdfs:name "Emeka Azuka Okoye' Profile Document"@en ;
  dcterms:created "2021-01-18"^^xsd:dateTime ;
  dcterms:creator :me ;
  schema:mainEntity :me ;
  foaf:primaryTopic :me .

```
