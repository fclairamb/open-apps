---
submittedBy: fclairamb
name: SolidPing
repoUrl: https://github.com/fclairamb/solidping
projectType: real-app
category: developer-tools
stack: react
summary: SolidPing is an uptime and synthetic monitoring server written in Go with a React dashboard.
  It runs 40+ check types (HTTP, TCP, DNS, TLS expiry, databases, headless browser, heartbeats),
  opens incidents, alerts on Slack, Discord, email or webhooks, and publishes status pages.
description: SolidPing is an AGPL-3.0 uptime monitor that runs as a single Go binary or Docker image,
  on SQLite by default, with a hosted free plan.
sourceDescription: "Distributed, self-hostable uptime monitoring: 40 check types, multi-region workers,
  private agents, status pages, incidents and on-call escalation — in a single Go binary."
platforms:
  - web
  - linux
  - macos
  - windows
licenses:
  - agpl-3.0
links:
  github: https://github.com/fclairamb/solidping
  website: https://www.solidping.io
  docs: https://docs.solidping.io
  download: https://github.com/fclairamb/solidping/releases/latest
distribution:
  channels:
    - type: self-host
      label: Docker image (ghcr.io/fclairamb/solidping)
      url: https://github.com/fclairamb/solidping/pkgs/container/solidping
      verified: true
    - type: github-releases
      label: Binaries for Linux, macOS and Windows
      url: https://github.com/fclairamb/solidping/releases/latest
      verified: true
    - type: web-app
      label: Hosted version with a free plan
      url: https://www.solidping.io
      verified: true
tags:
  - self-hosted
  - open-source
  - web-app
  - developer-tools
bestFor:
  - Watching websites, APIs, databases and TLS certificates and getting alerted when they fail.
  - Publishing a status page for users or a team.
  - Running checks from inside a private network with an agent that connects out.
whyListed:
  - The whole server is one Go binary on SQLite, with Postgres optional.
  - Checks go beyond HTTP, with databases, queues, DNS, SSH and a headless browser.
seo:
  title: SolidPing – Open Source Uptime Monitoring and Status Pages
addedAt: 2026-10-12
---
## Why it's listed

SolidPing is a self-hostable uptime monitor with 40+ check types, incidents with on-call escalation, and status pages. It is AGPL-3.0, runs as a single Go binary or Docker image, and also has a hosted free plan.
