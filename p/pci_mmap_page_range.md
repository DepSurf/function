# Function: <code>pci_mmap_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *dev, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff816f65a0)
Location: arch/x86/pci/i386.c:414
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff816f65a0-ffffffff816f665d: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *dev, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8175b210)
Location: arch/x86/pci/i386.c:414
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff8175b210-ffffffff8175b2d2: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *dev, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81787790)
Location: arch/x86/pci/i386.c:414
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff81787790-ffffffff8178784f: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff814b90e0)
Location: drivers/pci/mmap.c:25
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff814b90e0-ffffffff814b910b: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff814f9530)
Location: drivers/pci/mmap.c:25
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff814f9530-ffffffff814f955a: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81529ff0)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff81529ff0-ffffffff8152a01a: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8153feb0)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff8153feb0-ffffffff8153feda: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8156f7a0)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff8156f7a0-ffffffff8156f7ca: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff815907d0)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff815907d0-ffffffff81590866: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81638330)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff81638330-ffffffff816383c6: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8165cbe0)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff8165cbe0-ffffffff8165cc76: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8163f180)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff8163f180-ffffffff8163f216: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff816aff00)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff816aff00-ffffffff816affba: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff817d3440)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff817d3440-ffffffff817d351a: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (c0890340)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
c0890340-c08903e4: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (c0000000008745f0)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
c0000000008745f0-c0000000008746c8: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81584660)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff81584660-ffffffff815846f6: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81573430)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff81573430-ffffffff815734c6: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81584520)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff81584520-ffffffff815845b6: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_mmap_page_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8159e9d0)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff8159e9d0-ffffffff8159ea66: pci_mmap_page_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *pdev</code>
</li>
<li>
<b>Param added. </b>
<code>int bar</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pci_dev *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, vma, mmap_state, write_combine</code> ➡️ <code>pdev, bar, vma, mmap_state, write_combine</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
