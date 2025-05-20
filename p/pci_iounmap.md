# Function: <code>pci_iounmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814028c0)
Location: lib/iomap.c:247
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff814028c0-ffffffff814028f0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a5f0)
Location: lib/iomap.c:247
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8144a5f0-ffffffff8144a620: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468fb0)
Location: lib/iomap.c:247
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81468fb0-ffffffff81468fe0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e690)
Location: lib/iomap.c:247
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8146e690-ffffffff8146e6c0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a9c0)
Location: lib/iomap.c:248
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8149a9c0-ffffffff8149a9f0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfc70)
Location: lib/iomap.c:248
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove
```
**Symbols:**

```
ffffffff814cfc70-ffffffff814cfca0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e4580)
Location: lib/iomap.c:248
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff814e4580-ffffffff814e45b0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510f50)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81510f50-ffffffff81510f80: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815319c0)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff815319c0-ffffffff815319f0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595710)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81595710-ffffffff8159575c: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b11a0)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff815b11a0-ffffffff815b11ec: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bbfb0)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff815bbfb0-ffffffff815bbffc: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81622e00)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff81622e00-ffffffff81622e4c: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f2d70)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff816f2d70-ffffffff816f2de0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e4c10)
Location: lib/iomap.c:424
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff817e4c10-ffffffff817e4c80: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81824c50)
Location: lib/iomap.c:424
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81824c50-ffffffff81824cc0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876660)
Location: lib/iomap.c:424
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81876660-ffffffff818766d0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/devres.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/iomap.c (c031ac50)
Location: arch/arm/mm/iomap.c:36
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
```
**Symbols:**

```
c031ac50-c031aca4: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e4fa0)
Location: lib/iomap.c:380
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c0000000007e4fa0-c0000000007e4ff8: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/devres.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: include/asm-generic/io.h:896
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/io.h:896
Inline: True
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
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529fa0)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81529fa0-ffffffff81529fd0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8151a280)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8151a280-ffffffff8151a2b0: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81526030)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81526030-ffffffff81526060: pci_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f9b0)
Location: lib/iomap.c:380
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_release
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8153f9b0-ffffffff8153f9e0: pci_iounmap (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
