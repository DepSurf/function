# Function: <code>PageMlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a2c75)
Location: include/linux/page-flags.h:269
Inline: True
```
```
In mm/memory.c (ffffffff811bff94)
Location: include/linux/page-flags.h:269
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/rmap.c (ffffffff811cb09f)
Location: include/linux/page-flags.h:269
Inline: True
```
```
In mm/ksm.c (ffffffff811e5716)
Location: include/linux/page-flags.h:269
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In fs/fuse/dev.c (ffffffff8130ea91)
Location: include/linux/page-flags.h:269
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b9335)
Location: include/linux/page-flags.h:327
Inline: True
```
```
In mm/memory.c (ffffffff811d9f8d)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff811e7e76)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff812041e6)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/huge_memory.c (ffffffff81217982)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In fs/fuse/dev.c (ffffffff81342e8a)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/vmscan.c (ffffffff811c9972)
Location: include/linux/page-flags.h:343
Inline: True
```
```
In mm/memory.c (ffffffff811e9ab9)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff811f91f6)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff81216146)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81229f32)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In fs/fuse/dev.c (ffffffff81358ca6)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/vmscan.c (ffffffff811d2837)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff811f4b97)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff811f981a)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff81203ddf)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff8122192a)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81235ae4)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812449a1)
Location: include/linux/page-flags.h:346
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8136d1ef)
Location: include/linux/page-flags.h:346
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/vmscan.c (ffffffff811e7d4a)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff8120cc10)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff81211c4a)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff8121cb4f)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff8123cc6b)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81254889)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81264891)
Location: include/linux/page-flags.h:347
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81392028)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/vmscan.c (ffffffff81208e32)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff8122d88a)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff8123298a)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff8123e8d3)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff81260669)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81278672)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81288ff7)
Location: include/linux/page-flags.h:354
Inline: True
```
```
In fs/fuse/dev.c (ffffffff813c104f)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/vmscan.c (ffffffff8121bb12)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff81240e1f)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff81245f0c)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff81252e67)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff81274dc3)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81281c92)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128ccef)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8129df47)
Location: include/linux/page-flags.h:366
Inline: True
```
```
In fs/fuse/dev.c (ffffffff813da3b1)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/vmscan.c (ffffffff8122b7b2)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff812530a2)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff8125839d)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff8126528f)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff8128faf5)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8129dd7c)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a7a02)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812b90f7)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81405f14)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/vmscan.c (ffffffff81239682)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff81261602)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff8126686d)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff81273b38)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff8129f885)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812ad62c)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b8ee0)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812cafe7)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81420ad6)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/swap.c (ffffffff8125f586)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812658c1)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff8129179a)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff812966e1)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff812a507b)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff812d3ef5)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812e29d8)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ecee8)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81301097)
Location: include/linux/page-flags.h:407
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8146fb3a)
Location: include/linux/page-flags.h:407
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/swap.c (ffffffff81269b87)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81270274)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff8129c0cd)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff812a165a)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff812b056c)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff812df8e5)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812ede03)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f8180)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8130d0e7)
Location: include/linux/page-flags.h:415
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8148a3e2)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/swap.c (ffffffff8126d897)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8127607e)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff812a133f)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff812a73db)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff812b5b7c)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff812e8205)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812f3fb2)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fe701)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff813136a7)
Location: include/linux/page-flags.h:415
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8148ff37)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/swap.c (ffffffff812a9f08)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812b26d5)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff812e2289)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff812e8a1b)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff812f77fc)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff81330135)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8133e9e3)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813482a2)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff813603a3)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fuse/dev.c (ffffffff814e79a4)
Location: include/linux/page-flags.h:429
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/swap.c (ffffffff81305301)
Location: include/linux/page-flags.h:582
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130f455)
Location: include/linux/page-flags.h:582
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memory.c (ffffffff813441c2)
Location: include/linux/page-flags.h:582
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff8134ac7b)
Location: include/linux/page-flags.h:582
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/memory-failure.c (ffffffff813dba39)
Location: include/linux/page-flags.h:582
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fuse/dev.c (ffffffff81575e08)
Location: include/linux/page-flags.h:582
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/mlock.c (ffffffff813c3870)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/memory-failure.c (ffffffff81462673)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81498433)
Location: include/linux/page-flags.h:555
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c7a07)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
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
In mm/vmscan.c (ffff8000102ca59c)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffff8000102f88c0)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffff8000102fd648)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffff8000103096cc)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffff80001033ec7c)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff80001034f050)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff8000103595c8)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffff80001036e9d8)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (ffff800010503670)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/vmscan.c (c04f43dc)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (c051b0b4)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (c051c9e0)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (c05262fc)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In mm/ksm.c (c0545324)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (0)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (c06bfcfc)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/vmscan.c (c000000000387074)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (c0000000003c1e90)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (c0000000003c8ce4)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (c0000000003d8d68)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (c00000000041b234)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c0000000004313bc)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c000000000442b28)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (c00000000045f6b4)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (c0000000006481fc)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/vmscan.c (ffffffe0001e964a)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffe000208cb8)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffe00020beb2)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffe000213aa4)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In mm/ksm.c (ffffffe000234a64)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (0)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (ffffffe000370488)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/vmscan.c (ffffffff81231cd2)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff81259c52)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff8125eebd)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff8126c188)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff81297e65)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a5c0c)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b14c0)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812c35c7)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (ffffffff814190b6)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/vmscan.c (ffffffff81224d92)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff8124c081)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff812512ed)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff8125e1f8)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff81289a20)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812976da)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a2890)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812b4607)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81409b36)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/vmscan.c (ffffffff8122fa72)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff812579f2)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff8125cc5d)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff81269f28)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff81295c75)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a3a1c)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812af2d0)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812c13d7)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81415256)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/vmscan.c (ffffffff8123eebc)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff812673db)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffffffff8126c63d)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff81279898)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/ksm.c (ffffffff812a5a85)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812b422c)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bf620)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812d1e97)
Location: include/linux/page-flags.h:399
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8142bfbd)
Location: include/linux/page-flags.h:399
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
</details>
</li>
</ul>

## Differences
