# Description provenance

Provenance of the schema descriptions in `core/openapi/ogcapi-records-1-building-blocks.yaml`: every description was authored from the standard's own requirements classes and prose — none imported.

| Schema | Source | Description (first sentence) |
|---|---|---|
| `catalog` | OGC 21-045 requirements classes (Records - Part 1: Core) | A catalogue of records: an OGC API - Records deployment offering search and retrieval over its record collection. |
| `catalogCommonProperties` | OGC 21-045 requirements classes (Records - Part 1: Core) | The common properties of a catalogue: identifier, title, description, extent and links. |
| `catalogs` | OGC 21-045 requirements classes (Records - Part 1: Core) | A list of the catalogues available on this API. |
| `contact` | OGC 21-045 requirements classes (Records - Part 1: Core) | Identification of, and means of communication with, person responsible
for the resource. |
| `defaultSortOrder` | OGC 21-045 requirements classes (Records - Part 1: Core) | The default sort order applied to query results when the client does not specify one. |
| `format` | OGC 21-045 requirements classes (Records - Part 1: Core) | A format of the resource representation, with its media type and profile. |
| `landingPage` | OGC 21-045 requirements classes (Records - Part 1: Core) | The landing page of the API: links to the conformance declaration, collections and catalogues. |
| `language` | OGC 21-045 requirements classes (Records - Part 1: Core) | The language used for textual values in this record. |
| `license` | OGC 21-045 requirements classes (Records - Part 1: Core) | A legal document under which the resource is made available. |
| `link` | OGC 21-045 requirements classes (Records - Part 1: Core) | A hyperlink with its relation type, per the OGC API link conventions. |
| `linkBase` | OGC 21-045 requirements classes (Records - Part 1: Core) | The base properties common to all links: href, rel, type, title and hreflang. |
| `linkTemplate` | OGC 21-045 requirements classes (Records - Part 1: Core) | A templated link with URI variables for constructing resource URIs. |
| `recordCollectionGeoJSON` | OGC 21-045 requirements classes (Records - Part 1: Core) | A collection of records serialized as GeoJSON, with its numberMatched and numberReturned metadata. |
| `recordCommonProperties` | OGC 21-045 requirements classes (Records - Part 1: Core) | The common properties of a record: identifier, type, timestamps, title, description, links, contacts, themes, format, license and external identifiers. |
| `recordGeoJSON` | OGC 21-045 requirements classes (Records - Part 1: Core) | A record describing a resource in the catalogue, serialized as GeoJSON. |
| `roles` | OGC 21-045 requirements classes (Records - Part 1: Core) | The list of duties, job functions or permissions assigned by the system
and associated with the context of this member. |
| `scheme` | OGC 21-045 requirements classes (Records - Part 1: Core) | The concept scheme of a theme classification, identified by URI. |
| `theme` | OGC 21-045 requirements classes (Records - Part 1: Core) | A theme with which the resource is classified: a concept scheme and one or more of its concepts. |
| `time` | OGC 21-045 requirements classes (Records - Part 1: Core) | A temporal extent: an instant or an interval, optionally open-ended. |

These descriptions are offered upstream as part of the model-based publication program (metanorma-ogc#153); corrections by the editors are welcome and will be tracked here.
