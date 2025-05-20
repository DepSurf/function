# Function: <code>inode_peek_iversion_raw</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8d79)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffff81337a8f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8134e26e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81355497)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffff8136d85e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff8138cbba)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813a7fcc)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813aed6a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b27f4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In security/integrity/ima/ima_main.c (ffffffff81451d1f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814536a7)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff812cdeb9)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffff8134ed0f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8136640e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8136d7c6)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffff81385cde)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff813a57f9)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813c0dba)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813c7f49)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813c988a)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813cbee5)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff813ddf8e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff813ea007)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff8146ecdf)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff81470887)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff812eacf1)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffff81377abf)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8138f79b)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81396db0)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffff813afcbf)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff813cf8b8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813eb60a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f2b32)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f4428)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f66f4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff8140963e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814168ab)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff8149c6ec)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e237)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff812fc821)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffff8138fe3f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a81fb)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813af7e0)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffff813c8c7f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff813e8f88)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff81404fba)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140caf3)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8140e2f8)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff814105c4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff81422f9e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814307cb)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff814b686c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814b86d1)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff81335989)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
```
```
In fs/ext4/dir.c (ffffffff813db40f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f42ba)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff813fb840)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8141473f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff81435eb6)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff81452f78)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8145a15d)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8145c0ec)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8145e8d1)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff814726ce)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814803bc)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff81515eec)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff81518310)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff81341309)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
```
```
In fs/ext4/dir.c (ffffffff813ece3f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81406a4a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8140dfba)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81427d8f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff8144e8f6)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff8146f428)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814764ad)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81477fec)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8147a5a1)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff8148d03e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8149ba9f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff81532fbc)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff815352e0)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff81347649)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
```
```
In fs/ext4/dir.c (ffffffff813f336f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140cedf)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8141417a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8142ea06)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff81454406)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff814748f8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8147bf1d)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8147da83)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff8147ffe1)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff814928be)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814a0bbf)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff8153b46b)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d900)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff81395169)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
```
```
In fs/ext4/dir.c (ffffffff814453b0)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8145fd1f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814674da)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff814831a6)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff814a84c6)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff814cb638)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814d355a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814d5303)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff814d7881)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff814ea29e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814f8a9e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff81599eeb)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c790)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff81417fbf)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
```
```
In fs/ext4/dir.c (ffffffff814c1472)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814de464)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814e70e9)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/namei.c (ffffffff81507c90)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff815302cb)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff81557bd1)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8156096e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8156230e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff81564eed)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff81578e3e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8158908f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff8163eb0c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff8164180c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff814a20ca)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/libfs.c (ffffffff814b7b6f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/ext4/dir.c (ffffffff81559712)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815774d4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8157b9e6)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/xattr.c (ffffffff815ce38b)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/namei_vfat.c (ffffffff8160636b)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8162f5a8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff816f679c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff816f981c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff814d7402)
Location: include/linux/iversion.h:128
Inline: True
```
```
In fs/libfs.c (ffffffff814eca15)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/ext4/dir.c (ffffffff81591535)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815aea0c)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff815b2dde)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/xattr.c (ffffffff81605c5f)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/namei_vfat.c (ffffffff8163df0f)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8166781b)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/inode.c (ffffffff81509cdd)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/inode.c:inode_needs_update_time
```
```
In fs/libfs.c (ffffffff81520965)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/ext4/dir.c (ffffffff815ca275)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815e77cc)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff815ebbd4)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/xattr.c (ffffffff8163e96f)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/namei_vfat.c (ffffffff8167747f)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/readdir.c (ffffffff816a1b75)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff8177121c)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/inode.c (ffff8000103ac2b8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffff800010462794)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffff80001047ba48)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffff800010488e28)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffff8000104a06b8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffff8000104c1dc4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffff8000104e5cf4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffff8000104ed73c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffff8000104eee64)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffff8000104f19bc)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffff8000105069fc)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffff8000105152f8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffff8000105aea58)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0a30)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (c058d5ac)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (c0622a00)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c063d2d8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (c0645858)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (c06627dc)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (c0685b60)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (c06a2f88)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c06ab4b8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c06ac98c)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (c06af488)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (c06c49f8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
```
```
In fs/fuse/readdir.c (c06cffac)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (c075e144)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (c0760094)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (c0000000004a7854)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (c00000000057eefc)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c00000000059f060)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (c0000000005a9378)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (c0000000005ccb34)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (c0000000005f8e04)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (c000000000621128)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c00000000062c56c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c00000000062dfe4)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (c000000000630d74)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (c00000000064bed4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (c00000000065daac)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (c00000000072db00)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (c000000000730754)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffe000271802)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffe0002f1218)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffe000305db2)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffe00030c702)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffe0003229ea)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffe00033d2a0)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffe00035728a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffe00035dce6)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffe00035ef14)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffe000361292)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffe000372628)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffe00037ec7c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f6b78)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f8540)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff812f4e01)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffff8138841f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a07db)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a7dc0)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffff813c125f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff813e1568)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813fd59a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814050d3)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814068d8)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81408ba4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff8141b57e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff81428dab)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff814aee4c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814b0cb1)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff812e5a21)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffff81378eaf)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139126b)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81398850)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffff813b1cef)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff813d1fe8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813ee01a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f5b53)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f7358)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f9624)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff8140bffe)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8141982b)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff8149f86c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814a16d1)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff812f2c11)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffff81385d7f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139e03b)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a5620)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffff813be70f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff813de8e8)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813fa91a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff81402453)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81403c58)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81405f24)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff8141771e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff81424f4b)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff814aaeec)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814acd41)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/inode.c (ffffffff81304321)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (ffffffff81399a6f)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813b25ab)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813b9d60)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/namei.c (ffffffff813d37ef)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff813f3d08)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff8141057a)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff81418423)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814198c8)
Location: include/linux/iversion.h:110
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8141bbe4)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff8142e50e)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8143bde6)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff814c392c)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814c5791)
Location: include/linux/iversion.h:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
</details>
</li>
</ul>

## Differences
