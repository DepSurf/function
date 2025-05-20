# Function: <code>__mark_inode_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8123ac90)
Location: fs/fs-writeback.c:2019
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:nobh_write_end
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
```
**Symbols:**

```
ffffffff8123ac90-ffffffff8123b00b: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81262b30)
Location: fs/fs-writeback.c:2073
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_fault
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff81262b30-ffffffff81262ec5: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81275f80)
Location: fs/fs-writeback.c:2071
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_mapping_entry
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff81275f80-ffffffff81276315: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81283400)
Location: fs/fs-writeback.c:2080
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff81283400-ffffffff8128379a: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a5f80)
Location: fs/fs-writeback.c:2113
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_mapping_entry
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff812a5f80-ffffffff812a632f: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812ccb30)
Location: fs/fs-writeback.c:2114
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_mapping_entry
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff812ccb30-ffffffff812ccedd: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e1e60)
Location: fs/fs-writeback.c:2140
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:__generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_write_end
  - fs/iomap.c:iomap_set_page_dirty
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff812e1e60-ffffffff812e220d: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81300880)
Location: fs/fs-writeback.c:2155
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff81300880-ffffffff81300c1d: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81312f50)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff81312f50-ffffffff813132ed: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134c8b0)
Location: fs/fs-writeback.c:2251
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:touch_atime
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end_inline
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff8134c8b0-ffffffff8134cc54: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813598b0)
Location: fs/fs-writeback.c:2247
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:touch_atime
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end_inline
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff813598b0-ffffffff81359bd8: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813604c0)
Location: fs/fs-writeback.c:2241
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:touch_atime
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff813604c0-ffffffff813607a8: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813aeb40)
Location: fs/fs-writeback.c:2381
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:touch_atime
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff813aeb40-ffffffff813aee25: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81433130)
Location: fs/fs-writeback.c:2363
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:touch_atime
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
```
**Symbols:**

```
ffffffff81433130-ffffffff814334e6: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c1490)
Location: fs/fs-writeback.c:2387
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:touch_atime
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
```
**Symbols:**

```
ffffffff814c1490-ffffffff814c1837: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f6820)
Location: fs/fs-writeback.c:2398
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:touch_atime
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
```
**Symbols:**

```
ffffffff814f6820-ffffffff814f6bcd: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152af60)
Location: fs/fs-writeback.c:2420
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_update_time
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
```
**Symbols:**

```
ffffffff8152af60-ffffffff8152b30d: __mark_inode_dirty (STB_GLOBAL)
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
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c8760)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffff8000103c8760-ffff8000103c8b68: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a5078)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
c05a5078-c05a54a8: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c9c10)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
c0000000004c9c10-c0000000004ca0e0: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000286e6e)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffe000286e6e-ffffffe000287226: __mark_inode_dirty (STB_GLOBAL)
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
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130b530)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff8130b530-ffffffff8130b8cd: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fc150)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff812fc150-ffffffff812fc4ed: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81309320)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff81309320-ffffffff813096bd: __mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81319c70)
Location: fs/fs-writeback.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/namei.c:__page_symlink
  - fs/dcache.c:d_tmpfile
  - fs/inode.c:generic_update_time
  - fs/inode.c:generic_update_time
  - fs/libfs.c:simple_setattr
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/sync.c:vfs_fsync_range
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/dax.c:dax_insert_entry
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower
```
**Symbols:**

```
ffffffff81319c70-ffffffff8131a070: __mark_inode_dirty (STB_GLOBAL)
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
