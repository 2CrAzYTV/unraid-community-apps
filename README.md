# 2CrAzYTV Unraid Community Apps

This repository is the central Unraid Community Applications source maintained by **2CrAzYTV** and is the canonical CA repository for all listed apps.

It intentionally contains only Community Apps metadata and templates. The application source code, documentation, support issues and container images remain in the individual project repositories.

## Published applications

| Application | Source repository | Container image |
| --- | --- | --- |
| Multi-Coin Paper Daytrader | `2CrAzYTV/multi-coin-paper-daytrader` | `ghcr.io/2crazytv/multi-coin-paper-daytrader:latest` |
| Alarm-HUB | `2CrAzYTV/Alarm-HUB` | `ghcr.io/2crazytv/alarm-hub:latest` |
| WebComm Calendar Sync | `2CrAzYTV/webcomm-calendar-sync` | `ghcr.io/2crazytv/webcomm-calendar-sync:latest` |

## Repository structure

```text
unraid-community-apps/
├── ca_profile.xml
├── README.md
├── templates/
│   ├── multi-coin-paper-daytrader.xml
│   ├── alarm-hub.xml
│   └── webcomm-calendar-sync.xml
└── icons/
    └── webcomm-calendar-sync.png
```

The templates are the canonical Community Apps definitions. Every `<TemplateURL>` points back to the matching raw XML file in this repository.

## Privacy and configuration

No personal credentials, API keys, passwords, tokens, private IP addresses or user-specific Alarm-HUB URLs are shipped as template defaults. Optional integration fields are intentionally empty and must be configured by each user.

## Community Apps submission

Use this repository as the single CA repository for all 2CrAzYTV applications. After changes, run **Validate** and **Scan** in the Unraid Community Apps submission flow before publishing.

## Support

For application-specific issues, use the issue tracker linked from the corresponding template. For problems with the CA templates themselves, use this repository's issue tracker.
