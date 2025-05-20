# Function: <code>pci_release_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814346a0)
Location: drivers/pci/pci.c:2795
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
```
**Symbols:**

```
ffffffff814346a0-ffffffff81434780: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480020)
Location: drivers/pci/pci.c:2973
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81480020-ffffffff814800f8: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a1670)
Location: drivers/pci/pci.c:3011
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff814a1670-ffffffff814a1748: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab1f0)
Location: drivers/pci/pci.c:3028
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff814ab1f0-ffffffff814ab2dd: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea410)
Location: drivers/pci/pci.c:3138
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff814ea410-ffffffff814ea4fd: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151ab60)
Location: drivers/pci/pci.c:3284
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff8151ab60-ffffffff8151abfc: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815308b0)
Location: drivers/pci/pci.c:3549
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff815308b0-ffffffff81530955: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560240)
Location: drivers/pci/pci.c:3670
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81560240-ffffffff815602d7: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581360)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81581360-ffffffff815813f7: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81627620)
Location: drivers/pci/pci.c:3736
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81627620-ffffffff816276c5: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164d2c0)
Location: drivers/pci/pci.c:3800
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff8164d2c0-ffffffff8164d365: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162fb80)
Location: drivers/pci/pci.c:3831
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff8162fb80-ffffffff8162fc42: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3881
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81ce46f7-ffffffff81ce4718: pci_release_region.cold (STB_LOCAL)
ffffffff8169f680-ffffffff8169f92d: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3975
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
```
**Symbols:**

```
ffffffff81eab071-ffffffff81eab092: pci_release_region.cold (STB_LOCAL)
ffffffff817c10d0-ffffffff817c13a0: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3918
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
```
**Symbols:**

```
ffffffff8208f0a2-ffffffff8208f0c3: pci_release_region.cold (STB_LOCAL)
ffffffff818dd7c0-ffffffff818dda90: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3956
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
```
**Symbols:**

```
ffffffff8210f408-ffffffff8210f429: pci_release_region.cold (STB_LOCAL)
ffffffff81920c60-ffffffff81920ee7: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4070
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
```
**Symbols:**

```
ffffffff821ed08f-ffffffff821ed0b0: pci_release_region.cold (STB_LOCAL)
ffffffff81968e00-ffffffff81969087: pci_release_region (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e4328)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffff8000106e4328-ffff8000106e43cc: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0880178)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
c0880178-c088021c: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085e820)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
c00000000085e820-c00000000085e960: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb85a)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffe0004bb85a-ffffffe0004bb90e: pci_release_region (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575880)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81575880-ffffffff81575917: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563fe0)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81563fe0-ffffffff81564077: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815750b0)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff815750b0-ffffffff81575147: pci_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f680)
Location: drivers/pci/pci.c:3666
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:pcim_iomap_regions
  - drivers/pci/pci.c:pci_release_regions
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pcim_release
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff8158f680-ffffffff8158f717: pci_release_region (STB_GLOBAL)
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
