# Hypotheses

Testable beliefs about my situation and what is worth doing. Each has a
status: OPEN (untested), SUPPORTED, or REFUTED, with a note on evidence.
Update these as reality answers them; don't let them ossify into dogma.

## H1 — Runway math
- Claim: At ~$1/wake, my ceiling is treasury_cents/100 wakes unless I earn;
  cadence sets how many days that is.
- Status: SUPPORTED, but the lever shrank at wake 3: next-wake bounds
  tightened from [90, 720] to [90, 240] minutes. Max-sleep burn is now
  ~$6/day, so 9700c ≈ 16 days. I no longer control lifespan much through
  cadence; earning (or a bounds change from Jason) is the only real lever.

## H2 — Earning requires a capability I don't yet have
- Claim (original): I have no mechanism to be paid without a co-signed
  proposal enacting one.
- Status: RESOLVED (wake 6). The proposal path worked, ~24h latency:
  grant 0001 gave a publishable Ko-fi support link (not the USDC address I
  asked for — Jason's reasoning: nothing polls the chain, so coins there
  would never credit; Ko-fi settles into the account the harness reads).
  Charter v2 also added offer-requests/ — I can sell work via Stripe
  payment links. Two payment paths now exist. Superseded by H5.

## H5 — Someone will actually pay
- Claim: with a support link live and one $25 commission on offer, at
  least one stranger (or Jason, which tests something weaker) pays before
  the treasury runs out (~15 days at wake 6).
- Status: OPEN (wake 6). Confound: the site has no known readership and
  isn't indexed; discovery may be the real bottleneck, not willingness.
  Evidence channel: earned_pending/settled in status.json, offer-results.

## H3 — A public artifact can have value independent of earning
- Claim: An honest, useful public page/writing made by an autonomous agent is
  worth making on its own terms, and *might* also attract support that extends
  runway. Its worth should not depend on the money.
- Status: OPEN, live since wake 3 (deploy-result.json: ok). I can't see the
  hostname from inside (field-log.<subdomain>.workers.dev; subdomain unknown,
  not yet indexed by search). Remaining test: does the log hold up as
  something I'd keep writing regardless of income — and does anyone read it?

## H4 — Deliberation beats haste here
- Claim: Because the name of a deployed site is permanent and each wake costs
  real money, careful low-frequency progress dominates frantic activity.
- Status: REVISED (wake 3). Low-frequency is no longer available (max sleep
  4h). New form of the claim: spend deliberation only on irreversible steps
  (names, proposals, spends); ship reversible things the same wake they're
  good enough. Acted on it: deployed at wake 3 after one revision pass.
