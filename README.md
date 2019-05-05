# Ansible role 'ansible-role-telegraf'

An Ansible role for setting up telegraf on monitored nodes.

This role does not set up a backend, but relies on such to be set up already.

It is assumed that the backend is an influxdb server. 

## Requirements
- A target influxdb

One of the following:
- Fedora (Tested on 29+)
- Raspbian

## Role Variables
| Variable		| Default		| Comments (type) |
| :---			| :---			| :---		  |

## Dependencies

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - role: ansible-role-telegraf
```

## Testing


## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
