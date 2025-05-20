# Function: <code>find_dev_pagemap</code>

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
struct dev_pagemap *find_dev_pagemap(resource_size_t phys);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119e603)
Location: kernel/memremap.c:257
Inline: True
Inline callers:
  - kernel/memremap.c:to_vmem_altmap
  - kernel/memremap.c:devm_memremap_pages
Direct callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff8119e590-ffffffff8119e5bb: find_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dev_pagemap *find_dev_pagemap(resource_size_t phys);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811ae033)
Location: kernel/memremap.c:263
Inline: True
Inline callers:
  - kernel/memremap.c:to_vmem_altmap
  - kernel/memremap.c:devm_memremap_pages
Direct callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff811adfc0-ffffffff811adfeb: find_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dev_pagemap *find_dev_pagemap(resource_size_t phys);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b54b3)
Location: kernel/memremap.c:253
Inline: True
Inline callers:
  - kernel/memremap.c:to_vmem_altmap
  - kernel/memremap.c:devm_memremap_pages
Direct callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff811b5440-ffffffff811b546e: find_dev_pagemap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dev_pagemap *find_dev_pagemap(resource_size_t phys);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c95a3)
Location: kernel/memremap.c:318
Inline: True
Inline callers:
  - kernel/memremap.c:to_vmem_altmap
  - kernel/memremap.c:devm_memremap_pages
Direct callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff811c9530-ffffffff811c955e: find_dev_pagemap (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
