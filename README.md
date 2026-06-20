# @apnex/opencode-hub-plugin

**This is a GENERATED bundle — do not hand-edit.**

`dist/shim.js` is the self-contained OpenCode hub plugin: the agentic-network
Universal Agent Adapter, esbuilt into a single ESM file with zero external
`@apnex/*` dependencies.

## Install

OpenCode agents install it by referencing this repo in `opencode.json`:

```json
{
  "plugin": ["github:apnex/opencode-hub-plugin"]
}
```

OpenCode resolves the repo's default branch and loads the plugin from the
`main` field (`dist/shim.js`), which exports `HubPlugin`.

## Provenance

The bundle is produced by the agentic-network release pipeline
(`scripts/build/release-opencode-plugin.sh`) and **rebuilt + republished here
whenever the shared core changes**. Do not edit `dist/shim.js` or this repo's
contents by hand — changes will be overwritten on the next republish.
