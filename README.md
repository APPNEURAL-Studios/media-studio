# Media Studio

Video, audio, podcast and subtitles

Edit video with multi-track timelines, reels, webinars, and screen recordings, plus AI video generation and green-screen compositing. Produce podcasts, voice-overs, TTS, sound effects, audiobooks, and AI voice cloning.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (6):**

| Service | Status |
|---|---|
| `media-service` | New (Tier-1) |
| `publishing-service` | Core |
| `model-service` | Core |
| `agent-service` | Core |
| `asset-service` | Suggested — not yet built |
| `collaboration-service` | Suggested — not yet built |
