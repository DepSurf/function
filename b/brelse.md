# Function: <code>brelse</code>

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
In fs/buffer.c (ffffffff812433e5)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:buffer_cpu_notify
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff812910ee)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff81293e14)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff812964ad)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_reserve_inode_write
```
```
In fs/ext4/namei.c (ffffffff812a18e6)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_orphan_del
```
```
In fs/ext4/super.c (ffffffff812ace45)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812bec5b)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_fs
```
```
In fs/ext4/extents.c (ffffffff812c3ba7)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_drop_refs
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_fiemap
```
```
In fs/ext4/mballoc.c (ffffffff812cee3f)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
```
```
In fs/ext4/mmp.c (ffffffff812d7999)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/indirect.c (ffffffff812d8666)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
```
```
In fs/ext4/xattr.c (ffffffff812dd432)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
```
```
In fs/ext4/inline.c (ffffffff812df84e)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data
```
```
In fs/jbd2/recovery.c (ffffffff812eb68f)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff812ed9b9)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff812f0fde)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff812f5799)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff812f5ef5)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_subdirs
```
```
In fs/fat/fatent.c (ffffffff812f910a)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
```
```
In fs/fat/file.c (ffffffff812fa9d5)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff812fb947)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/fat/misc.c (ffffffff812fe282)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/nfs.c (ffffffff812fe8a0)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff812ff040)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_find_form
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
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
In fs/buffer.c (ffffffff8126b51a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:buffer_cpu_notify
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff812be6ca)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff812c2e00)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff812c9221)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff812d02ff)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812d3539)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/super.c (ffffffff812e7b3d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/resize.c (ffffffff812f12cd)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/extents.c (ffffffff812f973d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/mballoc.c (ffffffff81304f9d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81307ed0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff8130a2a2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130f045)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/ext4/inline.c (ffffffff81312c1a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/jbd2/recovery.c (ffffffff81319978)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff8131b309)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff8131f5e8)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff813291b0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff8132a953)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8132e0a9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8132e777)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff81330dea)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8133245c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81332815)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813344b7)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff8127e65a)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff812d3d3e)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff812d83f0)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff812dee61)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff812e60a4)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812e9289)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/super.c (ffffffff812fd87d)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/resize.c (ffffffff8130729d)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/extents.c (ffffffff8130f73d)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/mballoc.c (ffffffff8131af6d)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff8131dec0)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff813202a2)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff81324e65)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/ext4/inline.c (ffffffff81328bc6)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/jbd2/recovery.c (ffffffff8132f968)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff813312f9)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff81335658)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff8133eef0)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff81340693)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81343de9)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff813444fb)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff81346b3a)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813481fc)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813485b5)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8134a173)
Location: include/linux/buffer_head.h:289
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff8128c02a)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff812e5687)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff812edc84)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff812f66b2)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff812f8ef3)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff812fcbb8)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81302f2f)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81309b10)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8131232c)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81314ad0)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81318a5a)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff81321d6d)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813325e8)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff8133eb20)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff813446b4)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff81346251)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff8134a3e0)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff81353ab8)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff813553ac)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813588a9)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff81358faf)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff8135b5d4)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8135cc0c)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8135d11c)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8135ec84)
Location: include/linux/buffer_head.h:290
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff812aebda)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff8130a0b4)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81312744)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff8131ace2)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff8131d533)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81321418)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8132791f)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8132e589)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff81336b14)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81339290)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8133d221)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff813464ad)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81356af8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff81363100)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff81368d54)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff8136a8e1)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff8136ea30)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff813786d8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff81379fcc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8137d599)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8137dcbf)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff813802d7)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8138190c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81381e1c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81383944)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff812d672a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff8133804e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813405e8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff81348ccc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff8134b422)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8134f3ae)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81355621)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8135cbde)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff813650b2)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff813677da)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8136b7bf)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff8137430d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81384e13)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff8139189c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff81397970)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff81399610)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff8139d14d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff813a7184)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff813a87ca)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813abfce)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff813ac721)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff813ae9e7)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813b04cc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813b0c8b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b2985)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff812ebbaa)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff8134f2df)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81357bdd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff81360e8b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff81363572)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8136755e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8136d951)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81375023)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8137d472)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff8137fc5a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81383c7f)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff8138c74d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff8139d903)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff813aa4dc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff813b02a3)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff813b2380)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff813b5ebd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff813bff74)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff813c180a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813c50f0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff813c59ac)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff813c7be5)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813c9b2c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813ca38b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813cc067)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff8130d2ba)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff8137832d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813811d3)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff81389f60)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff8138c3fc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8139098e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81396fad)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8139e70b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff813a711e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff813a90aa)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813ad445)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff813b6e57)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813c7b24)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff813d46bd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff813dac87)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff813dc9f0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff813e05ee)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff813ea77b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff813ec052)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813efaba)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff813f04fa)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff813f27a1)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813f46bc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813f4eff)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813f687b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff8132028a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff813906cd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81394bff)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff813a2980)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff813a4e4c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813a93ee)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813af9dd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff813b74a3)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff813bffae)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff813c1fca)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c6379)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff813cfd7d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813e0ee4)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff813edd9d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff813f4cd7)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff813f6a30)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff813fa62e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff8140481b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff81406172)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81409b2a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8140a3da)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff8140c6a7)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8140e58c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8140edcf)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8141074b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff81359e50)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
```
```
In fs/ext4/dir.c (ffffffff813dbcd7)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813e5fad)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff813ee9cc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff813f0d52)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813f534d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813fba26)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81400a6b)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8140c089)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff8140e2e8)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81412815)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff8141c9c1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff8142dab9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff8143acca)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_block_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff81442129)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff814439e9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff81447b2d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff814526ba)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff81454238)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81457702)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8145807d)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/fat/inode.c (ffffffff8145a5dd)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8145c36c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8145c9b1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8145e7e0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
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
In fs/buffer.c (ffffffff81367f80)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
```
```
In fs/ext4/dir.c (ffffffff813ed78f)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813f828b)
Location: include/linux/buffer_head.h:286
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
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff81401135)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff81403452)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81407aed)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8140e192)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141337b)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8141f4b9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81421793)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81425cb5)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff81430786)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff81446779)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff8145383a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_block_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/ext4/fast_commit.c (ffffffff814554f6)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
```
In fs/jbd2/recovery.c (ffffffff8145e48d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff8145fac9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff814644fa)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff8146eb9a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff814706e8)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81473ac2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff814743ba)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/fat/inode.c (ffffffff8147692d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8147826c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff814786e1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8147a4b0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
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
In fs/buffer.c (ffffffff8136e970)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/dir.c (ffffffff813f3e0b)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813fe70b)
Location: include/linux/buffer_head.h:288
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
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff81407676)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff81409a12)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8140df5d)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81414354)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff814195eb)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/mballoc.c (ffffffff81425df2)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81427fb3)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142c8b9)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff81437382)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff8144bf29)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff8145915a)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/ext4/fast_commit.c (ffffffff8145ac2b)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
```
In fs/jbd2/recovery.c (ffffffff81463cbc)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff814651b9)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff81469c84)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff81474178)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff81475b77)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8147950e)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff81479d2a)
Location: include/linux/buffer_head.h:288
Inline: True
```
```
In fs/fat/inode.c (ffffffff8147c39d)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8147dcf8)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8147e151)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
```
In fs/fat/namei_vfat.c (ffffffff8147fef0)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
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
In fs/buffer.c (ffffffff813bd7fc)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/dir.c (ffffffff81445ef7)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81450a4b)
Location: include/linux/buffer_head.h:288
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
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff81459f16)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff8145c5fb)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81460e1d)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814676ce)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8146c7db)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/mballoc.c (ffffffff814799e1)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff8147bc63)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff814807b9)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff8148affe)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff8149ffa1)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff814ad26a)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/ext4/fast_commit.c (ffffffff814aedc3)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
```
In fs/ext4/orphan.c (ffffffff814b22e1)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_release_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/recovery.c (ffffffff814b927f)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff814bab39)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff814c019f)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff814cae2c)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff814cdd6f)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814d0a1e)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff814d1345)
Location: include/linux/buffer_head.h:288
Inline: True
```
```
In fs/fat/inode.c (ffffffff814d3a9d)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff814d5593)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff814d58f1)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
```
In fs/fat/namei_vfat.c (ffffffff814d7790)
Location: include/linux/buffer_head.h:288
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
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
In fs/buffer.c (ffffffff814439dc)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/dir.c (ffffffff814c1f53)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff814cdaae)
Location: include/linux/buffer_head.h:310
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
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff814d7cb5)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff814da930)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff814df81e)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
```
```
In fs/ext4/inode.c (ffffffff814e7315)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff814ece51)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff814fbc0d)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff814fe184)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815036f6)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff8150edf9)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff81526bd6)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/symlink.c (ffffffff8152e995)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_free_link
```
```
In fs/ext4/xattr.c (ffffffff81535302)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/ext4/fast_commit.c (ffffffff81537cd9)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
```
In fs/ext4/orphan.c (ffffffff8153aef1)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_release_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/recovery.c (ffffffff81542ec4)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff815449e5)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff8154a9a8)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff81556ed4)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff81559b69)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8155d599)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8155df8c)
Location: include/linux/buffer_head.h:310
Inline: True
```
```
In fs/fat/inode.c (ffffffff81560cdf)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff815625ec)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81562a1b)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
```
In fs/fat/namei_vfat.c (ffffffff81564dea)
Location: include/linux/buffer_head.h:310
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
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
In fs/buffer.c (ffffffff814d2f2c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/dir.c (ffffffff8155a1bf)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8156620e)
Location: include/linux/buffer_head.h:323
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
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff81570960)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff81573810)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81578962)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
```
```
In fs/ext4/inode.c (ffffffff81580cc9)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81586c75)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff815963ed)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff815989a4)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8159e257)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_init_symlink_block
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff815a9c99)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff815c44b6)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/symlink.c (ffffffff815ccae5)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_free_link
```
```
In fs/ext4/xattr.c (ffffffff815d3742)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/ext4/fast_commit.c (ffffffff815d5e53)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
```
In fs/ext4/orphan.c (ffffffff815d94ad)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_release_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/recovery.c (ffffffff815e1c49)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff815e3ab8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff815ea4a8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff815f8ad4)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff815fcc8c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff815ff5e9)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8160003c)
Location: include/linux/buffer_head.h:323
Inline: True
```
```
In fs/fat/inode.c (ffffffff81602fa1)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81604fa6)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8160544b)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
```
In fs/fat/namei_vfat.c (ffffffff8160807e)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
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
In fs/buffer.c (ffffffff81509952)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/dir.c (ffffffff81591fbb)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8159de9e)
Location: include/linux/buffer_head.h:336
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
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff815a874c)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff815ab4b7)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff815aff02)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_folio
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
```
```
In fs/ext4/inode.c (ffffffff815b8279)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815bd1d5)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff815ccdc0)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff815cf484)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815d4b67)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_init_symlink_block
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff815e04f9)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff815fbb97)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/symlink.c (ffffffff816045d5)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_free_link
```
```
In fs/ext4/xattr.c (ffffffff8160b2f2)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/ext4/fast_commit.c (ffffffff8160da08)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
```
In fs/ext4/orphan.c (ffffffff8161100e)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_release_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/recovery.c (ffffffff816195d1)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff8161b274)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff81622298)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff81630a54)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff81634eae)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff816375c9)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8163801c)
Location: include/linux/buffer_head.h:336
Inline: True
```
```
In fs/fat/inode.c (ffffffff8163aec1)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8163ceb6)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8163d35b)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
```
In fs/fat/namei_vfat.c (ffffffff8163fece)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
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
In fs/buffer.c (ffffffff8153e782)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/dir.c (ffffffff815cad2b)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff815d6aee)
Location: include/linux/buffer_head.h:306
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
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff815e14fc)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff815e4257)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff815e8cb2)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_folio
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
```
```
In fs/ext4/inode.c (ffffffff815f1019)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815f5f9e)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff81604829)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81607d14)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8160d210)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_init_symlink_block
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff81618fd9)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff81634737)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/symlink.c (ffffffff8163d3ed)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/symlink.c:ext4_free_link
```
```
In fs/ext4/xattr.c (ffffffff816440b2)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/ext4/fast_commit.c (ffffffff816467c8)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
```
In fs/ext4/orphan.c (ffffffff81649dce)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_release_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/recovery.c (ffffffff81652525)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff81654194)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff8165a7fc)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_load_superblock
  - fs/jbd2/journal.c:journal_load_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff81669f04)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff8166e38e)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81670ab9)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8167150c)
Location: include/linux/buffer_head.h:306
Inline: True
```
```
In fs/fat/inode.c (ffffffff81674420)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81676426)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff816768cb)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
```
In fs/fat/namei_vfat.c (ffffffff8167947e)
Location: include/linux/buffer_head.h:306
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
  - fs/fat/namei_vfat.c:vfat_create_shortname
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
In fs/buffer.c (ffff8000103d8024)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffff800010462f90)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffff80001046792c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffff800010475fd8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffff80001047855c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffff80001047ccfc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff8000104844a0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffff80001048cf64)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffff800010496bac)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffff800010499768)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffff80001049de8c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffff8000104a877c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffff8000104ba264)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffff8000104c6d78)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffff8000104d0730)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffff8000104d24ec)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffff8000104d76bc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffff8000104e3408)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffff8000104e4f74)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffff8000104e9fac)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffff8000104ea834)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffff8000104ed464)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffff8000104ef140)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffff8000104efc50)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffff8000104f1b4c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (c05b1668)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/dir.c (c062327c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c0628614)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (c0637a00)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (c063a004)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c063e79c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (c0645a78)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (c064e84c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (c0658c34)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (c065b1f8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (c065fb5c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (c066ab18)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (c067d908)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (c068ad40)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (c06932f8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (c0694c2c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (c0699744)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (c06a2570)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (c06a4398)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (c06a7e04)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (c06a87d0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (c06ab0b8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (c06acca0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (c06ad274)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (c06af654)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (c0000000004de154)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (c00000000057f9d8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c000000000585e2c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (c000000000597e80)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (c00000000059ad3c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c0000000005a08a4)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005a9688)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (c0000000005b3afc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (c0000000005c0de8)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (c0000000005c3b6c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (c0000000005c9788)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (c0000000005d6534)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (c0000000005ef988)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (c0000000005ff23c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (c000000000609788)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (c00000000060bc68)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (c0000000006122f4)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (c0000000006205f0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (c000000000622a90)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (c000000000627e64)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (c0000000006289d0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (c00000000062c158)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (c00000000062e39c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (c00000000062eb58)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (c000000000630ca4)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffe000291a36)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffe0002f18ba)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffe0002f5782)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffe00030197a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffe000303692)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffe000306b74)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe00030c8f0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffe000312e3e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffe00031b60e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffe00031d1fa)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffe000320a0a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffe000328d00)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffe00033679c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffe00034107a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffe000347dee)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffe00034959a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffe00034d3a4)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffe000356be4)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffe000358334)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffe00035af2e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffe00035b60c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffe00035d93c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffe00035f1a2)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffe00035fa3e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffe000361214)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff8131886a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff81388cad)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138d1df)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff8139af60)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff8139d42c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813a19ce)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a7fbd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff813afa83)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff813b858e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff813ba5aa)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813be959)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff813c835d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813d94c4)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff813e637d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff813ed2b7)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff813ef010)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff813f2c0e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff813fcdfb)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff813fe752)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8140210a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff814029ba)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff81404c87)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81406b6c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff814073af)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81408d2b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff8130945a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff8137973d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8137dc6f)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff8138b9f0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff8138debc)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8139245e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81398a4d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff813a0513)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff813a901e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff813ab03a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813af3e9)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff813b8ddd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813c9f44)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff813d6dfd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff813ddd37)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff813dfa90)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff813e368e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff813ed87b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff813ef1d2)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813f2b8a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff813f343a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff813f5707)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813f75ec)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813f7e2f)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813f97ab)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff8131633a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff8138660d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138ab3f)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff813987c0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff8139ac8c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8139f22e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a581d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff813ad2e3)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff813b5dee)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff813b7e0a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813bbf39)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff813c57ed)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813d6954)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff813e36fd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff813ea637)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff813ec390)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff813eff8e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff813fa17b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff813fbad2)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813ff48a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff813ffd3a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff81402007)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81403eec)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8140472f)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff814060ab)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
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
In fs/buffer.c (ffffffff8132807a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/dir.c (ffffffff8139a2f7)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139e87f)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_drop_refs
```
```
In fs/ext4/ialloc.c (ffffffff813acbe0)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/indirect.c (ffffffff813af14c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b379e)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b9f5d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff813c1c9c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff813caade)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff813ccb0a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813d0ee9)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_release
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
```
```
In fs/ext4/resize.c (ffffffff813daa1d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:verify_group_input
```
```
In fs/ext4/super.c (ffffffff813ebbfd)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_read
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/ext4/xattr.c (ffffffff813f8b0d)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
```
In fs/jbd2/recovery.c (ffffffff813fff8f)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/revoke.c (ffffffff81401d30)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff81405995)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/cache.c (ffffffff8140fdb6)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/dir.c (ffffffff814116f2)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_subdirs
  - fs/fat/dir.c:fat_dir_empty
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814150ba)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat12_ent_next
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/file.c (ffffffff8141596a)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/inode.c (ffffffff81417fd7)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81419b5c)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8141a3af)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8141bd6b)
Location: include/linux/buffer_head.h:292
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_find_form
```
</details>
</li>
</ul>

## Differences
