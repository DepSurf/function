# Function: <code>pcie_get_width_cap</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151eeff)
Location: drivers/pci/pci.c:5310
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8151ee60-ffffffff8151eeb5: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534e7f)
Location: drivers/pci/pci.c:5597
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8152f4d0-ffffffff8152f525: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8156433d)
Location: drivers/pci/pci.c:5693
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8155ec30-ffffffff8155ec85: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158561d)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8157fd90-ffffffff8157fde5: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c17d)
Location: drivers/pci/pci.c:5844
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff81625300-ffffffff81625355: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651ecd)
Location: drivers/pci/pci.c:5918
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8164b430-ffffffff8164b485: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816349bd)
Location: drivers/pci/pci.c:5967
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8162e010-ffffffff8162e065: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a4aad)
Location: drivers/pci/pci.c:6157
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8169ca90-ffffffff8169cae5: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6f1f)
Location: drivers/pci/pci.c:6253
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff817beaa0-ffffffff817beb06: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e43cf)
Location: drivers/pci/pci.c:6200
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff818daf60-ffffffff818dafc6: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81927a1f)
Location: drivers/pci/pci.c:6322
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8191e2c0-ffffffff8191e326: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819701bf)
Location: drivers/pci/pci.c:6466
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff81966340-ffffffff819663a6: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9d70)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffff8000106e2928-ffff8000106e2994: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0884cf4)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
c087e58c-c087e5f8: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864ee8)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
c00000000085c2b0-c00000000085c328: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bffe4)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffe0004ba160-ffffffe0004ba1ac: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579b3d)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff815742b0-ffffffff81574305: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8156827d)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff81562a10-ffffffff81562a65: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157936d)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff81573ae0-ffffffff81573b35: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum pcie_link_width pcie_get_width_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815937fd)
Location: drivers/pci/pci.c:5823
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
Direct callers:
  - drivers/pci/pci-sysfs.c:max_link_width_show
```
**Symbols:**

```
ffffffff8158dfc0-ffffffff8158e015: pcie_get_width_cap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
