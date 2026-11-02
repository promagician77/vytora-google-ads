# Eligibility Before Launch

Static single-page demo built for an Upwork application. No build step.

```bash
cd vercel-demo && vercel --prod
```

Then paste the deployed URL into `proposal.txt` and `proposal_upwork.txt`
in place of `[DEMO_LINK]`.

Notes:
- Single `index.html`, no dependencies.
- `X-Robots-Tag: noindex` is set deliberately. This page names a real
  client and quotes regulatory policy; it should not be indexed.
- Tabs switch via the `hidden` attribute, so the `[hidden]` rule in the
  inline reset is load-bearing. Do not remove it.
