# Function: <code>pci_mmap_resource_range</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff814b8ff0)
Location: drivers/pci/mmap.c:46
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff814b8ff0-ffffffff814b90da: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff814f9440)
Location: drivers/pci/mmap.c:46
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff814f9440-ffffffff814f952a: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81529f10)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81529f10-ffffffff81529feb: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8153fdc0)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff8153fdc0-ffffffff8153feaa: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8156f6a0)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff8156f6a0-ffffffff8156f796: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff815906e0)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff815906e0-ffffffff815907c4: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81638220)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81638220-ffffffff81638325: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8165cac0)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff8165cac0-ffffffff8165cbda: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8163f060)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff8163f060-ffffffff8163f17a: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff816afd50)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff816afd50-ffffffff816afef1: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff817d3290)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff817d3290-ffffffff817d3440: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff818f3c40)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff818f3c40-ffffffff818f3de4: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81937090)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff81937090-ffffffff8193721d: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8197fef0)
Location: drivers/pci/mmap.c:22
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff8197fef0-ffffffff8198007d: pci_mmap_resource_range (STB_GLOBAL)
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
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffff8000106f5818)
Location: drivers/pci/mmap.c:43
Inline: False
```
**Symbols:**

```
ffff8000106f5818-ffff8000106f58f8: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (c0890280)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_resource
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
c0890280-c0890340: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (c0000000008744b0)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
c0000000008744b0-c0000000008745e8: pci_mmap_resource_range (STB_GLOBAL)
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
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81584560)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81584560-ffffffff81584656: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81573340)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81573340-ffffffff81573424: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff81584430)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81584430-ffffffff81584514: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_mmap_resource_range(struct pci_dev *pdev, int bar, struct vm_area_struct *vma, enum pci_mmap_state mmap_state, int write_combine);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/mmap.c (ffffffff8159e8e0)
Location: drivers/pci/mmap.c:43
Inline: False
Direct callers:
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff8159e8e0-ffffffff8159e9c4: pci_mmap_resource_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
