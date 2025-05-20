# Function: <code>__pci_write_vpd</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff817ce875)
Location: drivers/pci/vpd.c:425
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818ee375)
Location: drivers/pci/vpd.c:425
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81931855)
Location: drivers/pci/vpd.c:425
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t __pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf, bool check_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8197a445)
Location: drivers/pci/vpd.c:455
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:pci_write_vpd_any
Direct callers:
  - drivers/pci/vpd.c:vpd_write
```
**Symbols:**

```
ffffffff8197a120-ffffffff8197a1d0: __pci_write_vpd (STB_LOCAL)
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
