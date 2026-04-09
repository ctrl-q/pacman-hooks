# pacman-hooks

Pacman hooks that run automatically after package operations.

| Hook | Trigger | Action |
|------|---------|--------|
| `rclone.hook` | rclone upgrade | Regenerates bash autocomplete |
| `reflector.hook` | pacman-mirrorlist upgrade | Updates mirror list via reflector |
| `restic.hook` | restic upgrade | Re-applies `cap_dac_read_search` capability |
| `restore-settings.hook` | any install/upgrade/remove | Restores GTK theme and keyboard layout |

## Installation

Copy the `.hook` files to `/etc/pacman.d/hooks/`.
