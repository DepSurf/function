# Function: <code>msi_domain_first_desc</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct msi_desc *msi_domain_first_desc(struct device *dev, unsigned int domid, enum msi_desc_filter filter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4bee)
Location: kernel/irq/msi.c:376
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
Direct callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:msi_verify_entries
  - arch/x86/pci/xen.c:xen_teardown_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs
```
**Symbols:**

```
ffffffff811a3570-ffffffff811a35b2: msi_domain_first_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct msi_desc *msi_domain_first_desc(struct device *dev, unsigned int domid, enum msi_desc_filter filter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b6b1d)
Location: kernel/irq/msi.c:376
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
Direct callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:msi_verify_entries
  - arch/x86/pci/xen.c:xen_teardown_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs
```
**Symbols:**

```
ffffffff811b5440-ffffffff811b5482: msi_domain_first_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct msi_desc *msi_domain_first_desc(struct device *dev, unsigned int domid, enum msi_desc_filter filter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c69ef)
Location: kernel/irq/msi.c:376
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
Direct callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:msi_verify_entries
  - arch/x86/pci/xen.c:xen_teardown_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs
```
**Symbols:**

```
ffffffff811c52c0-ffffffff811c5302: msi_domain_first_desc (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
