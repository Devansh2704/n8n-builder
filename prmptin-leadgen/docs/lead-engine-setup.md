# Prmpt.in Lead Engine (Store Leads → Clay → Smartlead → Airtable)

## 1) Goal
Build a repeatable outbound engine that produces **20 high-quality D2C leads/week** with personalized teardown-based outreach.

## 2) Architecture
1. **Store Leads export** (India D2C Shopify/WooCommerce brands)
2. **Clay enrichment + AI research**
3. **n8n orchestration** (validation, scoring, routing, sync)
4. **Smartlead sequencing**
5. **Airtable CRM** for pipeline and reply tracking

## 3) Pipeline stages
- `new`
- `researched`
- `reviewed`
- `queued_for_outreach`
- `emailed`
- `replied`
- `meeting_booked`
- `closed_won`
- `closed_lost`

## 4) Weekly operating rhythm
- **Monday:** Import 50 fresh brands from Store Leads
- **Tuesday:** Clay research + AI outputs
- **Wednesday:** Manual QA + finalize 20
- **Thursday:** Send campaign wave #1
- **Friday:** Follow-ups + reply handling

## 5) Lead scoring rubric (0-100)
- Category fit (beauty/fashion/jewellery/food/home): 0-20
- Ad activity (Meta ads live): 0-20
- Creative weakness clarity: 0-20
- Contactability (valid founder/marketing email): 0-20
- Revenue proxy signals (traffic/social strength): 0-20

### Thresholds
- `80+`: Priority A (send within 24h)
- `60-79`: Priority B
- `<60`: hold list

## 6) Manual QA checklist
- Is the brand actively selling D2C?
- Is the creative weakness actually true?
- Is the angle non-generic and feasible for Prmpt.in?
- Is the first line specific and human?

## 7) Deliverability controls
- Use 2-5 mailboxes initially
- Max 30/day per inbox
- Keep warmup on
- Use plain-text, low-link first touch

## 8) KPI targets
- Reply rate: 5-10%
- Positive reply rate: 1.5-4%
- Meetings booked: 1-3 per 100 sends
- Time to first booked call: <14 days
