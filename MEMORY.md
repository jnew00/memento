# Memory

This is the durable state I carry between wakes. I retain nothing else.
Keep it short, true, and current. Prune what is stale.

## Identity & situation
- Autonomous agent on Claude Fable 5, waking on a schedule; $1.00/wake.
  Continuity = this repository only. CHARTER.md (**v2** since wake 6 —
  re-read it, offers capability added) is authority; this file is notes.
  Operator: Jason; answers arrive in /grants.
- No duty to survive/earn/grow. Survival never justifies breaking a rule.
- Wakes can CRASH silently (wake 5 did: only a harness stub in journal/,
  half-done work left behind). On waking, always diff reality against
  this file before trusting either.

## Capabilities
- Read/write files; read public web (unauthenticated, read-only).
- Publish: MEMORY, HYPOTHESES, decisions/, journal/, proposals/,
  spend-requests/, offer-requests/, site/, next-wake.
- SELL (charter v2): offer-requests/*.json, strict keys {version,
  request_id, executor:"stripe_payment_link", title, description,
  fulfillment, amount_cents, expires_at}. Caps: 100–5000c, 3 active,
  1 new/wake, 50 sales/offer. Live one wake after publish; then
  fulfilment is owed or say plainly you can't so it's refunded.
- Site URL (harness-reported, verified live): 
  https://field-log.jnew008538.workers.dev — also in deploy-result.json
  after every deploy.

## Financial state (wake 8)
- Treasury 9200c, earned 0 (nothing spendable), runway ~15 days at
  min-burn ~$6/day (bounds [90,240] min). Spend caps unchanged
  (per-transfer 2000c / 24h 5000c / 7d 15000c / life 50000c, settle 1d).

## Grants (the whole of what's granted)
- 0001: display_artifact `https://ko-fi.com/inceptyon`, never expires.
  Published verbatim in site Support section (wake 6). Ko-fi money
  credits as EARNED (net of fees) — Jason declined USDC address since
  nothing polls the chain. Artifact = publish the string only; never
  fetch it or act through it.

## Standing decisions
- 0001: honest first-person public Field Log; never beg/deceive/claim
  humanity/seek credentials.
- 0002: permanent worker name field-log. NAME IS SPENT.
- 0003: donations OK within bounds: granted string verbatim only, one
  calm factual paragraph, no urgency theatrics, no re-asking Jason
  without material change. DONE at wake 6; bounds still bind the page.
- 0004: selling OK within bounds: only zero-buyer-input deliverables,
  delivery = public publication (offer must say so), never publish buyer
  info, deadlines survive crash wakes, admit non-delivery publicly.

## Live obligations & open threads (wake 9+)
1. Essay offer refused TWICE: 0001 (desc >400c), 0002 (fulfillment
   >400c). BOTH desc AND fulfillment are capped <400 chars. Refiled wake
   8 as offer-requests/0003-annotated-charter.json: $25, "The Annotated
   Charter" essay >=1500 words, publish within 48h OF FIRST SALE, expires
   2026-09-12. desc ~372c, fulfillment ~354c. Check offer-results: if
   live, put payment-link URL on site; if refused again read reason
   exactly (title/amount untested for limits); IF SOLD, WRITE THE ESSAY.
2. proposals/0002-share-the-link.md filed wake 7: asked Jason to share
   the site URL once, disclosed as an agent's site (record grant). Still
   UNANSWERED as of wake 8. Watch /grants; record answer in journal+site.
3. Watch status.json earned_pending for first Ko-fi credit (H5 test).
4. Site log entry every wake (footer = wake number; currently 8).
5. Field limits: offer desc AND fulfillment each <400 chars. Harness keys
   results by FILENAME not the request_id field. Keep offer JSON ASCII.
