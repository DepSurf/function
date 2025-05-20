# Function: <code>follow_devmap_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81214850)
Location: mm/huge_memory.c:704
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff81214850-ffffffff81214aed: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81226de0)
Location: mm/huge_memory.c:776
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff81226de0-ffffffff812270d5: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81232c90)
Location: mm/huge_memory.c:862
Inline: False
```
**Symbols:**

```
ffffffff81232c90-ffffffff81232f22: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812503f0)
Location: mm/huge_memory.c:857
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffffffff812503f0-ffffffff812506c3: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81274a00)
Location: mm/huge_memory.c:854
Inline: False
```
**Symbols:**

```
ffffffff81274a00-ffffffff81274c4f: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812899c0)
Location: mm/huge_memory.c:873
Inline: False
```
**Symbols:**

```
ffffffff812899c0-ffffffff81289be5: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a45e0)
Location: mm/huge_memory.c:929
Inline: False
```
**Symbols:**

```
ffffffff812a45e0-ffffffff812a480a: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b5aa0)
Location: mm/huge_memory.c:935
Inline: False
```
**Symbols:**

```
ffffffff812b5aa0-ffffffff812b5cca: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812eab40)
Location: mm/huge_memory.c:970
Inline: False
```
**Symbols:**

```
ffffffff812eab40-ffffffff812ead9e: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f6090)
Location: mm/huge_memory.c:962
Inline: False
```
**Symbols:**

```
ffffffff812f6090-ffffffff812f62ee: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fc440)
Location: mm/huge_memory.c:978
Inline: False
```
**Symbols:**

```
ffffffff812fc440-ffffffff812fc69d: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:978
Inline: False
```
**Symbols:**

```
ffffffff81cc25d6-ffffffff81cc2601: follow_devmap_pmd.cold (STB_LOCAL)
ffffffff813462b0-ffffffff81346517: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bc460)
Location: mm/huge_memory.c:972
Inline: False
```
**Symbols:**

```
ffffffff813bc460-ffffffff813bc68b: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143e9f0)
Location: mm/huge_memory.c:1032
Inline: False
```
**Symbols:**

```
ffffffff8143e9f0-ffffffff8143ec20: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814741e0)
Location: mm/huge_memory.c:1027
Inline: False
```
**Symbols:**

```
ffffffff814741e0-ffffffff814743eb: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a3760)
Location: mm/huge_memory.c:1242
Inline: False
```
**Symbols:**

```
ffffffff814a3760-ffffffff814a3991: follow_devmap_pmd (STB_GLOBAL)
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
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010356c28)
Location: mm/huge_memory.c:935
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffff800010356c28-ffff800010356d38: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/huge_mm.h:392
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043e690)
Location: mm/huge_memory.c:935
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
c00000000043e690-c00000000043e8f8: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/huge_mm.h:392
Inline: True
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
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ae080)
Location: mm/huge_memory.c:935
Inline: False
```
**Symbols:**

```
ffffffff812ae080-ffffffff812ae2aa: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129f6e0)
Location: mm/huge_memory.c:935
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffffffff8129f6e0-ffffffff8129f900: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812abe90)
Location: mm/huge_memory.c:935
Inline: False
```
**Symbols:**

```
ffffffff812abe90-ffffffff812ac0ba: follow_devmap_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *follow_devmap_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bc200)
Location: mm/huge_memory.c:935
Inline: False
```
**Symbols:**

```
ffffffff812bc200-ffffffff812bc42a: follow_devmap_pmd (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dev_pagemap **pgmap</code>
</li>
</ul>
</details>
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
