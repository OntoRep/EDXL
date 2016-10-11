# Introduction
EDXL vocabulary developed in COnCORDE project.

The Emergency Data Exchange Language (EDXL) is a broad initiative to create an integrated framework for a wide range of emergency data exchange standards to support operations, logistics, planning and finance. This vocabulary provides partial implementation of some of  its concepts modelled with RDF/Turtle.

##Visualization of current status
This document provides diagrams generated from Protege OntoGraph plug-in, those may not reflect the latest status of vocaubulary. A visualization of current snapshot of vocabulary can be found from:

[WEBOWL online visualization of current snapshot of ontology.](http://vowl.visualdataweb.org/webvowl/#iri=https://raw.githubusercontent.com/OntoRep/EDXL/master/EDXL.ttl "WEBOWL visualization")

##EDXL Categories and categorizable entities
EDXL vocabulary contains various categorizations based on EDXL standard.  These categories can be used by (Categorizable) data entities such as incidens and reports reports about them and link those to EDXL standard.

![Categorizable concepts](https://raw.githubusercontent.com/OntoRep/EDXL/master/CategorizableCategories.png)

##Reports 
Main EDXL report categories have been defined but no constraints are set in vocabulary on what information should be included. 

![Report categories](https://raw.githubusercontent.com/OntoRep/EDXL/master/ReportCategories.png)

##Relations between categories
Categories are modelled as OWL individuals. This allows to define relations between categoires including: 
* SKOS broader or narrower relations between the categories. 
* Keywords that help sarching information related to particular category.
* Hazards that may result of specific category of incident.
* Injuries that may be typical to victims of a specific incident category.

![Category relations](https://raw.githubusercontent.com/OntoRep/EDXL/master/CategoryRelations.png)

#Incident categories
![Incident related categories](https://raw.githubusercontent.com/OntoRep/EDXL/master/IncidentCategories.png)

##Incident types
![Incident types](https://github.com/OntoRep/EDXL/blob/master/IncidentTypes.png)

##Significant events
![Significant events](https://raw.githubusercontent.com/OntoRep/EDXL/master/SignificantEventCategories.png)

##Infrastructure affected
![Infrastructure affected](https://github.com/OntoRep/EDXL/blob/master/InfrastructureAffected.png)

##Injury events
Sub categoires of injury events has not defined in EDXL but a plan is to add sub-categories so that typical injuries related to incident types can be modelled.

#Status
This is initial draft to be evaluated in COnCORDE project, and still under work.




