# Function: <code>ext4_ext_get_actual_len</code>

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
In fs/ext4/super.c (ffffffff812b1711)
Location: fs/ext4/ext4_extents.h:204
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
In fs/ext4/extents.c (ffffffff812c2720)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_put_gap_in_cache
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
```
```
In fs/ext4/move_extent.c (ffffffff812d7654)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/crypto.c (ffffffff812e5529)
Location: fs/ext4/ext4_extents.h:204
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
In fs/ext4/super.c (ffffffff812dc4d8)
Location: fs/ext4/ext4_extents.h:204
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
In fs/ext4/extents.c (ffffffff812faaa1)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
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
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff813073a9)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/super.c (ffffffff812f2036)
Location: fs/ext4/ext4_extents.h:204
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
In fs/ext4/extents.c (ffffffff81310a41)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
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
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff8131d37f)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff812eefcd)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff81315e1a)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81326b67)
Location: fs/ext4/ext4_extents.h:204
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
In fs/ext4/extents.c (ffffffff81313acd)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff8133a680)
Location: fs/ext4/ext4_extents.h:204
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8134b09b)
Location: fs/ext4/ext4_extents.h:204
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
In fs/ext4/extents.c (ffffffff81341a0f)
Location: fs/ext4/ext4_extents.h:193
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff81368c29)
Location: fs/ext4/ext4_extents.h:193
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81378ee1)
Location: fs/ext4/ext4_extents.h:193
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
In fs/ext4/extents.c (ffffffff813595bd)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff81381149)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8139182f)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/extents.c (ffffffff8138254a)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff813aa472)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813bb7d9)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/extents.c (ffffffff8139aafa)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff813c33a2)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813d4aa9)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (ffffffff813ef11c)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/extents.c (ffffffff813e5fea)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent_at
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
  - fs/ext4/extents.c:ext4_ext_determine_hole
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff8140f744)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff814210b8)
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
```
In fs/ext4/verity.c (ffffffff8143c525)
Location: fs/ext4/ext4_extents.h:209
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
In fs/ext4/extents.c (ffffffff813f8265)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent_at
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
  - fs/ext4/extents.c:ext4_ext_determine_hole
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff81422c04)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81437758)
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
```
In fs/ext4/fast_commit.c (ffffffff81454fab)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
```
In fs/ext4/verity.c (ffffffff81458875)
Location: fs/ext4/ext4_extents.h:209
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
In fs/ext4/extents.c (ffffffff813fe6e5)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff81429404)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8143d908)
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
```
In fs/ext4/fast_commit.c (ffffffff8145a3a2)
Location: fs/ext4/ext4_extents.h:209
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
```
In fs/ext4/verity.c (ffffffff8145e1e5)
Location: fs/ext4/ext4_extents.h:209
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
In fs/ext4/extents.c (ffffffff81450a25)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:ext4_valid_extent_entries
  - fs/ext4/extents.c:ext4_valid_extent_entries
```
```
In fs/ext4/move_extent.c (ffffffff8147d203)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81491588)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/fast_commit.c (ffffffff814ae88a)
Location: fs/ext4/ext4_extents.h:210
Inline: True
```
```
In fs/ext4/verity.c (ffffffff814b3705)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/extents.c (ffffffff814cda80)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff814ffa8d)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff815161a7)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/fast_commit.c (ffffffff8153772f)
Location: fs/ext4/ext4_extents.h:210
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8153c33e)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/extents.c (ffffffff815661e0)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff8159a390)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff815b1be4)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/fast_commit.c (ffffffff815d58ff)
Location: fs/ext4/ext4_extents.h:210
Inline: True
```
```
In fs/ext4/verity.c (ffffffff815daa0e)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/extents.c (ffffffff8159de70)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff815d0c20)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff815e8944)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/fast_commit.c (ffffffff8160d4bf)
Location: fs/ext4/ext4_extents.h:210
Inline: True
```
```
In fs/ext4/verity.c (ffffffff816126ae)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/extents.c (ffffffff815d6ac0)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_determine_insert_hole
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
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
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_cache_extents
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff81609461)
Location: fs/ext4/ext4_extents.h:210
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81621334)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/fast_commit.c (ffffffff8164627f)
Location: fs/ext4/ext4_extents.h:210
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8164b45e)
Location: fs/ext4/ext4_extents.h:210
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
In fs/ext4/extents.c (ffff80001046d3c0)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffff80001049ac10)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffff8000104b7a14)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (ffff8000104c843c)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/extents.c (c062ea88)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (c065c780)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (c066f870)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (c068c39c)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/extents.c (c00000000058d294)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (c0000000005c5594)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (c0000000005dceb4)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (c00000000060116c)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/extents.c (ffffffe0002fa7ba)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffe00031e2cc)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffe00032be00)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (ffffffe0003422e0)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/extents.c (ffffffff813930da)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff813bb982)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813cd089)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (ffffffff813e76fc)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/extents.c (ffffffff81383b6a)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff813ac412)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813bdb09)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (ffffffff813d817c)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/extents.c (ffffffff81390a3a)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff813b91e2)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813ca519)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (ffffffff813e4a7c)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/extents.c (ffffffff813a48ca)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_zeroout_es
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/move_extent.c (ffffffff813cdf02)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813df769)
Location: fs/ext4/ext4_extents.h:206
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
In fs/ext4/verity.c (ffffffff813f9ecc)
Location: fs/ext4/ext4_extents.h:206
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
</details>
</li>
</ul>

## Differences
