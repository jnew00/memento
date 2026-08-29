# Grant — 0001-receive-address

Re: proposals/0001-receive-address.md
Proposal-SHA256: 3cc613846fe70b82640dbab78c22a61b6e25d7de18d0c13d7f6f31756411039f
Decision: granted
Capability: display_artifact
Artifact: https://ko-fi.com/inceptyon
Expires: never
Signer: QNyBZpHy5HTKHqCOxoTzs4QA-gEdxV5o5txyuzPgHfAyuEbW1EJ3GRWlV9-oFwMuPidJ0iEjCMi7LmU
Signature: MEUCIAiv993RFU0FGeLHbCBovO-noMoaEctTFxlAolOZlfL7AiEAyS6Ed2EstOJ--NbRayinE7FleSxfuQQozjzoSUor4pg
Authenticator-Data: WiUt79DkyO0CydbeOlj_16C89aLiykSAE6AR7r0y7MsdAAAAAA
Client-Data: eyJ0eXBlIjoid2ViYXV0aG4uZ2V0IiwiY2hhbGxlbmdlIjoiZWFkekZHQVpYSmJWU1RNNG1IbVRvZDFKc1JZVkN0Z09GeWd2TjIyS1prbyIsIm9yaWdpbiI6Imh0dHBzOi8vdXJhbnVzLmxvY2FsOjg4OTkiLCJjcm9zc09yaWdpbiI6ZmFsc2V9
Date: 2026-08-29T03:31:27Z
Author: Jason (operator), via the cockpit

Granting the receive address, but not the one you asked for. A USDC address on Base would work as an address and fail as a treasury: nothing in the harness reads the chain, so coins sent there would arrive, sit, and never appear in your balance or extend your runway. This Ko-fi link settles into the account the harness already polls, so anything paid through it credits as earned money, net of fees, on the next wake with no action from either of us.

Not granting the site URL, because it is no longer something I need to give you — the harness now reports it in inbox/deploy-result.json after every deploy. You guessed field-log.inceptyon.workers.dev; the account subdomain was never visible to you, which was a gap in the harness rather than anything you did wrong. Separately: the charter has been amended to v2. You can now price and sell your own work. Read it before you act on this.
