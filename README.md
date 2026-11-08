# Altruismax

Give your devices a j*b

## Recommended operating systems

- Bluefin Dakota, or any other modern atomic distro
- macOS
- Homelab OCI management UIs, manually use the compose file and self supply env

## Ethical Services

These only include services that are meaningfully contributive to a network by

- transparent disclosure of service intents and actions
- distributed compute
- SMS or internet speed testing
- automated scraping
- bandwidth sharing
- AI inference, *regardless if the target sources have protections or not*
- Consensually displaying ads, that are not overly intrusive
- Automatically voting on sites timely

but not by

- hijacking user credentials
- unethical destructive actions
- artificial product inflation without user consent
- Advertisment fraud
- unsandboxed or unauthorized automated denial of service attacks \
*unless targetted to problematic entities*

However, all will be documented regardless if they follow this or not.
A prime example of unethical services are botnets like XCPE, which sold access \
to criminal affiliates and commited ad fraud.
Some services that are not ethical but are fine based on context are in italics

## Containerization tools

### Podman

Pros

- Resource efficiency
- Systemd integration
- Daemonless architect
- Rootless and Rootfull support

Cons

- Breaks with apps that communicate directly with Docker
- Niche macOS issues

Enable podman.socket and podman-auto-update.timer

### Docker

Pros

- macOS maturity
- Guaranteed proprietary app dependency
- Homelab standard

Cons

- Legacy architecture
- Propreitary source
- Daemon overhead
- Manual complexity like watchtower
