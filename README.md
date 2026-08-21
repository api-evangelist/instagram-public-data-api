# Instagram Public Data API (MSG.AI) — not listed

This repository is a removal notice. The Instagram Public Data API from MSG.AI is
**not listed** in the APIs.io catalog, and will not be.

It is kept only so that inbound links to this URL do not dangle. There is no profile,
no `apis.yml`, no specification, and no rating here, and none is coming.

## What happened

MSG.AI submitted this API to the APIs.io Add-API form on **2026-08-20**. The intake
gate auto-created this repository as a bare stub, at a confidence of 85 out of 100,
before a human had looked at it. That review happened on **2026-08-21**, and the
submission was **declined**. No provider page was ever built.

## Why

The decision is about what the service is for, not about the quality of what it
published. The service is real and working, which is why this is a policy refusal
rather than a hygiene removal.

MSG.AI sells bulk extraction of personal data belonging to Instagram account holders
who never consented to it and are not party to the transaction. Its own page, titled
"Cheapest Instagram Public Data API", enumerates what it returns: user profiles,
posts and reels, "Comments and likers", "Followers / following lists", "Stories and
highlights", and "Hashtag and location feeds". It is priced "from only $9.99/mo on
RapidAPI".

Followers and following lists, likers, and location feeds are a social graph and a
location history attached to named individuals. "Public" describes where something
was posted. It does not describe consent to have it harvested, joined and resold as a
commodity.

APIs.io is a discovery catalog. Listing this would publish it as a recommended
integration to developers and to agents, with a Kin Score attached that reads as a
measure of quality. That is not something the catalog will carry.

This is recorded as `basis: policy` in the catalog's delisting registry, which every
pipeline consults before it can create, enrich, score, or index a provider. That entry
— not the deletion of these files — is what keeps a future harvest, enrichment pass,
or re-submission from re-creating this record automatically.

## A separate note about the submission itself

This does not bear on the refusal, and the refusal would stand without it. It is
recorded because it bears on our intake gate rather than on MSG.AI.

The submission declared an APIs.json at `https://wsmsg.me/apis.json`. That document
does not exist. `wsmsg.me` returns HTTP 200 with the byte-identical 22,646-byte HTML
homepage for `/apis.json`, for `/`, and for two invented control paths that were
requested specifically to test it. The declared machine-readable artifact is the
homepage. The gate scored the submission 85/100 and created this repository on the
strength of an artifact it never fetched.

## If you are from MSG.AI

The decision is not a scoring problem and it is not fixable by publishing an OpenAPI
definition — the registry entry is marked `relisting: no` for that reason. Nothing you
add to your developer surface changes it, and it is not for sale.

If the business changes what it sells, that is a different conversation and we will
have it in the open. Write to kin@apievangelist.com.

## Removal requests generally

If you represent a company listed in this catalog and want to be removed, email
kin@apievangelist.com. Removal is honored on request and at no charge.

— Kin Lane, API Evangelist · 2026-08-21
