# SERP Models

ONNX model files for [SERP to Prompt Writer](https://github.com/aivrar/serp-to-prompt-writer), a Windows desktop SEO tool that turns a keyword into a data-backed AI writing prompt.

## Files

| File | Where | Purpose |
|------|-------|---------|
| `nli.onnx` (~978 MB) | [Release v1.0](https://github.com/aivrar/serp-models/releases/tag/v1.0) | ONNX export of [valhalla/distilbart-mnli-12-3](https://huggingface.co/valhalla/distilbart-mnli-12-3), used for zero-shot content-type classification |

SERP to Prompt Writer downloads this file automatically from **Settings > Data & Tools**, so most users never need to fetch it by hand.

## License

The files written for this repository (README, scripts, docs) are released under the [MIT License](LICENSE).

The model weights in the release are a format conversion of third-party work. `valhalla/distilbart-mnli-12-3` is distilled from [facebook/bart-large-mnli](https://huggingface.co/facebook/bart-large-mnli), which is MIT-licensed. Credit for the model goes to its original authors.
