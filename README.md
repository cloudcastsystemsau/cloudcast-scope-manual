# CloudCast Scope — user manual

The published manual for **CloudCast Scope**, a broadcast signal analyser.

**Read it: https://cloudcastsystemsau.github.io/cloudcast-scope-manual/**

It covers:

- **NDI®** — picture, waveform, RGB parade, vectorscope, luma histogram,
  per-channel metering, EBU R128 loudness, timing, frame-arrival analysis and
  SCTE-104 cues (§1–§9).
- **Audio over IP** — AES67 and Livewire streams read off the wire, PTP,
  the Livewire clocks measured against the grandmaster, advertisements,
  multicast GPIO and SAP/SDP announcements (§10).
- **HLS** — the manifest checked against the media it describes, SCTE-35 ad
  breaks and why a consumer fires twice on one, decoded loudness (§11).
- **SRT** — packet-level link analysis from a capture: the shape of the loss,
  whether retransmissions arrived in time to be used, and whether the sender
  or the path was at fault (§12).
- **The API, MCP and the web UI** — every analyser as an HTTP call with an
  OpenAPI document, the same tools available to an agent over MCP, and
  drag-and-drop dashboards in a browser (§14), including mDNS / DNS-SD
  discovery of what a VLAN announces about itself.

This repository is a published copy. The manual is written as Markdown in the
product repository and built from there; corrections are welcome as issues.

> NDI® is a registered trademark of Vizrt NDI AB. CloudCast Scope is not
> affiliated with or endorsed by Vizrt; it contains no NDI SDK code and uses
> the separately-installed NDI Runtime.

© Cloudcast Systems PTY LTD.
