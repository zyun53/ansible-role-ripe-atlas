# Ansible Role: RIPE Atlas

![CI](https://github.com/zyun-i/ansible-role-ripe-atlas-software-probe/workflows/CI/badge.svg)

Setup [RIPE Atlas Software Probes](https://atlas.ripe.net/docs/software-probe/).

## Requirements

None.

## Role Variables

Change service status.

```yml
atlas_service_state: started
atlas_service_enabled: true
```

## Dependencies

None.

## Example Playbook

```yml
- hosts: servers
  roles:
     - zyun_i.ripe-atlas
```

Get probe key from `/var/atlas-probe/etc/probe_key.pub` .

## License

MIT

## Author Information

Isida Zyun'iti
