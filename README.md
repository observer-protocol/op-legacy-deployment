# op-legacy-deployment

**Renamed from `observer-protocol-spec` on 2026-08-03. This is not the specification repository.**

Despite the old name, nothing canonical lives here. This repository is a historical deployment tree:
an API server, database migrations, deployment logs, an auto-restart script and a `.env.example`. It
was named for what it was intended to be, not for what it became.

## Where things actually are

| You are looking for | It is here |
|---|---|
| **The specification** — AIP v0.6 through v0.9, delegation schemas, schema policy | [`observer-protocol/aip`](https://github.com/observer-protocol/aip) |
| **The published schemas**, dereferenceable and immutable | `https://observerprotocol.org/schemas/…` |
| **The policy engine** — verification runtime, MIT, on npm | [`observer-protocol/op-policy-engine`](https://github.com/observer-protocol/op-policy-engine) |
| **Verifying a credential** | `npm install @observer-protocol/policy-engine`, or `POST https://verify.observerprotocol.org/v1/verify` |
| **The issuer DID document** | `https://observerprotocol.org/.well-known/did.json` |

## Why this repository still exists

It is kept rather than archived so that its open issues stay writable and its history stays readable.
Renaming preserves both, and GitHub redirects the old URL — but that redirect is silent, so this file
exists to explain where you have landed.

**It is not maintained.** Do not read the documents here as current. In particular `WHITEPAPER.md`,
`REPO_MAP.md` and `CHANGELOG.md` describe an architecture and a repository layout that have since
changed, and `REPO_MAP.md` was last updated in April 2026.

## If you were sent here for the spec

You want [`observer-protocol/aip`](https://github.com/observer-protocol/aip).
