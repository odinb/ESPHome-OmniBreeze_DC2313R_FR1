# ESPHome OmniBreeze DC2313R FR-1 V1.0.

For hardware used, see here: <br /> [Costco OmniBreeze](https://www.costco.com/p/-/omnibreeze-tower-fan-with-internal-oscillation-and-wi-fi/4000230757) <br />

These fans currently come in 2 variants, based around the Beken chip FCM242D (BK7238).
They can be run with an online plugin like the Landbook-HA: https://github.com/zackwag/landbook-ha

They can also be flashed to run fiully offline. For this, I have found 4 projects, 2 for the old fan, and 2 for the newer.

Costco OmniBreeze DC2205-WiFi V1.3 (2023 batch) ESPHome: https://github.com/phdindota/Omnibreeze-esphome

Costco OmniBreeze DC2205-WiFi V1.3 (2023 batch) OpenBeken: https://github.com/surshis/OpenBekenCostcoFan

Costco OmniBreeze DC2313R FR-1 V1.0 (2025 batch) OpenBeken: https://github.com/ToTheLastByte/OpenBekenCostcoFan2025-

Costco OmniBreeze DC2313R FR-1 V1.0 (2025 batch) TinyLibre ESPHome: https://github.com/MrNRod/OmniBreeze-Fan-ESPHome-LibreTiny

Local control is much snappier than any of the cloud-integrations, and the TinyLibre implementation above works great!

For the TinyLibre implementation above, I have chosen to modify the yaml a bit, see file above.

When flashing using the ESPHome python version from command-line, it can be tricky to get the flash to kick in, but just be patient/stubborn, it will eventually work!


This is run with Home-assistant: https://www.home-assistant.io/ <br />
and the ESPHome integration: https://esphome.io/
