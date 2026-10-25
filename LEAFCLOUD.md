# LeafCloud adaptation

- Upstream: https://github.com/markhorn-dev/astro-nano
- Author: Mark Horn
- Licence: MIT (upstream `LICENSE` retained unchanged)
- Pinned upstream commit: 66aa017d614828ba5dba02a9e51a1a714850ad31
- Preview: https://tpl-nano.leafcloud.app

Adaptation: replaced upstream contact/social identity with fictional Asha Rao placeholders, set Astro's canonical site URL to the preview, and added LeafCloud setup guidance. Original design retained.

pnpm 11.11.0 compatibility: pinned `packageManager`, regenerated `pnpm-lock.yaml`, set `minimumReleaseAge: 0`, and approved the `esbuild` and `sharp` install scripts in `pnpm-workspace.yaml`. The Leaf build command uses pnpm. Set the visible site name to fictional student Asha Rao.

Removed unused root Vercel and Netlify deploy badge files (_deploy_netlify.svg and _deploy_vercel.svg). Project sample pages still use their separate public deploy icons.
