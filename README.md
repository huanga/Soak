Soak
====
**apt-get for Sponge**

Waiting for a solid base to develop on top of.

Plan:

```
> soak install essentials
[Soak/INFO] Retrieving http://example.com/SpongeBath/e/Essentials/1.0/Essentials-1.0.jar
[Soak/INFO] Installing Essentials...
[Server thread/INFO] [Essentials] v1.0 enabled
> soak update
[Soak/INFO] Checking for plugin and Sponge updates...
[Soak/INFO] Retrieving http://example.com/SpongeBath/s/Sponge/latest.json
[Soak/INFO] Retrieving http://example.com/SpongeBath/e/Essentials/latest.json
[Soak/INFO] Retrieving http://example.com/SpongeBath/s/Soak/latest.json
[Soak/INFO] Retrieving http://example.com/SpongeBath/w/WorldEdit/latest.json
[Soak/INFO] 2 updates are available: WorldEdit, Soak
[Soak/INFO] Use 'soak upgrade' to install these
> soak upgrade
[Soak/INFO] The following actions will be performed:
[Soak/INFO] Update WorldEdit from v6.2 to v6.3
[Soak/INFO] Update Soak from v0.8 to v1.2
[Soak/INFO] Would you like to continue [Y/n]?
> n
[Soak/INFO] Aborted 2 pending changes.

```

Misc Ideas
===
 - A pacman-like alternate command for people more familiar with Arch
 - Same as above for portage, emerge, yum, etc
 - Explosions
