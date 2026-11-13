<h1>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/openccu-lite/openccu-lite/main/docs/images/openccu-lite-dark@2x.png">
    <img src="https://raw.githubusercontent.com/openccu-lite/openccu-lite/main/docs/images/openccu-lite-light@2x.png" alt="openccu-lite" width="428">
  </picture>
</h1>

**openccu-lite** is a firmware for Homematic central units, a fork of the [OpenCCU project](https://github.com/OpenCCU/OpenCCU),
for everyone who runs their automation elsewhere (Home Assistant, ioBroker, Node-RED, …) and wants one thing above all
from the central unit: that it connects the Homematic devices reliably. It has no ReGaHSS and no CCU WebUI; a new web
interface, addons and open APIs take their place.

## The firmware

| Repository | |
| --- | --- |
| [openccu-lite](https://github.com/openccu-lite/openccu-lite) | the firmware: images, updates, documentation and issues |
| [occulited](https://github.com/openccu-lite/occulited) | the system service: web interface, metadata, sessions, system administration, addon management |
| [OpenCCU-Base](https://github.com/openccu-lite/OpenCCU-Base) | fork of OpenCCU-Base: the Homematic interface processes (rfd, hs485d, multimacd, HMIPServer) |
| [piVCCU](https://github.com/openccu-lite/piVCCU) | fork of Alexander Reinert's piVCCU: the radio module drivers |

## Addons

| Repository | |
| --- | --- |
| [lite-addon-forwarder](https://github.com/openccu-lite/lite-addon-forwarder) | forwards Homematic events to InfluxDB, webhooks and more |
| [lite-addon-nut](https://github.com/openccu-lite/lite-addon-nut) | Network UPS Tools client: a clean shutdown before the battery runs out |
| [lite-addon-snmp](https://github.com/openccu-lite/lite-addon-snmp) | SNMP agent: Linux MIBs and the Homematic side, read-only, SNMPv3 |
| [lite-addon-tailscale](https://github.com/openccu-lite/lite-addon-tailscale) | Tailscale remote access to the web interface |
| [lite-addon-wireguard](https://github.com/openccu-lite/lite-addon-wireguard) | WireGuard remote access to the web interface and the APIs |
| [lite-addon-tools](https://github.com/openccu-lite/lite-addon-tools) | troubleshooting tools over ssh: tcpdump, strace, nmap, htop and more |

## Tools and libraries

| Repository | |
| --- | --- |
| [occulite-client](https://github.com/openccu-lite/occulite-client) | the client library for openccu-lite's APIs (npm) |
| [occulite-backup](https://github.com/openccu-lite/occulite-backup) | downloads and checks the backups of openccu-lite systems, one shell script |
| [hm-radio-simulator](https://github.com/openccu-lite/hm-radio-simulator) | a simulated radio module and LAN gateway for black-box tests of rfd and hs485d |

## Thanks

openccu-lite builds on the work of the [OpenCCU project](https://github.com/OpenCCU), of eQ-3, who publish the
Homematic software, and of [Alexander Reinert](https://github.com/alexreinert), whose piVCCU drivers connect the radio
modules.

Questions, bugs and wishes: [openccu-lite's issues](https://github.com/openccu-lite/openccu-lite/issues).
