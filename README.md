# renovate-config-public

Base [Renovate](https://docs.renovatebot.com/) preset of the `l2nx` organization. Public repositories use it directly:
Renovate does not read a private preset from a public repository.

```json
{ "extends": ["github>l2nx/renovate-config-public"] }
```

Private repositories use the private preset, which extends this one. Common rules are changed here. This preset carries
no registry credentials: a repository that needs a private registry declares its own `hostRules`.
