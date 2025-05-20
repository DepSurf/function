# Function: <code>get_dev_pagemap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff810715bc)
Location: include/linux/memremap.h:84
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811d4c14)
Location: include/linux/memremap.h:84
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff8121498b)
Location: include/linux/memremap.h:84
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81075129)
Location: include/linux/memremap.h:84
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811e4c44)
Location: include/linux/memremap.h:84
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81226f1a)
Location: include/linux/memremap.h:84
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f0c9d)
Location: include/linux/memremap.h:84
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81233289)
Location: include/linux/memremap.h:84
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812057f2)
Location: include/linux/memremap.h:184
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81250bc5)
Location: include/linux/memremap.h:184
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811e9650)
Location: kernel/memremap.c:297
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff811e9650-ffffffff811e9722: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811f9ff0)
Location: kernel/memremap.c:288
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff811f9ff0-ffffffff811fa098: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812c2460)
Location: mm/memremap.c:365
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812c2460-ffffffff812c2511: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4390)
Location: mm/memremap.c:387
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812d4390-ffffffff812d4441: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130a040)
Location: mm/memremap.c:420
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
**Symbols:**

```
ffffffff8130a040-ffffffff8130a0f4: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81315cf0)
Location: mm/memremap.c:469
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
**Symbols:**

```
ffffffff81315cf0-ffffffff81315dd0: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131bee0)
Location: mm/memremap.c:475
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
**Symbols:**

```
ffffffff8131bee0-ffffffff8131bfc3: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813691c0)
Location: mm/memremap.c:472
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
```
**Symbols:**

```
ffffffff813691c0-ffffffff813692a3: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813e6fd0)
Location: mm/memremap.c:430
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff813e6fd0-ffffffff813e70c2: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8146ec30)
Location: mm/memremap.c:446
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff8146ec30-ffffffff8146ed0e: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814a33f0)
Location: mm/memremap.c:446
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff814a33f0-ffffffff814a34ce: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814d4290)
Location: mm/memremap.c:434
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff814d4290-ffffffff814d436e: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046da10)
Location: mm/memremap.c:387
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
c00000000046da10-c00000000046dba4: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/memremap.h:153
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/memremap.h:153
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
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cc970)
Location: mm/memremap.c:387
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812cc970-ffffffff812cca21: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812bd7e0)
Location: mm/memremap.c:387
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812bd7e0-ffffffff812bd891: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812ca780)
Location: mm/memremap.c:387
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812ca780-ffffffff812ca831: get_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dev_pagemap *get_dev_pagemap(long unsigned int pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812db480)
Location: mm/memremap.c:387
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812db480-ffffffff812db570: get_dev_pagemap (STB_GLOBAL)
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
