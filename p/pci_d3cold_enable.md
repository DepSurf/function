# Function: <code>pci_d3cold_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481730)
Location: drivers/pci/pci.c:2312
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81481730-ffffffff81481757: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4660)
Location: drivers/pci/pci.c:2350
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff814a4660-ffffffff814a4685: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae720)
Location: drivers/pci/pci.c:2367
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff814ae720-ffffffff814ae746: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814edaf0)
Location: drivers/pci/pci.c:2376
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff814edaf0-ffffffff814edb16: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d720)
Location: drivers/pci/pci.c:2451
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff8151d720-ffffffff8151d745: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532e60)
Location: drivers/pci/pci.c:2641
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81532e60-ffffffff81532e85: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815625d0)
Location: drivers/pci/pci.c:2756
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff815625d0-ffffffff815625f5: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81583770)
Location: drivers/pci/pci.c:2752
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81583770-ffffffff81583795: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162a2d0)
Location: drivers/pci/pci.c:2822
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff8162a2d0-ffffffff8162a2f5: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81650730)
Location: drivers/pci/pci.c:2989
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81650730-ffffffff81650755: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633340)
Location: drivers/pci/pci.c:3019
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81633340-ffffffff81633365: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a34e0)
Location: drivers/pci/pci.c:3061
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff816a34e0-ffffffff816a3505: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c5720)
Location: drivers/pci/pci.c:3148
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff817c5720-ffffffff817c5755: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e2820)
Location: drivers/pci/pci.c:3098
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff818e2820-ffffffff818e2855: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925c60)
Location: drivers/pci/pci.c:3136
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81925c60-ffffffff81925c95: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196e3e0)
Location: drivers/pci/pci.c:3249
Inline: True
```
**Symbols:**

```
ffffffff8196e3e0-ffffffff8196e415: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e7738)
Location: drivers/pci/pci.c:2752
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffff8000106e7738-ffff8000106e7780: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0882844)
Location: drivers/pci/pci.c:2752
Inline: False
```
**Symbols:**

```
c0882844-c0882874: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861f50)
Location: drivers/pci/pci.c:2752
Inline: False
```
**Symbols:**

```
c000000000861f50-c000000000861f78: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bde14)
Location: drivers/pci/pci.c:2752
Inline: False
```
**Symbols:**

```
ffffffe0004bde14-ffffffe0004bde5a: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577c90)
Location: drivers/pci/pci.c:2752
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81577c90-ffffffff81577cb5: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815663d0)
Location: drivers/pci/pci.c:2752
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff815663d0-ffffffff815663f5: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815774c0)
Location: drivers/pci/pci.c:2752
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff815774c0-ffffffff815774e5: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_d3cold_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81591980)
Location: drivers/pci/pci.c:2752
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81591980-ffffffff815919a5: pci_d3cold_enable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
