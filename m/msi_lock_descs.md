# Function: <code>msi_lock_descs</code>

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
void msi_lock_descs(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116fa85)
Location: kernel/irq/msi.c:226
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_get_virq
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff8116e1b0-ffffffff8116e1d1: msi_lock_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void msi_lock_descs(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a5e36)
Location: kernel/irq/msi.c:332
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_free_irqs_range
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_alloc_irqs_range
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_match_device_irq_domain
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_domain_get_virq
Direct callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff811a36a0-ffffffff811a36c1: msi_lock_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void msi_lock_descs(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b818a)
Location: kernel/irq/msi.c:332
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_free_irqs_range
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_alloc_irqs_range
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_match_device_irq_domain
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_domain_get_virq
Direct callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff811b5570-ffffffff811b5591: msi_lock_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void msi_lock_descs(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c804a)
Location: kernel/irq/msi.c:332
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_free_irqs_range
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_alloc_irqs_range
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_match_device_irq_domain
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_domain_get_virq
Direct callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff811c53f0-ffffffff811c5411: msi_lock_descs (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
