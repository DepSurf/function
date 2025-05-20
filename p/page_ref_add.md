# Function: <code>page_ref_add</code>

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
In arch/x86/mm/gup.c (ffffffff81071b3f)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In mm/page_alloc.c (ffffffff811ab450)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/shmem.c (ffffffff811c055f)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/huge_memory.c (ffffffff81217da6)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
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
In arch/x86/mm/gup.c (ffffffff810756b9)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In mm/page_alloc.c (ffffffff811bba27)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff811d0b3f)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/huge_memory.c (ffffffff8122a367)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/page_alloc.c (ffffffff811c3cdb)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff811d90cf)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8120ba66)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff81235f5a)
Location: include/linux/page_ref.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/page_alloc.c (ffffffff811d8a7b)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff811ee3af)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81225065)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff81254cb5)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/page_alloc.c (ffffffff811f9c0f)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff8120ecef)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81247662)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8126e819)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278c4f)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/page_alloc.c (ffffffff8120c2aa)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/shmem.c (ffffffff81221581)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125bbbb)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812824b9)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128d315)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8128fd87)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff81230dac)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81272510)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81276d77)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129e490)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2671)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812aaf4a)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff8123efd3)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81281370)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81286858)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812add3e)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b3b04)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812bc8d0)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff8126c848)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff8128792f)
Location: include/linux/page_ref.h:91
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b3847)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff812b8e01)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812e4871)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e941d)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f1dfc)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff8127728f)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff8129176f)
Location: include/linux/page_ref.h:91
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bf321)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff812c4573)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ef264)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f48cb)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812fe37d)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff8127c2f7)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff812975ec)
Location: include/linux/page_ref.h:91
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c43c5)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff812cb1f8)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812f5ed4)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fae4f)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81305037)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff812ba4a8)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff812d7fa0)
Location: include/linux/page_ref.h:91
Inline: True
```
```
In mm/page_alloc.c (ffffffff81308281)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff813101f3)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff813404b4)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81344c86)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8134edc7)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff812f239f)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff81317a5a)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81338482)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff81370586)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff8137ac81)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff813b1f7b)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813baba1)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff813c599e)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff8135a9af)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff8138aeec)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813afc8a)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff813ed518)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff813f87bc)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81431aad)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff8143d048)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8144a3de)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In net/core/skbuff.c (ffffffff81da45d6)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
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
In mm/filemap.c (ffffffff8138c3de)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813bd51a)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff813e7e2d)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff814224b4)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff8142b57e)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff814676cf)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81472525)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81480369)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In net/core/skbuff.c (ffffffff81e13227)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
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
In mm/filemap.c (ffffffff813b9747)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813e866e)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/gup.c (ffffffff81412a9a)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff8141fd65)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/page_alloc.c (ffffffff8144f1f9)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/swap_state.c (ffffffff81464d68)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8149895d)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a28b7)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff814ae459)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In net/core/skbuff.c (ffffffff81ed03e7)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
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
In mm/shmem.c (ffff8000102d1638)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffff800010319034)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffff800010320ffc)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffff80001034fc30)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff800010354a48)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffff80001035db14)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (c04f8a34)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (c0533af4)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (c0539938)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c0550f4c)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
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
In mm/shmem.c (c00000000038f0a8)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (c0000000003eba68)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (c0000000003f64bc)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c00000000043315c)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043bad0)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (c00000000044912c)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffe0001edb16)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffe00021ee64)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffe0002224aa)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffe00023ea46)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
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
In mm/shmem.c (ffffffff81237623)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff812799c0)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8127eea8)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a631e)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ac0e4)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b4eb0)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff8122a4b3)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff8126b8b0)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff81270cd8)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81297dce)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129dc54)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812a5ef3)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff812353c3)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81277760)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8127cc48)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a412e)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a9ef4)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b2cc0)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff812454d3)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/page_alloc.c (ffffffff81287350)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap_state.c (ffffffff8128c818)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812b389e)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ba174)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812c30fd)
Location: include/linux/page_ref.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
</ul>

## Differences
