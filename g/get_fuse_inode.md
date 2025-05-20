# Function: <code>get_fuse_inode</code>

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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:678
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:678
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:678
Inline: True
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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:688
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:688
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:688
Inline: True
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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:689
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:689
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:689
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:689
Inline: True
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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:685
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:685
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:685
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:685
Inline: True
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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
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
In fs/fuse/dir.c (ffffffff813c6cd4)
Location: fs/fuse/fuse_i.h:690
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff813cb83c)
Location: fs/fuse/fuse_i.h:690
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff813cdb5e)
Location: fs/fuse/fuse_i.h:690
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_alloc_inode
```
```
In fs/fuse/xattr.c (ffffffff813d03d7)
Location: fs/fuse/fuse_i.h:690
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
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
In fs/fuse/dir.c (ffffffff813e0a95)
Location: fs/fuse/fuse_i.h:758
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff813e6a15)
Location: fs/fuse/fuse_i.h:758
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff813e6f4e)
Location: fs/fuse/fuse_i.h:758
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_destroy_inode
  - fs/fuse/inode.c:fuse_alloc_inode
```
```
In fs/fuse/xattr.c (ffffffff813e9947)
Location: fs/fuse/fuse_i.h:758
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff813e9fa1)
Location: fs/fuse/fuse_i.h:758
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dev.c (ffffffff81408e43)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/dir.c (ffffffff8140c665)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff814128b5)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff81412f8e)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff81415aab)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff81416845)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (ffffffff814261f5)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff8142c6c5)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff8142d0de)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff8142f8eb)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff81430765)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (ffffffff814756d5)
Location: fs/fuse/fuse_i.h:770
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff8147c105)
Location: fs/fuse/fuse_i.h:770
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8147c3a9)
Location: fs/fuse/fuse_i.h:770
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff8147f759)
Location: fs/fuse/fuse_i.h:770
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff81480362)
Location: fs/fuse/fuse_i.h:770
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/fuse/dir.c (ffffffff81490385)
Location: fs/fuse/fuse_i.h:844
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81497045)
Location: fs/fuse/fuse_i.h:844
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81499d07)
Location: fs/fuse/fuse_i.h:844
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff8149ae85)
Location: fs/fuse/fuse_i.h:844
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff8149b024)
Location: fs/fuse/fuse_i.h:844
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8149c1fc)
Location: fs/fuse/fuse_i.h:844
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/dax.c (ffffffff8149d5b7)
Location: fs/fuse/fuse_i.h:844
Inline: True
Inline callers:
  - fs/fuse/dax.c:alloc_dax_mapping_reclaim
  - fs/fuse/dax.c:inode_inline_reclaim_one_dmap
  - fs/fuse/dax.c:inode_inline_reclaim_one_dmap
  - fs/fuse/dax.c:inode_inline_reclaim_one_dmap
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_upgrade_dax_mapping
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (ffffffff81495db5)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff8149c1a5)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_file_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8149ef33)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff814a00d5)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff814a0274)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814a14ac)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff814a21d2)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff814a2527)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (ffffffff814ed875)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff814f3ca5)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_file_mmap
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_file_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff814f664d)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff814f80e5)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff814f8294)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814f955c)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff814fa272)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff814fbb75)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:879
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:879
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:879
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:879
Inline: True
```
```
In fs/fuse/acl.c (0)
Location: fs/fuse/fuse_i.h:879
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: fs/fuse/fuse_i.h:879
Inline: True
```
```
In fs/fuse/ioctl.c (0)
Location: fs/fuse/fuse_i.h:879
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: fs/fuse/fuse_i.h:879
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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:882
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:882
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:882
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:882
Inline: True
```
```
In fs/fuse/acl.c (0)
Location: fs/fuse/fuse_i.h:882
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: fs/fuse/fuse_i.h:882
Inline: True
```
```
In fs/fuse/ioctl.c (0)
Location: fs/fuse/fuse_i.h:882
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: fs/fuse/fuse_i.h:882
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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:887
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:887
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:887
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:887
Inline: True
```
```
In fs/fuse/acl.c (0)
Location: fs/fuse/fuse_i.h:887
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: fs/fuse/fuse_i.h:887
Inline: True
```
```
In fs/fuse/ioctl.c (0)
Location: fs/fuse/fuse_i.h:887
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: fs/fuse/fuse_i.h:887
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
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:914
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:914
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:914
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:914
Inline: True
```
```
In fs/fuse/acl.c (0)
Location: fs/fuse/fuse_i.h:914
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: fs/fuse/fuse_i.h:914
Inline: True
```
```
In fs/fuse/ioctl.c (0)
Location: fs/fuse/fuse_i.h:914
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: fs/fuse/fuse_i.h:914
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
In fs/fuse/dir.c (ffff800010509a30)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffff800010510670)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffff800010510ee8)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffff800010514294)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffff800010515290)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (c06c59d0)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_invalidate_attr_mask
  - fs/fuse/dir.c:fuse_invalidate_attr_mask
```
```
In fs/fuse/file.c (c06cbdac)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_lk_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (c06cc810)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (c06cf0f0)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (c06cff24)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (c00000000064f8c0)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:__fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (c000000000658070)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (c000000000658c90)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (c00000000065c538)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (c00000000065da10)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (ffffffe00037545a)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffe00037ae20)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffe00037b784)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffe00037dd7c)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
```
```
In fs/fuse/readdir.c (ffffffe00037ec12)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (ffffffff8141e7d5)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81424ca5)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff814256be)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff81427ecb)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff81428d45)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (ffffffff8140f255)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81415725)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff8141613e)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff8141894b)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff814197c5)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (ffffffff8141a975)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81420e45)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff8142185e)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff8142406b)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff81424ee5)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_emit
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
In fs/fuse/dir.c (ffffffff81431715)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_init_dir
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81437c65)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_find_writeback
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff814386de)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_encode_fh
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_inode_set
  - fs/fuse/inode.c:fuse_inode_eq
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_free_inode
```
```
In fs/fuse/xattr.c (ffffffff8143aeab)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8143bd7a)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
</ul>

## Differences
