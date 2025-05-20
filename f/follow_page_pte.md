# Function: <code>follow_page_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811ba3a0)
Location: mm/gup.c:61
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff811ba3a0-ffffffff811ba74f: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d47f0)
Location: mm/gup.c:63
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff811d47f0-ffffffff811d4e19: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e4840)
Location: mm/gup.c:73
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff811e4840-ffffffff811e4e31: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811eeea0)
Location: mm/gup.c:73
Inline: False
```
**Symbols:**

```
ffffffff811eeea0-ffffffff811ef435: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81205f30)
Location: mm/gup.c:73
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffffffff81205f30-ffffffff81206598: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81226240)
Location: mm/gup.c:73
Inline: False
```
**Symbols:**

```
ffffffff81226240-ffffffff81226842: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123a5a0)
Location: mm/gup.c:78
Inline: False
```
**Symbols:**

```
ffffffff8123a5a0-ffffffff8123ab69: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124b8c0)
Location: mm/gup.c:188
Inline: False
```
**Symbols:**

```
ffffffff8124b8c0-ffffffff8124bea0: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81259db0)
Location: mm/gup.c:173
Inline: False
```
**Symbols:**

```
ffffffff81259db0-ffffffff8125a390: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81288290)
Location: mm/gup.c:402
Inline: False
```
**Symbols:**

```
ffffffff81288290-ffffffff8128886a: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291f70)
Location: mm/gup.c:366
Inline: False
```
**Symbols:**

```
ffffffff81291f70-ffffffff81292548: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81297b40)
Location: mm/gup.c:475
Inline: False
```
**Symbols:**

```
ffffffff81297b40-ffffffff81297ff0: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d8580)
Location: mm/gup.c:498
Inline: False
```
**Symbols:**

```
ffffffff812d8580-ffffffff812d8a30: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813384f0)
Location: mm/gup.c:520
Inline: False
```
**Symbols:**

```
ffffffff813384f0-ffffffff81338a38: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813afd30)
Location: mm/gup.c:534
Inline: False
```
**Symbols:**

```
ffffffff813afd30-ffffffff813b02c3: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e4430)
Location: mm/gup.c:579
Inline: False
```
**Symbols:**

```
ffffffff813e4430-ffffffff813e489d: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140ec50)
Location: mm/gup.c:579
Inline: False
```
**Symbols:**

```
ffffffff8140ec50-ffffffff8140f0fc: follow_page_pte (STB_LOCAL)
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
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f18d0)
Location: mm/gup.c:173
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffff8000102f18d0-ffff8000102f1e6c: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (c05140e0)
Location: mm/gup.c:173
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
c05140e0-c051451c: follow_page_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b5da0)
Location: mm/gup.c:173
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
c0000000003b5da0-c0000000003b66fc: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffe0002045c8)
Location: mm/gup.c:173
Inline: True
```
**Symbols:**

```
ffffffe0002045c8-ffffffe000204962: follow_page_pte.isra.0 (STB_LOCAL)
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
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81252400)
Location: mm/gup.c:173
Inline: False
```
**Symbols:**

```
ffffffff81252400-ffffffff812529e0: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812451c0)
Location: mm/gup.c:173
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
```
**Symbols:**

```
ffffffff812451c0-ffffffff81245788: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812501a0)
Location: mm/gup.c:173
Inline: False
```
**Symbols:**

```
ffffffff812501a0-ffffffff81250780: follow_page_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *follow_page_pte(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmd, unsigned int flags, struct dev_pagemap **pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125fb30)
Location: mm/gup.c:173
Inline: False
```
**Symbols:**

```
ffffffff8125fb30-ffffffff812600fe: follow_page_pte (STB_LOCAL)
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
