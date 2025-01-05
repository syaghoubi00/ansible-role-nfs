# NFS

An Ansible role to install NFS with optional kTLS encryption

## Requirements

None.

## Role Variables

```yaml
nfs_exports:
  - {
      name:
      path:
      allowed_subnets:
      opts:
    }
```

`nfs_ktls:` - Setup kTLS for encrypted NFS

## Dependencies

`ansible.posix` - Required to mount exports
`community.crypto` - Used to create certificates for TLS

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
