# Function: <code>pci_match_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8143a350)
Location: drivers/pci/pci-driver.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:store_new_id
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
**Symbols:**

```
ffffffff8143a350-ffffffff8143a3d0: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81486260)
Location: drivers/pci/pci-driver.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:store_new_id
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
**Symbols:**

```
ffffffff81486260-ffffffff814862e0: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814a7a20)
Location: drivers/pci/pci-driver.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:store_new_id
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
**Symbols:**

```
ffffffff814a7a20-ffffffff814a7aa0: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814b1b07)
Location: drivers/pci/pci-driver.c:222
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff814b1990-ffffffff814b1a09: pci_match_id.part.5 (STB_LOCAL)
ffffffff814b1a10-ffffffff814b1a28: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814f11e7)
Location: drivers/pci/pci-driver.c:222
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff814f1070-ffffffff814f10e9: pci_match_id.part.6 (STB_LOCAL)
ffffffff814f10f0-ffffffff814f1108: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815210f5)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81520f80-ffffffff81520ffd: pci_match_id.part.11 (STB_LOCAL)
ffffffff81521000-ffffffff81521018: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815373c5)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81536f20-ffffffff81536f9d: pci_match_id.part.13 (STB_LOCAL)
ffffffff81536fa0-ffffffff81536fb8: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81566d26)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81566890-ffffffff8156690e: pci_match_id.part.0 (STB_LOCAL)
ffffffff81566910-ffffffff81566928: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81588086)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81587bf0-ffffffff81587c6e: pci_match_id.part.0 (STB_LOCAL)
ffffffff81587c70-ffffffff81587c88: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162e216)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_aspm
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff8162e0a0-ffffffff8162e11e: pci_match_id.part.0 (STB_LOCAL)
ffffffff8162e120-ffffffff8162e138: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81653926)
Location: drivers/pci/pci-driver.c:104
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_aspm
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff816537b0-ffffffff8165382e: pci_match_id.part.0 (STB_LOCAL)
ffffffff81653830-ffffffff81653848: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816362d6)
Location: drivers/pci/pci-driver.c:104
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81636160-ffffffff816361de: pci_match_id.part.0 (STB_LOCAL)
ffffffff816361e0-ffffffff816361f8: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a64f6)
Location: drivers/pci/pci-driver.c:104
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_aspm
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff816a6380-ffffffff816a63fe: pci_match_id.part.0 (STB_LOCAL)
ffffffff816a6400-ffffffff816a6418: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c9040)
Location: drivers/pci/pci-driver.c:105
Inline: False
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff817c9040-ffffffff817c90ca: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e6980)
Location: drivers/pci/pci-driver.c:105
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff818e6980-ffffffff818e6a0a: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81929fa0)
Location: drivers/pci/pci-driver.c:105
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81929fa0-ffffffff8192a02a: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81972690)
Location: drivers/pci/pci-driver.c:105
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81972690-ffffffff8197271a: pci_match_id (STB_GLOBAL)
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
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106ec400)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
**Symbols:**

```
ffff8000106ebc68-ffff8000106ebd3c: pci_match_id.part.0 (STB_LOCAL)
ffff8000106ebd40-ffff8000106ebd88: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (c0887594)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
**Symbols:**

```
c0887384-c0887458: pci_match_id.part.0 (STB_LOCAL)
c0887458-c0887484: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (c000000000867cb4)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
**Symbols:**

```
c000000000867910-c0000000008679e8: pci_match_id.part.0 (STB_LOCAL)
c0000000008679f0-c000000000867a0c: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c14fe)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
**Symbols:**

```
ffffffe0004c100c-ffffffe0004c10a4: pci_match_id.part.0 (STB_LOCAL)
ffffffe0004c10a4-ffffffe0004c10e6: pci_match_id (STB_GLOBAL)
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
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157bf16)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff8157ba80-ffffffff8157bafe: pci_match_id.part.0 (STB_LOCAL)
ffffffff8157bb00-ffffffff8157bb18: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8156ace6)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff8156a850-ffffffff8156a8ce: pci_match_id.part.0 (STB_LOCAL)
ffffffff8156a8d0-ffffffff8156a8e8: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157bdd6)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff8157b940-ffffffff8157b9be: pci_match_id.part.0 (STB_LOCAL)
ffffffff8157b9c0-ffffffff8157b9d8: pci_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct pci_device_id *pci_match_id(const struct pci_device_id *ids, struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815960c6)
Location: drivers/pci/pci-driver.c:221
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
Direct callers:
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/quirks.c:quirk_fixed_dma_alias
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81595f50-ffffffff81595fce: pci_match_id.part.0 (STB_LOCAL)
ffffffff81595fd0-ffffffff81595fe8: pci_match_id (STB_GLOBAL)
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
