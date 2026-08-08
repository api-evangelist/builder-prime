# Builder Prime

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Builder Prime is an all-in-one CRM and business management platform built for home improvement
contractors and remodelers — lead and client management, appointment setting, estimating and price
books, proposals and e-signature contracts, project and production scheduling, invoicing and
payments, SMS and email, and sales reporting. Each customer works from its own subdomain, and
Builder Prime exposes a REST "Open API" plus webhooks and a Zapier app.

- Website: https://www.builderprime.com/
- Open API documentation: https://www.builderprime.com/blog/open-api-documentation
- Knowledge base: https://help.builderprime.com/bp-knowledgebase
- Integrations: https://www.builderprime.com/integrations
- Status: https://builderprime.statuspage.io/

**Note on coverage.** The Open API is live and callable — its resource paths return real `401
Unauthorized: Invalid key` responses while unknown paths return a different 404 envelope. But
Builder Prime publishes **no OpenAPI definition**, and its knowledge-base API reference articles now
return 404: the surviving public documentation page refers to "the document attached to this page",
and that attachment is not present in the served page. The artifacts in this repository were
assembled from the provider's published prose and from unauthenticated probes of the live API host —
no endpoint, field, event, or schema has been invented on Builder Prime's behalf.
