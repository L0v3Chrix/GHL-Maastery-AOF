# GHL Mastery AOF Funnel

Complete 4-page sales funnel for the AOF (Assessment-Operations-Framework) offer.

## Funnel Structure

| Page | File | Offer | Price |
|------|------|-------|-------|
| 1 | `index.html` | AOF Framework Training | $47 |
| 2 | `upsell-1.html` | Implementation Stack | +$97 |
| 3 | `upsell-2.html` | Accelerator + Strategy Session | +$297 |
| 4 | `thank-you.html` | Order Confirmation + VIP Teaser | — |

## Test Mode

All pages include a **TEST MODE** banner. Forms submit to the next page in the sequence so you can click through the entire funnel.

### Test Flow
1. Start at `index.html` (front-end offer)
2. Fill sample data, click "Get Instant Access"
3. Lands on `upsell-1.html` — click YES or NO
4. Lands on `upsell-2.html` — click YES or NO
5. Lands on `thank-you.html` — order complete

The thank-you page dynamically shows what was "purchased" based on URL params.

## Local Development

```bash
cd aof-repo
python3 -m http.server 8080
# Visit http://localhost:8080
```

## The AOF Process (Corrected)

```
FREE 15-min Call → Sell the $500 AOF Call
        ↓
$500 AOF Call (90 minutes, paid diagnostic)
        ↓
3-5 business days → Full Project Scope PDF
        ↓
Agency chooses: DIY with scope OR partner with VIP team ($497/mo)
```

## Files

```
aof-repo/
├── index.html          # Page 1: Front-end ($47)
├── upsell-1.html       # Page 2: Implementation Stack ($97)
├── upsell-2.html       # Page 3: Accelerator ($297)
├── thank-you.html      # Page 4: Confirmation + VIP
├── css/
│   └── styles.css      # Shared stylesheet
└── README.md           # This file
```

## Design Notes

- Dark gradient background (#0e1018 → #1a3aad)
- Poppins for headlines, Inter for body
- Green (#04b828) for CTAs and success states
- Orange (#f87e00) for secondary CTAs and urgency
- Clean bullet points (no colored boxes)
- Modeled after PaidCreators funnel structure

## Brand

**GHL Mastery** by RhinoMouse Marketing Inc.
- Owners: Adam McInnes & Brendan Barth
- VIP: $497/month with white-label build team

---

*Built by RTV Agency | 2026-02-10*
