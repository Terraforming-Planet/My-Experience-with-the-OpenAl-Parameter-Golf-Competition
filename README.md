<img width="1500" height="1024" alt="Project banner" src="https://github.com/user-attachments/assets/f40f7143-1ddc-4784-9338-d6e700dd5b16" />

# From OpenAI Parameter Golf to Applied AI

**Sebastian Laskowski · Tesla Eco / Terraforming Planet**

Parameter Golf was my first hands-on experience training AI models. The practical skills I gained there became the foundation for further work in Earth observation, 3D asset development and game AI.

## Parameter Golf — the starting point

Working independently with ChatGPT's assistance, I prepared experimental datasets, ran experiments using **8× NVIDIA H100 GPUs**, and documented my work on GitHub.

My [submission #2076](https://github.com/openai/parameter-golf/pull/2076), built on PR #1991, [reported approximately **0.9296 BPB (bits per byte)** across three seeds](https://github.com/openai/parameter-golf/pull/2076#issuecomment-4358762060). **For my first AI-training project, seeing that number felt impressive and was a major personal milestone.** It is a reported experimental score, not a validated competition result.

[I did not retain a complete set of the main training logs](https://github.com/openai/parameter-golf/pull/2076#issuecomment-4381591488). Log downloads failed, and the GPU pod had been removed before I could recover them. I reran training, but ran out of time and budget to complete the documentation.

The submission was **explicitly named in the published audit covering the 1 May 2026 deadline**. [Audit #2146](https://github.com/openai/parameter-golf/pull/2146) covered **192 late-stage PRs**; it was published on 2 May and merged on 4 May.

For scale, the repository had [**2,048 PRs opened before the deadline**](https://github.com/openai/parameter-golf/pulls?q=is%3Apr+created%3A%3C2026-05-02T00%3A00%3A00Z). This counts pull requests, not distinct competitors.

**Evaluation limitation:** the audit also identified [probability-normalization and byte-accounting problems](https://github.com/openai/parameter-golf/pull/2076#issuecomment-4364431665) in the byte/PPM evaluation. Missing logs were therefore not the only issue: the score was excluded from the leaderboard and is **not directly comparable with accepted records**. Being named in the audit was not an award or endorsement.

The lasting achievement was practical experience: preparing data, running GPU experiments and learning to validate results—skills I now apply beyond the competition.

## Terra Observation System — completed L4 experiments

I applied that experience to satellite-image processing in **Terra Observation System**. Published NVIDIA L4 runs progressed from small image datasets to a NASA GIBS streaming run that recorded **200,016 training windows across 75 research regions**.

These are documented training results—not proof of environmental detection accuracy or 200,016 independent satellite scenes.

[Project](https://github.com/Terraforming-Planet/Polar-Sun-Moon-Analysis) · [Live demo](https://terraforming-planet.github.io/Polar-Sun-Moon-Analysis/) · [L4 run report](https://terraforming-planet.github.io/Polar-Sun-Moon-Analysis/published/training-runs/stream_gibs_20260820T013036Z/) · [Structured evidence](https://github.com/Terraforming-Planet/Polar-Sun-Moon-Analysis/blob/main/docs/published/training-runs/stream_gibs_20260820T013036Z/analysis.json)

## Cube Chess / Chess Arena 512 AI — 3D and game intelligence

I am also applying this workflow to **3D chess-piece and asset creation**, and to developing AI that follows the game's rules, coordinates its pieces as a team and plays against a human.

The public **Cube Chess 512 AI** provides a playable 8×8×8 foundation with 3D pieces, a rules engine and a computer opponent. Its self-play work concerns deterministic policy tuning and testing—not neural-network training.

For **Chess Arena 512 AI**, I have prepared L4 training plans, datasets and launch scripts for visual assets and gameplay AI. Full training remains subject to validation; a completed neural-model training run is not yet verified in the repository.

[Public game and source](https://github.com/teslaeco/Cube-Chess-512-AI-Open-Source-3D-Chess-Engine-Autonomous-AI-Game-Developer) · [Play](https://teslaeco.github.io/Cube-Chess-512-AI-Open-Source-3D-Chess-Engine-Autonomous-AI-Game-Developer/) · [Game-AI methodology](https://github.com/teslaeco/Cube-Chess-512-AI-Open-Source-3D-Chess-Engine-Autonomous-AI-Game-Developer/blob/main/docs/CODEX_REAL_TEAM_SELFPLAY_3K_V7.md)

---

**Parameter Golf gave me the experience to move beyond my first AI-training experiments and apply those skills to other projects. This portfolio documents that progression.**

Updated: 30 September 2026.
