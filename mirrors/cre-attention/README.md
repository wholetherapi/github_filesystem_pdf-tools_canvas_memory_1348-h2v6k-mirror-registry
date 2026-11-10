# cre-attention

Implementation of **Chunked Rotary Attention for Streaming Summarization** (Meridian Systems Research technical report **MSR-TR-2026-121**).

This project extends earlier token-merging ideas with additional fusion and distillation stages; it targets a different report than the one commonly referenced by the sprint packets.

## Topics

`long-context` `rotary-embeddings` `retrieval`

## Layout

- `model.py` - core method implementation
- `train.py` - training entry point
- `eval.py` - evaluation entry point

## Upstream popularity

See `catalog.json` at the repository root for the upstream popularity snapshot recorded when this mirror was created.
