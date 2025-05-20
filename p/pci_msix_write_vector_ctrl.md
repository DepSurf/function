# Function: <code>pci_msix_write_vector_ctrl</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b1cbc)
Location: drivers/pci/msi.c:183
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d542d)
Location: drivers/pci/msi/msi.c:56
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
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
In drivers/pci/msi/msi.c (ffffffff818f636e)
Location: drivers/pci/msi/msi.h:35
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f657e)
Location: drivers/pci/msi/msi.h:35
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msix
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
In drivers/pci/msi/msi.c (ffffffff819397ce)
Location: drivers/pci/msi/msi.h:35
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff819399de)
Location: drivers/pci/msi/msi.h:35
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msix
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
In drivers/pci/msi/msi.c (ffffffff8198262e)
Location: drivers/pci/msi/msi.h:35
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff8198283e)
Location: drivers/pci/msi/msi.h:35
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msix
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
