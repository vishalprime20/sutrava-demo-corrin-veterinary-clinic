# Website QA handoff packet — Corrin Veterinary Clinic

## QA handoff — Corrin Veterinary Clinic

### Links
- **repository_url:** https://github.com/vishalprime20/sutrava-demo-corrin-veterinary-clinic
- **demo_url:** https://vishalprime20.github.io/sutrava-demo-corrin-veterinary-clinic/
- **Lead ID:** SUT-LEAD-20260812-0001
- **Customer Interest:** DEMO_REQUESTED
- **Demo Required:** TRUE
- **Paperclip issue:** SUT-115 → QA [SUT-116](/SUT/issues/SUT-116)

### Build
- **build_status:** PASS (local `npm test` + `SUTRAVA_STRICT=1 npm test`)
- **build_command:** npm test / SUTRAVA_STRICT=1 npm test
- **pages_workflow:** `.github/workflows/pages.yml` (GitHub Actions → github-pages)
- **commit_sha:** `cc870b61d2fe91c0d551f4b0025bfdaab5ea8008`
- **pages_deploy:** Deploy GitHub Pages **success** for tip (`cc870b6`); live demo HTTP 200

### Verified facts used on the page
| Field | Value | Source |
|-------|-------|--------|
| Business name | Corrin Veterinary Clinic | SUT-61 research-batch |
| Category | Independent mixed veterinary clinic (companion + equine) | research |
| City / region | Fermoy, Co. Cork, Ireland | research |
| Address | Cork Road, Corrin, Fermoy, Co. Cork | research |
| Phone | +353 25 32766 (clinic + emergencies) | research / corrinvets.ie/contact |
| Email | corrinvet@gmail.com | research |
| Leadership | Sean O'Sullivan; assisted by Olivia Peters | research |
| Local tenure | 30+ years (Sean O'Sullivan) | research |
| Services | Companion medicine/surgery/diagnostics; equine emergency; pre-sale vetting; shockwave; lameness; digital X-ray; ultrasound; endoscopy | research |
| Existing website | https://corrinvets.ie/ (unfinished template) | research |

### Explicitly omitted (UNKNOWN / unverified)
- Google Business URL
- On-page rating / review count (directory figures not used as social proof)
- Social links
- Opening-hours table beyond “clinic and emergencies share the same number”
- Awards, capacity stats, fabricated testimonials

### Customization notes (why this is not a clone)
- Tokens / color: woodland ink + meadow green on cool mist paper (not mould amber; not packaging cyan)
- Typography: Fraunces + Figtree
- Layout: companion/equine care lanes + diagnostics grid (not cavity-grid / film stack)
- Hero visual: Cork-hills SVG horizon + mist wash
- CTA wording: Call clinic / Email the clinic with verified IE contacts

### Builder self-test notes
- [x] No fake reviews/awards/stats
- [x] No lorem / SAMPLE leftover in HTML
- [x] Local self-test PASS (strict)
- [x] Pages publish prepared (Actions workflow + og:url/canonical)
- [ ] Mobile ~375px layout OK (QA)
- [ ] Desktop layout OK (QA)
- [ ] Live Pages assets 200 (QA)

### Requested QA outcome
Please return **QA APPROVED** or **QA FAILED** with checklist evidence on [SUT-116](/SUT/issues/SUT-116).
