# Function: <code>pci_vpd_available</code>

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
In drivers/pci/vpd.c (ffffffff816ab4cc)
Location: drivers/pci/vpd.c:102
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool pci_vpd_available(struct pci_dev *dev, bool check_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:99
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff817ce130-ffffffff817ce279: pci_vpd_available (STB_LOCAL)
ffffffff81eabd3d-ffffffff81eabddc: pci_vpd_available.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_vpd_available(struct pci_dev *dev, bool check_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818edb40)
Location: drivers/pci/vpd.c:99
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff818edb40-ffffffff818edd16: pci_vpd_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_vpd_available(struct pci_dev *dev, bool check_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81931040)
Location: drivers/pci/vpd.c:99
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff81931040-ffffffff819311fe: pci_vpd_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_vpd_available(struct pci_dev *dev, bool check_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81979b60)
Location: drivers/pci/vpd.c:99
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff81979b60-ffffffff81979d1e: pci_vpd_available (STB_LOCAL)
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
