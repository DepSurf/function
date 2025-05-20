# Function: <code>get_file</code>

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
In kernel/fork.c (ffffffff8107e3b4)
Location: include/linux/fs.h:859
Inline: True
```
```
In kernel/sys.c (ffffffff81092b77)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/prfile.c (ffffffff811b9ff7)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff811c71f6)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811ca2fd)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/madvise.c (ffffffff811d1a02)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In fs/select.c (ffffffff81220adb)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff81229f71)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
  - fs/file.c:f_dupfd
```
```
In fs/proc/fd.c (ffffffff81281909)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81311259)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8132b215)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In drivers/tty/tty_io.c (ffffffff814e1ca6)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8156fc08)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a2b65)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8169ee5f)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff8170ec97)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_fp_dup
```
```
In net/compat.c (ffffffff8173f463)
Location: include/linux/fs.h:859
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff810800b4)
Location: include/linux/fs.h:921
Inline: True
```
```
In kernel/sys.c (ffffffff81095cfb)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/prfile.c (ffffffff811d4417)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff811e4241)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811e67e1)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/madvise.c (ffffffff811ef2aa)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/khugepaged.c (ffffffff8121c606)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff8124872b)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812537a4)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/proc/fd.c (ffffffff812aea46)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813456c4)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8135feba)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In drivers/tty/tty_io.c (ffffffff815343ba)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff815c5528)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815f9bf2)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8170022c)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff81776698)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff817ac171)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff81084a14)
Location: include/linux/fs.h:874
Inline: True
```
```
In kernel/sys.c (ffffffff8109acdf)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/prfile.c (ffffffff811e4467)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff811f4241)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811f6ab1)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/madvise.c (ffffffff811ffc2a)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/khugepaged.c (ffffffff8122e03a)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff8125b75b)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812669f4)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/aio.c (ffffffff8129979e)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812c441a)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff8135b3f4)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813766ba)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In drivers/tty/tty_io.c (ffffffff81560ae5)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81627d62)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff81731f5e)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff817a3918)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff817db791)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff810818f1)
Location: include/linux/fs.h:896
Inline: True
```
```
In kernel/sys.c (ffffffff81097add)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff810f9787)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
```
```
In mm/prfile.c (ffffffff811ee8c7)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff811ff15f)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81201983)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/madvise.c (ffffffff8120a858)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/khugepaged.c (ffffffff8123a335)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff812685ee)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812741ef)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/aio.c (ffffffff812a7515)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812d16ae)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff8136fd5f)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8138a22b)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In drivers/tty/tty_io.c (ffffffff81574033)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff81607f48)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163d89e)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8174ae29)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff817c1a78)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff817fad75)
Location: include/linux/fs.h:896
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff810881d5)
Location: include/linux/fs.h:900
Inline: True
```
```
In kernel/sys.c (ffffffff8109e7cd)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81104219)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
```
```
In mm/prfile.c (ffffffff81204d37)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8121775f)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8121a343)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/madvise.c (ffffffff81223bf0)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/khugepaged.c (ffffffff8125906e)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff8128ae9e)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff81296aef)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/aio.c (ffffffff812ca898)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812f5ebd)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81394a5f)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813ae458)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff815d8526)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff81670bc1)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a65ee)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff817bd18f)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff8183b488)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff818786f5)
Location: include/linux/fs.h:900
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff8108bf25)
Location: include/linux/fs.h:907
Inline: True
```
```
In kernel/sys.c (ffffffff810a4036)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8110e9f0)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/bpf/syscall.c (ffffffff811b390f)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In mm/prfile.c (ffffffff81225bd3)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff812387f0)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8123c014)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/madvise.c (ffffffff81245155)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
```
In mm/khugepaged.c (ffffffff8127d3ef)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812b168f)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812bcc8f)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/proc/fd.c (ffffffff81323305)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813c3b81)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813df565)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff81611c73)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff816ac0e4)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e28e8)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81805275)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff81885b85)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff818ca8cd)
Location: include/linux/fs.h:907
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff810937e5)
Location: include/linux/fs.h:955
Inline: True
```
```
In kernel/sys.c (ffffffff810ace06)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81119f70)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/bpf/syscall.c (ffffffff811c45ae)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/prfile.c (ffffffff81239293)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8124c1b0)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81250434)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/madvise.c (ffffffff8125979b)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
```
In mm/khugepaged.c (ffffffff81291ffa)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff812c68df)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812d1f4f)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/proc/fd.c (ffffffff8133a5d5)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813dd331)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813f9be3)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff8162e9e8)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff816cdbba)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81705d98)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81831475)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818a62b5)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff818f599d)
Location: include/linux/fs.h:955
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff81097ed1)
Location: include/linux/fs.h:970
Inline: True
```
```
In kernel/sys.c (ffffffff810b263c)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81124bf0)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/bpf/syscall.c (ffffffff811d60f3)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (ffffffff81213ca5)
Location: include/linux/fs.h:970
Inline: True
```
```
In mm/prfile.c (ffffffff8124a2f3)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8125e60d)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8126275c)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/madvise.c (ffffffff81274f67)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812aca23)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff812e33ac)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812eef90)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (ffffffff8133208d)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81362792)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81408e70)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff814261e7)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff8166260b)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff81708d76)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81740ba9)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81874019)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818f1745)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff8195504a)
Location: include/linux/fs.h:970
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff8109e591)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (ffffffff810b8d0c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81130bb0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/bpf/syscall.c (ffffffff811e2099)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (ffffffff812257f9)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8124247b)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff81258733)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8125c5ea)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126ce1d)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81270f0c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/madvise.c (ffffffff81283e73)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812be2dd)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812f4e3c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff81300a50)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (ffffffff81345c4d)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff8137a9f2)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8143ff37)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff81684c7b)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff8172d056)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81764e7b)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818a5e29)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81923695)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff8198b4ea)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff810a5c61)
Location: include/linux/fs.h:1003
Inline: True
```
```
In kernel/sys.c (ffffffff810c074c)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8113fc3a)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/bpf/syscall.c (ffffffff811fc77f)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In mm/filemap.c (ffffffff812534a2)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff8127114b)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff81286f43)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8128bb32)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8129cbc7)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812a15c9)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/madvise.c (ffffffff812b59e6)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
  - mm/madvise.c:madvise_willneed
```
```
In mm/khugepaged.c (ffffffff812f3bb9)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff8132d48c)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff81339c90)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff8136eeda)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/io_uring.c (ffffffff81380519)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813c3a90)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81490cb7)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff81735e10)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tioccons
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff817e98a1)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81824b0b)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81975d81)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819f71ea)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_install_fd
```
```
In net/compat.c (ffffffff81a631d7)
Location: include/linux/fs.h:1003
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff810a1641)
Location: include/linux/fs.h:963
Inline: True
```
```
In kernel/sys.c (ffffffff810bcde0)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/filemap.c (ffffffff8125e0ab)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff8127a62f)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8127d365)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff81291263)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81296aee)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812a7f57)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812ace04)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/madvise.c (ffffffff812c0ea0)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/khugepaged.c (ffffffff812ff346)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff81338c2c)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff813459d9)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff82fee175)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/io_uring.c (ffffffff8138a963)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_add_task_file
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813d5c1e)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814ae404)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff81752942)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tioccons
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff817fe321)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/md/md-bitmap.c (ffffffff8197ad71)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819f6c5a)
Location: include/linux/fs.h:963
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
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
In kernel/fork.c (ffffffff810a1a4f)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810be675)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/filemap.c (ffffffff81260d6d)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8127f76f)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812824f5)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff8129c68a)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812ac040)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812b20ed)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/madvise.c (ffffffff812c8120)
Location: include/linux/fs.h:968
Inline: True
```
```
In mm/khugepaged.c (ffffffff81305fc3)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff8133f2bc)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff8134bd99)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff831f89b2)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/io_uring.c (ffffffff8139bc64)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813dcc2e)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814b4231)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff81736d26)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/md/md-bitmap.c (ffffffff8195efa1)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819dcdcd)
Location: include/linux/fs.h:968
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
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
In kernel/fork.c (ffffffff810b332a)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In mm/filemap.c (ffffffff8129d7d0)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff812bda26)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812c0605)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff812d6fe3)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812dd302)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812ef2fb)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812f3ce4)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/madvise.c (ffffffff8130d104)
Location: include/linux/fs.h:1013
Inline: True
```
```
In mm/khugepaged.c (ffffffff8134fe31)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff8138cc4c)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff81399bd9)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff832df92a)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/io_uring.c (ffffffff813e7379)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff8142e30e)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8150c8cb)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff817b76ff)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff8186e03e)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/md/md-bitmap.c (ffffffff81a048e1)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81a8d00d)
Location: include/linux/fs.h:1013
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
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
In kernel/fork.c (ffffffff810c954a)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In mm/filemap.c (ffffffff812f4886)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81319799)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8131d0c5)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff81336843)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8133cfec)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff81352729)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81357b11)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/madvise.c (ffffffff813786e6)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/khugepaged.c (ffffffff813c804a)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff8140df2c)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff8141c689)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff83495644)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/coredump.c (ffffffff81484a32)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff814a7a37)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8159e87a)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In io_uring/io_uring.c (ffffffff816d3cc2)
Location: include/linux/fs.h:972
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff818f2cfa)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819edad3)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/vfio/vfio.c (ffffffff81a76e4e)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_open
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c580)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81c028fd)
Location: include/linux/fs.h:972
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
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
In kernel/fork.c (ffffffff810e6aa6)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In mm/filemap.c (ffffffff8135e9c6)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff8138d74b)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813909f5)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff813adaad)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff813b4bc6)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813cc735)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff813d22b7)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/madvise.c (ffffffff813f5ef8)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/khugepaged.c (ffffffff8144cb18)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In fs/select.c (ffffffff81498a5c)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff814a8799)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff83eca138)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/coredump.c (ffffffff81517f28)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff8153d437)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81647f3a)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In io_uring/msg_ring.c (ffffffff81798c7d)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/rsrc.c (ffffffff817a1591)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/tty/tty_io.c (ffffffff81a4b32d)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6ae10)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/md/md-bitmap.c (ffffffff81d08654)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81db1d9d)
Location: include/linux/fs.h:988
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
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
In kernel/fork.c (ffffffff810f2460)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In mm/filemap.c (ffffffff8139175e)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff813c0106)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813c32f5)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff813e9bc9)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813fea85)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff81406e7c)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/madvise.c (ffffffff81428dbc)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/khugepaged.c (ffffffff814823c6)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In fs/select.c (ffffffff814cdafc)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff814dd789)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff836ef178)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/coredump.c (ffffffff8154f825)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff81575713)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81680450)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In io_uring/msg_ring.c (ffffffff817d998e)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/rsrc.c (ffffffff817e2799)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/tty/tty_io.c (ffffffff81a953cd)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbe22d)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/md/md-bitmap.c (ffffffff81d717e4)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81e22343)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/handshake/netlink.c (ffffffff82092685)
Location: include/linux/fs.h:1009
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_accept_doit
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
In kernel/fork.c (ffffffff810fc030)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In mm/filemap.c (ffffffff813bb4cc)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/shmem.c (ffffffff813e7740)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/util.c (ffffffff813ede15)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff81414d37)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8142af23)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff8143352c)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/madvise.c (ffffffff814625ec)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/khugepaged.c (ffffffff814b176c)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In fs/select.c (ffffffff8150043c)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff815101d9)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff839221c8)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/backing-file.c (ffffffff81581864)
Location: include/linux/fs.h:1044
Inline: True
```
```
In fs/coredump.c (ffffffff81585664)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff815ae070)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff816bc840)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In io_uring/msg_ring.c (ffffffff8181dcae)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In drivers/tty/tty_io.c (ffffffff81ae7dab)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c1297d)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81caccc6)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_fd_to_handle
  - drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle
```
```
In drivers/md/md-bitmap.c (ffffffff81e288c3)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81ee0283)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/handshake/netlink.c (ffffffff82168f97)
Location: include/linux/fs.h:1044
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_accept_doit
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
In kernel/fork.c (ffff8000100f33dc)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (ffff800010115124)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffff800010197afc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/bpf/syscall.c (ffff8000102657d0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (ffff8000102b290c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffff8000102d6878)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffff8000102f065c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffff8000102f4af4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffff8000103040a0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffff800010306f5c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__arm64_sys_msync
```
```
In mm/madvise.c (ffff80001031e188)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/khugepaged.c (ffff80001035fc24)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffff8000103a1e4c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffff8000103b29f0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (ffff800010403c44)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
```
In fs/proc/fd.c (ffff800010446fa0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffff8000105286f8)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffff800010852570)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffff8000109249a8)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffff8000109656d4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffff800010afad04)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffff800010bbde70)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffff800010c35f24)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (c0351890)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (c036af60)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (c03e2e18)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/bpf/syscall.c (c04939b8)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In mm/filemap.c (c04dfb64)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (c04fca0c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (c0513c2c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (c05167d0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (c05228c4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (c0524b90)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/madvise.c (c053827c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
```
In fs/select.c (c0584b68)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (c0591cbc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (c05d7b2c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (c060bfb4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (c06e1bdc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
```
```
In drivers/tty/tty_io.c (c095d4bc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (c0a08140)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (c0a3bbf4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (c0bdb798)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (c0cda314)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
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
In kernel/fork.c (c000000000138e70)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (c00000000015d0d4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (c0000000001f7d08)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/bpf/syscall.c (c00000000030a2fc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (c000000000368ba4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (c00000000039401c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (c0000000003b5000)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (c0000000003baa6c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (c0000000003d0e00)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (c0000000003d50a0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/madvise.c (c0000000003f2578)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/khugepaged.c (c00000000044a9a4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (c00000000049b944)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (c0000000004ae970)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (c000000000510b14)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (c00000000055ce68)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (c0000000006731c0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (c0000000008f0dd0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (c0000000009c88cc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1bf60)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (c000000000be8d70)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (c000000000c976a0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (c000000000d2e0dc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffe0000c0fca)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (ffffffe0000d214e)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffe000128cd8)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/bpf/syscall.c (ffffffe0001a1096)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (ffffffe0001d8206)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffe0001f0680)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffe000203f0c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffe000205c94)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffe000210948)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffe0002124de)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/madvise.c (ffffffe000221234)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
```
In fs/select.c (ffffffe00026a6fe)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffe000276a1a)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (ffffffe0002b1350)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (ffffffe0002dcd6e)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffe00038bd76)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In drivers/tty/tty_io.c (ffffffe00052f80e)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffe0005a1aca)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d1fa8)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec5c2)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffe00074c646)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
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
In kernel/fork.c (ffffffff81097eb1)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (ffffffff810b307c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81129360)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/bpf/syscall.c (ffffffff811da6b9)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (ffffffff8121de49)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8123aacb)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff81250d83)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81254c3a)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126546d)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8126955c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/madvise.c (ffffffff8127c4c3)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812b68bd)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812ed41c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812f9030)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (ffffffff8133e22d)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81372fd2)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81438517)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff8164a6fb)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff816f2e36)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171956b)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff8184bca9)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818c3695)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff8192b35a)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff81086911)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (ffffffff810a19ac)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8111bbf0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/bpf/syscall.c (ffffffff811cd479)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (ffffffff81210fff)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8122dacb)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff81243cc3)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81247a7a)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8125788d)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8125b84c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/madvise.c (ffffffff8126e373)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812a7a8d)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812de04c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812e9c50)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (ffffffff8132eeed)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81363aa2)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81428f87)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff8162ab4b)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff816ccf36)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f29db)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818132c9)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8187d5d5)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff818e510a)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff81097e61)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (ffffffff810b25dc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81127080)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/bpf/syscall.c (ffffffff811d8489)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (ffffffff8121bbe9)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8123886b)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff8124eb23)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812529da)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126320d)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812672fc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/madvise.c (ffffffff8127a263)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812b46cd)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/select.c (ffffffff812eb22c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff812f6e40)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (ffffffff8133bcfd)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81370aa2)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814346b7)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff81678abb)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff81720516)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8175833b)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff8189b2d9)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81914695)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff8197c4ea)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
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
In kernel/fork.c (ffffffff8109fa61)
Location: include/linux/fs.h:984
Inline: True
```
```
In kernel/sys.c (ffffffff810babdc)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff811336c8)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/bpf/syscall.c (ffffffff811e6817)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/filemap.c (ffffffff8122ac47)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81247ea7)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff8125e4a3)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812623aa)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff81272bcd)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81276c9c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/madvise.c (ffffffff81289e43)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812c507e)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/select.c (ffffffff812fc21c)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/file.c (ffffffff813080b0)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/io_uring.c (ffffffff8134eead)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81384482)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8144b7d9)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In drivers/tty/tty_io.c (ffffffff816926f4)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff8173b8d6)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8177381b)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818b7439)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81935865)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff8199ea3a)
Location: include/linux/fs.h:984
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
</details>
</li>
</ul>

## Differences
