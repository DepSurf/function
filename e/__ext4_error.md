# Function: <code>__ext4_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b83e0)
Location: fs/ext4/super.c:409
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/sysfs.c:ext4_attr_store
```
**Symbols:**

```
ffffffff812b83e0-ffffffff812b84dd: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e70e0)
Location: fs/ext4/super.c:438
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/sysfs.c:ext4_attr_store
```
**Symbols:**

```
ffffffff812e70e0-ffffffff812e71dd: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fccc0)
Location: fs/ext4/super.c:440
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/sysfs.c:ext4_attr_store
```
**Symbols:**

```
ffffffff812fccc0-ffffffff812fcdbd: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81331920)
Location: fs/ext4/super.c:445
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
```
**Symbols:**

```
ffffffff81331920-ffffffff81331a33: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81355dd0)
Location: fs/ext4/super.c:445
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff81355dd0-ffffffff81355ee3: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:448
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff8138b8b6-ffffffff8138b910: __ext4_error.cold.135 (STB_LOCAL)
ffffffff813841b0-ffffffff813842b4: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:490
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813a4416-ffffffff813a4470: __ext4_error.cold.139 (STB_LOCAL)
ffffffff8139cc90-ffffffff8139cd94: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:501
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813ce637-ffffffff813ce692: __ext4_error.cold (STB_LOCAL)
ffffffff813c6ec0-ffffffff813c6fc2: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813e7cf6-ffffffff813e7d51: __ext4_error.cold (STB_LOCAL)
ffffffff813e0280-ffffffff813e0382: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, int error, __u64 block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:534
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/ext4_jbd2.c:ext4_check_bdev_write_error
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:count_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff814347b6-ffffffff81434818: __ext4_error.cold (STB_LOCAL)
ffffffff8142ca90-ffffffff8142cbaf: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, bool force_ro, int error, __u64 block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:734
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:ext4_check_bdev_write_error
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff81bec649-ffffffff81bec6b6: __ext4_error.cold (STB_LOCAL)
ffffffff814458a0-ffffffff814459a2: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, bool force_ro, int error, __u64 block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:743
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff81bde6fb-ffffffff81bde768: __ext4_error.cold (STB_LOCAL)
ffffffff8144b170-ffffffff8144b272: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, bool force_ro, int error, __u64 block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:742
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff81ccd76a-ffffffff81ccd7d7: __ext4_error.cold (STB_LOCAL)
ffffffff8149f0f0-ffffffff8149f1ef: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, bool force_ro, int error, __u64 block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:761
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff81e8064a-ffffffff81e806b3: __ext4_error.cold (STB_LOCAL)
ffffffff815258c0-ffffffff81525a7a: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, bool force_ro, int error, __u64 block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c2f70)
Location: fs/ext4/super.c:754
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff815c2f70-ffffffff815c3190: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, bool force_ro, int error, __u64 block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fa6c0)
Location: fs/ext4/super.c:754
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff815fa6c0-ffffffff815fa8e0: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, bool force_ro, int error, __u64 block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff816332a0)
Location: fs/ext4/super.c:823
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
**Symbols:**

```
ffffffff816332a0-ffffffff816334c0: __ext4_error (STB_GLOBAL)
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
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b93b0)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffff8000104b93b0-ffff8000104b9520: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067ca2c)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
c067ca2c-c067cbb4: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ee680)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
c0000000005ee680-c0000000005ee848: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000335bf4)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffe000335bf4-ffffffe000335d0e: __ext4_error (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813e02d6-ffffffff813e0331: __ext4_error.cold (STB_LOCAL)
ffffffff813d8860-ffffffff813d8962: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813d0d56-ffffffff813d0db1: __ext4_error.cold (STB_LOCAL)
ffffffff813c92e0-ffffffff813c93e2: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813dd656-ffffffff813dd6b1: __ext4_error.cold (STB_LOCAL)
ffffffff813d5cf0-ffffffff813d5df2: __ext4_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ext4_error(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/balloc.c:ext4_get_group_desc
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff813f2a86-ffffffff813f2ae1: __ext4_error.cold (STB_LOCAL)
ffffffff813eaf60-ffffffff813eb079: __ext4_error (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int error</code>
</li>
<li>
<b>Param added. </b>
<code>__u64 block</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, function, line, fmt, (anon)</code> ➡️ <code>sb, function, line, error, block, fmt, (anon)</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force_ro</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, function, line, error, block, fmt, (anon)</code> ➡️ <code>sb, function, line, force_ro, error, block, fmt, (anon)</code>
</li>
</ul>
</details>
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
