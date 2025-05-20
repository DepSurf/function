# Function: <code>del_page_from_lru_list</code>

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
In mm/swap.c (ffffffff8119c9c8)
Location: include/linux/mm_inline.h:34
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff811a22c5)
Location: include/linux/mm_inline.h:34
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff811b60ea)
Location: include/linux/mm_inline.h:34
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2d0e)
Location: include/linux/mm_inline.h:34
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fed21)
Location: include/linux/mm_inline.h:34
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
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
In mm/swap.c (ffffffff811b2ae2)
Location: include/linux/mm_inline.h:53
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811bcae3)
Location: include/linux/mm_inline.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811cff54)
Location: include/linux/mm_inline.h:53
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811de8c1)
Location: include/linux/mm_inline.h:53
Inline: True
```
```
In mm/memcontrol.c (ffffffff8122485c)
Location: include/linux/mm_inline.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff811c3162)
Location: include/linux/mm_inline.h:53
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811cd0b0)
Location: include/linux/mm_inline.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811dff83)
Location: include/linux/mm_inline.h:53
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811ee6e1)
Location: include/linux/mm_inline.h:53
Inline: True
```
```
In mm/memcontrol.c (ffffffff81236e45)
Location: include/linux/mm_inline.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff811cb5f8)
Location: include/linux/mm_inline.h:60
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d5ea9)
Location: include/linux/mm_inline.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811e996e)
Location: include/linux/mm_inline.h:60
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811f9681)
Location: include/linux/mm_inline.h:60
Inline: True
```
```
In mm/memcontrol.c (ffffffff812428f5)
Location: include/linux/mm_inline.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff811e0aa2)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811eb3c9)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811ffcb4)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81211ab1)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff81262735)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81202388)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8120cba0)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81221422)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81232810)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff81286939)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81214d0a)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121fa61)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81234475)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81246050)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff8129b8c6)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81223eb6)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122f1d1)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812442a0)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125826a)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b6a23)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81231c46)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123d361)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81252760)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8126673a)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c88f3)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff8125e802)
Location: include/linux/mm_inline.h:62
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81265927)
Location: include/linux/mm_inline.h:62
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81282bc0)
Location: include/linux/mm_inline.h:62
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812967f8)
Location: include/linux/mm_inline.h:62
Inline: True
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
In mm/swap.c (ffffffff81268a49)
Location: include/linux/mm_inline.h:62
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81270303)
Location: include/linux/mm_inline.h:62
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8128d183)
Location: include/linux/mm_inline.h:62
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a1d02)
Location: include/linux/mm_inline.h:62
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff8126e708)
Location: include/linux/mm_inline.h:100
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812760c4)
Location: include/linux/mm_inline.h:100
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81291b24)
Location: include/linux/mm_inline.h:100
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a74cc)
Location: include/linux/mm_inline.h:100
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff812ab703)
Location: include/linux/mm_inline.h:100
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812b271b)
Location: include/linux/mm_inline.h:100
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812d187b)
Location: include/linux/mm_inline.h:100
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812e87a8)
Location: include/linux/mm_inline.h:100
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff81305563)
Location: include/linux/mm_inline.h:142
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130f49e)
Location: include/linux/mm_inline.h:142
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff81330bfc)
Location: include/linux/mm_inline.h:142
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134aca2)
Location: include/linux/mm_inline.h:142
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
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
In mm/compaction.c (ffffffff813a7a5d)
Location: include/linux/mm_inline.h:360
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c3897)
Location: include/linux/mm_inline.h:360
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c18c0)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102ce7bc)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffff8000102eb2ec)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffff8000102fd7e8)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffff80001036b830)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (c04ecc04)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f8584)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (c050e930)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (c051cb3c)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (c055cebc)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (c00000000037b678)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c00000000038c5a4)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (c0000000003ac874)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (c0000000003c8a74)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (c00000000045b330)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffe0001e2d7a)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ec908)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffe0001ff76e)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffe00020c006)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffe000248e72)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff8122a296)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812359b1)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8124adb0)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125ed8a)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c0ed3)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff8121d3b6)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81228a1b)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8123dd50)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812511ba)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b1f27)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81228036)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81233751)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81248b50)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125cb2a)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bece3)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81237376)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81242c88)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81258381)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8126c50a)
Location: include/linux/mm_inline.h:61
Inline: True
```
```
In mm/memcontrol.c (ffffffff812cf763)
Location: include/linux/mm_inline.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
</details>
</li>
</ul>

## Differences
