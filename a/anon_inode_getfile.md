# Function: <code>anon_inode_getfile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81256e00)
Location: fs/anon_inodes.c:70
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff81256e00-ffffffff81256f50: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8127f740)
Location: fs/anon_inodes.c:70
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff8127f740-ffffffff8127f89a: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff812932b0)
Location: fs/anon_inodes.c:70
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff812932b0-ffffffff8129340a: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff812a0550)
Location: fs/anon_inodes.c:70
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff812a0550-ffffffff812a06a8: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff812c3920)
Location: fs/anon_inodes.c:70
Inline: True
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff812c3920-ffffffff812c3a78: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff812ecba0)
Location: fs/anon_inodes.c:70
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff812ecba0-ffffffff812eccfa: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff813015b0)
Location: fs/anon_inodes.c:70
Inline: True
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff813015b0-ffffffff8130168d: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81322b20)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff81322b20-ffffffff81322c00: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81335880)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff81335880-ffffffff81335960: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8136f450)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:init_listener
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
```
**Symbols:**

```
ffffffff8136f450-ffffffff8136f530: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8137d1b0)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:init_listener
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
```
**Symbols:**

```
ffffffff8137d1b0-ffffffff8137d290: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81383e00)
Location: fs/anon_inodes.c:143
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
```
**Symbols:**

```
ffffffff81383e00-ffffffff81383e16: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff813d10a0)
Location: fs/anon_inodes.c:143
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
```
**Symbols:**

```
ffffffff813d10a0-ffffffff813d10b6: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8145a2a0)
Location: fs/anon_inodes.c:143
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/eventfd.c:do_eventfd
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_device_open
```
**Symbols:**

```
ffffffff8145a2a0-ffffffff8145a2c8: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff814e9750)
Location: fs/anon_inodes.c:143
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/eventfd.c:do_eventfd
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff814e9750-ffffffff814e9778: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff815204f0)
Location: fs/anon_inodes.c:143
Inline: False
Direct callers:
  - kernel/fork.c:__pidfd_prepare
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/eventfd.c:do_eventfd
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff815204f0-ffffffff81520518: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81554b00)
Location: fs/anon_inodes.c:143
Inline: False
Direct callers:
  - kernel/fork.c:__pidfd_prepare
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/eventfd.c:do_eventfd
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/gpu/drm/drm_file.c:mock_drm_getfile
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd
```
**Symbols:**

```
ffffffff81554b00-ffffffff81554b28: anon_inode_getfile (STB_GLOBAL)
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
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffff8000103f3250)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffff8000103f3250-ffff8000103f3330: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (c05c8698)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
c05c8698-c05c876c: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (c0000000004faf90)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
c0000000004faf90-c0000000004fb0dc: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffe0002a4c74)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffe0002a4c74-ffffffe0002a4d36: anon_inode_getfile (STB_GLOBAL)
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
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8132de60)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
**Symbols:**

```
ffffffff8132de60-ffffffff8132df40: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8131eac0)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8131eac0-ffffffff8131eba0: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8132b930)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8132b930-ffffffff8132ba10: anon_inode_getfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct file *anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8133e2e0)
Location: fs/anon_inodes.c:74
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8133e2e0-ffffffff8133e3c0: anon_inode_getfile (STB_GLOBAL)
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
