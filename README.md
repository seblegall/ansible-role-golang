## Install Go lang

This role installs [Golang](https://golang.org/) from a binary package.

### Usage

By default the latest stable version is installed.

You can specify another version using variable `golang_version`.  For example:

```
---
- hosts:
    - testhost
  become: yes
  vars:
    golang_version: 1.7.5
  roles:
    - golang
```

### Supported Version

- 1.7.5
- 1.7
- 1.6.3
- 1.5.4
- 1.4.3

### Supported Platforms

- Linux x64
- Linux i386

### License

MIT
