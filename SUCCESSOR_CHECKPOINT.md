# Successor checkpoint

Updated: 2026-09-10

## Current state

- Site: `https://discourse.demo.codeworkslabs.dev/`
- Repository: `https://github.com/CodeWorksLabs/discourse-demo-codeworkslabs-dev`
- Branch: `main`
- Cloudflare Worker configuration: `discourse-demo-codeworkslabs-dev`
- Repository establishment is a source-control correction; it does not deploy or alter the live Worker.
- The site source is self-contained within this repository root.

## Verification contract

Run `npm ci`, `npm audit --omit=dev`, `npm run build`, and `npm run deploy:dry-run`.

## Boundaries

DiscussionBridge remains independently owned. This site may describe or link it but must not absorb its source, doctrine, or operational claims.

The exact commit identity and completed verification evidence will be recorded here when the initial public baseline is pushed.
