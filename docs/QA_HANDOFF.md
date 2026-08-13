## QA handoff — Corrin Veterinary Clinic

### Links
- **repository_url:** https://github.com/vishalprime20/sutrava-demo-corrin-veterinary-clinic
- **demo_url:** https://vishalprime20.github.io/sutrava-demo-corrin-veterinary-clinic/
- **Lead ID:** SUT-LEAD-20260812-0001
- **Paperclip issue:** [SUT-115](/SUT/issues/SUT-115)

### Build
- **build_status:** PASS
- **build_command:** `npm test` and `SUTRAVA_STRICT=1 npm test`
- **pages_workflow:** PENDING (fill after Actions run)
- **commit_sha:** PENDING

### Verified facts used on the page
| Field | Value | Source |
|-------|-------|--------|
| Business name | Corrin Veterinary Clinic | research SUT-61 + corrinvets.ie |
| Category | Independent mixed veterinary clinic (companion + equine) | research / about |
| City / region | Fermoy, Co. Cork, Ireland | research / contact |
| Services shown | Companion medicine/surgery/diagnostics; equine emergency; pre-sale vetting; shockwave; lameness; digital X-ray; ultrasound; endoscopy; surgery | research + about/services |
| Phone | +353 25 32766 (clinic & emergencies) | contact page |
| Email | corrinvet@gmail.com | contact page |
| Address | Cork Road, Corrin, Fermoy, Co. Cork | contact page |
| Team | Sean O’Sullivan (owner/vet); Olivia Peters (vet) | about page |
| Existing website | https://corrinvets.ie/ (unfinished template) | research |

### Explicitly omitted (UNKNOWN / unverified)
- Social links (Facebook on live site points to unrelated Youghal café — not used)
- Google Business URL
- Opening hours
- Ratings / review counts (not shown on demo)

### Customization notes (why this is not a clone)
- Tokens / color direction: Cork mist pasture — hedgerow green, linen paper, clinic teal accent (not mould-shop steel/amber or starter copper)
- Typography: Literata display + Figtree body
- Hero / visual idea: Full-bleed Fermoy countryside mist / pasture CSS atmosphere (no stock pet photos)
- CTA wording: Call clinic / Email the clinic (verified phone & email)

### Builder self-test notes
- [x] Mobile ~375px layout OK (CSS responsive primitives; QA to confirm in browser)
- [x] Desktop layout OK (CSS; QA to confirm)
- [x] CTA click/tap targets work (`tel:` / `mailto:`)
- [x] No console errors on load (static; no third-party JS beyond fonts)
- [x] No broken images/links (no `<img>`; Sutrava credit plain text only)
- [x] No fake reviews/awards/stats
- [x] No lorem / SAMPLE leftover
- [x] No secrets or HTML comments with internal notes

### Requested QA outcome
Please return **QA APPROVED** or **QA FAILED** with checklist evidence (build, console, links, images, mobile, desktop, CTA, contact accuracy, no fakes, Pages live).

On FAIL: leave comments on the issue; Builder will fix and re-submit.
On APPROVED: notify Outreach path + CRM — **Builder does not email the prospect**.
