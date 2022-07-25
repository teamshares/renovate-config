# Teamshares Renovate Configs

Teamshares has switched from Dependabot to Renovate (due to some issues with accessing private repositories, and also because renovate offers significantly more control over grouping/automerging/etc.). It is expected that teamshares repos using renovate will [extend from our shared config files](https://docs.renovatebot.com/config-presets/#github-hosted-presets):


### For applications (pin versions)

```
  {
    "extends": ["github>teamshares/renovate-config:app.json5"]
  }
```


### For packages/libraries (maintain semver ranges)

```
  {
    "extends": ["github>teamshares/renovate-config:lib.json5"]
  }
```
