## Welcome to CIFER Shared API Guidelines

### Why Guidelines for Shared APIs in Higher Education and Research?

Over the last decade the higher education community has produced an impressive collection of open source components for identity and access management. Recently there have been efforts to bring these components together, to develop new components where there are gaps in coverage and to package the whole into a cohesive set of complementary services.

APIs will be key to delivering loosely coupled but readily integratable IAM services. Altogether there will be a large number of APIs since Each IAM component will have to define its own set of API based interfaces. If those APIs were to be designed by independent teams, their solutions would no doubt diverge from one another. The CIFER shared API Guidelines attempt to offer an alternative: a set of design rules and conventions intended to guide the work of independent teams. Such design efforts will confront developers with countless instances in which a choice between alternate approaches has to be made. These guidelines will prove their worth if they anticipate most of the main alternatives and recommend ones that developers will find good enough to abide by.

The guidelines are intended to make it easier to use the APIs as well by guaranteeing that they share a familiar look and feel. If a technologist has used one API from this collection, it should be relatively easy for them to learn and work with another.

### Specifics

The rude beginnings of this work can be seen in this [RAML](http://raml.org) (RESTful API Markup Language) [file](../specs/apiGuide/ciferApi.raml).