# Orca pet

A chibi orca sidekick for [Orca ADE](https://github.com/stablyai/orca), packaged as an importable `.codex-pet` bundle.

The character comes from the Orca ADE pet showcase sheet by [@sysCat64](https://x.com/sysCat64/status/2111709001113338142). That sheet contains one still frame per state, so the motion here is synthesized from those stills rather than copied from an existing animation.

## Install

1. Open Orca.
2. Click the pet segment in the status bar.
3. Choose **Import .codex-pet bundle...**.
4. Select the `orca.codex-pet` folder itself, not `pet.json`.
5. Restart Orca completely. A renderer reload is not enough.

## Bundle layout

```
orca.codex-pet/
  pet.json
  spritesheet.png
```

## Credits

Art by [@sysCat64](https://x.com/sysCat64/status/2111709001113338142). This repository only repackages that sheet into the Orca bundle format and adds generated in-between frames. Rights to the character stay with the original artist. The manifest and build output may be reused freely.
