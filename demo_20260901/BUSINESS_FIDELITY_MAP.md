# Business-fidelity map

**Fact recheck date:** 2026-09-01. All customer-visible claims must use this map; no facts from conflicting platform listings are combined.

| Planned visible element | Exact controlled claim | Evidence | Verification | Visual/CTA mapping | Exclusion boundary |
| --- | --- | --- | --- | --- | --- |
| Hero identity | `Fluffandtuff`; `Dog grooming in Welling` | Fresha venue and SumUp business pages, both match business identity and address. | High | Hero title / `.hero__title` | No owned-site, legal-entity, or owner claim. |
| Hero framing | `One-to-one grooming, from a home studio.` | Instagram bio directly linked from Fresha professional profile. | High as source claim | Hero eyebrow / `.hero__eyebrow` | Do not imply a guarantee, private appointment, or specialist accreditation. |
| Service 1 | `Full groom` | Current SumUp and Fresha service catalogues. | High | `.service-card--full` | No price, duration, breed, or process detail. |
| Service 2 | `Puppy introduction` | Current SumUp and Fresha service catalogues. | High | `.service-card--puppy` | No age, outcome, or training claim. |
| Service 3 | `Bath & de-shed` | Current SumUp and Fresha service catalogues. | High | `.service-card--bath` | No result, frequency, price, or duration claim. |
| Proof path | `See current reviews and availability on Fresha.` | Current Fresha business surface. | High | `.proof__link` | No copied review, reviewer identity, 5.0 rating, review total, or date claim. |
| Booking CTA | `Book with Fluffandtuff` outbound to selected current third-party page | Fresha and SumUp both current booking surfaces. | High for existence; final destination needs last-moment live check | `.cta--book` | No embedded/self-hosted booking, payment, account, or form. |
| Location close | `Welling` | Fresha and SumUp matching identity/location. | High | `.closing__location` | No street address or hours, because they add no commercial clarity and hours conflict. |

## Asset mapping

`FTD-02 → .hero__image` makes the grooming category visible without asserting a customer result.  
`FTD-03 → .care__image` supports care/service comprehension without asserting the groomer identity.  
`FTD-01 → .proof__identity` anchors the page in the known social identity at a safe small scale.  
`FTD-04 → .closing__image` sets the external-booking close without inventing premises.

`BUSINESS-FIDELITY QA: PENDING IMPLEMENTATION`.
