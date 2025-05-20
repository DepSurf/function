# Function: <code>__sb_end_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120ed50)
Location: fs/super.c:1224
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_write
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_sendfile
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_run_iocb
  - fs/dax.c:dax_pmd_fault
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_fault
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8120ed50-ffffffff8120ed73: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235780)
Location: fs/super.c:1244
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_run_iocb
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81235780-ffffffff812357a3: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81248320)
Location: fs/super.c:1290
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/pipe.c:pipe_write
  - fs/ioctl.c:ioctl_file_clone
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_complete
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81248320-ffffffff81248351: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81253c30)
Location: fs/super.c:1332
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/ioctl.c:ioctl_file_clone
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_complete
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81253c30-ffffffff81253c5d: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275cb0)
Location: fs/super.c:1332
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/ioctl.c:ioctl_file_clone
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file_path
  - fs/namespace.c:mnt_want_write_file_path
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_complete
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81275cb0-ffffffff81275cde: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c210)
Location: fs/super.c:1395
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/ioctl.c:ioctl_file_clone
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write_file_path
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8129c210-ffffffff8129c23e: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1350)
Location: fs/super.c:1381
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812b1350-ffffffff812b137e: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cdde0)
Location: fs/super.c:1537
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812cdde0-ffffffff812cde18: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812df810)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812df810-ffffffff812df848: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813165c0)
Location: fs/super.c:1636
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw_common
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff813165c0-ffffffff81316602: __sb_end_write (STB_GLOBAL)
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
In kernel/acct.c (ffffffff81165d69)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In mm/filemap.c (ffffffff8125ac2c)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff81319f93)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813209f8)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/pipe.c (ffffffff8132acdd)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813433fc)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81346a79)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8135ed42)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813667ec)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81385732)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8138a6f7)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw_common
```
```
In fs/coredump.c (ffffffff813b9462)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff813fb14d)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814129b6)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff814211f2)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff8143ef15)
Location: include/linux/fs.h:1587
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8149c5fb)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff817fcecc)
Location: include/linux/fs.h:1587
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff81166a99)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In mm/filemap.c (ffffffff8125f687)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff81320073)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81326a86)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/pipe.c (ffffffff81330990)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813496ec)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8134cd5f)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8136568c)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8136d09c)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8138c9a2)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8139a8f3)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
```
```
In fs/coredump.c (ffffffff813c0448)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff8140161d)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81418e16)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff814279a2)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81444d55)
Location: include/linux/fs.h:1756
Inline: True
```
```
In fs/fuse/dax.c (ffffffff814a262b)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff817e195c)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff8118c259)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In mm/filemap.c (ffffffff8129bdfc)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff8136d613)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81374026)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/pipe.c (ffffffff8137e110)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8139743c)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8139accf)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff813b3f7c)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813bbd7c)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff813d9ff2)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff813eb91a)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (ffffffff81410270)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff81453ba6)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8146c04a)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff8147b66d)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81498be5)
Location: include/linux/fs.h:1806
Inline: True
```
```
In fs/fuse/dax.c (ffffffff814fa6d6)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff8186d0fc)
Location: include/linux/fs.h:1806
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff811bb651)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In mm/filemap.c (ffffffff812f1ba1)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff813ec1ae)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f2fbe)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/pipe.c (ffffffff813fdd4d)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81419613)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8141e6fe)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814392a7)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8144265a)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814644de)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff81485f04)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff814d1089)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814ec014)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff814fdb25)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81523abb)
Location: include/linux/fs.h:1692
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8158ac11)
Location: include/linux/fs.h:1692
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/io_uring.c (ffffffff816ca791)
Location: include/linux/fs.h:1692
Inline: True
```
```
In drivers/block/loop.c (ffffffff819b6daf)
Location: include/linux/fs.h:1692
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
In kernel/acct.c (ffffffff811fd471)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In mm/filemap.c (ffffffff8135cc97)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff8147467e)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bc9a)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/pipe.c (ffffffff8148796d)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814a5053)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff814aae0e)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814c7597)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814d134a)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814f481e)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff815196f4)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff81569acd)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81585d7e)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff81598310)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff815c0ca2)
Location: include/linux/fs.h:1807
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8163136e)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff817a38d5)
Location: include/linux/fs.h:1807
Inline: True
```
```
In drivers/block/loop.c (ffffffff81b2c00b)
Location: include/linux/fs.h:1807
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
In kernel/acct.c (ffffffff812125fe)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In mm/filemap.c (ffffffff8138ecc5)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff814a9048)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b0845)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/pipe.c (ffffffff814bc7dd)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814da2d3)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff814dfcc1)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814fd4a9)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff81507640)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8152b5f1)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff81550fcc)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff8156097a)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/file.c (ffffffff815a18bd)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815bc639)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff815cee39)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff815f8422)
Location: include/linux/fs.h:1487
Inline: True
```
```
In fs/fuse/dax.c (ffffffff816695a4)
Location: include/linux/fs.h:1487
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff817e4908)
Location: include/linux/fs.h:1487
Inline: True
```
```
In drivers/block/loop.c (ffffffff81b7c340)
Location: include/linux/fs.h:1487
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
In kernel/acct.c (ffffffff81229c7e)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In mm/filemap.c (ffffffff813b80b2)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff814da0a7)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e1f9f)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/pipe.c (ffffffff814eed18)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8150c8be)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81512bc1)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff81532100)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
```
In fs/remap_range.c (ffffffff8153c7ec)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81560541)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/backing-file.c (ffffffff81581c7c)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/backing-file.c:backing_aio_rw_complete
```
```
In fs/coredump.c (ffffffff81586e5d)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff8159706a)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/file.c (ffffffff815da66d)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815f5419)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff816076c9)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81630fd2)
Location: include/linux/fs.h:1634
Inline: True
```
```
In fs/fuse/dax.c (ffffffff816a38a4)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff8182885e)
Location: include/linux/fs.h:1634
Inline: True
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
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010386270)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffff800010386270-ffff8000103862d8: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056f1b0)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:kiocb_end_write
  - fs/coredump.c:do_coredump
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
c056f1b0-c056f1fc: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047c7f0)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
c00000000047c7f0-c00000000047c864: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000258d14)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffe000258d14-ffffffe000258d82: __sb_end_write (STB_GLOBAL)
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
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7df0)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812d7df0-ffffffff812d7e28: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c8a70)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812c8a70-ffffffff812c8aa8: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d5c00)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812d5c00-ffffffff812d5c38: __sb_end_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sb_end_write(struct super_block *sb, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e6c10)
Location: fs/super.c:1638
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/splice.c:do_splice
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812e6c10-ffffffff812e6c60: __sb_end_write (STB_GLOBAL)
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
