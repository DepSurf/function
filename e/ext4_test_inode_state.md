# Function: <code>ext4_test_inode_state</code>

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
In fs/ext4/file.c (ffffffff81291903)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81292cfb)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81295e99)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_da_write_end
```
```
In fs/ext4/namei.c (ffffffff812a6b5b)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/extents.c (ffffffff812c44f5)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_can_extents_be_merged
  - fs/ext4/extents.c:ext4_fiemap
```
```
In fs/ext4/migrate.c (ffffffff812ccaa5)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/indirect.c (ffffffff812d9ced)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_direct_IO
```
```
In fs/ext4/extents_status.c (ffffffff812db342)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/xattr.c (ffffffff812dddc4)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/inline.c (ffffffff812df599)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
  - fs/ext4/inline.c:ext4_prepare_inline_data
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
In fs/ext4/file.c (ffffffff812bee63)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812c021c)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812c9326)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/namei.c (ffffffff812d5bbe)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/extents.c (ffffffff812f9613)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/migrate.c (ffffffff812fc419)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/extents_status.c (ffffffff8130acc2)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/xattr.c (ffffffff8130e24b)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/ext4/inline.c (ffffffff81310420)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
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
In fs/ext4/file.c (ffffffff812d4483)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812d5885)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812def5e)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/namei.c (ffffffff812eb8be)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/extents.c (ffffffff8130f613)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/migrate.c (ffffffff813123c9)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/extents_status.c (ffffffff81320cc2)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/xattr.c (ffffffff81324585)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/ext4/inline.c (ffffffff81328b6a)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
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
In fs/ext4/extents.c (ffffffff812edb4f)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff812efc72)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff812f0dfe)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812f35d3)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff812fcb4a)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813031a5)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/migrate.c (ffffffff81313db1)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8131b704)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/xattr.c (ffffffff8133eafa)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
In fs/ext4/extents.c (ffffffff8131260f)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff81314772)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81315a2e)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81317b6d)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813213aa)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81327b98)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/migrate.c (ffffffff81338571)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8133fd3c)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/xattr.c (ffffffff813630da)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/extents.c (ffffffff813404a4)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff813425f3)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81343835)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff813459f5)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8134f3c9)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813557f3)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/migrate.c (ffffffff81366b32)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8136dc6b)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/xattr.c (ffffffff8139187a)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/extents.c (ffffffff81357a99)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff8135a0c3)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff8135b975)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff8135db69)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81367579)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff8136db23)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/migrate.c (ffffffff8137efa2)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813860eb)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/xattr.c (ffffffff813aa4ba)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/extents.c (ffffffff81381135)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff8138310d)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81385185)
Location: fs/ext4/ext4.h:1599
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81386d03)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8139093a)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81397145)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/migrate.c (ffffffff813a83a3)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813b0159)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/xattr.c (ffffffff813d4699)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
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
In fs/ext4/extents.c (ffffffff81394b68)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff8139b5ed)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff8139dc25)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff8139f753)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813a939a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813afb75)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813b6eda)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813c125c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813c9119)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (ffffffff813cc638)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff813edd79)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (ffffffff813eebe3)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff813dd775)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
```
```
In fs/ext4/extents_status.c (ffffffff813e69bb)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff813e9715)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff813eb355)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/ext4/fsync.c:ext4_sync_parent
```
```
In fs/ext4/inline.c (ffffffff813f52e7)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813fb95c)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff814026d4)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8140d165)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff81414b57)
Location: fs/ext4/ext4.h:1739
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814187f7)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff8143ad31)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (ffffffff8143bd80)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff813ef065)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
```
```
In fs/ext4/extents_status.c (ffffffff813f8ceb)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff813fb3c5)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff813fd585)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/ext4/fsync.c:ext4_sync_parent
```
```
In fs/ext4/inline.c (ffffffff81407a87)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff8140e0cc)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff81414fac)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff814205c5)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff814281a7)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
```
```
In fs/ext4/readpage.c (ffffffff8142c33d)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff814538a1)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/fast_commit.c (ffffffff81456528)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/verity.c (ffffffff814580e0)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff813f5525)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
```
```
In fs/ext4/extents_status.c (ffffffff813ff41b)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81401895)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81403bf0)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8140def7)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff814144d2)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8141b217)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81426c95)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff8142eca9)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
```
```
In fs/ext4/readpage.c (ffffffff81433034)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff814591c1)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/fast_commit.c (ffffffff8145bfb9)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/verity.c (ffffffff8145dc40)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff81447c51)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
```
```
In fs/ext4/extents_status.c (ffffffff81451a2b)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81453e25)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff8145646a)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81460db7)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81467852)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8146e3f3)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8147a925)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff81483449)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
```
```
In fs/ext4/readpage.c (ffffffff81486954)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff814ad2d1)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/fast_commit.c (ffffffff814af5cb)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/orphan.c (ffffffff814b1561)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/verity.c (ffffffff814b3100)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff814c3861)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
```
```
In fs/ext4/extents_status.c (ffffffff814ce9cd)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff814d0de5)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff814d3ee0)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff814df73a)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff814e74f6)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff814eee2e)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff814fcd07)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff815065ca)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
```
```
In fs/ext4/readpage.c (ffffffff8150a22d)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff8153537e)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/fast_commit.c (ffffffff81536fa3)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/orphan.c (ffffffff8153a099)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/verity.c (ffffffff8153baf1)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff815654d5)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
```
```
In fs/ext4/extents_status.c (ffffffff8156722d)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81569815)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff8156cb5b)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8157887a)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81580eb6)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff81588e1d)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81597497)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff815a109a)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
```
```
In fs/ext4/readpage.c (ffffffff815a4d7a)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff815d37ba)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/fast_commit.c (ffffffff815d544a)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/orphan.c (ffffffff815d8609)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/verity.c (ffffffff815da171)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff8159d125)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
```
```
In fs/ext4/extents_status.c (ffffffff8159f3fd)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
```
```
In fs/ext4/file.c (ffffffff815a1605)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff815a49a7)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff815afe1a)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff815b8466)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_folio
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff815bf6a9)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff815cded7)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff815d7a1a)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
```
```
In fs/ext4/xattr.c (ffffffff8160b371)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/fast_commit.c (ffffffff8160d00a)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/orphan.c (ffffffff81610199)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/verity.c (ffffffff81611eb4)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff815d5d75)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
```
```
In fs/ext4/extents_status.c (ffffffff815d7f4d)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
```
```
In fs/ext4/file.c (ffffffff815da3c5)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff815dd7e6)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff815e8bca)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff815f1206)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_folio
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff815f844f)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81606757)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff8161008a)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
```
```
In fs/ext4/xattr.c (ffffffff81644131)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/fast_commit.c (ffffffff81645dca)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/orphan.c (ffffffff81648f59)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/verity.c (ffffffff8164ac54)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffff8000104678b8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffff80001046e278)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffff800010471184)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffff800010472a90)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffff80001047cc9c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffff80001048464c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffff80001048c9f0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffff80001049831c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/namei.c (ffff8000104a0bb0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (ffff8000104a4afc)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffff8000104c6d64)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (ffff8000104c860c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (c062851c)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (c062f800)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (c0631b28)
Location: fs/ext4/ext4.h:1637
Inline: True
```
```
In fs/ext4/fsync.c (c0633f2c)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (c063e74c)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (c0645c20)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (c064de90)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (c065a310)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c0662c9c)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (c06666f4)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (c068ad24)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (c068bdfc)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (c000000000585db0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (c00000000058e35c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (c000000000590ddc)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (c000000000593960)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (c0000000005a081c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (c0000000005a9930)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (c0000000005b2848)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (c0000000005c2a10)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c0000000005cd1d4)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (c0000000005d1c5c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (c0000000005ff220)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (c000000000600a60)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffe0002f5712)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffe0002fb24a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffe0002fd198)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffe0002fe932)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffe000306b14)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffe00030ca34)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffe000311f60)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffe00031c666)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffe000322d8e)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (ffffffe000325c1c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffe000341064)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (ffffffe000341e98)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff8138d148)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff81393bcd)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81396205)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81397d33)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813a197a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813a8155)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813af4ba)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813b983c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813c16f9)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (ffffffff813c4c18)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff813e6359)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (ffffffff813e71c3)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff8137dbd8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff8138465d)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81386c95)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff813887c3)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8139240a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff81398be5)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8139ff4a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813aa2cc)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813b2189)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (ffffffff813b5698)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff813d6dd9)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (ffffffff813d7c43)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff8138aaa8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff8139152d)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff81393b65)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81395693)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8139f1da)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813a59b5)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813acd1a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813b709c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813beba9)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (ffffffff813c20a8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff813e36d9)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (ffffffff813e4543)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff8139e7e8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_can_extents_be_merged
```
```
In fs/ext4/extents_status.c (ffffffff813a53bd)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/ext4/file.c (ffffffff813a7bf5)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff813a97e0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813b374a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
```
```
In fs/ext4/inode.c (ffffffff813ba0f0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813c16ba)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813cbdac)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813d3c89)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/readpage.c (ffffffff813d7228)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/xattr.c (ffffffff813f8ae9)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/ext4/verity.c (ffffffff813f9953)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
</details>
</li>
</ul>

## Differences
