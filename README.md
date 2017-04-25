# Ansible Watchman

[![Travis](https://travis-ci.org/mediapop/ansible-watchman.svg?branch=master)](https://travis-ci.org/mediapop/ansible-watchman)

Installs [watchman](https://facebook.github.io/watchman/).

## Role Variables

```yml
watchman_version: "4.7.0"
```

## Example Playbook

```yml
- hosts: webservers
  roles:
    - role: mediapop.watchman
```
        
## License

MIT

## Author

[Media Pop](http://www.mediapop.co)
