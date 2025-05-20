# Function: <code>fget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229cb0)
Location: fs/file.c:716
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:get_clock_desc
  - mm/mmap.c:SyS_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:do_io_submit
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81229cb0-ffffffff81229cc5: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252410)
Location: fs/file.c:717
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:get_clock_desc
  - mm/mmap.c:SyS_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:do_io_submit
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81252410-ffffffff81252425: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81265680)
Location: fs/file.c:717
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:get_clock_desc
  - mm/mmap.c:SyS_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:do_io_submit
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81265680-ffffffff81265695: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81272e00)
Location: fs/file.c:703
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:get_clock_desc
  - mm/mmap.c:SyS_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:do_io_submit
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81272e00-ffffffff81272e15: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81295730)
Location: fs/file.c:706
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:get_clock_desc
  - mm/mmap.c:SyS_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:do_io_submit
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81295730-ffffffff81295745: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bb8b0)
Location: fs/file.c:702
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:aio_prep_rw
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff812bb8b0-ffffffff812bb8c5: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d0aa0)
Location: fs/file.c:732
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:io_submit_one
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff812d0aa0-ffffffff812d0ab5: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812edad0)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff812edad0-ffffffff812edaea: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ff590)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff812ff590-ffffffff812ff5aa: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338870)
Location: fs/file.c:751
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_get
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:set_bitmap_file
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81338870-ffffffff8133889c: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344210)
Location: fs/file.c:851
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_get
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:set_bitmap_file
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81344210-ffffffff8134423c: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134a5b0)
Location: fs/file.c:863
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_get
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:set_bitmap_file
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff8134a5b0-ffffffff8134a5dc: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398350)
Location: fs/file.c:923
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_get_normal
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_get_tree
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:set_bitmap_file
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81398350-ffffffff8139837c: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141ac70)
Location: fs/file.c:925
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_get_tree
  - io_uring/io_uring.c:io_ringfd_register
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_files_update
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/md/md.c:set_bitmap_file
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff8141ac70-ffffffff8141ad14: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a69e0)
Location: fs/file.c:925
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_get_tree
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:__io_sqe_files_update
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:set_bitmap_file
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff814a69e0-ffffffff814a6a84: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814db9b0)
Location: fs/file.c:926
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/fuse/inode.c:fuse_get_tree
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:__io_sqe_files_update
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:set_bitmap_file
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff814db9b0-ffffffff814dba54: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150eb00)
Location: fs/file.c:1048
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/fuse/inode.c:fuse_get_tree
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:__io_sqe_files_update
  - io_uring/register.c:__do_sys_io_uring_register
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:set_bitmap_file
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff8150eb00-ffffffff8150eba4: fget (STB_GLOBAL)
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
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b0df8)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:io_submit_one
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffff8000103b0df8-ffff8000103b0e2c: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590938)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:get_clock_desc
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
c0590938-c059095c: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ac440)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/aio.c:io_submit_one
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
c0000000004ac440-c0000000004ac45c: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000274e52)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffe000274e52-ffffffe000274e80: fget (STB_GLOBAL)
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
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f7b70)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff812f7b70-ffffffff812f7b8a: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8790)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff812e8790-ffffffff812e87aa: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f5980)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff812f5980-ffffffff812f599a: fget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *fget(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307350)
Location: fs/file.c:738
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_get
  - mm/mmap.c:ksys_mmap_pgoff
  - fs/nsfs.c:proc_ns_fget
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/eventfd.c:eventfd_fget
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_submit_sqe
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/inode.c:fuse_fill_super
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_get
  - drivers/dma-buf/sync_file.c:sync_file_fdget
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/md/md.c:md_ioctl
  - net/socket.c:sockfd_lookup
```
**Symbols:**

```
ffffffff81307350-ffffffff8130736a: fget (STB_GLOBAL)
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
