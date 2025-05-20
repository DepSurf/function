# Function: <code>get_unused_fd_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a880)
Location: fs/file.c:559
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:SyS_dup
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:SyS_mq_open
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - net/socket.c:sock_map_fd
  - net/socket.c:SYSC_accept4
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff8122a880-ffffffff8122a8b2: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252fe0)
Location: fs/file.c:560
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:SyS_dup
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:SyS_mq_open
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff81252fe0-ffffffff81253012: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81266240)
Location: fs/file.c:560
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:SyS_dup
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:SyS_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff81266240-ffffffff81266272: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273a20)
Location: fs/file.c:546
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:SyS_dup
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81273a20-ffffffff81273a52: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296350)
Location: fs/file.c:547
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:SyS_dup
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81296350-ffffffff81296382: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc7b0)
Location: fs/file.c:542
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812bc7b0-ffffffff812bc7e2: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1a70)
Location: fs/file.c:542
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/fhandle.c:do_handle_open
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812d1a70-ffffffff812d1aa2: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eea80)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812eea80-ffffffff812eeab2: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300540)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81300540-ffffffff81300572: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339ba4)
Location: fs/file.c:548
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:pidfd_getfd
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:__scm_install_fd
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_open_file
```
**Symbols:**

```
ffffffff813396c0-ffffffff813396f2: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344ccb)
Location: fs/file.c:533
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__receive_fd
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_open_file
```
**Symbols:**

```
ffffffff81344970-ffffffff8134499b: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134ae8e)
Location: fs/file.c:533
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__receive_fd
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff8134ada0-ffffffff8134adcb: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398bee)
Location: fs/file.c:533
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81398b80-ffffffff81398bab: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141b433)
Location: fs/file.c:562
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff8141b3d0-ffffffff8141b405: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a74f3)
Location: fs/file.c:562
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff814a7480-ffffffff814a74b5: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dc4d3)
Location: fs/file.c:562
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
Direct callers:
  - kernel/fork.c:__pidfd_prepare
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
**Symbols:**

```
ffffffff814dc460-ffffffff814dc495: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150ee0b)
Location: fs/file.c:562
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
Direct callers:
  - kernel/fork.c:__pidfd_prepare
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_create_getfd
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_uring_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
**Symbols:**

```
ffffffff8150e780-ffffffff8150e7b5: get_unused_fd_flags (STB_GLOBAL)
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
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b2208)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__arm64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffff8000103b2208-ffff8000103b2248: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0591620)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - ipc/mqueue.c:__se_sys_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
c0591620-c0591660: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae060)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
c0000000004ae060-c0000000004ae090: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002762c2)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - ipc/mqueue.c:__se_sys_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffe0002762c2-ffffffe0002762fc: get_unused_fd_flags (STB_GLOBAL)
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
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8b20)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812f8b20-ffffffff812f8b52: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9740)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812e9740-ffffffff812e9772: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6930)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812f6930-ffffffff812f6962: get_unused_fd_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307b60)
Location: fs/file.c:543
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/file.c:ksys_dup
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81307b60-ffffffff81307b92: get_unused_fd_flags (STB_GLOBAL)
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
