# ATB Financial (atb-financial)

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

ATB Financial (formerly Alberta Treasury Branches) is a financial institution and Crown corporation wholly owned by the Government of Alberta, established in 1938 and operating under the provincial ATB Financial Act rather than the federal Bank Act. Headquartered in Edmonton, it is Alberta's largest home-grown financial institution and the largest public bank in North America, with roughly C$64 billion in assets, more than 800,000 customers, and 300+ branches and agencies across the province. Deposits are guaranteed by the Province of Alberta rather than covered by CDIC.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/atb-financial/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/atb-financial/refs/heads/main/apis.yml)

## Open Finance & API Posture

ATB Financial does **not** operate a public first-party developer portal or a documented public API surface. The conventional `developer.atb.com` host returns HTTP 404, and no public OpenAPI/Swagger specifications are downloadable.

Canada's federal **Consumer-Driven Banking** framework — legislated through Budget 2024 and the Fall Economic Statement 2024, with the Financial Consumer Agency of Canada (FCAC) named as overseer — is legislated but **not yet operational**. As a result, open-finance access in Canada today remains voluntary and fragmented.

Consumer financial-data access to ATB is therefore **aggregator-mediated**, reached through third-party data aggregators rather than a first-party bank API:

- **Finicity** (a Mastercard company) — supported institution for account and transaction data.
- **Flinks** — Canadian aggregator that lists ATB as a supported connection.

ATB maintains a GitHub organization ([ATBFinancial](https://github.com/ATBFinancial)) with no public repositories at the time of review.

## Tags

- Financial Services
- Banking
- Canada
- Alberta
- Crown Corporation
- Public Bank
- Data Aggregation
- Open Banking
- Consumer-Driven Banking

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public, first-party developer APIs are documented for ATB Financial. Data access is available only via third-party aggregators (Finicity, Flinks).

## Common Properties

- [Website](https://www.atb.com)
- [About](https://www.atb.com/about/)
- [Blog](https://www.atb.com/personal/good-advice/)
- [GitHub Organization](https://github.com/ATBFinancial)
- [LinkedIn](https://www.linkedin.com/company/atb-financial)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
