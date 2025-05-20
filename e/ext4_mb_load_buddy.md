# Function: <code>ext4_mb_load_buddy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_mb_load_buddy(struct super_block *sb, ext4_group_t group, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812cf7b0)
Location: fs/ext4/mballoc.c:1112
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff812cf7b0-ffffffff812cfade: ext4_mb_load_buddy (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff813054f8)
Location: fs/ext4/mballoc.c:1251
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
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
In fs/ext4/mballoc.c (ffffffff8131b4bf)
Location: fs/ext4/mballoc.c:1251
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
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
In fs/ext4/mballoc.c (ffffffff81313045)
Location: fs/ext4/mballoc.c:1249
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
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
In fs/ext4/mballoc.c (ffffffff81337805)
Location: fs/ext4/mballoc.c:1249
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81365d9e)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137e1fe)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a768e)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c052e)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8140c65e)
Location: fs/ext4/mballoc.c:1299
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141face)
Location: fs/ext4/mballoc.c:1275
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8142639b)
Location: fs/ext4/mballoc.c:1609
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8147a04b)
Location: fs/ext4/mballoc.c:1613
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814fc2d1)
Location: fs/ext4/mballoc.c:1610
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
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
In fs/ext4/mballoc.c (ffffffff81596a62)
Location: fs/ext4/mballoc.c:1567
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
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
In fs/ext4/mballoc.c (ffffffff815cd451)
Location: fs/ext4/mballoc.c:1706
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
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
In fs/ext4/mballoc.c (ffffffff81605cd1)
Location: fs/ext4/mballoc.c:1722
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff80001049713c)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
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
In fs/ext4/mballoc.c (c06593f0)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005c1648)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
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
In fs/ext4/mballoc.c (ffffffe00031bb44)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b8b0e)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a959e)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b636e)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813cb08e)
Location: fs/ext4/mballoc.c:1238
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
