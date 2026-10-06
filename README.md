# Research proposal

We propose an empirical study of reasoning efficiency in DeepSeek V4.1 Flash, measuring answer accuracy and reasoning-token usage under controlled input conditions.

The study requires raw completion or token-ID access that preserves the model's canonical serialized prompt. The serving API must not add a chat template or system instructions, rewrite the supplied prompt, or impose separate reasoning controls. We also need the complete generated reasoning, token accounting, finish reasons, and documented model and decoding settings.

We request a small initial allocation of inference credits to verify these requirements before conducting the main experiment. This repository contains the proposal only; the detailed experimental protocol remains private while the study is being prepared.
