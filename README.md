![avaRiskLogo](icons/86x86/harbour-avarisk.png)

# avaRisk
SailfishOS Client for EAWS Avalanche Bulletins

[![Latest release](https://img.shields.io/github/v/release/fridlmue/harbour-avarisk)](https://github.com/fridlmue/harbour-avarisk/releases)
[![SFOS](https://img.shields.io/badge/SailfishOS-OpenRepos-1CA198)](https://openrepos.net/content/fridl/avarisk-avalanche-bulletins)

## Download and Install
- avaRisk can be found and installed from openrepos. (https://openrepos.net/content/fridl/avarisk-avalanche-bulletins)
- avaRisk can be found and installed from the Jolla Store/Sailfish Harbour. (https://harbour.jolla.com/)

## Remarks
- The App always requires an internet connection when opening a Report.

## Supported Regions
At the moment the following regions are supported:
- AT Tirol (https://avalanche.report) (EN/DE)
- AT Kärnten (https://lawinenwarndienst.ktn.gv.at/) (DE)
- AT Oberöstereich (https://www.land-oberoesterreich.gv.at/lawinenwarndienst.htm) (DE)
- AT Niederösterreich (https://www.lawinenwarndienst-niederoesterreich.at/) (DE)
- AT Salzburg (https://lawine.salzburg.at/) (EN/DE)
- AT Styria (https://www.lawine-steiermark.at/) (EN/DE)
- AT Vorarlberg (https://warndienste.cnv.at/dibos/lawine/index.html) (EN/DE)
- IT Bolzano (https://avalanche.report) (EN/DE)
- IT Trentino (https://avalanche.report) (EN/DE)
- DE Bavaria (EN/DE)
- ES Val d'Aran (EN/DE)

### Support considered
- Slovenia: Some or all regions want to partitipate in "CROSSRISK" (http://crossrisk.eu). I'll get the XML-URIs as soon as they are available and the Implement the regions.
- IT Veneto: (https://www.arpa.veneto.it/neve_valanghe/it/xml/dolomiti_nevevalanghe.xml) (Not CAAML-Compatible)

### Regions, that can't be implemented at the moment
- Swiss: seems not to have a open API
- Finnland: answered on 2020-12-22 not to have an open api. Publication is here: https://en.ilmatieteenlaitos.fi/avalanche-forecast. Open Datasets of this provider can be found here: https://en.ilmatieteenlaitos.fi/open-data-sets-available.

### Additional Regions:
For other Regions (in Europe) I need local help to figure out if the local Avalanche Warning Service releases an XML in the CAAML-Format (http://caaml.org/Schemas/V5.0/Profiles/BulletinEAWS/). Then I need the Link to the XML (if available also for different Languages) and the names of all the "micro regions" that are served in that bulletin/XML. This is normally an ID and a Name (e.g. from TYROL: "AT-07-08" - "Zentrale Lechtaler Alpen", can be found here: https://lawinen.report/education/handbook).

## Translation

For Tyrol, South Tirol and Trentino the Bulletins are available in much more language versions (ES, FR, IT, CA and OC). But I'm not able to translate the App to those. So if someone can translate the Translation-Strings it is possible to make full localized versions of those languages. The region names for the sub regions also could be translated. The names can be found here: https://avalanche.report/education/handbook. If someone want to help with a translation please create an Issue. I'm happy to support for any kind of questions. 

## License
Licensed under GNU GPLv3

## Contact
avarisk(at)10hoch-6.de

## Credits
Assets have been taken from https://avalanche.report / https://gitlab.com/albina-euregio/albina-website. It is great, that they started with providing high quality Avalanche Risk Assessments in a common open format in the international ALBINA project.
Many thanks to the "CROSSRISK" project partners (in particular ZAMG https://www.zamg.ac.at/) for providing unifyed data at https://www.avalanche-warnings.eu/. 
Big thanks to all the Avalanche Warning Services who provide the data open and for the great work they do and EAWS (https://www.avalanches.org/) for the standardization efforts.
