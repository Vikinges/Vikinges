## Vladimir Linartas

**Embedded & IoT firmware engineer.** I build the whole path — from a bare microcontroller to a running cloud backend — and I ship it as a product, not a prototype.

Based in Germany. Founder of [LinArt](https://linart.club), a self-hosted IoT platform running in production.

> ### What you will find here
>
> Only what is open — and that is a small slice of the work. Almost everything I build now lives in a **private GitLab**, which also serves as the OTA release source for the deployed device fleet: the LinArt platform, the gateway and sensor firmware, the mobile client and the backend. This profile is a sample, not a portfolio.
>
> I am glad to walk through the private code and the architecture in a conversation — just ask.

---

### What I do

- **Firmware in C / C++** — ESP32 (ESP-IDF, C3/C5/C6), STM32, STM8, nRF52, RP2040. Drivers written from datasheets, FreeRTOS, hard RAM budgets.
- **Radio & connectivity** — BLE (including a battery-BMS driver written from scratch), LoRa and mesh, Wi-Fi, MQTT/MQTTS over TLS, GNSS.
- **Device lifecycle** — OTA with staged rollout and rollback, git tag to CI to OTA, provisioning, fleet telemetry and diagnostics over a constrained uplink.
- **Hardware** — schematic design and board bring-up in Altium, RF sanity checks, oscilloscope, logic analyser, JTAG/SWD.
- **Everything above the device** — Python, Node.js, TypeScript, React dashboards, REST APIs, self-hosted SSO/IdP with 2FA, Linux and Proxmox infrastructure.

### LinArt — self-hosted IoT platform

A full IoT ecosystem I designed, built and operate on my own infrastructure in Germany: own ESP32 sensor and gateway hardware, live telemetry, floor-plan visualisation, analytics, alerting, automations, an in-house identity provider, and integrations with Solis inverters, Shelly devices and third-party BMS.

### Selected public work

- [social-stats-display](https://github.com/Vikinges/social-stats-display) — ESP32 social-statistics counter: OLED display, web interface, OTA updates.
- [STM8_PWM_Controller](https://github.com/Vikinges/STM8_PWM_Controller) — PWM fan controller on an STM8S103F3P6.
- [Cube_HAL_stm32f072rbt6](https://github.com/Vikinges/Cube_HAL_stm32f072rbt6) — STM32 HAL working examples.
- [linmain](https://github.com/Vikinges/linmain) — linart.club web hub and microservices.
- [PDF_generator](https://github.com/Vikinges/PDF_generator) — PDF generator for service technicians.

### Elsewhere

- Website — [linart.club](https://linart.club)
- LinkedIn — [vladimir-linartas](https://www.linkedin.com/in/vladimir-linartas)

Languages: English, German, Russian, Lithuanian, Norwegian.
