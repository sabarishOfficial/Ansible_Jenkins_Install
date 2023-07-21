## Version Support
```bash
Ubuntu 18.0x
Ubuntu 20.0x

```

## Steps

## Inventroy File Create 

```bash
touch inventroy

vi inventroy

hostname ansible_host=0.0.0.0 ansible_user=username ansible_ssh_private_key_file=you_pem_file.pem

chmod 400 you_pem_file.pem
```
## server connection check

```bash
ansible -i inventroy -m ping hostname
```

## Script execute command
```bash
ansible -i inventroy Jenkins.yaml
```
