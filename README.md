# Renovate Config

Shared Renovate bot config preset. You can adjust for your own architecture by forking this repo and modifying. Change the `extends` property to your forked repository.

## Usage

Add the following to your `renovate.json` file:

```jsonc
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>nicksp/renovate-config:default.json5"],

  // override any settings here
  "automerge": true
}
```
