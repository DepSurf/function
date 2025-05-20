# Function: <code>irq_domain_is_msi_parent</code>

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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a5100)
Location: include/linux/irqdomain.h:569
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_get_device_domain
  - kernel/irq/msi.c:msi_setup_device_data
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f6c6d)
Location: include/linux/irqdomain.h:569
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
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
In kernel/irq/msi.c (ffffffff811b81d4)
Location: include/linux/irqdomain.h:565
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_alloc_irqs_all_locked
  - kernel/irq/msi.c:__msi_domain_alloc_locked
  - kernel/irq/msi.c:msi_match_device_irq_domain
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_setup_device_data
  - kernel/irq/msi.c:msi_ctrl_valid
  - kernel/irq/msi.c:msi_insert_desc
```
```
In drivers/pci/msi/irqdomain.c (ffffffff8193a0cd)
Location: include/linux/irqdomain.h:565
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
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
In kernel/irq/msi.c (ffffffff811c8094)
Location: include/linux/irqdomain.h:565
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_alloc_irqs_all_locked
  - kernel/irq/msi.c:__msi_domain_alloc_locked
  - kernel/irq/msi.c:msi_match_device_irq_domain
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_setup_device_data
  - kernel/irq/msi.c:msi_ctrl_valid
  - kernel/irq/msi.c:msi_insert_desc
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81982f2d)
Location: include/linux/irqdomain.h:565
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
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
