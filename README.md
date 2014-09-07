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
> soak check
[Soak/INFO] Checking for plugin and Sponge updates...
[Soak/INFO] Retrieving http://example.com/SpongeBath/s/Sponge/latest.txt
[Soak/INFO] Retrieving http://example.com/SpongeBath/e/Essentials/latest.txt
[Soak/INFO] Retrieving http://example.com/SpongeBath/s/Soak/latest.txt
[Soak/INFO] Retrieving http://example.com/SpongeBath/w/WorldEdit/latest.txt
[Soak/INFO] Two updates are available: WorldEdit, Soak
[Soak/INFO] Use 'soak update' to install these
> soak update
[Soak/INFO] The following actions will be performed:
[Soak/INFO] Update WorldEdit from v6.2 to v6.3
[Soak/INFO] Update Soak from v0.8 to v1.2
[Soak/INFO] Would you like to continue? Use 'soak confirm' or 'soak abort'
> soak abort
[Soak/INFO] Aborted 2 pending changes.

```
