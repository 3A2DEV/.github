
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
<picture>
  <source
    srcset="../orgflow.svg"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="../orgflow_white.svg"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="../orgflow.svg" />
</picture>

---

### Links

- [ans2dev.general collection](https://github.com/3A2DEV/ans2dev.general)
- [ans2dev.general Documentation](https://3a2dev.github.io/ans2dev.general/branch/main)
- [ans2dev.general Galaxy](https://galaxy.ansible.com/ui/repo/published/ans2dev/general)
- [ANS2BOT collections bot](https://github.com/3A2DEV/ANS2BOT)