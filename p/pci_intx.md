# Function: <code>pci_intx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814344b0)
Location: drivers/pci/pci.c:3251
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff814344b0-ffffffff81434575: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147fe40)
Location: drivers/pci/pci.c:3561
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8147fe40-ffffffff8147ff05: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a1490)
Location: drivers/pci/pci.c:3599
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff814a1490-ffffffff814a1555: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac470)
Location: drivers/pci/pci.c:3737
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff814ac470-ffffffff814ac52a: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb540)
Location: drivers/pci/pci.c:3752
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff814eb540-ffffffff814eb5fa: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151aeb0)
Location: drivers/pci/pci.c:3957
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff8151aeb0-ffffffff8151af5e: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530c20)
Location: drivers/pci/pci.c:4222
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81530c20-ffffffff81530cce: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560560)
Location: drivers/pci/pci.c:4320
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81560560-ffffffff8156060d: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581680)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff81581680-ffffffff8158172d: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81627090)
Location: drivers/pci/pci.c:4387
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff81627090-ffffffff8162714d: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164cd30)
Location: drivers/pci/pci.c:4462
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff8164cd30-ffffffff8164cded: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162f8b0)
Location: drivers/pci/pci.c:4511
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff8162f8b0-ffffffff8162f96d: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169f5c0)
Location: drivers/pci/pci.c:4561
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff8169f5c0-ffffffff8169f67d: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c0e00)
Location: drivers/pci/pci.c:4657
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff817c0e00-ffffffff817c0ed1: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dd610)
Location: drivers/pci/pci.c:4600
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff818dd610-ffffffff818dd6e1: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81920ac0)
Location: drivers/pci/pci.c:4638
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81920ac0-ffffffff81920b91: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81968c60)
Location: drivers/pci/pci.c:4748
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81968c60-ffffffff81968d31: pci_intx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e47b8)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
**Symbols:**

```
ffff8000106e47b8-ffff8000106e4884: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0880510)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
**Symbols:**

```
c0880510-c08805e0: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085edf0)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
c00000000085edf0-c00000000085eee0: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bbc5c)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffe0004bbc5c-ffffffe0004bbcee: pci_intx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575ba0)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81575ba0-ffffffff81575c4d: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564300)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff81564300-ffffffff815643ad: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815753d0)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_remove
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff815753d0-ffffffff8157547d: pci_intx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_intx(struct pci_dev *pdev, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f9a0)
Location: drivers/pci/pci.c:4316
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff8158f9a0-ffffffff8158fa4d: pci_intx (STB_GLOBAL)
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
