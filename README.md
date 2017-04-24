# ansible-upgrade-once for Debian/Ubuntu

Ansible role runs a system upgrade cycle for packages. This is once only **once** per host.

__Note: Some packages will already be in place with default Ubuntu install but there is no harm in making sure.__

## Debugging

If you run into errors, uncomment the `- debug: msg="{{ ... }}"` statements.
