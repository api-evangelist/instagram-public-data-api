# Instagram Public Data API (MSG.AI) — not listed

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
