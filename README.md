[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-unifi-video.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-unifi-video)

# Ansible Role: UniFi Video

An Ansible role that installs UniFi Video (Ubiquiti Networks) on Debian like systems.

## Requirements

none

## Role Variables

none

## Dependencies

- lifeofguenter.oracle-java

## Example Playbook

    - hosts: nvr
      roles:
        - { role: lifeofguenter.unifi-video }

## License

MIT
