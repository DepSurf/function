# Function: <code>__devm_release_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086970)
Location: kernel/resource.c:1382
Inline: True
```
**Symbols:**

```
ffffffff81086970-ffffffff810869f6: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810899c0)
Location: kernel/resource.c:1451
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810899c0-ffffffff81089a46: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e910)
Location: kernel/resource.c:1451
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8108e910-ffffffff8108e996: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b8f0)
Location: kernel/resource.c:1451
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8108b8f0-ffffffff8108b967: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092670)
Location: kernel/resource.c:1469
Inline: True
Direct callers:
  - mm/hmm.c:hmm_devmem_add
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81092670-ffffffff810926e7: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096030)
Location: kernel/resource.c:1439
Inline: True
Direct callers:
  - mm/hmm.c:hmm_devmem_add
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81096030-ffffffff810960a7: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e3a0)
Location: kernel/resource.c:1448
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8109e3a0-ffffffff8109e417: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff810a3964)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810a3964-ffffffff810a3977: __devm_release_region.cold (STB_LOCAL)
ffffffff810a2920-ffffffff810a2999: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8ef0)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810a8ef0-ffffffff810a8f69: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0320)
Location: kernel/resource.c:1476
Inline: True
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810b0320-ffffffff810b0397: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aba40)
Location: kernel/resource.c:1549
Inline: True
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810aba40-ffffffff810abab7: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810acdc0)
Location: kernel/resource.c:1602
Inline: True
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810acdc0-ffffffff810ace37: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810be930)
Location: kernel/resource.c:1602
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810be930-ffffffff810be9a7: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6050)
Location: kernel/resource.c:1589
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810d6050-ffffffff810d60d4: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f53e0)
Location: kernel/resource.c:1581
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810f53e0-ffffffff810f5464: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81101820)
Location: kernel/resource.c:1581
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81101820-ffffffff811018a4: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110af70)
Location: kernel/resource.c:1636
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8110af70-ffffffff8110aff4: __devm_release_region (STB_GLOBAL)
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
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100c40)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/bus/fsl-mc/mc-io.c:fsl_destroy_mc_io
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/tty/serial/meson_uart.c:meson_uart_release_port
  - drivers/tty/serial/owl-uart.c:owl_uart_release_port
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffff800010100c40-ffff800010100ce8: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035ce6c)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_free
  - drivers/tty/serial/meson_uart.c:meson_uart_release_port
  - drivers/tty/serial/owl-uart.c:owl_uart_release_port
  - drivers/tty/serial/rda-uart.c:rda_uart_release_port
```
**Symbols:**

```
c035ce6c-c035cf20: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147f60)
Location: kernel/resource.c:1471
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
c000000000147f60-c000000000148010: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8404)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffe0000c8404-ffffffe0000c8482: __devm_release_region (STB_GLOBAL)
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
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2810)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810a2810-ffffffff810a2889: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810911f0)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810911f0-ffffffff81091269: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a27c0)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810a27c0-ffffffff810a2839: __devm_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __devm_release_region(struct device *dev, struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa830)
Location: kernel/resource.c:1471
Inline: True
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff810aa830-ffffffff810aa8a9: __devm_release_region (STB_GLOBAL)
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
