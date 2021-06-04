# Ansible Role: UniFi Video

[![Build Status](https://travis-ci.com/lifeofguenter/ansible-role-unifi-video.svg?branch=main)](https://travis-ci.org/lifeofguenter/ansible-role-unifi-video)

An Ansible role that installs UniFi Video (Ubiquiti Networks) on Debian like systems.

_NB: this will install the legacy NVR version, please [read here](https://community.ui.com/questions/UniFi-Video-Products-End-of-Life-Announcement/dc529d39-0e58-43cc-96f0-8f0eed0d002c) for further info._

## Requirements

none

## Role Variables

- `unifi_video_jvm_mx: 520M`
- `unifi_video_app_session_timeout: 1440`

## Dependencies

- [lifeofguenter.java](https://galaxy.ansible.com/lifeofguenter/java)

## Example Playbook

    - hosts: nvr
      roles:
        - { role: lifeofguenter.unifi_video }

## License

MIT
