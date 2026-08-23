# Rasmus Sööt — CV

**[Download the latest PDF](../../releases/latest/download/Rasmus_Soot_CV.pdf)**

One-page CV, rendered from [`rendercv-onepage.yaml`](rendercv-onepage.yaml) by
[RenderCV](https://rendercv.com). Every push re-renders the PDF and replaces the
asset on the rolling [`latest` release](../../releases/latest).

## Render locally

```sh
devbox run render   # → release/Rasmus_Soot_CV.pdf
```

Needs [devbox](https://www.jetify.com/devbox); tool versions are pinned in
`devbox.lock`.

## Note

This repo is a publish target — the content is generated from a private master
and pushed here automatically, so PRs against the YAML won't stick.
