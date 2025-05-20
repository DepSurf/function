# Function: <code>msi_create_irq_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810e2e90)
Location: kernel/irq/msi.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff810e2e90-ffffffff810e2f69: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810e8930)
Location: kernel/irq/msi.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff810e8930-ffffffff810e8a09: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810ef3c0)
Location: kernel/irq/msi.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff810ef3c0-ffffffff810ef49c: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810ef1d0)
Location: kernel/irq/msi.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff810ef1d0-ffffffff810ef2e7: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810f7cc0)
Location: kernel/irq/msi.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff810f7cc0-ffffffff810f7dd3: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811000b0)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff811000b0-ffffffff811001c7: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8110b880)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff8110b880-ffffffff8110b997: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81114f70)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81114f70-ffffffff81115084: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81121160)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81121160-ffffffff81121274: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8112d740)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff8112d740-ffffffff8112d85a: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81129250)
Location: kernel/irq/msi.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_create_irq_domain
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff81129250-ffffffff811293d5: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81129530)
Location: kernel/irq/msi.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff81129530-ffffffff811296b5: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81149e60)
Location: kernel/irq/msi.c:425
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff81149e60-ffffffff81149fe5: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116f100)
Location: kernel/irq/msi.c:679
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff8116f100-ffffffff8116f2a8: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a5040)
Location: kernel/irq/msi.c:850
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff811a5040-ffffffff811a5061: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b71d0)
Location: kernel/irq/msi.c:847
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff811b71d0-ffffffff811b71f1: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c7090)
Location: kernel/irq/msi.c:847
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff811c7090-ffffffff811c70b1: msi_create_irq_domain (STB_GLOBAL)
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
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffff800010187338)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/fsl-mc-msi.c:fsl_mc_msi_create_irq_domain
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/soc/ti/ti_sci_inta_msi.c:ti_sci_inta_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffff800010187338-ffff800010187494: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (c03d5f30)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
c03d5f30-c03d6090: msi_create_irq_domain (STB_GLOBAL)
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
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffe00011cfba)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffe00011cfba-ffffffe00011d0ac: msi_create_irq_domain (STB_GLOBAL)
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
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81119740)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81119740-ffffffff81119854: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8110a7b0)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff8110a7b0-ffffffff8110a8c4: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81117630)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81117630-ffffffff81117744: msi_create_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_domain *msi_create_irq_domain(struct fwnode_handle *fwnode, struct msi_domain_info *info, struct irq_domain *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81122cc0)
Location: kernel/irq/msi.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81122cc0-ffffffff81122dd4: msi_create_irq_domain (STB_GLOBAL)
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
