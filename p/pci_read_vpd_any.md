# Function: <code>pci_read_vpd_any</code>

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
ssize_t pci_read_vpd_any(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff817ce1b2)
Location: drivers/pci/vpd.c:419
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_available
  - drivers/pci/vpd.c:pci_vpd_available
```
**Symbols:**

```
ffffffff817cea80-ffffffff817ceb25: pci_read_vpd_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd_any(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818edbc2)
Location: drivers/pci/vpd.c:419
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_available
  - drivers/pci/vpd.c:pci_vpd_available
```
**Symbols:**

```
ffffffff818ee5b0-ffffffff818ee655: pci_read_vpd_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd_any(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff819310c2)
Location: drivers/pci/vpd.c:419
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_available
  - drivers/pci/vpd.c:pci_vpd_available
```
**Symbols:**

```
ffffffff81931a90-ffffffff81931b35: pci_read_vpd_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd_any(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81979be2)
Location: drivers/pci/vpd.c:449
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_available
  - drivers/pci/vpd.c:pci_vpd_available
```
**Symbols:**

```
ffffffff8197a5c0-ffffffff8197a665: pci_read_vpd_any (STB_GLOBAL)
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
