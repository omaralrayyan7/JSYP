# JoRide at JSYP 2025

Pitch deck and competition documentation for **JoRide** — a self-service, IoT-integrated car-rental platform — presented at the **Jordan Students and Young Professionals Congress (JSYP 2025)**.

> JSYP is one of Jordan's premier innovation events, connecting students, researchers, and entrepreneurs to showcase technology solutions to real-world problems.

## What Is JoRide?

JoRide is an end-to-end smart transportation platform built for the Jordanian market. It connects users with a vehicle fleet through a Flutter mobile app, an ASP.NET Core REST backend, Firestore data persistence, and in-vehicle GPS/IoT hardware (Teltonika FMC130 with CAN bus relay) for real-time tracking and remote keyless access.

| Layer | Technology |
|---|---|
| Mobile App | Flutter (Dart) — AR/EN, dark/light |
| Backend API | ASP.NET Core 8 + JWT |
| Database | Firebase Firestore |
| GPS / IoT | Teltonika FMC130 + CAN bus relay |
| Real-time | SignalR push notifications |

## JSYP Pitch Summary

| Aspect | Details |
|---|---|
| Problem | Fragmented, cash-only, ride-hailing with no self-service option |
| Solution | Self-service app: browse → book → digital key → drive → return |
| Differentiator | In-vehicle IoT hardware for real keyless access (not just ride-hailing) |
| Business Model | Per-minute / hourly / daily pricing + corporate fleet leases |
| Traction | University incubation, pitched at Fintech Forum, JSYP, NTP competitions |

## Repositories

| Repo | Description |
|---|---|
| [joride-backend](https://github.com/omaralrayyan7/joride-backend) | ASP.NET Core 8 REST API |
| [joride-frontend](https://github.com/omaralrayyan7/joride-frontend) | Flutter mobile + web app |

## License

[MIT](LICENSE)
