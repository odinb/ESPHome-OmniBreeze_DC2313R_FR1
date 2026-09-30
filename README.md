# ESPHome OmniBreeze DC2313R FR-1 V1.0.

Hardware: See the {"fallbackMarkdown":"Costco OmniBreeze Tower Fan
","reference":{"matched_text":"","prefix":null,"start_idx":149,"end_idx":277,"safe_urls":[],"refs":[],"alt":"Costco OmniBreeze Tower Fan
","prompt_text":"Costco OmniBreeze Tower Fan
","type":"url","title":"Costco OmniBreeze Tower Fan","logo":null,"item":{"title":"Costco OmniBreeze Tower Fan","url":"https://www.costco.com/p/-/omnibreeze-tower-fan-with-internal-oscillation-and-wi-fi/4000230757?utm_source=chatgpt.com","attribution":"costco.com","pub_date":null,"snippet":null,"attribution_segments":null,"supporting_websites":null,"refs":[],"hue":null,"attributions":null},"layout":null},"showLoginRequiredCard":false}.

Owner’s Manual: See the {"fallbackMarkdown":"OmniBreeze Tower Fan Owner’s Manual
","reference":{"matched_text":"","prefix":null,"start_idx":308,"end_idx":437,"safe_urls":[],"refs":[],"alt":"OmniBreeze Tower Fan Owner’s Manual
","prompt_text":"OmniBreeze Tower Fan Owner’s Manual
","type":"url","title":"OmniBreeze Tower Fan Owner’s Manual","logo":null,"item":{"title":"OmniBreeze Tower Fan Owner’s Manual","url":"https://manuals.plus/m/f299da9d8b7156e83251e5034d1b58032552d9876ac7544473ea7cca1ee75738?utm_source=chatgpt.com","attribution":"manuals.plus","pub_date":null,"snippet":null,"attribution_segments":null,"supporting_websites":null,"refs":[],"hue":null,"attributions":null},"layout":null},"showLoginRequiredCard":false}.

These fans currently come in 2 variants, based around the Beken chip FCM242D (BK7238).
They can be run with an online plugin like the Landbook-HA: https://github.com/zackwag/landbook-ha

They can also be flashed to run filly offline. For this, I have found 4 projects, 2 for the old fan, and 2 for the new.<br />
This is the one I picked:

Costco OmniBreeze DC2313R FR-1 V1.0 (2025 batch) TinyLibre ESPHome: https://github.com/MrNRod/OmniBreeze-Fan-ESPHome-LibreTiny
<br />
<br />
<br />
Local control is much snappier than any of the cloud-integrations, and the TinyLibre implementation is my chosen implementation.<br />
It works great! Thanks MrNRod!

For the TinyLibre implementation above, I have chosen to modify the yaml a bit, see attached yaml-file above.

When flashing using the ESPHome python version from command-line, it can be tricky to get the flash to kick in, but just be patient/stubborn, it will eventually work!


This is run with Home-assistant: https://www.home-assistant.io/ <br />
and the ESPHome integration: https://esphome.io/
<br />
<br />
Other variants/implementations (references):<br />

Costco OmniBreeze DC2205-WiFi V1.3 (2023 batch) ESPHome: https://github.com/phdindota/Omnibreeze-esphome

Costco OmniBreeze DC2205-WiFi V1.3 (2023 batch) OpenBeken: https://github.com/surshis/OpenBekenCostcoFan

Costco OmniBreeze DC2313R FR-1 V1.0 (2025 batch) OpenBeken: https://github.com/ToTheLastByte/OpenBekenCostcoFan2025-
