# Function: <code>ext4_ext_drop_refs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c3b80)
Location: fs/ext4/extents.c:710
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff812c3b80-ffffffff812c3bc9: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f3550)
Location: fs/ext4/extents.c:723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff812f3550-ffffffff812f3599: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81309500)
Location: fs/ext4/extents.c:723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff81309500-ffffffff81309549: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e7c50)
Location: fs/ext4/extents.c:723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff812e7c50-ffffffff812e7c9a: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130c6f0)
Location: fs/ext4/extents.c:723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff8130c6f0-ffffffff8130c73a: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133b890)
Location: fs/ext4/extents.c:711
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff8133b890-ffffffff8133b8d9: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81352f40)
Location: fs/ext4/extents.c:711
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff81352f40-ffffffff81352f89: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137c320)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff8137c320-ffffffff8137c369: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813947f0)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813947f0-ffffffff81394839: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e5f85)
Location: fs/ext4/extents.c:684
Inline: True
Inline callers:
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
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
Direct callers:
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff813e0b10-ffffffff813e0b59: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f8282)
Location: fs/ext4/extents.c:684
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
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
Direct callers:
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
```
**Symbols:**

```
ffffffff813f23a0-ffffffff813f23e9: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fe702)
Location: fs/ext4/extents.c:684
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
ffffffff813f8820-ffffffff813f8869: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81450a42)
Location: fs/ext4/extents.c:723
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
ffffffff8144acb0-ffffffff8144acf9: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814cda97)
Location: fs/ext4/extents.c:723
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
ffffffff814c74c0-ffffffff814c7515: ext4_ext_drop_refs (STB_GLOBAL)
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
In fs/ext4/extents.c (ffffffff815661f7)
Location: fs/ext4/extents.c:109
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
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
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
In fs/ext4/extents.c (ffffffff8159de87)
Location: fs/ext4/extents.c:109
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
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
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
In fs/ext4/extents.c (ffffffff815d6ad7)
Location: fs/ext4/extents.c:109
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
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff8000104674d8)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffff8000104674d8-ffff800010467530: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0628124)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
c0628124-c0628174: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000585870)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
c000000000585870-c0000000005858fc: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f53ba)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffe0002f53ba-ffffffe0002f5404: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138cdd0)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8138cdd0-ffffffff8138ce19: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137d860)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8137d860-ffffffff8137d8a9: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138a730)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8138a730-ffffffff8138a779: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_ext_drop_refs(struct ext4_ext_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139e470)
Location: fs/ext4/extents.c:715
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8139e470-ffffffff8139e4b9: ext4_ext_drop_refs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
