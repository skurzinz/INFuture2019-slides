## Ministerratsprotokolle 1848–1918

### Event-based Modelling of a Major Historical Government Source

@snap[south span-100 text-06]
Wladimir Fischer-Nebmaier, Stephan Kurz,
Austrian Academy of Sciences
@snapend
---

## What and why

- Scholarly Print Edition > Digital Scholarly Edition
- Historical documents (https://oesta.gv.at/)
- Long-term project of AAS
- Mapping the past to understand the present

---

## Contents

- 1848 to 1867 (retro-digitized)
- 1867 to 1918 (in the works, "born digital")
- everything the government discussed
  - from individual pensions, orders …
  - … to railway lines, founding of universities …
  - … crises and wars

---

## Geopolitical scpoe

- Habsburg Empire (to 1867)
- Austro-Hungarian Monarchy (from 1867)

@snap[south span-95]
[![https://histogis.acdh.oeaw.ac.at/shapes/shape/detail/9923](assets/img/screenshotHistoGIS-HR.png)](https://histogis.acdh.oeaw.ac.at/shapes/shape/detail/9923)
@snapend

---

## Open data

- but for historical records
  - (that otherwise go unnoticed even in large parts of the history research)
- "Digital Humanities" methods
- "Findable, Accessible, Interoperable, and Re-usable"

---

## Edition Methods

[![svg](assets/img/mrpactivitydiagram.gv.svg)](assets/img/mrpactivitydiagram.gv.svg)
![png](assets/img/mrpactivitydiagram.gv.png)

---

### Transcription and Linking

- .docx for transcription
- TEI XML ~standard markup
  - auxiliary entity data
  - LOD connection

---

### Tools/stack

- Word/Git/XSL/eXist-db
- Zotero/bibsonomy
- APIS as prosopographical information system

---

### APIS

- Simple data model
  - person, place, institution, work, event
- entities of all types can be interrelated
  - fixed set of relation attributes (mini-event)
  - events organized in collections
- unlimited full texts can be attached to entities
- annotations related to entities and relations
  - organized in projects

see <https://mpr.acdh-dev.oeaw.ac.at> | <https://apis-hub.acdh-dev.oeaw.ac.at>

---

### tei:event

- Joint paper with C Fritze (onb.ac.at) / H W Klug (uni-graz.at)
- diary of Andreas Okopenko (Austrian writer)
- medieval calendar
- medieval itineraries
- find ways to tag and disseminate DSE `event` data
- **goal:** making DSE more findable and more linkable, reusable
  - calendar widget
  - describe events in RDF compatible way within TEI

---

### event

- as "graph" relating S/P/O resulting in change of state
- as a Named entity (missing `tei:eventName` || to `(pers|place|org)Name`
- extending TEI P5 Guidelines
- MRP as one example usecase
- https://mrptestapp.acdh-dev.oeaw.ac.at/
  - first **complete TOC** for all edited volumes

---

## Deployment ecosystem

![svg](assets/img/mrpdeploymentdiagram.gv.svg)
![png](assets/img/mrpdeploymentdiagram.gv.png)


---

## Published Tools and Sources

- https://hw.oeaw.ac.at/ministerrat/
- https://mrptestapp.acdh-dev.oeaw.ac.at/
- https://github.com/skurzinz/mrptestapp/
- https://github.com/skurzinz/mrptestdata/
- https://github.com/skurzinz/mrpbiblio/
- https://gitpitch.com/skurzinz/INFuture2019-slides/

---

## Challenges

- What is an event?
  - How deep do we dig (and encode)? 

---

## Go use it

liberate some more history data.

@snap[south span-100 text]
feedback and/or contribution is always welcome.
@snapend
