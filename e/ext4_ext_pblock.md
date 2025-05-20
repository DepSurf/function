# Function: <code>ext4_ext_pblock</code>

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
In fs/ext4/super.c (ffffffff812b16fd)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
```
```
In fs/ext4/extents.c (ffffffff812c26c6)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
```
```
In fs/ext4/migrate.c (ffffffff812ccec4)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/crypto.c (ffffffff812e55aa)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
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
In fs/ext4/super.c (ffffffff812dc4bf)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/extents.c (ffffffff812fadc2)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff812fc801)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
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
In fs/ext4/super.c (ffffffff812f201d)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/extents.c (ffffffff81310d62)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff813127b1)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
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
In fs/ext4/extents.c (ffffffff812ef22c)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff813142ed)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff81326b4e)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff81313d2c)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff81338aad)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff8134b082)
Location: fs/ext4/ext4_extents.h:220
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff81341bf6)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff81366f3a)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff81378ec8)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff81359246)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff8137f3ac)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff81391816)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff813822dd)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff813a8809)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813bb7c0)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff8139a88d)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff813c170f)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813d4a90)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff813e5d96)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff8140d9f4)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff814210a2)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff813f75bf)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff81420e40)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff81437742)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/fast_commit.c (ffffffff81455006)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
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
In fs/ext4/extents.c (ffffffff813fd9b3)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff81427600)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff8143d8f2)
Location: fs/ext4/ext4_extents.h:225
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/fast_commit.c (ffffffff8145a739)
Location: fs/ext4/ext4_extents.h:225
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
In fs/ext4/extents.c (ffffffff8144fced)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:ext4_valid_extent_entries
  - fs/ext4/extents.c:ext4_valid_extent_entries
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff8147b27d)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff81491572)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/fast_commit.c (ffffffff814ae8f1)
Location: fs/ext4/ext4_extents.h:226
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
In fs/ext4/extents.c (ffffffff814ccac3)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff814fd6cc)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff81516191)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/fast_commit.c (ffffffff81537786)
Location: fs/ext4/ext4_extents.h:226
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
In fs/ext4/extents.c (ffffffff815651e3)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff81597ea4)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff815b1bce)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/fast_commit.c (ffffffff815d5956)
Location: fs/ext4/ext4_extents.h:226
Inline: True
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
In fs/ext4/extents.c (ffffffff8159ce46)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff815ce922)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff815e892e)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/fast_commit.c (ffffffff8160d516)
Location: fs/ext4/ext4_extents.h:226
Inline: True
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
In fs/ext4/extents.c (ffffffff815d595e)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff816071a2)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff8162131e)
Location: fs/ext4/ext4_extents.h:226
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
```
In fs/ext4/fast_commit.c (ffffffff816462d6)
Location: fs/ext4/ext4_extents.h:226
Inline: True
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
In fs/ext4/extents.c (ffff80001046d1a8)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffff800010498bac)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffff8000104b7a00)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (c062e87c)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (c065a7a4)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (c066f864)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (c00000000058ccbc)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (c0000000005c2f70)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (c0000000005dcea0)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffe0002fa58a)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffe00031caa2)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffe00032be16)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff81392e6d)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff813b9cef)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813cd070)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff813838fd)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff813aa77f)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813bdaf0)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff813907cd)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff813b754f)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813ca500)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
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
In fs/ext4/extents.c (ffffffff813a465d)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_find_goal
```
```
In fs/ext4/migrate.c (ffffffff813cc25f)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813df750)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_event_raw_event_ext4_remove_blocks
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_event_raw_event_ext4_ext_convert_to_initialized_enter
```
</details>
</li>
</ul>

## Differences
