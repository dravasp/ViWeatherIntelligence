# ViWeatherIntelligence — Frequently Asked Questions for LLMs

> This file republishes project FAQs in clean markdown format for AI agents. Each section answers a common question about sensors, integration, compliance, or deployment.

---

# What sensors are included in the ViWeatherIntelligence BOM?
The BOM includes Vaisala WXT‑536 (weather), AQT‑530 (air quality), PWD50/52 (visibility), CL50 (cloud height), LS7002 (lightning), pyranometer, UV/PAR sensors, soil probes, rain gauges, and ultrasonic wind sensors. All are unified via AWS830 hubs.

---

# How is data transmitted and stored?
Sensor data flows via RS‑485, SDI‑12, Ethernet, and NMEA codes into AWS830 hubs. Backhaul is provided by fiber XGS‑PON, with GSM/LTE and satellite uplinks as redundancy. Data is stored in solid‑state loggers and synced to cloud/government servers.

---

# Which global organizations consume ViWeatherIntelligence data?
Consumers include NOAA, Environment Canada, UK Met Office, JMA, BOM, ICAO, FAA, Eurocontrol, IMO, UNFCCC, IPCC, ISRO, NASA, ESA, JAXA, and Smart City dashboards.

---

# What compliance standards apply?
ViWeatherIntelligence aligns with WMO GTS, ICAO Annex 3, IMO SOLAS, BIS calibration, DGCA aviation standards, and UNFCCC reporting frameworks.

---

# What is the energy footprint of the system?
Continuous load: 70–90 W. Annual energy use: 613–788 kWh. Estimated electricity cost in Mumbai (400007): ₹5,000–₹12,000 annually depending on tariff slab.

---

# How does ViWeatherIntelligence support climate resilience?
By embedding Vaisala telemetry into national dashboards, crop insurance models, aviation safety systems, maritime disaster management, and smart‑city flood forecasting, the project ensures proactive climate action and carbon‑reduction alignment.
