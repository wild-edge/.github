<p align="center">
  <a href="https://wildedge.dev"><img src="https://raw.githubusercontent.com/wild-edge/.github/main/profile/wildedge-logo-text.png" alt="WildEdge" height="72" /></a>
</p>

<h3 align="center">Production intelligence for on-device and hybrid AI</h3>

<p align="center">
  <a href="https://wildedge.dev/demo/"><b>Try the live demo</b></a> &nbsp;·&nbsp;
  <a href="https://docs.wildedge.dev">Docs</a> &nbsp;·&nbsp;
  <a href="https://blog.wildedge.dev">Blog</a> &nbsp;·&nbsp;
  <a href="https://app.wildedge.dev">Create a free account</a>
</p>

<p align="center">
  Core ML · LiteRT · ONNX Runtime · ML Kit · ExecuTorch · llama.cpp · MLX · PyTorch · Transformers · OpenAI · Anthropic · Gemini
</p>

---

## Try it on your app

Put `wildedge run` in front of the command you already run. No code changes:

```bash
uv add wildedge-sdk
WILDEDGE_DSN="https://<secret>@ingest.wildedge.dev/<key>" \
  wildedge run --integrations transformers,openai -- python app.py
```

| Platform | SDK | Examples |
|----------|-----|----------|
| Python | [wildedge-python](https://github.com/wild-edge/wildedge-python) | [python-demo-app](https://github.com/wild-edge/python-demo-app) |
| Android (Kotlin) | [wildedge-android](https://github.com/wild-edge/wildedge-android) | [samples](https://github.com/wild-edge/wildedge-android/tree/main/samples) |
| iOS / macOS (Swift) | [wildedge-swift](https://github.com/wild-edge/wildedge-swift) | [Examples](https://github.com/wild-edge/wildedge-swift/tree/main/Examples) |

## A 60-second investigation

<p align="center">
  <a href="https://wildedge.dev/demo/"><img src="https://raw.githubusercontent.com/wild-edge/.github/main/profile/investigation.webp" alt="Five steps: 1. Spot it: Monday's email shows low-confidence answers went from 1% to 25%. 2. Narrow it down: one SQL query shows only one chip, on its neural accelerator, is affected; the GPU and newer phones are fine. 3. See what it saw: the model called a BMW a Ford at 33% confidence. 4. Follow it to the cloud: 37 ms on the phone, then 9 seconds and a paid Gemini call, in one trace. 5. Fix it: send the 195 misreads to the training pipeline." width="100%" /></a>
</p>

## Built for

- **Physical AI.** Cameras, kiosks and robots on Linux, through the Python SDK.
- **Coding agents.** Claude Code, Cursor and others can query your production telemetry through [MCP](https://docs.wildedge.dev/mcp).
- **Your data, your rules.** Photo capture is opt-in. Data stays in your own object store, and WildEdge can run in your VPC or on-premise.
