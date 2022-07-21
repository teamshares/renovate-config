# Teamshares Renovate Configs

Teamshares has switched from Dependabot to Renovate (due to some issues with accessing private repositories, and also because renovate offers significantly more control over grouping/automerging/etc.). It is expected that teamshares repos using renovate will [extend from this shared, default config file](https://docs.renovatebot.com/config-presets/#github-hosted-presets) by adding this line to their own renovate configs:

```
  {
    "extends": ["github>teamshares/renovate-config"]
  }
```
