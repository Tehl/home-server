https://fedoraproject.org/wiki/Changes/systemd-resolved#Local_stub_resolver_on_port_53

https://github.com/eriksjolund/podman-traefik-socket-activation

.config/containers/systemd

.config/systemd/user


https://github.com/qdm12/gluetun-wiki/blob/main/errors/tun.md#tun-device-is-not-available-open-devnettun-permission-denied
checkmodule -M -m -o gluetun_policy.mod gluetun_policy.te
semodule_package -o gluetun_policy.pp -m gluetun_policy.mod
semodule -i gluetun_policy.pp
