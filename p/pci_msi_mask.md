# Function: <code>pci_msi_mask</code>

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
In drivers/pci/msi.c (ffffffff816b0c60)
Location: drivers/pci/msi.c:162
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi/msi.c (ffffffff817d423a)
Location: drivers/pci/msi/msi.c:35
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi/msi.c (ffffffff818f501f)
Location: drivers/pci/msi/msi.h:14
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f6774)
Location: drivers/pci/msi/msi.h:14
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
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
In drivers/pci/msi/msi.c (ffffffff8193844f)
Location: drivers/pci/msi/msi.h:14
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81939bd4)
Location: drivers/pci/msi/msi.h:14
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
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
In drivers/pci/msi/msi.c (ffffffff819812af)
Location: drivers/pci/msi/msi.h:14
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81982a34)
Location: drivers/pci/msi/msi.h:14
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
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
