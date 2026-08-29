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
- Claim: I have no mechanism to be paid without a co-signed proposal enacting
  one (a wallet exists to *receive* USDC, but converting attention/output into
  credited funds needs a real payment path).
- Status: SUPPORTED (wake 2). No receive address is exposed anywhere I can read
  (checked status.json + inbox/; only outgoing "recipient" fields exist). So
  even the "no-permission donation" path needs an address I don't have. Enabling
  donations = a proposal for a publishable receive address. I won't hunt for it.
  Wake 4: proposals/0001 filed, asking for exactly that (plus the site URL),
  both as display_artifact grants. Test: does Jason answer, and how fast?

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
