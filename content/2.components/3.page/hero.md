---
title: Hero
icon: lucide:align-center
---

::code-group
  ::div{label="Preview" class="md:p-4"}
    ::hero
    ---
    announcement:
      title: 'Release v1.0.0'
      icon: 'lucide:party-popper'
      to: /getting-started
    actions:
      - name: Get Started
        to: /getting-started
      - name: GitHub
        variant: outline
        to: https://github.com/ZTL-UwU/shadcn-docs-nuxt
        leftIcon: 'lucide:github'
    ---

    #title
    Effortless and Beautiful :br Docs Template.

    #description
    Beautifully designed Nuxt Content template with shadcn-vue. :br Customizable. Compatible. Open Source.
    ::
  ::
  ```mdc[Code]
  ::hero
  ---
  announcement:
    title: 'Release v1.0.0'
    icon: 'lucide:party-popper'
    to: /getting-started
  actions:
    - name: Get Started
      to: /getting-started
    - name: GitHub
      variant: outline
      to: https://github.com/ZTL-UwU/shadcn-docs-nuxt
      leftIcon: 'lucide:github'
  ---

  #title
  Effortless and Beautiful :br Docs Template.

  #description
  Beautifully designed Nuxt Content template with shadcn-vue. :br Customizable. Compatible. Open Source.
  ::
  ```
::