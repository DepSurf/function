# Function: <code>ext4_free_ext_path</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ext4_free_ext_path(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815661f7)
Location: fs/ext4/extents.c:122
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
Direct callers:
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
```
**Symbols:**

```
ffffffff8155eda0-ffffffff8155edfd: ext4_free_ext_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ext4_free_ext_path(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8159de87)
Location: fs/ext4/extents.c:122
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
Direct callers:
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
```
**Symbols:**

```
ffffffff81596b60-ffffffff81596bbd: ext4_free_ext_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_free_ext_path(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d6ad7)
Location: fs/ext4/extents.c:122
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
Direct callers:
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
```
**Symbols:**

```
ffffffff815cf810-ffffffff815cf86d: ext4_free_ext_path (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
