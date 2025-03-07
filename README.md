
---

```yaml
---
- name: Organization init
  hosts: localhost
  gather_facts: no

  vars:
    name: 3A2DEV
    logo: true
    country: Italy

  tasks:
    - name: Init
      command: "/usr/sbin/organization init {{ country }}.{{ name }}"
```
---