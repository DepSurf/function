# Function: <code>inc_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ad5a0)
Location: mm/vmstat.c:371
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:SyS_move_pages
  - mm/huge_memory.c:khugepaged
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff811ad5a0-ffffffff811ad652: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6650)
Location: mm/vmstat.c:449
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/mempolicy.c:alloc_page_interleave
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff811c6650-ffffffff811c66fa: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d67e0)
Location: mm/vmstat.c:449
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/mempolicy.c:alloc_page_interleave
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff811d67e0-ffffffff811d688a: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811df640)
Location: mm/vmstat.c:449
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/mempolicy.c:alloc_page_interleave
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff811df640-ffffffff811df6e5: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f52a0)
Location: mm/vmstat.c:524
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff811f52a0-ffffffff811f5345: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216580)
Location: mm/vmstat.c:524
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff81216580-ffffffff81216625: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229480)
Location: mm/vmstat.c:524
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff81229480-ffffffff81229525: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239140)
Location: mm/vmstat.c:525
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff81239140-ffffffff812391e5: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247450)
Location: mm/vmstat.c:525
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff81247450-ffffffff812474f5: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81275170)
Location: mm/vmstat.c:525
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff81275170-ffffffff81275214: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127fa00)
Location: mm/vmstat.c:534
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff8127fa00-ffffffff8127faa9: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284b40)
Location: mm/vmstat.c:540
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff81284b40-ffffffff81284be2: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c3160)
Location: mm/vmstat.c:586
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff812c3160-ffffffff812c325a: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320420)
Location: mm/vmstat.c:615
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff81320420-ffffffff8132053e: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394340)
Location: mm/vmstat.c:602
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff81394340-ffffffff8139445e: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c6d10)
Location: mm/vmstat.c:603
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff813c6d10-ffffffff813c6e2e: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1830)
Location: mm/vmstat.c:603
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff813f1830-ffffffff813f1948: inc_zone_page_state (STB_GLOBAL)
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
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102db638)
Location: mm/vmstat.c:525
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:pgd_pgtable_alloc
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffff8000102db638-ffff8000102db79c: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c05020b4)
Location: mm/vmstat.c:613
Inline: False
Direct callers:
  - arch/arm/mm/mmu.c:late_alloc
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
c05020b4-c05020f0: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039bd20)
Location: mm/vmstat.c:613
Inline: False
Direct callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
c00000000039bd20-c00000000039bd94: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f51be)
Location: mm/vmstat.c:613
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffe0001f51be-ffffffe0001f520e: inc_zone_page_state (STB_GLOBAL)
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
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123faa0)
Location: mm/vmstat.c:525
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff8123faa0-ffffffff8123fb45: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81232aa0)
Location: mm/vmstat.c:525
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff81232aa0-ffffffff81232b45: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123d840)
Location: mm/vmstat.c:525
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff8123d840-ffffffff8123d8e5: inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124cf70)
Location: mm/vmstat.c:525
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff8124cf70-ffffffff8124d015: inc_zone_page_state (STB_GLOBAL)
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
