# Function: <code>add_page_to_lru_list</code>

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
In mm/swap.c (ffffffff8119cc01)
Location: include/linux/mm_inline.h:25
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a372a)
Location: include/linux/mm_inline.h:25
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffffffff811fee72)
Location: include/linux/mm_inline.h:25
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
In mm/swap.c (ffffffff811b1fb4)
Location: include/linux/mm_inline.h:46
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811bcba4)
Location: include/linux/mm_inline.h:46
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81224996)
Location: include/linux/mm_inline.h:46
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
In mm/swap.c (ffffffff811c2615)
Location: include/linux/mm_inline.h:46
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811cd27c)
Location: include/linux/mm_inline.h:46
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81236f85)
Location: include/linux/mm_inline.h:46
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
In mm/swap.c (ffffffff811caa98)
Location: include/linux/mm_inline.h:46
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811d5f5d)
Location: include/linux/mm_inline.h:46
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81242a40)
Location: include/linux/mm_inline.h:46
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
In mm/swap.c (ffffffff811df808)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811eb47d)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81262880)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff81201eb6)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8120cc55)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff81286ad1)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff81214836)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8121fb1e)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/memcontrol.c (ffffffff8129ba58)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff81224513)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff8122f289)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffffffff812b6b2a)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff812322a3)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8123d419)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffffffff812c89fa)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff8125f4de)
Location: include/linux/mm_inline.h:48
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff812659d7)
Location: include/linux/mm_inline.h:48
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
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
In mm/swap.c (ffffffff81269ad7)
Location: include/linux/mm_inline.h:48
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff812703b4)
Location: include/linux/mm_inline.h:48
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
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
Location: include/linux/mm_inline.h:82
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff812761e7)
Location: include/linux/mm_inline.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
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
Location: include/linux/mm_inline.h:82
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff812b285e)
Location: include/linux/mm_inline.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (ffffffff81305d82)
Location: include/linux/mm_inline.h:108
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff8130f5af)
Location: include/linux/mm_inline.h:108
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/mlock.c (ffffffff8134adb0)
Location: include/linux/mm_inline.h:108
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c39c6)
Location: include/linux/mm_inline.h:326
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
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
In mm/swap.c (ffff8000102c10e8)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffff8000102ce874)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffff80001036b978)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (c04ed3ec)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (c04f85fc)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (c055cf8c)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (c00000000037c184)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (c00000000038c644)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (c00000000045b480)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffe0001e3618)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffe0001ec97e)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffffffe000248f16)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff8122a8f3)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81235a69)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffffffff812c0fda)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff8121da13)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81228ad3)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffffffff812b202e)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff81228693)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81233809)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffffffff812bedea)
Location: include/linux/mm_inline.h:47
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
In mm/swap.c (ffffffff81237a03)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81242d40)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memcontrol.c (ffffffff812cf86a)
Location: include/linux/mm_inline.h:47
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
</details>
</li>
</ul>

## Differences
