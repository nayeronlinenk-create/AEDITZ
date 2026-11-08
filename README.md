# AEDITZ starter

## Run in GitHub Codespaces

1. Upload/extract these files into your repository root.
2. Open the Codespaces terminal.
3. Run:

```bash
npm install
npm run dev -- --host 0.0.0.0
```

4. Open the forwarded port 5173.

## Current status

- Responsive landing page and AEDITZ branding
- Free and Pro Monthly (₹150/month) pricing UI
- Ad placeholder for free users
- Video upload and browser preview
- Trim start/end controls (preview only)

## Before launch

- The payment button is a demo. Connect a payment provider and verify subscriptions on a secure backend.
- Replace the ad placeholder with an approved ad network integration. Do not place ads over the editing canvas or disrupt editing.
- Implement real video rendering/export (e.g. FFmpeg.wasm or a server-side media pipeline).
- Add authentication, subscription status, and server-side ad-free entitlement checks.
- Verify branding/domain availability and publish privacy policy, terms, and refund/cancellation details.
