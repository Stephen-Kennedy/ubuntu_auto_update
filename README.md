# ubuntu_auto_update — ARCHIVED

> **This repository is superseded by [sysmaint](https://github.com/Stephen-Kennedy/auto_updater_package).**
>
> sysmaint is a strict superset: same `apt-get update / upgrade / dist-upgrade`
> behavior, plus configurable SMTP relay, systemd timer with jitter and
> catch-up, structured weekly email, reboot-required tracking, disk + service
> monitoring, and fleet-friendly install. Install it instead:
>
> ```bash
> sudo apt install -y pipx
> sudo PIPX_HOME=/opt/pipx PIPX_BIN_DIR=/usr/local/bin pipx install \
>   git+https://github.com/Stephen-Kennedy/auto_updater_package.git@v1.0.1
> sudo sysmaint install
> ```
>
> This repo is archived (read-only) and kept for history. No further updates
> will be made here.

---

## Original description

Bash to auto update, upgrade, dist-upgrade.

A single 65-line shell script (`custom-updates-ubuntu`) from 2016 that ran
`apt-get update / upgrade / dist-upgrade` and emailed results via the local
`mail` command. The great-great-grandparent of sysmaint.
