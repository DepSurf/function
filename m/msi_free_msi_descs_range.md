# Function: <code>msi_free_msi_descs_range</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void msi_free_msi_descs_range(struct device *dev, enum msi_desc_filter filter, unsigned int first_index, unsigned int last_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116ee00)
Location: kernel/irq/msi.c:148
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs_descs_locked
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_add_simple_msi_descs
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff8116ee00-ffffffff8116eee3: msi_free_msi_descs_range (STB_GLOBAL)
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
In drivers/pci/msi/irqdomain.c (ffffffff818f6a34)
Location: include/linux/msi.h:354
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
```
```
In drivers/base/platform-msi.c (ffffffff81b29550)
Location: include/linux/msi.h:354
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
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
In drivers/pci/msi/irqdomain.c (ffffffff81939e8d)
Location: include/linux/msi.h:358
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
```
```
In drivers/base/platform-msi.c (ffffffff81b79700)
Location: include/linux/msi.h:358
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
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
In drivers/pci/msi/irqdomain.c (ffffffff81982ced)
Location: include/linux/msi.h:358
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
```
```
In drivers/base/platform-msi.c (ffffffff81bcd630)
Location: include/linux/msi.h:358
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
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
