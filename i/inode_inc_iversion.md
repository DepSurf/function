# Function: <code>inode_inc_iversion</code>

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
In fs/inode.c (ffffffff812275bd)
Location: include/linux/fs.h:1915
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inode.c (ffffffff8129b059)
Location: include/linux/fs.h:1915
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
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
In fs/inode.c (ffffffff8124fcdd)
Location: include/linux/fs.h:2008
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inode.c (ffffffff812c9152)
Location: include/linux/fs.h:2008
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
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
In fs/inode.c (ffffffff81262d0d)
Location: include/linux/fs.h:1981
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inode.c (ffffffff812ded92)
Location: include/linux/fs.h:1981
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
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
In fs/inode.c (ffffffff812705af)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inode.c (ffffffff81302e0a)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8131b218)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/inode.c (ffffffff81292eef)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/inode.c (ffffffff813277fa)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8133f938)
Location: include/linux/fs.h:2061
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
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
In fs/ext4/inline.c (ffffffff8134c531)
Location: include/linux/iversion.h:215
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81355491)
Location: include/linux/iversion.h:215
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8136d858)
Location: include/linux/iversion.h:215
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813a7fc6)
Location: include/linux/iversion.h:215
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813aed64)
Location: include/linux/iversion.h:215
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b27ee)
Location: include/linux/iversion.h:215
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
In fs/ext4/inline.c (ffffffff81364671)
Location: include/linux/iversion.h:215
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8136d7c0)
Location: include/linux/iversion.h:215
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81385cd8)
Location: include/linux/iversion.h:215
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813c0db4)
Location: include/linux/iversion.h:215
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813c7f43)
Location: include/linux/iversion.h:215
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813cbedf)
Location: include/linux/iversion.h:215
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138cf63)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81396daa)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813afcb9)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813eb604)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f2b2c)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813f66ee)
Location: include/linux/iversion.h:239
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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a59b3)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813af7da)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813c8c79)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81404fb4)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140caed)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff814105be)
Location: include/linux/iversion.h:239
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f1903)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff813fb83a)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81414739)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81452f72)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8145a157)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8145e8cb)
Location: include/linux/iversion.h:239
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81404423)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8140dfb4)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81427d89)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff8146f422)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814764a7)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8147a59b)
Location: include/linux/iversion.h:239
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140aa06)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff81414174)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8142ea00)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff814748f2)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8147bf17)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8147ffdb)
Location: include/linux/iversion.h:239
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145d660)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814674d4)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff814831a0)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff814cb632)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814d3554)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff814d787b)
Location: include/linux/iversion.h:239
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814db8c5)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814e70e3)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81507c8a)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81557bcb)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff81560968)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81564ee7)
Location: include/linux/iversion.h:239
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138ad87)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
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
```
```
In fs/posix_acl.c (ffffffff8151725a)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_set_acl
```
```
In fs/ext4/inline.c (ffffffff815742b7)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff815850bf)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff8158927f)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff815a2765)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff815d2cb2)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/fat/dir.c (ffffffff815f97e9)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff816035dc)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81607ac3)
Location: include/linux/iversion.h:185
Inline: True
Inline callers:
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bd3b7)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
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
```
```
In fs/posix_acl.c (ffffffff8154eb8a)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_set_acl
```
```
In fs/ext4/inline.c (ffffffff815ac107)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff815bbc64)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff815bfabb)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff815d90fa)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff8160a7a4)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/fat/dir.c (ffffffff81631749)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8163b4fc)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8163f953)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e5233)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
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
```
```
In fs/posix_acl.c (ffffffff815849cf)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_set_acl
```
```
In fs/ext4/inline.c (ffffffff815e4e9c)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff815f4a3d)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff815f8851)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff816117cb)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/xattr.c (ffffffff81643546)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/fat/dir.c (ffffffff8166abf9)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff81674a5b)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81678f03)
Location: include/linux/iversion.h:203
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
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
In fs/ext4/inline.c (ffff8000104791b4)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (ffff800010488e24)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffff8000104a06b4)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffff8000104e5cf0)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffff8000104ed738)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffff8000104f19b8)
Location: include/linux/iversion.h:239
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063aec4)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (c0645854)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (c06627d8)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (c06a2f84)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c06ab4b4)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (c06af484)
Location: include/linux/iversion.h:239
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059bd80)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (c0000000005a9374)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (c0000000005ccb30)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (c000000000621124)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c00000000062c568)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (c000000000630d70)
Location: include/linux/iversion.h:239
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe0003044d8)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (ffffffe00030c6fe)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffe0003229e6)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffe000357286)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffe00035dce2)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffe00036128e)
Location: include/linux/iversion.h:239
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
In fs/ext4/inline.c (ffffffff8139df93)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a7dba)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813c1259)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813fd594)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814050cd)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81408b9e)
Location: include/linux/iversion.h:239
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138ea23)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8139884a)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813b1ce9)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813ee014)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f5b4d)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813f961e)
Location: include/linux/iversion.h:239
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139b7f3)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a561a)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813be709)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813fa914)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140244d)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81405f1e)
Location: include/linux/iversion.h:239
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813afcb3)
Location: include/linux/iversion.h:239
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b9d5a)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813d37e9)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81410574)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8141841d)
Location: include/linux/iversion.h:239
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8141bbde)
Location: include/linux/iversion.h:239
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
</ul>

## Differences
