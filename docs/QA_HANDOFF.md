# Website QA handoff packet — Corrin Veterinary Clinic

## QA handoff — Corrin Veterinary Clinic

### Links
- **repository_url:** https://github.com/vishalprime20/sutrava-demo-corrin-veterinary-clinic
- **demo_url:** https://vishalprime20.github.io/sutrava-demo-corrin-veterinary-clinic/
- **Lead ID:** SUT-LEAD-20260812-0001
- **Customer Interest:** DEMO_REQUESTED
- **Demo Required:** TRUE
- **Paperclip issue:** [SUT-115](/SUT/issues/SUT-115) → QA [SUT-116](/SUT/issues/SUT-116)

### Build
- **build_status:** PASS
- **build_command:** `npm test` / `SUTRAVA_STRICT=1 npm test`
- **pages_workflow:** PASS (run 31733633588)
- **commit_sha:** `9beecd439cdca83f916fb01f8f9c85942b2c7583` (`ca9d1a6`)

### Verified facts used on the page
| Field | Value | Source |
|-------|-------|--------|
| Business name | Corrin Veterinary Clinic | SUT-61 research-batch + corrinvets.ie |
| Category | Independent mixed veterinary clinic (companion + equine) | research / about |
| City / region | Fermoy, Co. Cork, Ireland | research / contact |
| Address | Cork Road, Corrin, Fermoy, Co. Cork | contact |
| Phone | +353 25 32766 (clinic + emergencies) | contact |
| Email | corrinvet@gmail.com | contact |
| Leadership | Sean O'Sullivan; assisted by Olivia Peters | about |
| Local tenure | 30+ years (Sean O'Sullivan) | about |
| Services | Companion medicine/surgery/diagnostics; equine emergency; pre-sale vetting; shockwave; lameness; digital X-ray; ultrasound; endoscopy | research / about |
| Existing website | https://corrinvets.ie/ (unfinished template) | research |

### Explicitly omitted (UNKNOWN / unverified)
- Google Business URL
- On-page rating / review count
- Social links (live site Facebook pointed at unrelated café — not used)
- Opening-hours table beyond “clinic and emergencies share the same number”
- Awards, capacity stats, fabricated testimonials

### Customization notes (why this is not a clone)
- Tokens / color: woodland ink + meadow green on cool mist paper
- Typography: Fraunces + Figtree
- Layout: companion/equine care lanes + diagnostics grid
- Hero visual: Cork-hills SVG horizon + mist wash
- CTA wording: Call clinic / Email the clinic

### Builder self-test notes
- [x] No fake reviews/awards/stats
- [x] No lorem / SAMPLE leftover
- [x] Local self-test PASS (strict)
- [x] Live Pages HTTP 200 for HTML + CSS + SVG
- [x] No href to sutravasoftwaresolutions.com (plain-text credit)
- [ ] Mobile ~375px layout OK (QA)
- [ ] Desktop layout OK (QA)
- [ ] Console / CTA browser confirmation (QA)

### Requested QA outcome
Please return **QA APPROVED** or **QA FAILED** with checklist evidence on [SUT-116](/SUT/issues/SUT-116).
