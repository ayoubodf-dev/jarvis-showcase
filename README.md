# JARVIS Local Assistant

JARVIS is a local-first personal assistant combining voice interaction, system
automation, live information panels, and privacy-conscious AI routing.

![JARVIS live command demo](docs/images/demo.png)

## Highlights

- Voice and text command channel
- Local system controls and telemetry
- FastAPI service with a web and Android client
- Local-model support with optional cloud providers
- Reminders, weather, prayer times, market data, and activity feed

## Architecture

```mermaid
flowchart LR
    UI["Desktop and Android clients"] --> API["Private FastAPI core"]
    API --> Router["Safety and intent router"]
    Router --> Local["Local tools and automation"]
    Router --> Model["Local or optional cloud AI"]
    API --> Data["Weather, reminders, and live panels"]
```

## Source availability

The production implementation and automation logic are private and proprietary.
This public repository is a source-free product showcase.

Copyright © 2026 Ayoub Odf. All rights reserved.
