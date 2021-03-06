## About

This document is a record of the participant introduction sessions, both remote and in Colorado. 

Realtime notes gathered at http://board.net/p/wfs3-intros and then transferred to here.

## Participants

**Even Rouault**: Core GDAL developer, implemented WFS 1.0, 1.1, 2.0 client in GDAL/OGR, upgraded QGIS WFS client to 
support WFS 1.1 and 2.0, and upgraded MapServer WFS client to support WFS 2.0. Topic of interest for this hackaton will be to 
develop an experimental WFS 3.0 client in GDAL/OGR.

**Philippe Duchesne**: Background is 10+ years spent on the implementation of the OGC specs. Experimentation with REST portage
of CSW. For the hackathon he's working on a WFS3 js client integrated in a linked data portal, using so far 
https://www.ldproxy.nrw.de as a test platform.
Looking forward to integrating further features of the spec, in particular those that allow a true linked data approach :
 - support for content-type negotiation using HTTP headers
 - 'Link' HTTP headers that link a feature URL to its collection/service description
 
**Francesco Bartoli**: Core GeoNode developer, has 10+ years understanding of WxS OGC specs while supporting clients mostly with GeoServer installation. Interested to prototype an experimental WFS3 implementation with python in order to become a valid back-end alternative for vector layers in the future of GeoNode. Goal of this hackathon is to develop with the geopython community a common library to manage wfs3 objects which can then be used by any framework.

**Andrea Aime**: Core GeoServer developer, participated in various OGC protocol implementations as well as CITE compliance efforts.  Topic of interest for this hackaton will be to develop an experimental WFS 3.0 server plugin for GeoServer.

**Samuel Okoroafor**: Senior GIS Developer @eHealthAfrica, implemented several WFS clients for different projects over the last 5 years. Topic of interest for this hackathon is to adapt existing clients to include WFS3.0 support, to do a test run for the WFS update feature and to provide support to any project implementing a WFS client.

**Angelos Tzotsos**: Core pycsw developer and core GeoNode developer. Participated in OGC CSW 3.0 efforts with the first reference implementation. Interested in implementing WFS 3.0 for GeoNode and STAC for pycsw. Goal of this hackathon is to develop with the geopython community a common library to manage wfs3 objects which can then be used by any framework

## Observers 

(Observer) Scott Serich: OGC staff member, Testbed 14 Initiative Director: short-term goal is to use the momentum from the hackathon to accelerate the WFS 3.0 work in Testbed 14 and avoid as much duplication of effort as possible; long-term goal is to use lessons learned from this effort to inform future OGC Innovation Program initiatives that might adopt a similar "implementation-first" approach to advancing the OGC standards baseline.
