
<div style="text-align:center">
    <img src="https://avatars.githubusercontent.com/u/202336212?s=400&u=c0954dc817d656ed69efa5c00193ed355f9987db&v=4" style="width: 40%; border-radius: 30px">
    </img>
</div>

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