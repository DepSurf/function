# Function: <code>fd_install</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a9a0)
Location: fs/file.c:624
Inline: True
Inline callers:
  - fs/file.c:SyS_dup
  - fs/file.c:f_dupfd
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
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
ffffffff8122a9a0-ffffffff8122a9c7: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812537a9)
Location: fs/file.c:625
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff81253100-ffffffff81253127: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812669f9)
Location: fs/file.c:625
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff81266350-ffffffff81266377: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812741f4)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff81273b30-ffffffff81273b57: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296af4)
Location: fs/file.c:615
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup
Direct callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/shmem.c:SyS_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff81296410-ffffffff81296437: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bcc94)
Location: fs/file.c:610
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
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
ffffffff812bc870-ffffffff812bc897: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1f54)
Location: fs/file.c:610
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/nsfs.c:open_related_ns
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_getfd
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
ffffffff812d1b30-ffffffff812d1b57: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eef95)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff812eeb50-ffffffff812eeb79: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300a55)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff81300610-ffffffff81300639: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339c95)
Location: fs/file.c:616
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:pidfd_getfd
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/core/scm.c:__scm_install_fd
  - net/compat.c:scm_detach_fds_compat
  - net/unix/af_unix.c:unix_open_file
```
**Symbols:**

```
ffffffff813397c0-ffffffff813397e9: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344bf0)
Location: fs/file.c:573
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__receive_fd
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
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_open_file
```
**Symbols:**

```
ffffffff81344bf0-ffffffff81344c87: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134a980)
Location: fs/file.c:573
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__receive_fd
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
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff8134a980-ffffffff8134aa17: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:573
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
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
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81cc3dcb-ffffffff81cc3de0: fd_install.cold (STB_LOCAL)
ffffffff81398730-ffffffff813987cc: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
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
  - io_uring/io_uring.c:io_socket
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_openat2
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/unix/af_unix.c:unix_ioctl
```
**Symbols:**

```
ffffffff81e766ce-ffffffff81e766e3: fd_install.cold (STB_LOCAL)
ffffffff8141ab00-ffffffff8141abcd: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
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
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
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
ffffffff82068b6c-ffffffff82068b81: fd_install.cold (STB_LOCAL)
ffffffff814a66d0-ffffffff814a679d: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
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
  - net/core/sock.c:sk_getsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
**Symbols:**

```
ffffffff820e84aa-ffffffff820e84bf: fd_install.cold (STB_LOCAL)
ffffffff814db690-ffffffff814db75d: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:602
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/memfd.c:__do_sys_memfd_create
  - fs/open.c:do_sys_openat2
  - fs/exec.c:begin_new_exec
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/nsfs.c:open_related_ns
  - fs/init.c:init_dup
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/eventpoll.c:do_epoll_create
  - fs/anon_inodes.c:anon_inode_create_getfd
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/eventfd.c:do_eventfd
  - fs/fhandle.c:do_handle_open
  - ipc/mqueue.c:do_mq_open
  - io_uring/io_uring.c:io_uring_create
  - io_uring/openclose.c:io_openat2
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/dma-buf/dma-buf.c:dma_buf_fd
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd
  - net/socket.c:__sys_accept4
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
ffffffff821c5204-ffffffff821c5219: fd_install.cold (STB_LOCAL)
ffffffff8150dda0-ffffffff8150de8c: fd_install (STB_GLOBAL)
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
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b2a04)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__arm64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffff8000103b2320-ffff8000103b235c: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c0591cd8)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
c0591710-c0591748: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae984)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
c0000000004ae190-c0000000004ae1b8: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000276a24)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__se_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffe0002763b8-ffffffe0002763ee: fd_install (STB_GLOBAL)
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
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f9035)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff812f8bf0-ffffffff812f8c19: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9c55)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff812e9810-ffffffff812e9839: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6e45)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff812f6a00-ffffffff812f6a29: fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fd_install(unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813080b5)
Location: fs/file.c:611
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - fs/open.c:do_sys_open
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:do_pipe_flags
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
ffffffff81307c50-ffffffff81307c79: fd_install (STB_GLOBAL)
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
