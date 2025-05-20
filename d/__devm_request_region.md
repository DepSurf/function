# Function: <code>__devm_request_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086c50)
Location: kernel/resource.c:1356
Inline: False
Direct callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81086c50-ffffffff81086cfb: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089c90)
Location: kernel/resource.c:1425
Inline: False
Direct callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81089c90-ffffffff81089d2d: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ebe0)
Location: kernel/resource.c:1425
Inline: False
Direct callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8108ebe0-ffffffff8108ec7d: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108bba0)
Location: kernel/resource.c:1425
Inline: False
Direct callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8108bba0-ffffffff8108bc3d: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092920)
Location: kernel/resource.c:1443
Inline: False
Direct callers:
  - mm/hmm.c:hmm_devmem_add
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff81092920-ffffffff810929bd: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810962e0)
Location: kernel/resource.c:1413
Inline: False
Direct callers:
  - mm/hmm.c:hmm_devmem_add
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff810962e0-ffffffff8109637d: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e650)
Location: kernel/resource.c:1423
Inline: False
Direct callers:
  - mm/hmm.c:hmm_devmem_add
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8109e650-ffffffff8109e6ed: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2c00)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - kernel/resource.c:devm_request_free_mem_region
  - lib/devres.c:devm_ioremap_resource
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810a2c00-ffffffff810a2ca0: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a91d0)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810a91d0-ffffffff810a9270: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b06c0)
Location: kernel/resource.c:1451
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810b06c0-ffffffff810b0760: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810abde0)
Location: kernel/resource.c:1524
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810abde0-ffffffff810abe80: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad3a0)
Location: kernel/resource.c:1577
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810ad3a0-ffffffff810ad43d: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bef10)
Location: kernel/resource.c:1577
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810bef10-ffffffff810befb4: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5e80)
Location: kernel/resource.c:1564
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810d5e80-ffffffff810d5f31: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f51b0)
Location: kernel/resource.c:1556
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810f51b0-ffffffff810f5261: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811015f0)
Location: kernel/resource.c:1556
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff811015f0-ffffffff811016a1: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110ad40)
Location: kernel/resource.c:1611
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff8110ad40-ffffffff8110adf1: __devm_request_region (STB_GLOBAL)
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
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100f30)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/bus/fsl-mc/mc-io.c:fsl_create_mc_io
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_request_port
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/edac/altera_edac.c:altr_edac_device_probe
```
**Symbols:**

```
ffff800010100f30-ffff800010100ff4: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d274)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_request_port
  - drivers/tty/serial/rda-uart.c:rda_uart_request_port
  - drivers/misc/sram.c:sram_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c035d274-c035d320: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000148490)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c000000000148490-c0000000001485b0: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8264)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffe0000c8264-ffffffe0000c82fe: __devm_request_region (STB_GLOBAL)
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
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2af0)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810a2af0-ffffffff810a2b90: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810914d0)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/dax/device.c:dev_dax_probe
  - drivers/dax/pmem/core.c:__dax_pmem_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810914d0-ffffffff81091570: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2aa0)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810a2aa0-ffffffff810a2b40: __devm_request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct resource *__devm_request_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aab20)
Location: kernel/resource.c:1446
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff810aab20-ffffffff810aabc0: __devm_request_region (STB_GLOBAL)
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
