# Function: <code>__sb_start_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120f500)
Location: fs/super.c:1234
Inline: True
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
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_run_iocb
  - fs/dax.c:dax_pmd_fault
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_fault
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8120f500-ffffffff8120f533: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235f30)
Location: fs/super.c:1254
Inline: True
Direct callers:
  - kernel/acct.c:do_acct_process
  - mm/filemap.c:filemap_page_mkwrite
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_run_iocb
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81235f30-ffffffff81235f63: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81248bd0)
Location: fs/super.c:1300
Inline: True
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
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81248bd0-ffffffff81248c40: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812544e0)
Location: fs/super.c:1342
Inline: True
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
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812544e0-ffffffff81254547: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812765f0)
Location: fs/super.c:1342
Inline: True
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
  - fs/namespace.c:mnt_want_write_file_path
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812765f0-ffffffff81276657: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c2f0)
Location: fs/super.c:1405
Inline: True
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
  - fs/namespace.c:mnt_want_write_file_path
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8129c2f0-ffffffff8129c357: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1430)
Location: fs/super.c:1391
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812b1430-ffffffff812b1497: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cdec0)
Location: fs/super.c:1547
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812cdec0-ffffffff812cdf3b: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812df910)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812df910-ffffffff812df98b: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813166c0)
Location: fs/super.c:1646
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff813166c0-ffffffff8131673b: __sb_start_write (STB_GLOBAL)
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
In mm/filemap.c (ffffffff8125abc0)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff81319ff2)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81320af4)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff813490d3)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8135ed63)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813667c0)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81383238)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff81397e72)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/coredump.c (ffffffff813b9483)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff813fc12b)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8141293c)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff81421168)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff8149c5dc)
Location: include/linux/fs.h:1592
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff817fceac)
Location: include/linux/fs.h:1592
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
In mm/filemap.c (ffffffff8125f620)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff813200d2)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81326bd5)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff8134fad3)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff813656ad)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8136d070)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8138a2c0)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff8139d8ce)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/coredump.c (ffffffff813c05f4)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff8140256d)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81418d9c)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff81427918)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff814a260c)
Location: include/linux/fs.h:1761
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff817e193c)
Location: include/linux/fs.h:1761
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
In mm/filemap.c (ffffffff8129bd90)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff8136d682)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81374195)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff8139de33)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff813b3f9d)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813bbd50)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff813d75d0)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff813ec0ef)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/coredump.c (ffffffff8141041c)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff81454c34)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8146bfcc)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff8147b5bb)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff814fa6b7)
Location: include/linux/fs.h:1811
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff8186d0dc)
Location: include/linux/fs.h:1811
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
In mm/filemap.c (ffffffff812f1b21)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff813ec249)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f30d4)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff81420e33)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814392e1)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff81442612)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81461235)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff81485ec4)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff814d2406)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814ebf80)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff814fda4b)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff8158abd9)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/io_uring.c (ffffffff816d7668)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff819b6d69)
Location: include/linux/fs.h:1697
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
In mm/filemap.c (ffffffff8135cbdb)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff81474719)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bdc2)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff814ad453)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814c75d1)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814d1302)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814f11c5)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff81519753)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff8156af53)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81585ced)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff8159823b)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff81631336)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff817a4ac3)
Location: include/linux/fs.h:1812
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81b2bfc5)
Location: include/linux/fs.h:1812
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
In mm/filemap.c (ffffffff8138ec0e)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff814a90f6)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b0989)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff814e2233)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814fd4e7)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff815075f8)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8152853e)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff8155102b)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff81560949)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/file.c (ffffffff815a2e09)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815bc5a4)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff815cee02)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff8166956c)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff817e5ac6)
Location: include/linux/fs.h:1492
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81b7c297)
Location: include/linux/fs.h:1492
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
In mm/filemap.c (ffffffff813b7ffe)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/open.c (ffffffff814da148)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e214a)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff81512f13)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8153213a)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
```
In fs/remap_range.c (ffffffff8153c82a)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8155d5be)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/backing-file.c (ffffffff81581b31)
Location: include/linux/fs.h:1639
Inline: True
```
```
In fs/coredump.c (ffffffff81586ebc)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff81597039)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/file.c (ffffffff815dbb29)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815f5384)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff81607692)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff816a386c)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff81829d80)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff8000103862d8)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffff8000103862d8-ffff800010386398: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c056fd38)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
c056fd38-c056fdd4: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047db00)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
c00000000047db00-c00000000047dc14: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000258ec8)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffe000258ec8-ffffffe000258f86: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7ef0)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812d7ef0-ffffffff812d7f6b: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c8b70)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812c8b70-ffffffff812c8beb: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d5d00)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812d5d00-ffffffff812d5d7b: __sb_start_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __sb_start_write(struct super_block *sb, int level, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e7650)
Location: fs/super.c:1648
Inline: True
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
  - fs/splice.c:do_splice
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812e7650-ffffffff812e76d2: __sb_start_write (STB_GLOBAL)
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
