# Function: <code>msi_first_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct msi_desc *msi_first_desc(struct device *dev, enum msi_desc_filter filter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116eb09)
Location: kernel/irq/msi.c:267
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msi_verify_entries
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_check_cap
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_check_cap
  - arch/x86/pci/xen.c:xen_teardown_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs
```
**Symbols:**

```
ffffffff8116ea40-ffffffff8116ea7a: msi_first_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4bee)
Location: include/linux/msi.h:262
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In drivers/pci/msi/msi.c (ffffffff818f5967)
Location: include/linux/msi.h:262
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b6b1d)
Location: include/linux/msi.h:266
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In drivers/pci/msi/msi.c (ffffffff81938d97)
Location: include/linux/msi.h:266
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c69ef)
Location: include/linux/msi.h:266
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In drivers/pci/msi/msi.c (ffffffff81981bf7)
Location: include/linux/msi.h:266
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
