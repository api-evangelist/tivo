# TiVo

TiVo provides a universe of high-quality entertainment imagery and information through its metadata APIs. The company offers Video Metadata API and Music Metadata API delivering TV, movie, and music content data for streaming platforms, smart TVs, IPTV systems, and entertainment applications.

**URL:** [https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Entertainment, Metadata, Television, Movies, Music, Streaming

## APIs

### TiVo Video Metadata API

The TiVo Video Metadata API v3 provides access to high-quality entertainment imagery and information for TV shows, movies, and episodes. Supports content search by metadata fields and precise ID-based lookup using Rovi 1.1, Rovi 2.0, TMDB, and EIDR identifiers.

**Human URL:** [https://business.tivo.com/products-solutions/metadata/tv-movie-metadata-api](https://business.tivo.com/products-solutions/metadata/tv-movie-metadata-api)
**Base URL:** `https://data.tivo.com`

#### Tags

Entertainment, Metadata, Television, Movies, Streaming

#### Properties

- [Documentation](https://tivo.stoplight.io/docs/video-metadata-api-v3/ZG9jOjQ3NjAxNTk-introduction)
- [OpenAPI](openapi/tivo-video-metadata-openapi.yml)
- [Developer Portal](https://developers.tivo.com/)
- [JSON Schema](json-schema/tivo-content-schema.json)
- [JSON Structure](json-structure/tivo-content-structure.json)
- [JSON-LD Context](json-ld/tivo-context.jsonld)
- [Spectral Rules](rules/tivo-rules.yml)

### TiVo Music Metadata API

The TiVo Music Metadata API provides access to high-quality music information including artist details, album data, track information, and music imagery.

**Human URL:** [https://tivo.stoplight.io/docs/music-metadata-api/ZG9jOjQ3NjAxNTk-introduction](https://tivo.stoplight.io/docs/music-metadata-api/ZG9jOjQ3NjAxNTk-introduction)

#### Tags

Music, Metadata, Entertainment

## Features

- Content search by multiple metadata fields
- ID-based lookup for precise content retrieval
- Support for Rovi 1.1, Rovi 2.0, TMDB, and EIDR identifiers
- High-quality entertainment imagery
- TV series season and episode data
- Cast and crew information
- Movie and TV show metadata
- Music artist, album, and track data
- Multi-language metadata support
- FTP delivery option for bulk data

## Use Cases

- Smart TV content discovery
- Streaming platform content enrichment
- IPTV guide data
- Entertainment recommendation engines
- Content catalog management
- EPG (Electronic Program Guide) population
- Music service metadata enrichment

## Capabilities

### Shared Definitions

| API | File |
|---|---|
| TiVo Video Metadata | [capabilities/shared/tivo-video-metadata.yaml](capabilities/shared/tivo-video-metadata.yaml) |

### Workflow Capabilities

| Workflow | File | APIs |
|---|---|---|
| Entertainment Metadata | [capabilities/entertainment-metadata.yaml](capabilities/entertainment-metadata.yaml) | TiVo Video Metadata (6 tools) |

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [tivo-video-metadata-openapi.yml](openapi/tivo-video-metadata-openapi.yml) |
| JSON Schema | [tivo-content-schema.json](json-schema/tivo-content-schema.json) |
| JSON Structure | [tivo-content-structure.json](json-structure/tivo-content-structure.json) |
| JSON-LD Context | [tivo-context.jsonld](json-ld/tivo-context.jsonld) |
| Spectral Rules | [tivo-rules.yml](rules/tivo-rules.yml) |
| Vocabulary | [tivo-vocabulary.yml](vocabulary/tivo-vocabulary.yml) |

## Examples

- [Search Content](examples/tivo-search-content-example.json)
- [Lookup Content By ID](examples/tivo-lookup-content-by-id-example.json)

## Integrations

- Smart TV platforms
- DTS AutoStage automotive platform
- IPTV platforms
- Streaming services

## Solutions

- Entertainment metadata platform
- Content experience enrichment
- Smart TV application development
- Automotive in-car entertainment

## Common Properties

- [Website](https://business.tivo.com/)
- [Documentation](https://business.tivo.com/products-solutions/metadata/tv-movie-metadata-api)
- [Developer Portal](https://developers.tivo.com/)
- [GitHub Organization](https://github.com/tivo)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
