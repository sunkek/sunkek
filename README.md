## Nikita Zotov

Back-end software engineer since 2021. I build small, explicit Go libraries with zero external dependencies — and the infrastructure components around them.

Based in Armenia.

---

### What I work on

I design and maintain an open-source ecosystem for running Go services:

- **[samsara](https://github.com/sunkek/samsara)** — a small, explicit lifecycle runtime for Go services. Coordinates startup, health monitoring, graceful shutdown, and orchestrator integration, with zero external dependencies.
- **[samsara-components](https://github.com/sunkek/samsara-components)** — production-ready infrastructure components for samsara: Fiber, gRPC, PostgreSQL, Redis, RabbitMQ, and S3, each following one consistent lifecycle pattern.
- **[mishap](https://github.com/sunkek/mishap)** — a small, explicit typed error-code package for Go, with zero external dependencies.

And two projects that take a different shape:

- **[Vitae Viscera](https://vitae-viscera.suncake.xyz)** — an asynchronous biopunk colony sim, and where samsara runs in production. You grow a living flesh-ecosystem: feed it, spawn creature-drones, send them on missions, and mutate what comes back. A Go backend — a domain per feature, argon2id passwords with rotating refresh tokens, and an event log stored as a recipe and rendered in the reader's own language — behind a React SPA on PostgreSQL. A solo project, currently in closed alpha: the source is private, but it is live and playable by invite at [vitae-viscera.suncake.xyz](https://vitae-viscera.suncake.xyz).
- **[noir-code](https://github.com/sunkek/noir-code)** — a QR-like code rendered as a hand-inked noir art piece. It encodes text into a halftone cityscape and reads it back from a photo, using grayscale tonal channels and Reed–Solomon error correction. Go gateway, Python computer-vision sidecar, React frontend. Live at [noir-code.suncake.xyz](https://noir-code.suncake.xyz).

---

### How I build

- Idiomatic Go with small, explicit APIs and no unnecessary dependencies
- One consistent architecture across components, applied the same way everywhere
- Race-clean test suites, with integration tests run against real infrastructure in Docker
- CI on GitHub Actions: pinned action versions, separate unit and integration jobs, race detector enforced

---

### Tech

**Primary:** Go
**Infrastructure:** PostgreSQL · Redis · RabbitMQ · S3 · gRPC · Fiber · Docker · Kubernetes · GitHub Actions

---

### Elsewhere

- Website — [suncake.xyz](https://suncake.xyz)
- LinkedIn — [Nikita Zotov](https://www.linkedin.com/in/nikita-zotov-64a98613a)
- Upwork — [Nikita Zotov](https://www.upwork.com/freelancers/~01bf31a95981a5b512)
