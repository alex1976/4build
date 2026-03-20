# 4Build

4Build is a repository focused on open source software tools and resources for the AEC sector (Architecture, Engineering, and Construction).

The project aims to collect practical assets that help teams:
- To develop software solutions
- To improve digital flows
- To optimize workflows
- to make deployment more efficient

## Current Repository Content

At the moment, the repository contains:
- `index.html`: a single-page project presentation that describes the 4Build vision, themes, and collaboration approach.

## Planned/Target Structure

Based on the project description in `index.html`, the target organization is:

```text
4build/
+-- tools/
+-- apis/
+-- datasets/
+-- agents/
+-- bim/
+-- README.md
```

## Scope of Content

The repository is intended to include:
- software tools and implementation guidance for construction workflows
- API integration patterns (for ERP, BIM, and field systems)
- agent templates for QA, reporting, and coordination tasks
- data and documentation standards for governance and reuse

## AEC Resource Catalog (Web + GitHub)

The following resources were selected from official websites and active GitHub repositories.

### Tools

- [IfcOpenShell](https://github.com/IfcOpenShell/IfcOpenShell): open source IFC toolkit and geometry engine for reading/writing BIM data.
- [Speckle Server](https://github.com/specklesystems/speckle-server): open source AEC data hub for model exchange, automation, and collaboration.
- [GeoPandas](https://geopandas.org/): Python library for geospatial data processing (useful for site and infrastructure workflows).
- [OSMnx](https://osmnx.readthedocs.io/): Python package to download/analyze street networks and geospatial features from OSM.
- [Pyrosm](https://github.com/pyrosm/pyrosm): fast parser for OpenStreetMap PBF files into GeoDataFrames.

### APIs

- [Autodesk Platform Services (APS)](https://aps.autodesk.com/): AEC-focused APIs for Viewer, Automation, and Data Management.
- [APS GitHub Organization](https://github.com/autodesk-platform-services): official SDKs and sample repositories for APS integrations.
- [BCF API (buildingSMART)](https://github.com/buildingSMART/BCF-API): REST API specification for BIM issue/topic exchange between tools.
- [Google Maps Platform APIs](https://developers.google.com/maps/documentation): maps, routes, geocoding, places, and environment APIs.
- [Azure Maps REST APIs](https://learn.microsoft.com/en-us/rest/api/maps/): geospatial APIs for search, route, weather, traffic, and map rendering.
- [Azure Maps Code Samples](https://github.com/Azure-Samples/AzureMapsCodeSamples): practical implementation samples for Azure Maps.

### Datasets

- [Microsoft Global ML Building Footprints](https://github.com/microsoft/GlobalMLBuildingFootprints): large global open building footprint dataset with regular regional coverage updates.
- [Microsoft US Building Footprints](https://github.com/microsoft/USBuildingFootprints): nationwide U.S. building polygon dataset in GeoJSON format.
- [Microsoft Canadian Building Footprints](https://github.com/microsoft/CanadianBuildingFootprints): country-scale building footprints for all Canadian provinces and territories.
- [OpenStreetMap](https://www.openstreetmap.org/): community-maintained open map data widely used in AEC geospatial workflows.
- [Daylight Map Distribution of OpenStreetMap](https://registry.opendata.aws/daylight-osm/): analysis-ready OSM distribution (including parquet) for large-scale querying.
- [Overture Maps Data Repo](https://github.com/OvertureMaps/data): cloud-native open map releases with building, transportation, and place themes.
- [Open City Model (OCM)](https://registry.opendata.aws/opencitymodel/): U.S.-focused 3D city/building data initiative (CityGML-oriented workflows).
- [USGS 3DEP LiDAR Point Clouds](https://registry.opendata.aws/usgs-lidar/): high-value elevation and point-cloud source for terrain, grading, and infrastructure analysis.
- [Open Nation-Scale LiDAR Collection](https://registry.opendata.aws/open-lidar-data/): aggregated open LiDAR datasets (including COPC conversions) for multi-country coverage.
- [NREL End-Use Load Profiles for U.S. Building Stock](https://registry.opendata.aws/nrel-pds-building-stock/): calibrated residential/commercial building energy-use profiles for retrofit and decarbonization studies.
- [buildingSMART Sample & Test Files](https://github.com/buildingSMART/Sample-Test-Files): official openBIM test datasets across IFC versions for interoperability checks.
- [buildingSMART Community Sample Test Files](https://github.com/buildingsmart-community/Community-Sample-Test-Files): community-contributed IFC/BCF/IDS sample datasets for pipeline validation.

### Agents (Skills, Instructions, Prompts)

- [OpenAI API Docs (Agents)](https://developers.openai.com/api/docs/guides/agents): guidance for building tool-using and workflow agents.
- [Microsoft AutoGen](https://microsoft.github.io/autogen/stable/): framework for single- and multi-agent applications.
- [Speckle Automate](https://speckle.systems/build-with-speckle): AEC-oriented automation workflows that can host validation/reporting logic.
- [APS MCP/Revit Automation Samples](https://github.com/search?q=topic%3Aautodesk-designautomation+org%3Aautodesk-platform-services&type=Repositories): examples of AI-connected and automation-oriented workflows in AEC contexts.
- [POWERBI MCP server](https://github.com/microsoft/powerbi-modeling-mcp): repo for the official Power BI MCP server, which can be used to interact with data model.
- [Claude Estimation Skill](https://github.com/alex1976/4build/tree/main/skills/estimation): example of a skill for creating and editing estimates in Excel based on input data and price lists.
- [Claude Construction Site Scheduling Skill](https://github.com/alex1976/4build/tree/main/skills/planning): example of a skill for creating and editing a construction site scheduling in Excel based on estimate.

### BIM resoruces

- [buildingSMART IFC Standard](https://www.buildingsmart.org/standards/bsi-standards/industry-foundation-classes/): official source for IFC versions and compliance resources.
- [IFC5 Development](https://github.com/buildingSMART/IFC5-development): next-generation IFC development examples.
- [IDS (Information Delivery Specification)](https://github.com/buildingSMART/IDS): XML standard for machine-readable BIM information requirements.
- [IfcOpenShell Website](https://www.ifcopenshell.org/): toolkit downloads and documentation ecosystem for openBIM workflows.
- [buildingSMART Data Dictionary (bSDD)](https://www.buildingsmart.org/users/services/buildingsmart-data-dictionary/): standardized dictionary service to link terms/properties in BIM workflows.
- [Bonsai BIM](https://bonsaibim.org/): Free, open source, native IFC authoring platform.
- [That Open BIM](https://docs.thatopen.com/intro): Open source BIM libraries to create your own 3D BIM software.
- [IFC.js](https://ifcjs.github.io/info/): JavaScript library for IFC parsing and visualization in web applications.
- [Xeokit sdk](https://github.com/xeokit/xeokit-sdk): JavaScript software development kit for building 3D web-based BIM viewers and applications.
- [XBim Toolkit](https://docs.xbim.net/): .NET open-source software development BIM toolkit for working with IFC data and building applications.

## Notes

- This list is a starting point and can be expanded with region-specific tools, national standards, and domain-specific datasets (rail, roads, utilities, ports).
- Verify license and usage terms for each resource before production use.

## Collaboration Workflow

Suggested contribution flow:
1. Open an issue describing the use case and AEC context.
2. Provide examples (API, tool, or data model) to make the proposal reproducible.
3. Submit a pull request with validation notes and documentation updates.
4. Complete architecture, security, and maintainability review before merge.

## License

MIT (as indicated in the project page footer).
