# Function: <code>put_unused_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229b30)
Location: fs/file.c:573
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:SyS_mq_open
  - net/socket.c:sock_map_fd
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff81229b30-ffffffff81229b9e: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252280)
Location: fs/file.c:574
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:SyS_mq_open
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff81252280-ffffffff812522f2: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812654f0)
Location: fs/file.c:574
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:SyS_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
```
**Symbols:**

```
ffffffff812654f0-ffffffff81265562: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81272d00)
Location: fs/file.c:560
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81272d00-ffffffff81272d72: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81295630)
Location: fs/file.c:561
Inline: False
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:SyS_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:SyS_eventfd
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_accept4
  - net/socket.c:sock_map_fd
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81295630-ffffffff812956a2: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bbba0)
Location: fs/file.c:556
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812bbba0-ffffffff812bbc12: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d0d90)
Location: fs/file.c:556
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812d0d90-ffffffff812d0e02: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eddd0)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812eddd0-ffffffff812ede3b: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ff890)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812ff890-ffffffff812ff8fb: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813389a0)
Location: fs/file.c:562
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:__scm_install_fd
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_open_file
```
**Symbols:**

```
ffffffff813389a0-ffffffff81338a0f: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344340)
Location: fs/file.c:547
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/file.c:__receive_fd
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_open_file
```
**Symbols:**

```
ffffffff81344340-ffffffff813443af: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134a6e0)
Location: fs/file.c:547
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/file.c:__receive_fd
  - fs/namespace.c:__do_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff8134a6e0-ffffffff8134a74f: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398480)
Location: fs/file.c:547
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__do_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81398480-ffffffff813984ef: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141a6a0)
Location: fs/file.c:576
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_socket
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_openat2
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff8141a6a0-ffffffff8141a719: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a6b50)
Location: fs/file.c:576
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_uring_create
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff814a6b50-ffffffff814a6bc9: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dbb20)
Location: fs/file.c:576
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__pidfd_prepare
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/sock.c:sk_getsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff814dbb20-ffffffff814dbb99: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150e0e0)
Location: fs/file.c:576
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__pidfd_prepare
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_create_getfd
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/sock.c:sk_getsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
**Symbols:**

```
ffffffff8150e0e0-ffffffff8150e159: put_unused_fd (STB_GLOBAL)
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
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b10a0)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__arm64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffff8000103b10a0-ffff8000103b1190: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590ca0)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - ipc/mqueue.c:__se_sys_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
c0590ca0-c0590d4c: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ad1b0)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
c0000000004ad1b0-c0000000004ad2cc: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002752f8)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__se_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - ipc/mqueue.c:__se_sys_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffe0002752f8-ffffffe0002753c4: put_unused_fd (STB_GLOBAL)
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
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f7e70)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812f7e70-ffffffff812f7edb: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8a90)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812e8a90-ffffffff812e8afb: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f5c80)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff812f5c80-ffffffff812f5ceb: put_unused_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81306a90)
Location: fs/file.c:557
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/io_uring.c:io_uring_create
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:scm_detach_fds
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81306a90-ffffffff81306afd: put_unused_fd (STB_GLOBAL)
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
