# Independent Visual Acceptance — Fluffandtuff Dog Groomers

**Reviewer:** independent from the build Owner; read-only review.  
**Review date:** 2026-09-01.  
**Reviewed:** `index.html`, `styles.css`, Desktop `qa/desktop-1440x900.png`, Mobile `qa/mobile-390x844.png`, Mobile `qa/mobile-css390-dpr2.png`, plus the existing asset/fact ledgers and pre-code review.

## Conclusion

```text
INDEPENDENT VISUAL ACCEPTANCE: FAIL
CLIENT-SHOWABLE DEMO: FAIL
VISUAL QUALITY RUBRIC: NOT PASSABLE — required trustworthy mobile and full-page visual evidence is absent.
```

This is not a judgement that the visual direction is low quality. The Desktop Hero is coherent and customer-relevant, but the required Concept identity is absent and the supplied mobile captures are horizontally clipped/scale-anomalous. A code review cannot substitute for final real-browser Mobile evidence.

## Evidence separated by layer

| Layer | Result | Evidence / boundary |
| --- | --- | --- |
| Client-visible internal-text gate | **FAIL** | `index.html` contains no low-interference `Independent concept preview` (or applicable `Unlisted concept preview`) label. It contains none of the banned AI/rights/internal-authorisation phrases, but the mandatory minimal Concept identity is also missing. |
| Fact and asset boundary | **PARTIAL PASS** | Business name, Welling, one-to-one/home framing, selected services and Fresha path align with the Business-Fidelity Map. All four local image hashes match the Image Ledger; concept assets have natural, non-AI alt text and the small Instagram image is not stretched as a logo. |
| Client-visible fact boundary | **P1 FAIL** | The Hero lede adds `sent home feeling their best`, an outcome/welfare claim not permitted by the controlled Hero claims in `BUSINESS_FIDELITY_MAP.md`; it should not appear unless explicitly evidenced and mapped. |
| Desktop visual evidence | **PARTIAL PASS ONLY** | `desktop-1440x900.png` credibly shows a polished, legible Hero: clear dog-grooming recognition, Welling label, category-relevant hero, readable hierarchy and no visible above-fold overflow. It does not show the Services, Proof or Closing portions, so it is not full-page Desktop evidence. |
| Mobile visual evidence | **NOT TRUSTWORTHY / NOT PASS** | Both nominal-390px screenshots crop content at the right edge: the header booking label, Hero figcaption, headline and lede are cut. `mobile-css390-dpr2.png` is also scale-anomalous. Per the supplied known headless-Chrome limitation, these captures cannot prove a Mobile defect in the implementation, but equally cannot prove a 390px pass. |
| Static responsive-code review | **PLAUSIBLE, NOT A VISUAL PASS** | The 760px media query changes the Hero, service/proof grids and footer to one column; `min-width:0`, `max-width:100%` for images, a 40px mobile shell, and `overflow-x:hidden` are present. This is useful implementation evidence only; it cannot establish rendered crop, readable type, CTA visibility or no horizontal overflow at 390px. |
| L0 self-contained boundary | **P1 FAIL** | `P2_L0_SCOPE.md` specifies a self-contained local preview with local ledgered assets, but `index.html` imports Google Fonts from `fonts.googleapis.com`/`fonts.gstatic.com`. Thus the final typography/visual result still depends on a remote request rather than the declared self-contained package. |

## P0 / P1 defects blocking acceptance

| Severity | Blocking issue | Required closure evidence |
| --- | --- | --- |
| **P0** | Add the required low-distraction visible identity text: `Independent concept preview` (the page is local, not unlisted/public). Keep AI, rights, authorisation and internal-governance language out of the client page. | Final rendered Desktop and Mobile evidence showing the natural, low-interference label. |
| **P0** | The two supplied Mobile screenshots are unusable as acceptance evidence. | A trustworthy real-browser 390×844 capture, with URL/viewport/date and top/middle/bottom or full-page coverage; confirm legible text, CTA visibility, image crop and no horizontal clipping. |
| **P1** | Remove or source-map the unverified Hero outcome claim `sent home feeling their best`. | Updated Business-Fidelity Map plus final rendered page, or remove the claim. |
| **P1** | Produce complete final Desktop visual coverage; the one 1440×900 capture only proves the Hero and start of the next section. | Desktop top/middle/bottom or full-page evidence at 1440×900. |
| **P1** | Resolve the declared L0 self-contained package conflict caused by remote Google Fonts. | Either package permitted font assets locally with a ledgered source/disposition, or explicitly revise the approved L0 scope before relying on remote fonts. |

## Provisional visual observations (not a completed rubric)

- **5-second recognition:** Desktop Hero passes at the category level: dog, grooming table/tools, business name and Welling are immediately legible. It does not establish customer-result authenticity; the Image Ledger correctly restricts the photo to a generic concept role.
- **Commercial upgrade:** the visible Hero supports the intended calmer, service-led alternative to fragmented booking platforms, but the unexplained rest of the full page has not been visually evidenced.
- **Owner-reply perspective:** promising above the fold, but `would-I-reply` cannot be passed without reviewing the Proof/Closing journey and a trustworthy Mobile render.
- No score is assigned to the ten-point rubric: assigning a mobile score or average from the clipped captures would misrepresent the evidence. Accordingly, `VISUAL QUALITY RUBRIC = PASS` is not available.

## Other observations

- No prohibited visible text (`AI`, asset rights, internal review, draft, authorisation, or transfer language) was found in the HTML, meta text, alt text, labels or footer.
- All listed local images are unique by SHA-256 and map to separate roles; no duplicate-image issue was found in the inspected page.
- The header’s `Book a visit ↗` is an in-page `#book` link, not an outbound link; the arrow convention is mildly misleading but is not an acceptance blocker compared with the P0/P1 items above.

No deployment, upload, contact, download, account action, external link visit, or other external write occurred during this review.
