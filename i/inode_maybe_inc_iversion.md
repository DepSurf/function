# Function: <code>inode_maybe_inc_iversion</code>

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
In fs/inode.c (ffffffff812b89a2)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffff8134c531)
Location: include/linux/iversion.h:174
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81355491)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8136d858)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813a7fc6)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813aed64)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b27ee)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
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
In fs/inode.c (ffffffff812cdaf2)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffff81364671)
Location: include/linux/iversion.h:174
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8136d7c0)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81385cd8)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813c0db4)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813c7f43)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813c9884)
Location: include/linux/iversion.h:174
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813cbedf)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff813ddf88)
Location: include/linux/iversion.h:174
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff812ea892)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffff8138cf63)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81396daa)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813afcb9)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813eb604)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f2b2c)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f4422)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f66ee)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff81409638)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff812fc2c2)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffff813a59b3)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813af7da)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813c8c79)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81404fb4)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140caed)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8140e2f2)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff814105be)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff81422f98)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff813352b0)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813f1903)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff813fb83a)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81414739)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81452f72)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8145a157)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8145c0e6)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8145e8cb)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff814726c8)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff81340c20)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81404423)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8140dfb4)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81427d89)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff8146f422)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814764a7)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81477fe6)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8147a59b)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff8148d038)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff81347041)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8140aa06)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff81414174)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8142ea00)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff814748f2)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8147bf17)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8147da7d)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff8147ffdb)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff814928b8)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff81394a71)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8145d660)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814674d4)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff814831a0)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff814cb632)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814d3554)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814d52fd)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff814d787b)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff814ea298)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff81416d13)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814db8c5)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814e70e3)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81507c8a)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81557bcb)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff81560968)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81562308)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff81564ee7)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff81578e38)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inode_maybe_inc_iversion(struct inode *inode, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b7b60)
Location: fs/libfs.c:1558
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fileattr_set
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/posix_acl.c:simple_set_acl
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/misc.c:fat_update_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff814b7b60-ffffffff814b7bac: inode_maybe_inc_iversion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inode_maybe_inc_iversion(struct inode *inode, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ec9b0)
Location: fs/libfs.c:1553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fileattr_set
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/posix_acl.c:simple_set_acl
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/misc.c:fat_update_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff814ec9b0-ffffffff814ec9fc: inode_maybe_inc_iversion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inode_maybe_inc_iversion(struct inode *inode, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81520900)
Location: fs/libfs.c:1854
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_fileattr_set
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/inode.c:inode_update_timestamps
  - fs/posix_acl.c:simple_set_acl
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff81520900-ffffffff8152094c: inode_maybe_inc_iversion (STB_GLOBAL)
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
In fs/inode.c (ffff8000103ac8b4)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffff8000104791b4)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (ffff800010488e24)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffff8000104a06b4)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffff8000104e5cf0)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffff8000104ed738)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffff8000104eee60)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffff8000104f19b8)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffff8000105069f8)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (c058db2c)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (c063aec4)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (c0645854)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (c06627d8)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (c06a2f84)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c06ab4b4)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c06ac988)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (c06af484)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (c06c49f4)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
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
In fs/inode.c (c0000000004a8490)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (c00000000059bd80)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (c0000000005a9374)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (c0000000005ccb30)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (c000000000621124)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c00000000062c568)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c00000000062dfe0)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (c000000000630d70)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (c00000000064bed0)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffe000271222)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffe0003044d8)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (ffffffe00030c6fe)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffe0003229e6)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffe000357286)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffe00035dce2)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffe00035ef10)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffe00036128e)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffe000372624)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff812f48a2)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffff8139df93)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a7dba)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813c1259)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813fd594)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814050cd)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814068d2)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81408b9e)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff8141b578)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff812e54c2)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffff8138ea23)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8139884a)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813b1ce9)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813ee014)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f5b4d)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f7352)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f961e)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff8140bff8)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff812f26b2)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffff8139b7f3)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a561a)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813be709)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813fa914)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140244d)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81403c52)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81405f1e)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff81417718)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
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
In fs/inode.c (ffffffff81303dc2)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inline.c (ffffffff813afcb3)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b9d5a)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813d37e9)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81410574)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8141841d)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814198c2)
Location: include/linux/iversion.h:198
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8141bbde)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
```
```
In fs/fuse/dir.c (ffffffff8142e508)
Location: include/linux/iversion.h:198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
</details>
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
