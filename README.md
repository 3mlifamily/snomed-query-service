# SNOMED CT Release Query Service
This service enables querying of a SNOMED CT release.
This is a pet project and is not supported by IHTSDO.

There is support for a subset of SNOMED CT Expression Constraint Language.

## Documentation / Live Demo
API documentation here with live demo: http://srqs.kaicube.com/

## Live Example Expression Constraint Language queries:
* Descendant of "Administrative statuses (finding)" [http://srqs.kaicube.com/concepts?ecQuery=<<307824009](http://srqs.kaicube.com/concepts?ecQuery=<307824009)
* Ancestor or self of "Fitting of contact lens (procedure)" having attribute "Method (attribute)" [http://srqs.kaicube.com/concepts?ecQuery=>>448642000:260686004](http://srqs.kaicube.com/concepts?ecQuery=>>448642000:260686004)
* Concepts having attribute "Direct device (attribute)" with value "Plaster cast, device (physical object)" [http://srqs.kaicube.com/concepts?ecQuery=*:363699004=34164001](http://srqs.kaicube.com/concepts?ecQuery=*:363699004=34164001)
* Concepts in the ICD-O simple map reference set having attribute "Procedure site (attribute)" [http://srqs.kaicube.com/concepts?ecQuery=^446608001:363704007](http://srqs.kaicube.com/concepts?ecQuery=^446608001:363704007)

## Project Info
Trello board here: https://trello.com/b/fZ0jvg0e/srqs

### Build Status
[![Build Status](https://travis-ci.org/kaicode/srqs.svg)](https://travis-ci.org/kaicube/srqs)

### licence
 Apache 2.0 Open Source Licence :sunglasses:
