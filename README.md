# Introduction
EDXL vocabulary developed in COnCORDE project.

The Emergency Data Exchange Language (EDXL) is a broad initiative to create an integrated framework for a wide range of emergency data exchange standards to support operations, logistics, planning and finance. This vocabulary provides partial implementation of some of  its concepts modelled with RDF/Turtle.

#EDXL Categories
EDXL vocabulary contains various categorizations based on EDXL standard.  These categories can be used by (Categorizable) data entities such as incidens and reports reports about them and link those to EDXL standard.

![Categorizable concepts](https://raw.githubusercontent.com/OntoRep/EDXL/master/CategorizableCategories.png)

Categories are modelled as OWL individuals. This allows to define relatinons such as those defined by SKOS ontology between the categoies. OWL punning is used to define subclass hierarchies where metaclasses are also individuals. 

##Incident categories

![Incident related categories](https://raw.githubusercontent.com/OntoRep/EDXL/master/IncidentRelatedCategories.png)

###Incident types

![Incident types](https://github.com/OntoRep/EDXL/blob/master/IncidentTypes.png)


##Status
This is initial draft to be evaluated in COnCORDE project, and still under work.

##Visualizations

[WEBOWL online visualization of current snapshot of ontology.](http://vowl.visualdataweb.org/webvowl/#iri=https://raw.githubusercontent.com/OntoRep/EDXL/master/EDXL.ttl "WEBOWL visualization")


