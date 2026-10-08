### Hi, I'm Rishabh

Computer Engineering student at the University of Waterloo (class of 2028). I like building real-time systems and running them on infrastructure I set up myself.

Previously a software developer at Doctalk (Jan–Apr 2026), where I moved our API and WebSocket services from Cloud Run to Terraform-managed GCE instance groups, and at ccLeaf (summer 2025), building search for a music licensing platform on ElasticSearch and MongoDB.

**Projects**

- **[LeetBattle](https://github.com/rishabhvenu/LeetBattle)**: real-time 1v1 coding battles with ELO matchmaking. Colyseus over WebSockets, self-hosted Judge0 on k3s with custom ARM64 images, Argo CD GitOps, a 6-node Redis cluster, and a Next.js frontend on Lambda + CloudFront via CDK. An OpenAI pipeline writes problems and reference solutions in four languages, and every passing submission must also clear a time-complexity check.
- **[AbilityEngine](https://github.com/rishabhvenu/abilityengine)**: a modular Minecraft plugin framework for Paper 1.21+. Abilities can be written in Java, JavaScript, or YAML.
- **[Intraday Market Factor Dashboard](https://github.com/rishabhvenu/intraday-market-factor-dashboard)**: Next.js dashboard that pulls intraday OHLC data from Finnhub, runs PCA to find hidden factors, and simulates simple factor-based trading strategies.
- **[Athar](https://github.com/rishabhvenu/athar)** (in progress): a Quran reflection PWA on Next.js and Supabase, with pgvector search over your own notes.

**Open source**

Fixes merged upstream:

- **[argocd-image-updater](https://github.com/argoproj-labs/argocd-image-updater/pulls?q=is%3Apr+author%3Arishabhvenu+is%3Amerged)**: a data race on the shared Argo CD client ([#1831](https://github.com/argoproj-labs/argocd-image-updater/pull/1831)), retries for registry requests throttled with 429 ([#1847](https://github.com/argoproj-labs/argocd-image-updater/pull/1847)), SCM API calls that ignored the Argo CD TLS certificate store ([#1832](https://github.com/argoproj-labs/argocd-image-updater/pull/1832)), and a racy webhook test ([#1830](https://github.com/argoproj-labs/argocd-image-updater/pull/1830)).
- **[opennextjs-aws](https://github.com/opennextjs/opennextjs-aws/pull/1268)**: overlapping requests could be handed each other's `waitUntil` through the Next.js request context.
- **[ioredis](https://github.com/redis/ioredis/pull/2218)**: after a queue flush, `exec()` put its own error inside that error's `previousErrors`, which made it circular.
- **[helm-diff](https://github.com/databus23/helm-diff/pull/1086)**: `--reuse-values` failed on a release that was not installed yet.
- **Minecraft server tooling**: [Grim](https://github.com/GrimAnticheat/Grim/pulls?q=is%3Apr+author%3Arishabhvenu+is%3Amerged) anticheat false positives, [spark](https://github.com/lucko/spark/pull/592), [LuckPerms](https://github.com/LuckPerms/LuckPerms/pull/4325) and [AuthMe](https://github.com/AuthMe/AuthMeReloaded/pull/3160).

**Tools I use most:** TypeScript, Java, Python, React/Next.js, PostgreSQL, MongoDB, Redis, Docker, Kubernetes, Terraform, AWS, GCP

[rishabhvenu.xyz](https://rishabhvenu.xyz) · [LinkedIn](https://linkedin.com/in/rishabh-venu)
