# NFS

An Ansible role to install NFS with optional kTLS encryption

## Requirements

None.

## Role Variables

`nfs_ktls:` - Setup kTLS for encrypted NFS

## Dependencies

None.

## Example Playbook

```yaml
- hosts: nfs
  roles:
    - syaghoubi00.nfs
```

## License

GPL-3.0-or-later

## Author Information

Created by Sebastian Yaghoubi
