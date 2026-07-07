# What is HADR?

**HADR** stands for **Humanitarian Assistance and Disaster Response** — the coordinated
effort to help people affected by natural or human-made disasters.

## In plain terms

When a disaster strikes — an earthquake, flood, cyclone, wildfire, or conflict — HADR is
everything that happens to save lives and reduce suffering:

- **Humanitarian Assistance** — providing food, water, shelter, medical care and other
  essentials to people in need.
- **Disaster Response** — the immediate actions taken to protect people and property once a
  disaster occurs, from search-and-rescue to restoring critical services.

## Why it matters here

Effective HADR depends on knowing, quickly and accurately:

- **What happened** — the type and cause of the event
- **Where** — the location and area affected
- **How bad** — the severity and scale
- **Who is affected** — the people and communities impacted

The faster and clearer that picture is, the sooner responders can act. This project builds a
monitoring agent that watches live disaster feeds (GDACS, USGS, ReliefWeb), filters out the
noise, and turns raw alerts into a concise daily situation report.

## Common feeds and sources

- **GDACS** — Global Disaster Alert and Coordination System
- **USGS** — earthquake data from the U.S. Geological Survey
- **ReliefWeb** — humanitarian news and reports curated by the UN OCHA

See the [`feeds/`](../feeds) directory for how each source is used.
