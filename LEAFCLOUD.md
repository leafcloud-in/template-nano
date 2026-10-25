# LeafCloud adaptation

- Upstream: https://github.com/markhorn-dev/astro-nano
- Author: Mark Horn
- Licence: MIT (upstream `LICENSE` retained unchanged)
- Pinned upstream commit: 66aa017d614828ba5dba02a9e51a1a714850ad31
- Preview: https://tpl-nano.leafcloud.app

Adaptation: replaced upstream contact/social identity with fictional Asha Rao placeholders, set Astro's canonical site URL to the preview, and added LeafCloud setup guidance. Original design retained.

Build note: the original pnpm lock was incompatible with the installed pnpm 11. Regenerated the lock and verified the static build with pnpm 9.15.9; Leaf's managed build rechecks with pnpm 11 and can fail the minimum-release-age policy (see the task report).
