# Function: <code>msix_setup_msi_descs</code>

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
int msix_setup_msi_descs(struct pci_dev *dev, void *base, struct msix_entry *entries, int nvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d3e30)
Location: drivers/pci/msi/msi.c:505
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff817d3e30-ffffffff817d3ffb: msix_setup_msi_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msix_setup_msi_descs(struct pci_dev *dev, struct msix_entry *entries, int nvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f5a90)
Location: drivers/pci/msi/msi.c:607
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
```
**Symbols:**

```
ffffffff818f5a90-ffffffff818f5bc1: msix_setup_msi_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msix_setup_msi_descs(struct pci_dev *dev, struct msix_entry *entries, int nvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81938ec0)
Location: drivers/pci/msi/msi.c:607
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
```
**Symbols:**

```
ffffffff81938ec0-ffffffff81938ff5: msix_setup_msi_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msix_setup_msi_descs(struct pci_dev *dev, struct msix_entry *entries, int nvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81981d20)
Location: drivers/pci/msi/msi.c:609
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
```
**Symbols:**

```
ffffffff81981d20-ffffffff81981e55: msix_setup_msi_descs (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *base</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, base, entries, nvec, masks</code> ➡️ <code>dev, entries, nvec, masks</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
