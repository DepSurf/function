# Function: <code>pci_msi_create_irq_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81453bb0)
Location: drivers/pci/msi.c:1273
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - arch/x86/kernel/apic/msi.c:arch_create_msi_irq_domain
  - drivers/pci/msi.c:pci_msi_create_default_irq_domain
```
**Symbols:**

```
ffffffff81453bb0-ffffffff81453c53: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a04d0)
Location: drivers/pci/msi.c:1406
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/pci/msi.c:pci_msi_create_default_irq_domain
```
**Symbols:**

```
ffffffff814a04d0-ffffffff814a057e: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c2080)
Location: drivers/pci/msi.c:1472
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/pci/msi.c:pci_msi_create_default_irq_domain
```
**Symbols:**

```
ffffffff814c2080-ffffffff814c212e: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cc5c0)
Location: drivers/pci/msi.c:1432
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff814cc5c0-ffffffff814cc67f: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150caf0)
Location: drivers/pci/msi.c:1432
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff8150caf0-ffffffff8150cbaf: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81541940)
Location: drivers/pci/msi.c:1431
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff81541940-ffffffff81541a13: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81558dc0)
Location: drivers/pci/msi.c:1451
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff81558dc0-ffffffff81558e9d: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1481
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff8158a939-ffffffff8158a963: pci_msi_create_irq_domain.cold (STB_LOCAL)
ffffffff81588e80-ffffffff81588f65: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aa820)
Location: drivers/pci/msi.c:1482
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff815aa820-ffffffff815aa903: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816534e0)
Location: drivers/pci/msi.c:1466
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
**Symbols:**

```
ffffffff816534e0-ffffffff816535cf: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165d380)
Location: drivers/pci/msi.c:1481
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
**Symbols:**

```
ffffffff8165d380-ffffffff8165d47e: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8163f7c0)
Location: drivers/pci/msi.c:1487
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
**Symbols:**

```
ffffffff8163f7c0-ffffffff8163f8c2: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b0830)
Location: drivers/pci/msi.c:1405
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
**Symbols:**

```
ffffffff816b0830-ffffffff816b0932: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff817d56b0)
Location: drivers/pci/msi/irqdomain.c:161
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
**Symbols:**

```
ffffffff817d56b0-ffffffff817d57ab: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff818f68d0)
Location: drivers/pci/msi/irqdomain.c:114
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
**Symbols:**

```
ffffffff818f68d0-ffffffff818f6997: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff81939d30)
Location: drivers/pci/msi/irqdomain.c:114
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
**Symbols:**

```
ffffffff81939d30-ffffffff81939df7: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff81982b90)
Location: drivers/pci/msi/irqdomain.c:114
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
**Symbols:**

```
ffffffff81982b90-ffffffff81982c57: pci_msi_create_irq_domain (STB_GLOBAL)
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
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010713df8)
Location: drivers/pci/msi.c:1482
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init_one
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
```
**Symbols:**

```
ffff800010713df8-ffff800010713f58: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089e64c)
Location: drivers/pci/msi.c:1482
Inline: False
Direct callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
```
**Symbols:**

```
c089e64c-c089e79c: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004dd8be)
Location: drivers/pci/msi.c:1482
Inline: False
```
**Symbols:**

```
ffffffe0004dd8be-ffffffe0004dd9b8: pci_msi_create_irq_domain (STB_GLOBAL)
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
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159dff0)
Location: drivers/pci/msi.c:1482
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff8159dff0-ffffffff8159e0d3: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158d180)
Location: drivers/pci/msi.c:1482
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff8158d180-ffffffff8158d263: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159e570)
Location: drivers/pci/msi.c:1482
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff8159e570-ffffffff8159e653: pci_msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_domain *pci_msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b89a0)
Location: drivers/pci/msi.c:1482
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
**Symbols:**

```
ffffffff815b89a0-ffffffff815b8a83: pci_msi_create_irq_domain (STB_GLOBAL)
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
