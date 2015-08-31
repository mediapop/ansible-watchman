# README.md
# Ansible Role: Watchman

Make sure [watchman](https://facebook.github.io/watchman/) is available.

## Example Playbook

```yml
- hosts: webservers
  roles:
    - role: Celc.watchman
```
        
## Example as a dependency in your meta


```yml
---
dependencies:
- role: Celc.watchman
```

## License

MIT
