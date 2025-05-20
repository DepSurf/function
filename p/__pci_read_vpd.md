# Function: <code>__pci_read_vpd</code>

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
ssize_t __pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf, bool check_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff817ceb49)
Location: drivers/pci/vpd.c:387
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:vpd_read
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_available
  - drivers/pci/vpd.c:pci_vpd_available
```
**Symbols:**

```
ffffffff817ce080-ffffffff817ce12f: __pci_read_vpd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t __pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf, bool check_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818ee689)
Location: drivers/pci/vpd.c:387
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:vpd_read
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_available
  - drivers/pci/vpd.c:pci_vpd_available
```
**Symbols:**

```
ffffffff818eda80-ffffffff818edb2f: __pci_read_vpd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t __pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf, bool check_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81931b69)
Location: drivers/pci/vpd.c:387
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:vpd_read
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_available
  - drivers/pci/vpd.c:pci_vpd_available
```
**Symbols:**

```
ffffffff81930f80-ffffffff81931030: __pci_read_vpd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t __pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf, bool check_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff819799b0)
Location: drivers/pci/vpd.c:417
Inline: True
Direct callers:
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:pci_vpd_available
  - drivers/pci/vpd.c:pci_vpd_available
```
**Symbols:**

```
ffffffff819799b0-ffffffff81979a60: __pci_read_vpd (STB_LOCAL)
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
