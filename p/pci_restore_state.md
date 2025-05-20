# Function: <code>pci_restore_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435ee0)
Location: drivers/pci/pci.c:1121
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff81435ee0-ffffffff81436129: pci_restore_state.part.33 (STB_LOCAL)
ffffffff81436130-ffffffff8143614a: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481c7a)
Location: drivers/pci/pci.c:1142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff81481a10-ffffffff81481c49: pci_restore_state.part.36 (STB_LOCAL)
ffffffff81481c50-ffffffff81481c6a: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a314a)
Location: drivers/pci/pci.c:1167
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff814a2ee0-ffffffff814a3119: pci_restore_state.part.38 (STB_LOCAL)
ffffffff814a3120-ffffffff814a313a: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff814acf62)
Location: drivers/pci/pci.c:1163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff814acce0-ffffffff814acf13: pci_restore_state.part.39 (STB_LOCAL)
ffffffff814acf20-ffffffff814acf3b: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ec332)
Location: drivers/pci/pci.c:1166
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff814ec0b0-ffffffff814ec2e3: pci_restore_state.part.40 (STB_LOCAL)
ffffffff814ec2f0-ffffffff814ec30b: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151beb6)
Location: drivers/pci/pci.c:1216
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff8151baa0-ffffffff8151be6a: pci_restore_state.part.42 (STB_LOCAL)
ffffffff8151be70-ffffffff8151be8a: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81533cd6)
Location: drivers/pci/pci.c:1388
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff815338d0-ffffffff81533c8a: pci_restore_state.part.44 (STB_LOCAL)
ffffffff81533c90-ffffffff81533caa: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815631f6)
Location: drivers/pci/pci.c:1457
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff81562da0-ffffffff815631ad: pci_restore_state.part.0 (STB_LOCAL)
ffffffff815631b0-ffffffff815631ca: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815843b6)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff81583f30-ffffffff81584361: pci_restore_state.part.0 (STB_LOCAL)
ffffffff81584370-ffffffff8158438a: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162abf6)
Location: drivers/pci/pci.c:1522
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff8162a910-ffffffff8162aba2: pci_restore_state.part.0 (STB_LOCAL)
ffffffff8162abb0-ffffffff8162abca: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164e3a6)
Location: drivers/pci/pci.c:1657
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff8164e0c0-ffffffff8164e360: pci_restore_state.part.0 (STB_LOCAL)
ffffffff8164e360-ffffffff8164e37a: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81630fb6)
Location: drivers/pci/pci.c:1687
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff81630ba0-ffffffff81630f68: pci_restore_state.part.0 (STB_LOCAL)
ffffffff81630f70-ffffffff81630f8a: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a21d9)
Location: drivers/pci/pci.c:1722
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff816a1ea0-ffffffff816a2186: pci_restore_state.part.0 (STB_LOCAL)
ffffffff81ce4851-ffffffff81ce4890: pci_restore_state.part.0.cold (STB_LOCAL)
ffffffff816a2190-ffffffff816a21aa: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4269)
Location: drivers/pci/pci.c:1785
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff817c3f20-ffffffff817c420f: pci_restore_state.part.0 (STB_LOCAL)
ffffffff81eab2b6-ffffffff81eab2f5: pci_restore_state.part.0.cold (STB_LOCAL)
ffffffff817c4210-ffffffff817c4236: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e1179)
Location: drivers/pci/pci.c:1761
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff818e0e30-ffffffff818e10f7: pci_restore_state.part.0 (STB_LOCAL)
ffffffff8208f196-ffffffff8208f1d5: pci_restore_state.part.0.cold (STB_LOCAL)
ffffffff818e1110-ffffffff818e1136: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff819245b9)
Location: drivers/pci/pci.c:1799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff81924270-ffffffff81924537: pci_restore_state.part.0 (STB_LOCAL)
ffffffff8210f4fc-ffffffff8210f53b: pci_restore_state.part.0.cold (STB_LOCAL)
ffffffff81924550-ffffffff81924576: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196cc89)
Location: drivers/pci/pci.c:1896
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff8196c940-ffffffff8196cc07: pci_restore_state.part.0 (STB_LOCAL)
ffffffff821ed183-ffffffff821ed1c2: pci_restore_state.part.0.cold (STB_LOCAL)
ffffffff8196cc20-ffffffff8196cc46: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e8724)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
```
**Symbols:**

```
ffff8000106e8240-ffff8000106e86c0: pci_restore_state.part.0 (STB_LOCAL)
ffff8000106e86c0-ffff8000106e86f4: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c08837f4)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
```
**Symbols:**

```
c08832f8-c0883798: pci_restore_state.part.0 (STB_LOCAL)
c0883798-c08837c0: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c0000000008633c4)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_restore_dev_state
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
c000000000862df0-c000000000863354: pci_restore_state.part.0 (STB_LOCAL)
c000000000863360-c000000000863380: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bed1a)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
```
**Symbols:**

```
ffffffe0004be848-ffffffe0004becbc: pci_restore_state.part.0 (STB_LOCAL)
ffffffe0004becbc-ffffffe0004becf2: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815788d6)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/nvme/host/pci.c:nvme_slot_reset
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff81578450-ffffffff81578881: pci_restore_state.part.0 (STB_LOCAL)
ffffffff81578890-ffffffff815788aa: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81567016)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/nvme/host/pci.c:nvme_slot_reset
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff81566b90-ffffffff81566fc1: pci_restore_state.part.0 (STB_LOCAL)
ffffffff81566fd0-ffffffff81566fea: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578106)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_resume
```
**Symbols:**

```
ffffffff81577c80-ffffffff815780b1: pci_restore_state.part.0 (STB_LOCAL)
ffffffff815780c0-ffffffff815780da: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815925c6)
Location: drivers/pci/pci.c:1453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_restore
Direct callers:
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci.c:pci_dev_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff81592140-ffffffff81592571: pci_restore_state.part.0 (STB_LOCAL)
ffffffff81592580-ffffffff8159259a: pci_restore_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
