# PLUG-INS

Ce dossier est la matérialisation des plugins installés dans `~/.claude/plugins/`.

## Principe

Les plugins Claude Code sont installés localement sur chaque machine via la marketplace.
**Sur une nouvelle machine, ils doivent être réinstallés manuellement.**

Ce dossier sert de registre : un sous-dossier par plugin, contenant son audit-repo (analyse fmaths + verdict PM).

## Plugins installés

| Plugin | Installé via | Commande de réinstallation |
|--------|-------------|---------------------------|
| claude-mem (thedotmack) | Claude Code marketplace | `npx claude-mem install` |

## Règle

Avant d'installer un nouveau plugin → lancer `/repo-audit <url-github>` → ranger le HTML dans `PLUG-INS/<nom-plugin>/`.
