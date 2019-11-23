# spctl

[![Build Status](https://cloud.drone.io/api/badges/machippie/spctl/status.svg)](https://cloud.drone.io/machippie/spctl)

Ansible role to configure spctl

## Table of content

* [Default Variables](#default-variables)
  * [spctl_disable_master](#spctl_disable_master)
  * [spctl_gatekeeper_policy](#spctl_gatekeeper_policy)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### spctl_disable_master

Disable/Enable master system policy

#### Default value

```YAML
spctl_disable_master: true
```

### spctl_gatekeeper_policy

Update gatekeeper policy

#### Default value

```YAML
spctl_gatekeeper_policy: false
```

## Dependencies

None.

## License

Apache-2.0

## Author

Thomas Boerger
