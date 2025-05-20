# Function: <code>msi_domain_alloc_irq_at</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
struct msi_map msi_domain_alloc_irq_at(struct device *dev, unsigned int domid, unsigned int index, const struct irq_affinity_desc *affdesc, union msi_instance_cookie *icookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a5a80)
Location: kernel/irq/msi.c:1472
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_ims_alloc_irq
```
**Symbols:**

```
ffffffff811a5a80-ffffffff811a5bf8: msi_domain_alloc_irq_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct msi_map msi_domain_alloc_irq_at(struct device *dev, unsigned int domid, unsigned int index, const struct irq_affinity_desc *affdesc, union msi_instance_cookie *icookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b7d20)
Location: kernel/irq/msi.c:1469
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_ims_alloc_irq
```
**Symbols:**

```
ffffffff811b7d20-ffffffff811b7f09: msi_domain_alloc_irq_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct msi_map msi_domain_alloc_irq_at(struct device *dev, unsigned int domid, unsigned int index, const struct irq_affinity_desc *affdesc, union msi_instance_cookie *icookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c7be0)
Location: kernel/irq/msi.c:1459
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_ims_alloc_irq
```
**Symbols:**

```
ffffffff811c7be0-ffffffff811c7dc9: msi_domain_alloc_irq_at (STB_GLOBAL)
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
