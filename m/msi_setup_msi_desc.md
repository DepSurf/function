# Function: <code>msi_setup_msi_desc</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int msi_setup_msi_desc(struct pci_dev *dev, int nvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (0)
Location: drivers/pci/msi/msi.c:364
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff817d3b10-ffffffff817d3ca8: msi_setup_msi_desc (STB_LOCAL)
ffffffff81eac5fb-ffffffff81eac61f: msi_setup_msi_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int msi_setup_msi_desc(struct pci_dev *dev, int nvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (0)
Location: drivers/pci/msi/msi.c:281
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff818f4a40-ffffffff818f4bda: msi_setup_msi_desc (STB_LOCAL)
ffffffff8208f427-ffffffff8208f44b: msi_setup_msi_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int msi_setup_msi_desc(struct pci_dev *dev, int nvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (0)
Location: drivers/pci/msi/msi.c:281
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81937e70-ffffffff8193800a: msi_setup_msi_desc (STB_LOCAL)
ffffffff8210f7d3-ffffffff8210f7f7: msi_setup_msi_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int msi_setup_msi_desc(struct pci_dev *dev, int nvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (0)
Location: drivers/pci/msi/msi.c:282
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81980cd0-ffffffff81980e6a: msi_setup_msi_desc (STB_LOCAL)
ffffffff821ed469-ffffffff821ed48d: msi_setup_msi_desc.cold (STB_LOCAL)
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
