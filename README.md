# ansible-role-hostname

Role set linux hostname an fix setting in /etc/hosts.

## Table of content

- [Default Variables](#default-variables)
  - [hostname](#hostname)
  - [hostname_change_fix_etc_hosts](#hostname_change_fix_etc_hosts)
  - [hostname_change_force_reboot](#hostname_change_force_reboot)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### hostname

#### Default value

```YAML
hostname: '{{ inventory_hostname_short }}'
```

### hostname_change_fix_etc_hosts

#### Default value

```YAML
hostname_change_fix_etc_hosts: true
```

### hostname_change_force_reboot

#### Default value

```YAML
hostname_change_force_reboot: true
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
