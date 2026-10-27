<img src="https://storage.googleapis.com/pictograph-assets/logos/FullLogo_Transparent_NoBuffer.png" alt="Pictograph" height="48">

**Real-time vision tools for agents and developers.**

[Pictograph](https://pictograph.io) takes a vision task from raw images to a live endpoint:

- **Label fast.** SAM3 drafts boxes and masks from a click, a box or a text prompt, on one image or a whole dataset. You review the drafts before you train. [Auto-annotation](https://pictograph.io/auto-annotate)
- **Train small, task-specific models.** RF-DETR (detection, instance segmentation, keypoints), YOLOX, Segformer and classifiers on managed GPUs, evaluated with mAP, precision and recall. [Training](https://pictograph.io/train)
- **Run them in real time.** Deploy a model as a TensorRT endpoint on a T4, L4 or A100, stream live video to it over WebRTC or RTSP and get each frame's results back, or build workflows that track, count and measure dwell time. [Deployments](https://pictograph.io/deployments) · [Streams](https://pictograph.io/docs/streams) · [Workflows](https://pictograph.io/workflows)
- **Hand it to your agent.** Every CLI command takes `--json`, and `pictograph agents install-skill` teaches Claude Code the platform. Your trained models become tools an agent can call. [Agents](https://pictograph.io/docs/agents)

```bash
pip install 'pictograph[cli]'
pictograph login
pictograph agents install-skill   # Claude Code; `pictograph init` writes an AGENTS.md for Codex
```

[Docs](https://pictograph.io/docs) · [Python SDK](https://github.com/pictograph-io/pictograph-sdk) · [PyPI](https://pypi.org/project/pictograph/) · [Hugging Face](https://huggingface.co/pictograph) · [Explore datasets and models](https://pictograph.io/explore) · [App](https://app.pictograph.io)
