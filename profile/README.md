<p align="center">
  <a href="https://wildedge.dev"><img src="https://raw.githubusercontent.com/wild-edge/.github/main/profile/wildedge-logo-text.png" alt="Wild Edge" height="72" /></a>
</p>

<p align="center">
  Turn edge cases into training data
</p>

<p align="center">
  <a href="https://docs.wildedge.dev">Docs</a> &nbsp;·&nbsp;
  <a href="https://blog.wildedge.dev">Blog</a> &nbsp;·&nbsp;
  <a href="https://github.com/orgs/wild-edge/discussions">Discussions</a> &nbsp;·&nbsp;
  <a href="https://app.wildedge.dev">🚀 Create a free account</a>
</p>

---

Wild Edge is an on-device ML monitoring platform. The SDK instruments inference calls and emits structured telemetry: latency, confidence scores, drift, hardware state, thermal data. No raw inputs or outputs are captured by default. Opt-in capture is available for teams that need it.

That telemetry feeds a full loop:

1. **Monitor** model quality across device, OS, and accelerator
2. **Capture** production events by confidence or outcome, attach inputs, build labeled datasets from real failures and user feedback
3. **Retrain** faster by querying the full inference history in SQL or natural language and exporting to your pipeline

Your data lands in your own object store under your own keys. Wild Edge can run inside your VPC or on-premise if you need it.

## SDKs

| Language | Repo | Demo |
|----------|------|------|
| Python | [wildedge-python](https://github.com/wild-edge/wildedge-python) | [demo-app](https://github.com/wild-edge/demo-app) |
| Android (Kotlin) | [wildedge-android](https://github.com/wild-edge/wildedge-android) | [Examples](https://github.com/wild-edge/wildedge-android/tree/main/samples) |
| iOS / macOS (Swift) | [wildedge-swift](https://github.com/wild-edge/wildedge-swift) | [Examples](https://github.com/wild-edge/wildedge-swift/tree/main/Examples) |

Need a specific platform? [Open a discussion](https://github.com/orgs/wild-edge/discussions/new/choose).
