<h1>
  <a href="https://github.com/openccu-lite/openccu-lite">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/openccu-lite/openccu-lite/main/docs/images/openccu-lite-dark@2x.png">
      <img src="https://raw.githubusercontent.com/openccu-lite/openccu-lite/main/docs/images/openccu-lite-light@2x.png" alt="openccu-lite" width="428">
    </picture>
  </a>
</h1>

[![stable release](https://img.shields.io/github/v/release/openccu-lite/openccu-lite?label=stable)](https://github.com/openccu-lite/openccu-lite/releases/latest)

## Download: openccu-lite 1.2.1

| System | Download |
| --- | --- |
| CCU3 (Update) | [`openccu-lite-aarch64-rpi3-1.2.1-ccu3.tgz`](https://github.com/openccu-lite/openccu-lite/releases/download/v1.2.1/openccu-lite-aarch64-rpi3-1.2.1-ccu3.tgz) |
| Raspberry Pi 3 / Charly | [`openccu-lite-aarch64-rpi3-1.2.1.zip`](https://github.com/openccu-lite/openccu-lite/releases/download/v1.2.1/openccu-lite-aarch64-rpi3-1.2.1.zip) |
| Raspberry Pi 4 | [`openccu-lite-aarch64-rpi4-1.2.1.zip`](https://github.com/openccu-lite/openccu-lite/releases/download/v1.2.1/openccu-lite-aarch64-rpi4-1.2.1.zip) |
| VM (Proxmox, VirtualBox, …) | [`openccu-lite-x86_64-ova-1.2.1.ova`](https://github.com/openccu-lite/openccu-lite/releases/download/v1.2.1/openccu-lite-x86_64-ova-1.2.1.ova) |

Alle Dateien, Prüfsummen und Hinweise / all files, checksums and notes:
[Release v1.2.1](https://github.com/openccu-lite/openccu-lite/releases/tag/v1.2.1)

<a id="deutsch"></a>
**Deutsch** · [English](#english)

**[openccu-lite](https://github.com/openccu-lite/openccu-lite#readme)** ist eine Firmware für Homematic-Zentralen, ein Fork
des [OpenCCU-Projekts](https://github.com/OpenCCU/OpenCCU). Sie ist für alle gedacht, die ihre Automatisierung woanders
betreiben, etwa in Home Assistant, ioBroker oder Node-RED, und von der Zentrale vor allem eines wollen: dass sie die
Homematic-Geräte zuverlässig anbindet. Sie hat kein ReGaHSS und keine CCU-WebUI; an ihre Stelle treten eine neue
Oberfläche, Addons und offene Schnittstellen.

### Firmware

| Repository | |
| --- | --- |
| [openccu-lite](https://github.com/openccu-lite/openccu-lite) | die Firmware: Images, Updates, Dokumentation und Issues |
| [occulited](https://github.com/openccu-lite/occulited) | der Systemdienst: Oberfläche, Metadaten, Sitzungen, Systemverwaltung, Addon-Verwaltung |
| [OpenCCU-Base](https://github.com/openccu-lite/OpenCCU-Base) | Fork von OpenCCU-Base: die Schnittstellenprozesse (rfd, hs485d, multimacd, HMIPServer) |
| [piVCCU](https://github.com/openccu-lite/piVCCU) | Fork von Alexander Reinerts piVCCU: die Treiber für die Funkmodule |

### Addons

| Repository | |
| --- | --- |
| [lite-addon-forwarder](https://github.com/openccu-lite/lite-addon-forwarder) | leitet Homematic-Ereignisse an InfluxDB, Webhooks und mehr weiter |
| [lite-addon-nut](https://github.com/openccu-lite/lite-addon-nut) | Network-UPS-Tools-Client: sauber herunterfahren, bevor die USV-Batterie leer ist |
| [lite-addon-snmp](https://github.com/openccu-lite/lite-addon-snmp) | SNMP-Agent: Linux-MIBs und die Homematic-Seite, nur lesend, SNMPv3 |
| [lite-addon-tailscale](https://github.com/openccu-lite/lite-addon-tailscale) | Fernzugriff auf die Oberfläche über Tailscale |
| [lite-addon-wireguard](https://github.com/openccu-lite/lite-addon-wireguard) | Fernzugriff auf Oberfläche und Schnittstellen über WireGuard |
| [lite-addon-tools](https://github.com/openccu-lite/lite-addon-tools) | Werkzeuge zur Fehlersuche über ssh: tcpdump, strace, nmap, htop und mehr |

### Werkzeuge und Bibliotheken

| Repository | |
| --- | --- |
| [occulite-client](https://github.com/openccu-lite/occulite-client) | die Client-Bibliothek für die Schnittstellen von openccu-lite (npm) |
| [occulite-backup](https://github.com/openccu-lite/occulite-backup) | lädt und prüft die Backups von openccu-lite-Systemen, ein Shell-Skript |
| [hm-radio-simulator](https://github.com/openccu-lite/hm-radio-simulator) | simuliertes Funkmodul und LAN-Gateway für Blackbox-Tests von rfd und hs485d |

### Dank

openccu-lite baut auf der Arbeit des [OpenCCU-Projekts](https://github.com/OpenCCU) auf, auf der Homematic-Software von
eQ-3 und auf den piVCCU-Treibern von [Alexander Reinert](https://github.com/alexreinert), die die Funkmodule anbinden.

Fragen, Fehler und Wünsche: [Issues von openccu-lite](https://github.com/openccu-lite/openccu-lite/issues).

---

<a id="english"></a>
**English** · [Deutsch](#deutsch)

**[openccu-lite](https://github.com/openccu-lite/openccu-lite/blob/main/README.en.md)** is a firmware for Homematic
central units, a fork of the [OpenCCU project](https://github.com/OpenCCU/OpenCCU), for everyone who runs their
automation elsewhere (Home Assistant, ioBroker, Node-RED, …) and wants one thing above all from the central unit: that
it connects the Homematic devices reliably. It has no ReGaHSS and no CCU WebUI; a new web interface, addons and open
APIs take their place.

### The firmware

| Repository | |
| --- | --- |
| [openccu-lite](https://github.com/openccu-lite/openccu-lite) | the firmware: images, updates, documentation and issues |
| [occulited](https://github.com/openccu-lite/occulited) | the system service: web interface, metadata, sessions, system administration, addon management |
| [OpenCCU-Base](https://github.com/openccu-lite/OpenCCU-Base) | fork of OpenCCU-Base: the interface processes (rfd, hs485d, multimacd, HMIPServer) |
| [piVCCU](https://github.com/openccu-lite/piVCCU) | fork of Alexander Reinert's piVCCU: the radio module drivers |

### Addons

| Repository | |
| --- | --- |
| [lite-addon-forwarder](https://github.com/openccu-lite/lite-addon-forwarder) | forwards Homematic events to InfluxDB, webhooks and more |
| [lite-addon-nut](https://github.com/openccu-lite/lite-addon-nut) | Network UPS Tools client: a clean shutdown before the battery runs out |
| [lite-addon-snmp](https://github.com/openccu-lite/lite-addon-snmp) | SNMP agent: Linux MIBs and the Homematic side, read-only, SNMPv3 |
| [lite-addon-tailscale](https://github.com/openccu-lite/lite-addon-tailscale) | remote access to the web interface through Tailscale |
| [lite-addon-wireguard](https://github.com/openccu-lite/lite-addon-wireguard) | remote access to the web interface and the APIs through WireGuard |
| [lite-addon-tools](https://github.com/openccu-lite/lite-addon-tools) | troubleshooting tools over ssh: tcpdump, strace, nmap, htop and more |

### Tools and libraries

| Repository | |
| --- | --- |
| [occulite-client](https://github.com/openccu-lite/occulite-client) | the client library for openccu-lite's APIs (npm) |
| [occulite-backup](https://github.com/openccu-lite/occulite-backup) | downloads and checks the backups of openccu-lite systems, one shell script |
| [hm-radio-simulator](https://github.com/openccu-lite/hm-radio-simulator) | a simulated radio module and LAN gateway for black-box tests of rfd and hs485d |

### Thanks

openccu-lite builds on the work of the [OpenCCU project](https://github.com/OpenCCU), on eQ-3's Homematic software and
on [Alexander Reinert](https://github.com/alexreinert)'s piVCCU drivers, which connect the radio modules.

Questions, bugs and wishes: [openccu-lite's issues](https://github.com/openccu-lite/openccu-lite/issues).
