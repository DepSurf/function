# Function: <code>page_lru</code>

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
In mm/swap.c (ffffffff8119cb92)
Location: include/linux/mm_inline.h:89
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a290e)
Location: include/linux/mm_inline.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/compaction.c (ffffffff811b60cc)
Location: include/linux/mm_inline.h:89
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2ce2)
Location: include/linux/mm_inline.h:89
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fecef)
Location: include/linux/mm_inline.h:89
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
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
In mm/swap.c (ffffffff811b1f5b)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811ba0b7)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811cff27)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811de898)
Location: include/linux/mm_inline.h:106
Inline: True
```
```
In mm/memcontrol.c (ffffffff81224832)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff811c25bb)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811ca744)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811dff53)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811ee6b8)
Location: include/linux/mm_inline.h:106
Inline: True
```
```
In mm/memcontrol.c (ffffffff81236e1b)
Location: include/linux/mm_inline.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff811caa3a)
Location: include/linux/mm_inline.h:113
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811d3296)
Location: include/linux/mm_inline.h:113
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811e9cfa)
Location: include/linux/mm_inline.h:113
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811f9658)
Location: include/linux/mm_inline.h:113
Inline: True
```
```
In mm/memcontrol.c (ffffffff812428cc)
Location: include/linux/mm_inline.h:113
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff811df7aa)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811e87e6)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8120004f)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81211a88)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff8126270c)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81201e32)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff81209cb9)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812213f5)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812327e7)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff812868cc)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff812147b2)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8121c999)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81234448)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81246027)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff8129b857)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81224473)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8122c856)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81244204)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125822f)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b69a4)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81232203)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8123aa6e)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812526c4)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812666ff)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c8874)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff8125f5a3)
Location: include/linux/mm_inline.h:115
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff81269efc)
Location: include/linux/mm_inline.h:115
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81282af1)
Location: include/linux/mm_inline.h:115
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812967cf)
Location: include/linux/mm_inline.h:115
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
In mm/swap.c (ffffffff81269bab)
Location: include/linux/mm_inline.h:115
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8126feb2)
Location: include/linux/mm_inline.h:115
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8128d0b0)
Location: include/linux/mm_inline.h:115
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a1c48)
Location: include/linux/mm_inline.h:115
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
In mm/swap.c (ffffffff8126d8c1)
Location: include/linux/mm_inline.h:66
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81276122)
Location: include/linux/mm_inline.h:66
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81291b7c)
Location: include/linux/mm_inline.h:66
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a752b)
Location: include/linux/mm_inline.h:66
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
In mm/swap.c (ffffffff812a9f31)
Location: include/linux/mm_inline.h:66
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812b277b)
Location: include/linux/mm_inline.h:66
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812d18d6)
Location: include/linux/mm_inline.h:66
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812e8804)
Location: include/linux/mm_inline.h:66
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c11c0)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffff8000102cb73c)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffff8000102eb284)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffff8000102fd784)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffff80001036b7c4)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (c04ed348)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (c04f581c)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (c050e908)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (c051cb18)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (c055ce94)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (c00000000037c250)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (c0000000003888ac)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (c0000000003ac850)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (c0000000003c8a50)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (c00000000045b30c)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffe0001e355a)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffe0001ea404)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffe0001ff74e)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffe00020bfee)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffe000248e58)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff8122a853)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff812330be)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8124ad14)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125ed4f)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c0e54)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff8121d973)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff81226158)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8123dcb4)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125117f)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b1ea8)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff812285f3)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff81230e5e)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81248ab4)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125caef)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bec64)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff81237963)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff812402a4)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812582e5)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8126c4cf)
Location: include/linux/mm_inline.h:114
Inline: True
```
```
In mm/memcontrol.c (ffffffff812cf6e4)
Location: include/linux/mm_inline.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
</details>
</li>
</ul>

## Differences
