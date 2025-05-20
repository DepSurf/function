# Function: <code>SetPageLRU</code>

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
In mm/swap.c (ffffffff8119cbfb)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a21fc)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff811fee32)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
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
In mm/swap.c (ffffffff811b1fa1)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811b7ca2)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81224948)
Location: include/linux/page-flags.h:262
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
In mm/swap.c (ffffffff811c2602)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811c82f4)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81236f38)
Location: include/linux/page-flags.h:272
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
In mm/swap.c (ffffffff811caa85)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811d0c78)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff812429f2)
Location: include/linux/page-flags.h:272
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
In mm/swap.c (ffffffff811df7f5)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811e6168)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81262832)
Location: include/linux/page-flags.h:273
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
In mm/swap.c (ffffffff81201e08)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff812076e3)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81286a36)
Location: include/linux/page-flags.h:280
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
In mm/swap.c (ffffffff81214788)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8121a263)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff8129b9b9)
Location: include/linux/page-flags.h:289
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
In mm/swap.c (ffffffff81224449)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8122c847)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (ffffffff812b6aad)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (ffffffff812321d9)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8123aa5f)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (ffffffff812c897d)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (ffffffff8125f44c)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff81265239)
Location: include/linux/page-flags.h:328
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
In mm/swap.c (ffffffff81269a4a)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8127020f)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/compaction.c (ffffffff8128cad6)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/huge_memory.c (ffffffff812f3d89)
Location: include/linux/page-flags.h:336
Inline: True
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
In mm/swap.c (ffffffff8126d83a)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff81276017)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/compaction.c (ffffffff81291d50)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/huge_memory.c (ffffffff812fa1e9)
Location: include/linux/page-flags.h:336
Inline: True
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
In mm/swap.c (ffffffff812a9eaa)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812b266f)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/compaction.c (ffffffff812d13e5)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/huge_memory.c (ffffffff81343f09)
Location: include/linux/page-flags.h:350
Inline: True
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
In mm/swap.c (ffffffff8130591a)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8130f6c0)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/compaction.c (ffffffff81330e9a)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134ab19)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/huge_memory.c (ffffffff813b9e03)
Location: include/linux/page-flags.h:500
Inline: True
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
In mm/compaction.c (ffffffff813a7836)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c36ff)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/huge_memory.c (ffffffff8143c8e0)
Location: include/linux/page-flags.h:479
Inline: True
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
In mm/huge_memory.c (ffffffff81471f39)
Location: include/linux/page-flags.h:473
Inline: True
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
In mm/huge_memory.c (ffffffff814a2682)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In mm/swap.c (ffff8000102c1060)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffff8000102cb71c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (ffff80001036b8e8)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (c04ed32c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (c04f5814)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (c055cf48)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (c00000000037c0e8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (c000000000388894)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (c00000000045b3f8)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (ffffffe0001e3532)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffe0001ea4f2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (ffffffe000248ee4)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (ffffffff8122a829)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff812330af)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (ffffffff812c0f5d)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (ffffffff8121d949)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff81226149)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (ffffffff812b1fb1)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (ffffffff812285c9)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff81230e4f)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (ffffffff812bed6d)
Location: include/linux/page-flags.h:320
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
In mm/swap.c (ffffffff81237939)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff81240295)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/memcontrol.c (ffffffff812cf7ed)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
</details>
</li>
</ul>

## Differences
