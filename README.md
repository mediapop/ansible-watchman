# README.md
# Ansible Role: Watchman

Make sure [watchman](https://facebook.github.io/watchman/) is available.

## Example Playbook

```yml
- hosts: webservers
  roles:
    - role: mediapop.watchman
```
        
## Example as a dependency in your meta


```yml
---
dependencies:
- role: mediapop.watchman
```

## License

MIT
