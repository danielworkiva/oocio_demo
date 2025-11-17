# OoCIO Demo Repository

This repository contains the OoCIO demo pages and supporting files used to illustrate UI flows and simulated external AI calls. 

> **Status:** demo / proof of concept — not production-ready.

---

## Files overview

### `OoCIO Demo - Mocked Mobile.html`
Mobile-mock version of the OoCIO demo. This page simulates a mobile user flow and uses mocked data to emulate the app behavior on smaller screens. Works well in a mobile.

### `OoCIO Demo.html`
Primary demo page for the OoCIO demo flow. 100% MOCKED DATA for all steps of the demo flow. 

### `OoCIO External AI Call.html`
Same code as the OoCIO demo.html file. The only difference: this file replaces the "INVOKE STRATEGIC SENTINEL AI" mocked call by a real GROC call, receiving answers in real time from GROC. It uses mocked data retrieved from Workiva to make the GROC call. It also needs a proxy and an orchestrator (i.e: Pipedream).

### `index.html`
File created to redirect calls to the OoCIO Demo - Mocked Mobile.html file. We are using GitHub Pages to host calls from mobile devices. 

---
