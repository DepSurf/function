# Function: <code>ext4_ext_store_pblock</code>

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
In fs/ext4/extents.c (ffffffff812c4e15)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
```
```
In fs/ext4/migrate.c (ffffffff812cc04f)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff812fade4)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff812fb98d)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff81310d84)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff8131193d)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff812ef24e)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff813133bd)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff81313d4e)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff81337b7d)
Location: fs/ext4/ext4_extents.h:247
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff81341c02)
Location: fs/ext4/ext4_extents.h:236
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff81366102)
Location: fs/ext4/ext4_extents.h:236
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff81359252)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff8137e562)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff813822e9)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff813a79e3)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff8139a899)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff813c0813)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff813e5da2)
Location: fs/ext4/ext4_extents.h:252
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff8140c9e1)
Location: fs/ext4/ext4_extents.h:252
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff813f7ac5)
Location: fs/ext4/ext4_extents.h:252
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff8141fe41)
Location: fs/ext4/ext4_extents.h:252
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/fast_commit.c (ffffffff814550ec)
Location: fs/ext4/ext4_extents.h:252
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff813fdf55)
Location: fs/ext4/ext4_extents.h:252
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff81426681)
Location: fs/ext4/ext4_extents.h:252
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/fast_commit.c (ffffffff8145a38d)
Location: fs/ext4/ext4_extents.h:252
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff81450255)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff8147a311)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/fast_commit.c (ffffffff814ae1f5)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff814cd068)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff814fc5f7)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/fast_commit.c (ffffffff81536928)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff815657a8)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff81596d37)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/fast_commit.c (ffffffff815d4cd8)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff8159d441)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff815cd777)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/fast_commit.c (ffffffff8160c8c8)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff815d6091)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff81605ff7)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/fast_commit.c (ffffffff81645688)
Location: fs/ext4/ext4_extents.h:253
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffff80001046d1ac)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffff800010497b60)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (c062e880)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (c0659784)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (c00000000058ccd4)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (c0000000005c1af0)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffe0002fa5a0)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffe00031be12)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff81392e79)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff813b8df3)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff81383909)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff813a9883)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff813907d9)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff813b6653)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
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
In fs/ext4/extents.c (ffffffff813a4669)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/migrate.c (ffffffff813cb363)
Location: fs/ext4/ext4_extents.h:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
</details>
</li>
</ul>

## Differences
