<p align="center">
  <img src="assets/wx-alert-logo.svg" alt="WX Alert Service" width="640">
</p>

<p align="center">
  <em>Automated aeronautical weather alerts — a lightweight decision-support tool for pilots. Free of charge.</em>
</p>

<p align="center">
  <a href="./LICENSE"><img alt="License" src="https://img.shields.io/badge/license-proprietary-2F3842"></a>
  <img alt="Access" src="https://img.shields.io/badge/access-free-3F7D58">
  <img alt="Scope" src="https://img.shields.io/badge/decision--support-only-E3A21A">
</p>

---

WX Alert Service watches your planned flights and warns you, ahead of time, when the weather at a departure, destination, or alternate aerodrome may make it unusable. It does the tedious cross-checking automatically so you can focus on the decision — which always remains yours.

> ⚠️ **Decision-support only.** WX Alert Service never authorises or refuses a flight. It flags risk and surfaces the relevant weather; the final go / no-go decision rests entirely with the pilot in command.

---

## What it does

- **Reads your scheduled flights automatically** and checks the aerodromes involved without any manual input.
- **Pulls the relevant terminal forecasts (TAF)** for departure, destination, and alternate aerodromes.
- **Evaluates each aerodrome against clear operational limits** — visibility, ceiling, wind (including gusts, crosswind, and tailwind) — within a time window around your planned times.
- **Assigns a simple status** to each leg so you can read the situation at a glance.
- **Sends you an alert** as soon as a forecast suggests an aerodrome may not be usable.
- **Gives early long-range advisories** (day-before and two-days-before) when fog, mist, or strong wind is expected at departure or destination, so a marginal day never takes you by surprise.

## Status at a glance

Each evaluated aerodrome is reported with a plain, unambiguous status:

| Status | Meaning |
|-----------|--------------------------------------------------|
| 🟢 **GO** | Forecast within limits for the evaluated window. |
| 🟡 **MARGINAL** | Conditions close to the limits — worth a closer look. |
| 🔴 **NO-GO** | Forecast below the retained minima. |

## How the checks work

- **Time windows.** Each aerodrome is assessed over a window around your planned departure and arrival, so a forecast trend that just misses your exact ETA is still caught.
- **Minima adapted to the aerodrome.** The thresholds applied depend on the type of approach available at each field, up to CAT I capability.
- **Conservative by design.** Transient or low-probability improvements in a forecast never clear an alert on their own — a warning stands until the forecast genuinely supports the flight.
- **Alternates handled explicitly.** Departure, destination, and alternate aerodromes are each evaluated with limits appropriate to their role.

## Notifications

- **Email** — the default channel.
- **WhatsApp** — available as an option.

Alerts reach you where you already look, without a new app to install or a dashboard to keep open.

---

## Getting access

WX Alert Service is **free**. Access is granted individually, on request.

📧 **To request access, contact us by email:** *[contact@wx-alert.com]*

Please include a short note about your operation (aircraft, typical aerodromes, and whether you use a compatible flight-planning setup) so access can be configured for you.

---

## Good to know

- WX Alert Service is a small, focused project — deliberately lightweight and easy to run.
- It complements, and never replaces, your own pre-flight weather briefing and the official information sources you are required to consult.
- Forecast data is drawn from established aviation and meteorological sources; as with any forecast, actual conditions can differ.

---

*WX Alert Service — helping you see the marginal day coming.*
