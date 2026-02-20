# OHC SAP Demo — Static Version

**Red Hat OpenShift + SAP Business Technology Platform Reference Architecture**

## Overview

This is a static GitHub Pages deployment of the OpenShift Hybrid Cloud (OHC) SAP Demo platform. This version runs entirely in the browser with simulated data, requiring no backend connectivity.

## Live Demo

**GitHub Pages:** https://jodonnel.github.io/ohc-demo-static/

## Features

- **Live Dashboard** — Real-time event monitoring with class visualization
- **Presenter Views** — Multiple industry-specific demonstration scenarios
- **Interactive QR** — Audience participation interface
- **Scenario Library** — PI/PO migration, MII/DMC, Shop Floor, Utilities, Rail, GRC, and more

## Architecture

The live version runs on:
- Red Hat OpenShift 4.x
- Python 3.12 (Flask + gunicorn)
- Redis 7.x (pub/sub + persistence)
- nginx (reverse proxy)
- Server-Sent Events (SSE) for real-time updates

This static version:
- Pure HTML/CSS/JavaScript
- Local simulation mode (no backend required)
- GitHub Pages hosting
- Offline-capable

## Use Cases

- **SAP PI/PO Migration** → SAP Integration Suite
- **SAP MII/ME Migration** → SAP Digital Manufacturing Cloud
- **Connected Vehicles** → SAP BTP (Mercedes-Benz integration)
- **Manufacturing IoT** → SAP S/4HANA
- **Facility Management** → SAP Asset Intelligence Network
- **Utilities OT** → SAP Enterprise Asset Management

## Demonstration Venues

- SAP Insider Las Vegas (March 2026)
- Red Hat Summit (2026)
- SAP Customer Briefings

## Contact

**Jim O'Donnell**
Red Hat / SAP Solutions Architecture
Email: jodonnel@redhat.com

---

**Note:** This is a fallback static deployment. The live OpenShift cluster provides full backend integration with SAP BTP, Event Mesh, and Integration Suite.

**Repository:** https://github.com/jodonnel/ohc-demo-static
**License:** Reference Architecture (Red Hat + SAP collaboration)
