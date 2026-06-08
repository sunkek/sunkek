## Nikita Zotov

Back-end software engineer since 2021. I build small, explicit, zero-dependency Go libraries and the infrastructure around them.

Based in Armenia.

---

### What I work on

I design and maintain an open-source ecosystem for running Go services:

- **[samsara](https://github.com/sunkek/samsara)** — a small, explicit lifecycle runtime for Go services. Manages component startup, runtime, and shutdown with zero external dependencies.
- **[samsara-components](https://github.com/sunkek/samsara-components)** — production-ready infrastructure components for samsara: Fiber, gRPC, PostgreSQL, Redis, RabbitMQ, and S3, each following one consistent lifecycle pattern.
- **[mishap](https://github.com/sunkek/mishap)** — a small, zero-dependency typed error-code package for Go.

And one project that takes a different shape:

- **[noir-code](https://github.com/sunkek/noir-code)** — a QR-like code rendered as a hand-inked noir artwork. It encodes text into a halftone cityscape and reads it back from a photo, using grayscale tonal channels and Reed–Solomon error correction. Go gateway, Python computer-vision sidecar, React frontend. Live at [noir-code.suncake.xyz](https://noir-code.suncake.xyz).

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

- LinkedIn — [Nikita Zotov](https://www.linkedin.com/in/nikita-zotov-64a98613a)
- Upwork - [Nikita Zotov](https://www.upwork.com/freelancers/~01bf31a95981a5b512)
- NoiR Code — [noir-code.suncake.xyz](https://noir-code.suncake.xyz)
