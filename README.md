[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-unifi-video.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-unifi-video)

# Ansible Role: UniFi Video

An Ansible role that installs UniFi Video (Ubiquiti Networks) on Debian like systems.

## Requirements

none

## Role Variables

- `unifi_video_version: 3.6.3`
- `unifi_video_jvm_mx: 520M`
- `unifi_video_app_session_timeout: 1440`

## Dependencies

- lifeofguenter.oracle-java

## Example Playbook

    - hosts: nvr
      roles:
        - { role: lifeofguenter.unifi-video }

## License

MIT
