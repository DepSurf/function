# Function: <code>vfs_fsync_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81240590)
Location: fs/sync.c:183
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:SyS_msync
  - fs/sync.c:do_fsync
  - fs/block_dev.c:blkdev_write_iter
  - fs/direct-io.c:dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81240590-ffffffff81240637: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812688d0)
Location: fs/sync.c:183
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:SyS_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff812688d0-ffffffff81268977: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8127b8f0)
Location: fs/sync.c:184
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:SyS_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_complete_work
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8127b8f0-ffffffff8127b997: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81288c80)
Location: fs/sync.c:184
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:SyS_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_complete_work
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81288c80-ffffffff81288d27: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812ab7c0)
Location: fs/sync.c:185
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:SyS_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap.c:iomap_dio_complete_work
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff812ab7c0-ffffffff812ab870: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812d2430)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff812d2430-ffffffff812d24ac: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812e7810)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff812e7810-ffffffff812e788c: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813060c0)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff813060c0-ffffffff8130613f: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81319140)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81319140-ffffffff813191bf: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81352fd3)
Location: fs/sync.c:193
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__do_sys_msync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/block_dev.c:blkdev_write_iter
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:io_issue_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81352db0-ffffffff81352e2f: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8135f8b3)
Location: fs/sync.c:193
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__do_sys_msync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/block_dev.c:blkdev_write_iter
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:io_issue_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff8135f690-ffffffff8135f70f: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81366522)
Location: fs/sync.c:192
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__do_sys_msync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/block_dev.c:blkdev_write_iter
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:io_issue_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81366120-ffffffff8136619f: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813b4c92)
Location: fs/sync.c:193
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__do_sys_msync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:io_issue_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff813b4a70-ffffffff813b4aef: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8143a256)
Location: fs/sync.c:180
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__do_sys_msync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - block/fops.c:blkdev_write_iter
  - io_uring/io_uring.c:io_fsync
```
**Symbols:**

```
ffffffff81439dc0-ffffffff81439e54: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814c8656)
Location: fs/sync.c:180
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__do_sys_msync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - block/fops.c:blkdev_write_iter
  - io_uring/sync.c:io_fsync
```
**Symbols:**

```
ffffffff814c8140-ffffffff814c81d4: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814fe886)
Location: fs/sync.c:180
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__do_sys_msync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - block/fops.c:blkdev_write_iter
  - io_uring/sync.c:io_fsync
```
**Symbols:**

```
ffffffff814fe370-ffffffff814fe40a: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81533486)
Location: fs/sync.c:180
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__do_sys_msync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - block/fops.c:blkdev_write_iter
  - io_uring/sync.c:io_fsync
```
**Symbols:**

```
ffffffff81532f70-ffffffff8153300a: vfs_fsync_range (STB_GLOBAL)
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
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffff8000103d0118)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__arm64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffff8000103d0118-ffff8000103d01a0: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05ab494)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__se_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c05ab494-c05ab528: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d26f0)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__se_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c0000000004d26f0-c0000000004d27d8: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c432)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__se_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffe00028c432-ffffffe00028c49a: vfs_fsync_range (STB_GLOBAL)
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
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81311720)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81311720-ffffffff8131179f: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81302330)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81302330-ffffffff813023af: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8130f510)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8130f510-ffffffff8130f58f: vfs_fsync_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_fsync_range(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81320d10)
Location: fs/sync.c:190
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - fs/sync.c:do_fsync
  - fs/direct-io.c:dio_complete
  - fs/io_uring.c:__io_submit_sqe
  - fs/dax.c:dax_finish_sync_fault
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81320d10-ffffffff81320d8f: vfs_fsync_range (STB_GLOBAL)
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
