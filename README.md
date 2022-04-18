# lifeofguenter.unifi-video

[![CircleCI](https://circleci.com/gh/lifeofguenter/ansible-role-unifi-video/tree/main.svg?style=svg)](https://circleci.com/gh/lifeofguenter/ansible-role-unifi-video/tree/main)

An Ansible role that installs and configures UniFi Video (Ubiquiti Networks) on
Debian-like systems.

_NB: this will install the legacy NVR version, please [read here](https://community.ui.com/questions/UniFi-Video-Products-End-of-Life-Announcement/dc529d39-0e58-43cc-96f0-8f0eed0d002c) for further info._

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

```yaml
unifi_video_version: 3.10.13

unifi_video_jvm_mx: 520M
```

## Dependencies

- [lifeofguenter.java](https://galaxy.ansible.com/lifeofguenter/java)
- [lifeofguenter.monogdb](https://galaxy.ansible.com/lifeofguenter/mongodb)

## Example Playbook


```yaml
- hosts: nvr
  roles:
    - { role: lifeofguenter.unifi_video }
```

## License

**MIT**, see the [LICENSE file](LICENSE) for details.

## Author Information

[Günter Grodotzki](https://www.lifeofguenter.de)
