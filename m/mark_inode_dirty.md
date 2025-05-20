# Function: <code>mark_inode_dirty</code>

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
In mm/filemap.c (ffffffff8118f160)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff81216b2b)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812244ee)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff81233e51)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff81244668)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:nobh_write_end
```
```
In fs/proc/base.c (ffffffff8127a276)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff8127ed63)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff81284276)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inode.c (ffffffff8129ea73)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff812a7443)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/mballoc.c (ffffffff812d416f)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff812ddb13)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812e15a0)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4f86)
Location: include/linux/fs.h:1880
Inline: True
```
```
In fs/fat/dir.c (ffffffff812f6a11)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff812fa876)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff812fcaab)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff812fe33c)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff81300300)
Location: include/linux/fs.h:1880
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
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
In mm/filemap.c (ffffffff811a2764)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff8123db04)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff8124b3ee)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff8125c486)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8126c78a)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/proc/base.c (ffffffff812a6f36)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812abda7)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812b1346)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inode.c (ffffffff812ccff3)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff812d651d)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/mballoc.c (ffffffff813038be)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130d49b)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff813114eb)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff81328120)
Location: include/linux/fs.h:1973
Inline: True
```
```
In fs/fat/dir.c (ffffffff8132a061)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff8132eb02)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8133075a)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff8133233b)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff81334546)
Location: include/linux/fs.h:1973
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff811b25a4)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812508f1)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff8125e3ce)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff8126f9f1)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8127f7ea)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/proc/base.c (ffffffff812bc81b)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812c167c)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812c6bdb)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inode.c (ffffffff812e2d8b)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff812ec21d)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/mballoc.c (ffffffff8131987e)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81323390)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff813273c5)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff8133de70)
Location: include/linux/fs.h:1946
Inline: True
```
```
In fs/fat/dir.c (ffffffff8133fd95)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff81344859)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff813464b4)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff813480db)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff8134a3f0)
Location: include/linux/fs.h:1946
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff811b9252)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff8125ca6a)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff8126bc2e)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff8127d1e3)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8128d830)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/proc/base.c (ffffffff812c9b9b)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812ce99c)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812d3f0b)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff812fb23d)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81306ee9)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/mballoc.c (ffffffff81310bf2)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff8131beea)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff8133c7e2)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff81352aee)
Location: include/linux/fs.h:1996
Inline: True
```
```
In fs/fat/dir.c (ffffffff813549b3)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff813592b9)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8135aed4)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff8135cafb)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff8135eea3)
Location: include/linux/fs.h:1996
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff811cf6e5)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff8127edba)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff8128e4be)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff8129fc83)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff812b03e4)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/proc/base.c (ffffffff812ee42b)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812f316c)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812f873b)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8131f9d0)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8132ba32)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/mballoc.c (ffffffff81335a93)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff81340518)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff81360d62)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff8137761e)
Location: include/linux/fs.h:2026
Inline: True
```
```
In fs/fat/dir.c (ffffffff813795d3)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff8137dfc9)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff8137fbd4)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff813817fb)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff81383b63)
Location: include/linux/fs.h:2026
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff811f079f)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812a574a)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812b4f72)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff812c6561)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff812d7c81)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/proc/base.c (ffffffff8131b463)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff81320044)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff81325803)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8134dabc)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8135a0a5)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/mballoc.c (ffffffff81363c8f)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff8136e526)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff8138f6cf)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6272)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff813a804f)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff813aca05)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff813ae0ca)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff813b03bb)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff813b2b4f)
Location: include/linux/fs.h:2057
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff81200f8f)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812ba8ba)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812ca292)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff812db761)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff812ed791)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:__generic_write_end
```
```
In fs/iomap.c (ffffffff813241cd)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_write_end
```
```
In fs/proc/base.c (ffffffff813324f3)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff81337124)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff8133c9a3)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff81365c5c)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813723ee)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff81375237)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8137bf31)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff813869b6)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff813a8056)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff813beca2)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff813c0e34)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff813c5c6b)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffff813c75de)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff813c9a1b)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff813cc21f)
Location: include/linux/fs.h:2142
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff81218b9c)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812d74b4)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812e6cf4)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff812f9df4)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8130ee15)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8134c563)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8134dc9e)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (ffffffff8135a452)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff8135f252)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff81364c42)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8138ef7d)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8139bb42)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff8139d633)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813a6083)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff813b095d)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff813d2542)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9536)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff813eb68e)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff813f07b9)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff813f20cf)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff813f45ab)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff813f6a41)
Location: include/linux/fs.h:2149
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff8122644c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812e9014)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812f88f4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff8130ba24)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff81321e35)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff81364833)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff81365f4f)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (ffffffff81372682)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff813774b2)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff8137ced2)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff813a79dd)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813b4723)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff813b60a3)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813beef3)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff813c998d)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff813ebc22)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff814035d6)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff8140503e)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff8140a699)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff8140bfcf)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff8140e47b)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff81410911)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff812513a4)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff813216d4)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff81331764)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff813451c4)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8135d0c5)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff813aa879)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end_inline
```
```
In fs/iomap/direct-io.c (ffffffff813ad983)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/proc/base.c (ffffffff813ba972)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff813c0242)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff813c6902)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff813f39fd)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813ff795)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff81401af7)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff8140afc1)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff814152fd)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff81438e0a)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff8145139c)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff81452ff4)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff8145833e)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff8145a0f7)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff8145c25b)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff8145ebac)
Location: include/linux/fs.h:2217
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff8125cb73)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff8132cc74)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff8133d104)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff81351514)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff81369bc2)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff813bca76)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end_inline
```
```
In fs/iomap/direct-io.c (ffffffff813befc3)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/proc/base.c (ffffffff813cc4c2)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff813d2092)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff813d88c2)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8140618d)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81411f49)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff81414500)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff8141e41a)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff814289a7)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff81451933)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d8bc)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff8146f4a4)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff8147467e)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff81476447)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff8147815b)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff8147a87c)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff812617f7)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff81332834)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff81343584)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff8135822c)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8136fd62)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff813c4aea)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff813c6103)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/proc/base.c (ffffffff813d3490)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff813d8f80)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff813df7a0)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8140c66c)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81418373)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff8141a775)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81424d99)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff8142f4b2)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff81457063)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff81472e36)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff81474974)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff8147a016)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff8147beb7)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff8147dbeb)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff814802ba)
Location: include/linux/fs.h:2402
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff8129a0ed)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff8137ffc4)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff81391124)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff813a66ac)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff813bf63c)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff81414279)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff814154cf)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/base.c (ffffffff814249e0)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff8142a6b0)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff81431130)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8145ec02)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8146b589)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff8146d95c)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81478ab1)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff8147db12)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff814ab0d9)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff814c9946)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff814cb6b4)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff814d16a6)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff814d3797)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff814d546b)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff814d7b5a)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff812f7199)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff814001b7)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/dcache.c (ffffffff814129a2)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff8142aee9)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff814471e1)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8148a3fd)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8148cc1c)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/base.c (ffffffff8149d60f)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff814a3c2f)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff814ab13f)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff814dd36b)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814eb79f)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff814ee200)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff814fb299)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff81500557)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff81532db2)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff81555aff)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff81557c57)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff8155e2c3)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff815614a8)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff815624c2)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff81565214)
Location: include/linux/fs.h:2330
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff81360a3e)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff8148a207)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/dcache.c (ffffffff8149dd33)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff814b8069)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff814d5e26)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8151ddea)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8152013f)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/base.c (ffffffff8153213f)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff81538fcf)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff81540fdf)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8157639b)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815850db)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff815880e2)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81595a39)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff8159b007)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff815d1282)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6d7f)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff815f9867)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff81600422)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff81603a08)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff81604e4e)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff816080e3)
Location: include/linux/fs.h:2463
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff81392f2e)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff814bf0e4)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/dcache.c (ffffffff814d3056)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff814ed279)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8150a9ba)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff81555f86)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff815581af)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/ext4/inline.c (ffffffff815adc3d)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815bbc80)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff815be966)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff815cc42f)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff815d1885)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff81608e22)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ee3f)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff816317c7)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff816383d1)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff8163b928)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff8163cd5e)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff8163ff33)
Location: include/linux/fs.h:2152
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff813bcbde)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff814f1784)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/dcache.c (ffffffff81505793)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff815211d9)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8153f50a)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8158c47a)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8158e7df)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/ext4/inline.c (ffffffff815e69fd)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815f4a59)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff815f770f)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81604ebf)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff8160a025)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff81641b62)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff8166832f)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff8166ac77)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff816718c1)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff81674e88)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff816762ce)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff816794e3)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffff8000102b3750)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffff800010392364)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffff8000103a7030)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffff8000103c00bc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffff8000103d99bc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffff80001042b354)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffff80001042cdec)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (ffff80001043cbac)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffff800010443078)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffff8000104498f0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffff80001047b32c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffff800010488ddc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffff80001048aa00)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffff800010495be0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffff8000104a1560)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffff8000104c4acc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2054)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffff8000104e5db8)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffff8000104eaad4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffff8000104ec958)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffff8000104ef044)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffff8000104f1cb4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (c04e0a18)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (c057997c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (c05885cc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (c059d34c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (c05b3ed8)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (c05f4670)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (c05f5bf0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (c0602b24)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (c0608424)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (c060eef0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (c063cbd4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (c064b2cc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (c064cd6c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c06577b4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (c06636ec)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (c0688ae0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (c06a3050)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (c06a8aa0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (c06a97dc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (c06acb84)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (c06af7fc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (c00000000036a3a0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (c00000000048ad80)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (c0000000004a150c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (c0000000004befac)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (c0000000004dfc7c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (c00000000053bc80)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (c00000000053e6f4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (c0000000005508a0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (c000000000558588)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (c000000000560970)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (c00000000059e620)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (c0000000005afa90)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (c0000000005b1ea4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0000000005bf8bc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (c0000000005cdf60)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (c0000000005fc400)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (c00000000061eb1c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (c000000000621220)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (c000000000628d68)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (c000000000629ca8)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (c00000000062e228)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (c000000000631070)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffe0001d8e3c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffe0002615c0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffe00026d10c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffe000280896)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffe0002935ca)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffe0002c89d0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffe0002ca174)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (ffffffe0002d4c46)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffe0002d9840)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffe0002df1ca)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffe000305862)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffe00031079c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffe000311db6)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffe00031a7ca)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffe00032352e)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffe00033f3c0)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffe000355b74)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffe000357314)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffe00035b894)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/fat/inode.c (ffffffe00035c07a)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffe00035f0ca)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffe0003614ce)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff8121ea9c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812e15f4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812f0ed4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff81304004)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8131a415)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8135ce13)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8135e52f)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (ffffffff8136ac62)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff8136fa92)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff813754b2)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8139ffbd)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813acd03)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff813ae683)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813b74d3)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff813c1f6d)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff813e4202)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff813fbbb6)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff813fd61e)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff81402c79)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff814045af)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff81406a5b)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff81408ef1)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff81211c5c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812d2234)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812e1b04)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff812f4c24)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff8130afb5)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8134dab3)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8134f1cf)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (ffffffff8135b6f2)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff81360522)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff81365f82)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff81390a4d)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8139d793)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff8139f113)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813a7f63)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff813b29fd)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff813d4c82)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec636)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff813ee09e)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff813f36f9)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff813f502f)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff813f74db)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff813f9971)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff8121c83c)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812df404)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812eece4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff81301df4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff81317ee5)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8135a8e3)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8135bfff)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (ffffffff81368732)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff8136d562)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff81372f82)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff8139d81d)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813aa563)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff813abee3)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813b4d33)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff813bf41d)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff813e1582)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8f36)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff813fa99e)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff813ffff9)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff8140192f)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff81403ddb)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff81406271)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In mm/filemap.c (ffffffff8122b8cc)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In fs/namei.c (ffffffff812f07f4)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/dcache.c (ffffffff812ffe44)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
```
```
In fs/libfs.c (ffffffff81313304)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/libfs.c:simple_setattr
```
```
In fs/buffer.c (ffffffff81329af5)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8136e043)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8136f74f)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/base.c (ffffffff8137bd82)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff81380e92)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff81386ad2)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In fs/ext4/inline.c (ffffffff813b1d8d)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813bee73)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff813c0883)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813c9955)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/namei.c (ffffffff813d44fd)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_tmpfile
```
```
In fs/ext4/xattr.c (ffffffff813f6998)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/hugetlbfs/inode.c (ffffffff8140ed76)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
```
```
In fs/fat/dir.c (ffffffff814105fe)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff81415c29)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff81417a5f)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_write_end
```
```
In fs/fat/misc.c (ffffffff81419a4b)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
```
In fs/fat/namei_vfat.c (ffffffff8141bf31)
Location: include/linux/fs.h:2184
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
</ul>

## Differences
