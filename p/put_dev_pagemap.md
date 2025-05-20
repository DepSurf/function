# Function: <code>put_dev_pagemap</code>

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
In arch/x86/mm/gup.c (ffffffff81071618)
Location: include/linux/memremap.h:109
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/memremap.c (ffffffff8119e319)
Location: include/linux/memremap.h:109
Inline: True
Inline callers:
  - kernel/memremap.c:put_zone_device_page
```
```
In mm/gup.c (ffffffff811d4ca9)
Location: include/linux/memremap.h:109
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812149fb)
Location: include/linux/memremap.h:109
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
In arch/x86/mm/gup.c (ffffffff81075189)
Location: include/linux/memremap.h:109
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/memremap.c (ffffffff811add49)
Location: include/linux/memremap.h:109
Inline: True
Inline callers:
  - kernel/memremap.c:put_zone_device_page
```
```
In mm/gup.c (ffffffff811e4ce2)
Location: include/linux/memremap.h:109
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81226f87)
Location: include/linux/memremap.h:109
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
In mm/swap.c (ffffffff811cba39)
Location: include/linux/memremap.h:109
Inline: True
```
```
In mm/gup.c (ffffffff811f0bcf)
Location: include/linux/memremap.h:109
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812332d6)
Location: include/linux/memremap.h:109
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
In mm/swap.c (ffffffff811e0437)
Location: include/linux/memremap.h:209
Inline: True
```
```
In mm/gup.c (ffffffff8120574e)
Location: include/linux/memremap.h:209
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81250c12)
Location: include/linux/memremap.h:209
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
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
In kernel/memremap.c (ffffffff811e9678)
Location: include/linux/memremap.h:162
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/swap.c (ffffffff812013b7)
Location: include/linux/memremap.h:162
Inline: True
```
```
In mm/gup.c (ffffffff81226c14)
Location: include/linux/memremap.h:162
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81275127)
Location: include/linux/memremap.h:162
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memory-failure.c (ffffffff812896bb)
Location: include/linux/memremap.h:162
Inline: True
```
```
In drivers/dax/super.c (ffffffff816e2244)
Location: include/linux/memremap.h:162
Inline: True
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
In kernel/memremap.c (ffffffff811fa018)
Location: include/linux/memremap.h:138
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/swap.c (ffffffff81214669)
Location: include/linux/memremap.h:138
Inline: True
```
```
In mm/gup.c (ffffffff81239d17)
Location: include/linux/memremap.h:138
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff8129e517)
Location: include/linux/memremap.h:138
Inline: True
```
```
In drivers/dax/super.c (ffffffff8170565f)
Location: include/linux/memremap.h:138
Inline: True
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
In mm/swap.c (ffffffff81224324)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/gup.c (ffffffff8124afb1)
Location: include/linux/memremap.h:169
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff812ba25f)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/memremap.c (ffffffff812c2488)
Location: include/linux/memremap.h:169
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
```
```
In mm/hmm.c (ffffffff812c5000)
Location: include/linux/memremap.h:169
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (ffffffff8173f7ff)
Location: include/linux/memremap.h:169
Inline: True
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
In mm/swap.c (ffffffff812320bc)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (ffffffff812594a1)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff812cc11b)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812d43b8)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812d69b0)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (ffffffff817639df)
Location: include/linux/memremap.h:170
Inline: True
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
In mm/swap.c (ffffffff8125e4cf)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - mm/swap.c:__put_page
```
```
In mm/gup.c (ffffffff8128a900)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff81300fa7)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8130a068)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In drivers/dax/super.c (ffffffff818238af)
Location: include/linux/memremap.h:179
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In mm/swap.c (ffffffff8126880b)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff812945b0)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff8130ddb5)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff81315d20)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
```
In drivers/dax/super.c (ffffffff818324e7)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In mm/swap.c (ffffffff8126e57b)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff8129a000)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory_hotplug.c (ffffffff812c643a)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/memory-failure.c (ffffffff813140d0)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8131bf10)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
```
In drivers/dax/super.c (ffffffff818152d7)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In mm/swap.c (ffffffff812ab584)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff812da98d)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory_hotplug.c (ffffffff8130af2a)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/memory-failure.c (ffffffff8136024f)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff813691f0)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
```
In drivers/dax/super.c (ffffffff8189fb01)
Location: include/linux/memremap.h:191
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133a4da)
Location: include/linux/memremap.h:211
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory_hotplug.c (ffffffff8137460c)
Location: include/linux/memremap.h:211
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/memory-failure.c (ffffffff813db102)
Location: include/linux/memremap.h:211
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff813e7005)
Location: include/linux/memremap.h:211
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
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
In mm/gup.c (ffffffff813b1f98)
Location: include/linux/memremap.h:248
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory_hotplug.c (ffffffff813f1769)
Location: include/linux/memremap.h:248
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/memory-failure.c (ffffffff8146146f)
Location: include/linux/memremap.h:248
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8146fb28)
Location: include/linux/memremap.h:248
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e6d38)
Location: include/linux/memremap.h:248
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory_hotplug.c (ffffffff814252a7)
Location: include/linux/memremap.h:248
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/memory-failure.c (ffffffff814980bf)
Location: include/linux/memremap.h:248
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff814a4308)
Location: include/linux/memremap.h:248
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff814119c5)
Location: include/linux/memremap.h:237
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory_hotplug.c (ffffffff814524e8)
Location: include/linux/memremap.h:237
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/memory-failure.c (ffffffff814c7736)
Location: include/linux/memremap.h:237
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff814d514a)
Location: include/linux/memremap.h:237
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
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
In mm/swap.c (0)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (ffff8000102f26d8)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (0)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/hmm.c (ffff80001037b878)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (0)
Location: include/linux/memremap.h:170
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
In mm/swap.c (0)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/hmm.c (c0566598)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (0)
Location: include/linux/memremap.h:170
Inline: True
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
In mm/swap.c (c00000000037be34)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (c0000000003b7130)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (c000000000461360)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (c00000000046da64)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (c000000000470a1c)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (c000000000a19fd0)
Location: include/linux/memremap.h:170
Inline: True
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
In mm/swap.c (0)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (ffffffe000204bb2)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/hmm.c (ffffffe000251f74)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (0)
Location: include/linux/memremap.h:170
Inline: True
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
In mm/swap.c (ffffffff8122a70c)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (ffffffff81251af1)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff812c46fb)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812cc998)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812cef90)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (ffffffff817180cf)
Location: include/linux/memremap.h:170
Inline: True
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
In mm/swap.c (ffffffff8121d82c)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (ffffffff81244a88)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff812b573b)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812bd808)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812bfc22)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (ffffffff816f05ff)
Location: include/linux/memremap.h:170
Inline: True
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
In mm/swap.c (ffffffff812284ac)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (ffffffff8124f891)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff812c250b)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812ca7a8)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ccda0)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (ffffffff81756e9f)
Location: include/linux/memremap.h:170
Inline: True
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
In mm/swap.c (ffffffff812377fc)
Location: include/linux/memremap.h:170
Inline: True
```
```
In mm/gup.c (ffffffff8125f201)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
  - mm/gup.c:follow_page
```
```
In mm/memory-failure.c (ffffffff812d2f96)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812db4aa)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ddb30)
Location: include/linux/memremap.h:170
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In drivers/dax/super.c (ffffffff81772327)
Location: include/linux/memremap.h:170
Inline: True
```
</details>
</li>
</ul>

## Differences
