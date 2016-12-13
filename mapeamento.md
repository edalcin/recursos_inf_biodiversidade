# Mapeamento das ferramentas

Mapeamento das APIs das ferramentas para a estrutura do ElasticSearch.

| Elastic  | DSpace | Ckan | ResourceSpace | Geonode | 
| ------------- | :---: | :---: | :---: | :---: | 
| [name](http://schema.org/name)  | name  | name | field8 | title |
| [author](http://schema.org/author) | dc.contributor | ?? |  |  |
| [description](http://schema.org/description)  | dc.description.abstract | description |  | abstract 
| taxonCoverage  | |  |  |  |
| [spatialCoverage.name](https://schema.org/spatialCoverage)  | dc.coverage.spatial |  |  |  |
| [keywords](http://schema.org/keywords)  | dc.subject | ?? |  |  |
| [temporalCoverage](https://schema.org/temporalCoverage).year  | dc.date.issued | created | field12 |  date |
| [temporalCoverage](https://schema.org/temporalCoverage).date  | dc.date.available | created | field12 |  date |
| [url](https://schema.org/url)  | dc.identifier.uri | url |  | distribution_url |

