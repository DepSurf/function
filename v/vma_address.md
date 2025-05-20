# Function: <code>vma_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_address(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811ca5c0)
Location: mm/rmap.c:579
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811ca5c0-ffffffff811ca601: vma_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e6b71)
Location: mm/internal.h:326
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f7f11)
Location: mm/internal.h:329
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8120347b)
Location: mm/internal.h:343
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121bfbb)
Location: mm/internal.h:344
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123e0d6)
Location: mm/internal.h:344
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff8128898f)
Location: mm/internal.h:344
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81252669)
Location: mm/internal.h:344
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff8129d68f)
Location: mm/internal.h:344
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812647f6)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff812b89c5)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81273066)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff812ca8a5)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4096)
Location: mm/internal.h:393
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff81300695)
Location: mm/internal.h:393
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812af966)
Location: mm/internal.h:397
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff8130c842)
Location: mm/internal.h:397
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff812b2f94)
Location: mm/internal.h:392
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff812b4be4)
Location: mm/internal.h:392
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81312fa4)
Location: mm/internal.h:392
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff812f4b24)
Location: mm/internal.h:389
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff812f6a34)
Location: mm/internal.h:389
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8135fa64)
Location: mm/internal.h:389
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int vma_address(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff81357d60)
Location: mm/internal.h:579
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff8135bbbe)
Location: mm/internal.h:579
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff813da5ce)
Location: mm/internal.h:579
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff81357d60-ffffffff81357ef7: vma_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff813d31aa)
Location: mm/internal.h:577
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813d6879)
Location: mm/internal.h:577
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
long unsigned int vma_address(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff814070c0)
Location: mm/internal.h:648
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff8140b3a0)
Location: mm/internal.h:648
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
**Symbols:**

```
ffffffff814070c0-ffffffff814071ed: vma_address (STB_LOCAL)
ffffffff8140b3a0-ffffffff8140b4cd: vma_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
long unsigned int vma_address(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff81433770)
Location: mm/internal.h:728
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff81437cf0)
Location: mm/internal.h:728
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
**Symbols:**

```
ffffffff81433770-ffffffff8143385f: vma_address (STB_LOCAL)
ffffffff81437cf0-ffffffff81437ddf: vma_address (STB_LOCAL)
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
In mm/rmap.c (ffff800010308db0)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (0)
Location: mm/internal.h:352
Inline: True
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
In mm/rmap.c (c0525908)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d804c)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (c00000000045e940)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/rmap.c (ffffffe0002133e4)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b6b6)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff812c2e85)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125d956)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff812b3f85)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81269456)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff812c0c95)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81278f86)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/memory-failure.c (ffffffff812d1755)
Location: mm/internal.h:352
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
