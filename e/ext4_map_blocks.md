# Function: <code>ext4_map_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81298a50)
Location: fs/ext4/inode.c:458
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81298a50-ffffffff81298eef: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c5c50)
Location: fs/ext4/inode.c:474
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812c5c50-ffffffff812c6202: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812db480)
Location: fs/ext4/inode.c:481
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/file.c:ext4_overwrite_io
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812db480-ffffffff812dba5a: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812ffd30)
Location: fs/ext4/inode.c:487
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff812ffd30-ffffffff813002fe: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81324550)
Location: fs/ext4/inode.c:497
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81324550-ffffffff81324b1e: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81352780)
Location: fs/ext4/inode.c:498
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81352780-ffffffff81352d55: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136a8a0)
Location: fs/ext4/inode.c:498
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8136a8a0-ffffffff8136ae87: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81393db0)
Location: fs/ext4/inode.c:502
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81393db0-ffffffff813943c0: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ac740)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813ac740-ffffffff813acd3c: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f8a20)
Location: fs/ext4/inode.c:490
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff813f8a20-ffffffff813f8fa4: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140b0f0)
Location: fs/ext4/inode.c:501
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_del_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff8140b0f0-ffffffff8140b678: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814112a0)
Location: fs/ext4/inode.c:502
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff814112a0-ffffffff81411830: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:501
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:skip_hole
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff81ccab67-ffffffff81ccabbd: ext4_map_blocks.cold (STB_LOCAL)
ffffffff814640f0-ffffffff814646c1: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:500
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:skip_hole
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff81e7d96a-ffffffff81e7d9b5: ext4_map_blocks.cold (STB_LOCAL)
ffffffff814e3640-ffffffff814e3cae: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:506
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:skip_hole
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff8206ded4-ffffffff8206df1f: ext4_map_blocks.cold (STB_LOCAL)
ffffffff8157cb40-ffffffff8157d1ae: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:478
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:skip_hole
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/super.c:ext4_journal_bmap
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff820edbc3-ffffffff820edc0d: ext4_map_blocks.cold (STB_LOCAL)
ffffffff815b3f40-ffffffff815b4553: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:478
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:skip_hole
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/super.c:ext4_journal_bmap
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff821cacf2-ffffffff821cad3c: ext4_map_blocks.cold (STB_LOCAL)
ffffffff815ecd40-ffffffff815ed36b: ext4_map_blocks (STB_GLOBAL)
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
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010480f08)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffff800010480f08-ffff800010481470: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0641ff0)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
c0641ff0-c064262c: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a5350)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
c0000000005a5350-c0000000005a5b2c: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000309c5e)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffe000309c5e-ffffffe00030a162: ext4_map_blocks (STB_GLOBAL)
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
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4d20)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813a4d20-ffffffff813a531c: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813957b0)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813957b0-ffffffff81395dac: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a2580)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813a2580-ffffffff813a2b7c: ext4_map_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b6c60)
Location: fs/ext4/inode.c:511
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813b6c60-ffffffff813b725c: ext4_map_blocks (STB_GLOBAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
