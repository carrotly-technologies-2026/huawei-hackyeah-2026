# huawei-hackyeah-2026

Submission for the Huawei challenge at HackYeah 2026: an app for an OpenHarmony-based mobile device. Challenge statement: <https://github.com/onirodeveloper/hackyeah2026-challenge/blob/main/hackathon_challenge.md>

> Status: project scaffolding. The ArkTS application has not been generated yet.

## What it does

_TBD. See [`HACKATHON_BRIEF.md`](HACKATHON_BRIEF.md)._

- Challenge theme: _TBD_ (Intelligent Experiences / Spatial Experiences / Human-Centric Technology)
- Platform capability used: _TBD_

## Requirements

- DevEco Studio with the region set to China, so phone emulators are available
- Compatible SDK **API 20** (6.0.0), Compile SDK **API 23**, Target SDK **API 24**
- Emulator: _TBD (device and image version)_

## Setup, build, install and launch

_TBD: exact commands (`hvigorw` / `devecocli` / `hdc install`), signing steps and how to launch the app._

## Architecture

_TBD: components, data flow, and the platform APIs used._

## Demo

_TBD: link to the recording._

## Tests

_TBD._

## Submission checklist

- [ ] Public repository (currently private — make it public before submission)
- [ ] Reproducible setup, build, installation and launch instructions
- [ ] Working `.hap` package (attached to a release)
- [ ] Short demo recording
- [ ] Architecture and implementation description
- [ ] [`AI_WORKFLOW.md`](AI_WORKFLOW.md)
- [ ] AI integration documentation, if the app has AI features

## Repository layout

| Path | Contents |
| --- | --- |
| `AGENTS.md` (+ `CLAUDE.md`, `GEMINI.md`) | Guidance for coding agents |
| `HACKATHON_BRIEF.md` | Product brief |
| `AI_WORKFLOW.md` | Required disclosure of AI tool usage |
| `hackathon-resources/` | `devecocli` reference and emulator capabilities |
| `.claude/skills/` | OpenHarmony / ArkTS agent skills from the organizers' starter kit |

## Generating the app project

Create the project in DevEco Studio using **Hackathon Template** (or Empty Ability): Phone, Compatible SDK 6.0.0 (API 20). Put it at the root of this repository, keeping the existing files.
