# Function: <code>dec_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ac490)
Location: mm/vmstat.c:377
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memory.c:__pte_alloc
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff811ac490-ffffffff811ac545: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c5240)
Location: mm/vmstat.c:455
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff811c5240-ffffffff811c52ef: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d5350)
Location: mm/vmstat.c:455
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff811d5350-ffffffff811d53ff: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811de1d0)
Location: mm/vmstat.c:455
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff811de1d0-ffffffff811de27b: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f3c60)
Location: mm/vmstat.c:530
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff811f3c60-ffffffff811f3d0b: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81215050)
Location: mm/vmstat.c:530
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff81215050-ffffffff812150f9: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81227f30)
Location: mm/vmstat.c:530
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff81227f30-ffffffff81227fd9: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81237ba0)
Location: mm/vmstat.c:531
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff81237ba0-ffffffff81237c49: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81245e50)
Location: mm/vmstat.c:531
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff81245e50-ffffffff81245ef9: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81275220)
Location: mm/vmstat.c:531
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff81275220-ffffffff812752c3: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127fab0)
Location: mm/vmstat.c:540
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff8127fab0-ffffffff8127fb5d: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284bf0)
Location: mm/vmstat.c:546
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
ffffffff81284bf0-ffffffff81284c97: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c3260)
Location: mm/vmstat.c:592
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
ffffffff812c3260-ffffffff812c335f: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320540)
Location: mm/vmstat.c:621
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
ffffffff81320540-ffffffff81320663: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394200)
Location: mm/vmstat.c:608
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
ffffffff81394200-ffffffff81394323: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c6e40)
Location: mm/vmstat.c:609
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
ffffffff813c6e40-ffffffff813c6f63: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1700)
Location: mm/vmstat.c:609
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
ffffffff813f1700-ffffffff813f181e: dec_zone_page_state (STB_GLOBAL)
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
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102db4d0)
Location: mm/vmstat.c:531
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
ffff8000102db4d0-ffff8000102db634: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c05022f4)
Location: mm/vmstat.c:625
Inline: False
Direct callers:
  - arch/arm/mm/pgd.c:pgd_free
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
c05022f4-c0502330: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039c020)
Location: mm/vmstat.c:625
Inline: False
Direct callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_free
  - arch/powerpc/mm/pgtable-frag.c:pte_frag_destroy
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
c00000000039c020-c00000000039c094: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f547a)
Location: mm/vmstat.c:625
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
```
**Symbols:**

```
ffffffe0001f547a-ffffffe0001f54d0: dec_zone_page_state (STB_GLOBAL)
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
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e4a0)
Location: mm/vmstat.c:531
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff8123e4a0-ffffffff8123e549: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812314a0)
Location: mm/vmstat.c:531
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff812314a0-ffffffff81231549: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123c240)
Location: mm/vmstat.c:531
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff8123c240-ffffffff8123c2e9: dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124b9a0)
Location: mm/vmstat.c:531
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - block/bounce.c:bounce_end_io
```
**Symbols:**

```
ffffffff8124b9a0-ffffffff8124ba49: dec_zone_page_state (STB_GLOBAL)
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
