<p align="center">
  <a href="https://wildedge.dev"><img src="https://raw.githubusercontent.com/wild-edge/.github/main/profile/wildedge-logo-text.png" alt="Wild Edge" height="72" /></a>
</p>

<p align="center">
  Know where your AI struggles in the real world
</p>

<p align="center">
  <a href="https://docs.wildedge.dev">Docs</a> &nbsp;·&nbsp;
  <a href="https://blog.wildedge.dev">Blog</a> &nbsp;·&nbsp;
  <a href="https://github.com/orgs/wild-edge/discussions">Discussions</a> &nbsp;·&nbsp;
  <a href="https://app.wildedge.dev">🚀 Create a free account</a>
</p>

---

See where model behavior changes across releases, runtimes, and devices. Inspect captured inputs, outputs, and feedback, then turn selected examples into datasets for evaluation and training.

The SDK instruments inference calls and emits structured telemetry: latency, confidence scores, drift, hardware state, thermal data, plus the feedback your users give on each result. Turn on capture and the raw inputs and outputs land next to the event that produced them.

That feeds a full loop:

1. **Compare** model behavior across app releases, model versions, runtimes, and device classes
2. **Inspect** the events that went wrong, with their captured inputs, outputs, and user feedback
3. **Build datasets** from selected examples and export them to your evaluation and training pipelines

Capture is opt-in. Leave it off and the SDK sends telemetry only, never raw inputs or outputs.

Your data lands in your own object store under your own keys. Wild Edge can run inside your VPC or on-premise if you need it.

## SDKs

| Language | Repo | Demo |
|----------|------|------|
| Python | [wildedge-python](https://github.com/wild-edge/wildedge-python) | [demo-app](https://github.com/wild-edge/demo-app) |
| Android (Kotlin) | [wildedge-android](https://github.com/wild-edge/wildedge-android) | [Examples](https://github.com/wild-edge/wildedge-android/tree/main/samples) |
| iOS / macOS (Swift) | [wildedge-swift](https://github.com/wild-edge/wildedge-swift) | [Examples](https://github.com/wild-edge/wildedge-swift/tree/main/Examples) |

Need a specific platform? [Open a discussion](https://github.com/orgs/wild-edge/discussions/new/choose).
