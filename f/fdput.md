# Function: <code>fdput</code>

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
In kernel/sys.c (ffffffff81092a96)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/module.c (ffffffff8110668e)
Location: include/linux/file.h:37
Inline: True
```
```
In kernel/kexec_file.c (ffffffff8110e41a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/kexec_file.c:copy_file_from_fd
```
```
In kernel/taskstats.c (ffffffff8113e36a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811729ec)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get
  - kernel/bpf/syscall.c:bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/verifier.c (ffffffff811765f2)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff8117eb9a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_event_get
  - kernel/events/core.c:perf_event_get
```
```
In mm/readahead.c (ffffffff8119c483)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff811d12ae)
Location: include/linux/file.h:37
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fc477)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8120a43c)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/open.c:SyS_fallocate
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchown
```
```
In fs/read_write.c (ffffffff8120c3bb)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/read_write.c:compat_SyS_lseek
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:__compat_sys_preadv64
  - fs/read_write.c:__compat_sys_pwritev64
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_readv
  - fs/read_write.c:SyS_writev
  - fs/read_write.c:SyS_preadv
  - fs/read_write.c:SyS_pwritev
  - fs/read_write.c:compat_SyS_readv
  - fs/read_write.c:compat_SyS_writev
```
```
In fs/stat.c (ffffffff81211553)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8121900b)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8121ee75)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/ioctl.c (ffffffff81220332)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
```
```
In fs/readdir.c (ffffffff812207de)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/readdir.c:SyS_old_readdir
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_getdents64
```
```
In fs/select.c (ffffffff812213a3)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
```
```
In fs/xattr.c (ffffffff81232f0f)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fremovexattr
```
```
In fs/splice.c (ffffffff8123f712)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
```
```
In fs/sync.c (ffffffff8124069d)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
  - fs/sync.c:SyS_sync_file_range2
```
```
In fs/utimes.c (ffffffff81240eee)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81241ca3)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8125249e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812537d6)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff81255c13)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
```
```
In fs/signalfd.c (ffffffff81257760)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
```
```
In fs/timerfd.c (ffffffff81257ffc)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81259147)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81262987)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat.c (ffffffff81264e5e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_old_readdir
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_getdents64
```
```
In fs/compat_ioctl.c (ffffffff8126689a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff81270322)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff812a0e72)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8132c36f)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
```
```
In net/socket.c (ffffffff816fd42e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
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
In kernel/sys.c (ffffffff81095c2a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff811469ba)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff8118194b)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff81185136)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff8119385a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
```
In mm/readahead.c (ffffffff811b1648)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff811ee44e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/memcontrol.c (ffffffff8121f7a7)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8123103e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_fallocate
```
```
In fs/read_write.c (ffffffff81232099)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
```
```
In fs/stat.c (ffffffff81238003)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/exec.c (ffffffff81239769)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff8123e02a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81246805)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/ioctl.c (ffffffff81247df2)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff81248639)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
```
In fs/select.c (ffffffff81249db9)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff8125b85d)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/splice.c (ffffffff81268458)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/sync.c (ffffffff81268ea2)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
```
```
In fs/utimes.c (ffffffff8126921e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81269ff3)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127af93)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127cc3e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8127f5ca)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81280645)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/timerfd.c (ffffffff81280ff7)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81281b27)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8128eb9b)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat.c (ffffffff81291389)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_old_readdir
```
```
In fs/compat_ioctl.c (ffffffff81292bea)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff8129bb64)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff812cfc02)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8136100d)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
```
In net/socket.c (ffffffff81763f5e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
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
In kernel/sys.c (ffffffff8109ac1a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8115089a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff8118dbd6)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811924dd)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff811a3049)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
```
In mm/readahead.c (ffffffff811c1c88)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff811fed9e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/memcontrol.c (ffffffff81231e17)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812435ee)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_fallocate
```
```
In fs/read_write.c (ffffffff8124440e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
```
```
In fs/stat.c (ffffffff8124acc3)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/exec.c (ffffffff8124c4a9)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff81250e0a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812597f5)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/ioctl.c (ffffffff8125ae32)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8125b669)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
```
In fs/select.c (ffffffff8125cd80)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff8126ee0d)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/splice.c (ffffffff8127b428)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/sync.c (ffffffff8127be82)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
```
```
In fs/utimes.c (ffffffff8127c1ce)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8127cfa3)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128eb43)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812907de)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8129314a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff812941b5)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/timerfd.c (ffffffff81294b2e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81295657)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff812a3b40)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat.c (ffffffff812a6119)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_old_readdir
```
```
In fs/compat_ioctl.c (ffffffff812a796a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff812b0724)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff812e59f7)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81377813)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
```
In net/socket.c (ffffffff81790f8e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
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
In kernel/sys.c (ffffffff81097a1a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81152e25)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81192bb1)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff81199452)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff8119ebc1)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/events/core.c (ffffffff811aa7ec)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
```
In mm/readahead.c (ffffffff811c9f2a)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff8120997c)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/memcontrol.c (ffffffff8123e003)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8124ed1e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_fallocate
```
```
In fs/read_write.c (ffffffff8124fb95)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
```
```
In fs/stat.c (ffffffff812567aa)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812585b9)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff8125c55f)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812663d4)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/ioctl.c (ffffffff81267832)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812684d7)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/readdir.c:compat_SyS_getdents
  - fs/readdir.c:compat_SyS_old_readdir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
```
In fs/select.c (ffffffff81269953)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff8127c61d)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/splice.c (ffffffff812887de)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/sync.c (ffffffff812891f3)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
```
```
In fs/utimes.c (ffffffff812894d5)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8128a953)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b9a3)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129d667)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff812a03b5)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff812a148d)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/timerfd.c (ffffffff812a1dbb)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff812a2960)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff812b27ce)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat_ioctl.c (ffffffff812b410e)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff812bdbb2)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff81309536)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8138b301)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff817ae8ae)
Location: include/linux/file.h:37
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
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
In kernel/sys.c (ffffffff8109e70a)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8115f645)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811a0027)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811a83c4)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811aea63)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/events/core.c (ffffffff811be0ca)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
```
```
In mm/readahead.c (ffffffff811dedfa)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff81222aa4)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/memcontrol.c (ffffffff8125db9e)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81270c9e)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_fallocate
```
```
In fs/read_write.c (ffffffff81271add)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_write
  - fs/read_write.c:SyS_read
  - fs/read_write.c:SyS_llseek
  - fs/read_write.c:compat_SyS_lseek
```
```
In fs/stat.c (ffffffff812789fa)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff8127a929)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff8127e9c8)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81288c94)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
```
In fs/ioctl.c (ffffffff8128a0e2)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8128ad87)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/readdir.c:compat_SyS_getdents
  - fs/readdir.c:compat_SyS_old_readdir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
```
```
In fs/select.c (ffffffff8128c1ef)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff8129f0bd)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/splice.c (ffffffff812ab30e)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/sync.c (ffffffff812abd1a)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
```
```
In fs/utimes.c (ffffffff812abff5)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812ad673)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812bedb3)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812c0ae6)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff812c3792)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff812c47ba)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/timerfd.c (ffffffff812c50e1)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff812c5c10)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff812d6332)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat_ioctl.c (ffffffff812d799e)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff812e12a2)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8132e0ea)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813b0691)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff8182698e)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
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
In kernel/sys.c (ffffffff810a3f6a)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8116e6da)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811b4bff)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811bec3a)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811c6214)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811c94ee)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/bpf/sockmap.c (ffffffff811d06be)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sockmap_get_from_fd
```
```
In kernel/events/core.c (ffffffff811de972)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/readahead.c (ffffffff8120055c)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/fadvise.c (ffffffff812447a9)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/memcontrol.c (ffffffff8128141f)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81296928)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8129795e)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff8129f33a)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812a1469)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812a77cf)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812aef33)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812b0462)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812b1061)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff812b29bb)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff812c5412)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff812d1247)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff812d290e)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff812d2d5d)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812d53b3)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e7124)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e8870)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff812ea8d1)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff812ed31e)
Location: include/linux/file.h:38
Inline: True
```
```
In fs/timerfd.c (ffffffff812ee192)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff812eee40)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81300b0c)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81302c6f)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8130d4c0)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8135c75b)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813e1363)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff8186fffe)
Location: include/linux/file.h:38
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
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
In kernel/sys.c (ffffffff810acd3a)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8117c1aa)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811c4051)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811cf8ff)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811d7d04)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811dcdee)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff811eed89)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff812062b1)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81212f27)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81295e4f)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812ab718)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812ac766)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff812b431a)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812b6709)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812bc89e)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812c4034)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812c55c2)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812c6261)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff812c7acb)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff812da612)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff812e6487)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff812e7cee)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff812e813d)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812ea6d3)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fbd64)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fdc8b)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff81300af1)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8130197e)
Location: include/linux/file.h:40
Inline: True
```
```
In fs/timerfd.c (ffffffff81302c22)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff813037d0)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81316559)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff813182ff)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff813230b0)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff81374c5f)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813fbf43)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff81890bce)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff818f337e)
Location: include/linux/file.h:40
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/signal.c (ffffffff810aff80)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b2578)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8118903a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811d5896)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811d964f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811ec695)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f2426)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8120677d)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff8121d631)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8122293b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812b1f5b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812c7f18)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812c8ecf)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff812d108a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812d346c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812d937f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812e09ba)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812e2042)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812e2d06)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff812e472f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812f3143)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff812f8be2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff813050e6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff81306631)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81306a41)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81309142)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8130b9a8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c6d2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e81b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff81321d92)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81322eee)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (ffffffff81324873)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81324d5a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff81332218)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8133dd59)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8133fa27)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8134aac1)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8139e34c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81428218)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff818daadb)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81945840)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (ffffffff810a5c29)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b6591)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b8c48)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81194f7a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811e238d)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811e5d4f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811f8df5)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811feb36)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff812134e0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff8122b011)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812303eb)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812c38fe)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812d9928)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812da8df)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff812e2c1a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812e4ffc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812eae8f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812f246a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812f3b12)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812f4a76)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff812f60f6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81304d03)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff8130a812)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff81318176)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff813196b1)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81319aa1)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8131c1b2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8131e9b8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f4c2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8133164b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff813342f2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81335c4e)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (ffffffff813375d3)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81337aea)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff81345dd8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff81356349)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81358175)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff81362ca9)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813b6b51)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81441f48)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff817d2229)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817d28d5)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d6f44)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff8190cc2b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8197a860)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (ffffffff810ad768)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810be7a1)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810c0688)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810cdb6d)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
```
In kernel/taskstats.c (ffffffff811aa744)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811fd1ec)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff81205951)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff8121cbf6)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81225edc)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8123fc99)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff8124c68d)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81257de1)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8125d69b)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812f9610)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8130f6e8)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81310e2a)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff8131aeed)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff8131c0ac)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff81322d9d)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8132a6b8)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8132c078)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8132d11f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff8132dd0c)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8133e8da)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff81343812)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff81352b00)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff81353607)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81353a3f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81355ec7)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff813587d1)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813698b2)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136c11a)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8136e8a2)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8136f9b7)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff81370920)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81371900)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8138171c)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_start
```
```
In fs/locks.c (ffffffff8139d169)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813a882c)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff814025a7)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81492b45)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff8189d094)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff8189da35)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a468b)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819de996)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a4fd6d)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/signal.c (ffffffff810b9aa1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810bccf8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810c85cd)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811a7cf4)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811fc4bc)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff812066b1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff8121fb21)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff8122c93c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8124a21d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81256acd)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff812626b1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81267a4b)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81305cb0)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8131b998)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81320d0e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff8132665a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8132e326)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81335c28)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff813376f8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff813388ff)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff8133955b)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8134a93a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff8134ffd2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff8135f3e0)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff8135fee7)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81360297)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81362807)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81365151)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff81365e74)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff813662ff)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81376ad2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813799dc)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8137bc78)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8137d717)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff8137e696)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff8137f6b2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8138f7ec)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
```
```
In fs/locks.c (ffffffff813aeb39)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813b9b7c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff81414e7f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814b0445)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/integrity/ima/ima_main.c (ffffffff81533801)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff818abcc4)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff818ac655)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b36d6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819e0c86)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a55d7d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/signal.c (ffffffff810bb291)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810be587)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810ca0f1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811a8629)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81201be6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff8120861a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff812235a1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff812316fc)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8124e3c9)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff8125af6d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81267141)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8126c65b)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff8130b115)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81321ae8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81326e0e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff8132c76a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8133494e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8133bdb8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8133dd2f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8133ef69)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff8133fb11)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81351196)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff81356a81)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff81365ed0)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff813669f6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81366d37)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813692a7)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8136bba1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff8136c8b4)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff8136cd06)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d4a1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813805c6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff813823dc)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81384397)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff81385316)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81386332)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8139ee2f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/locks.c (ffffffff813b5e98)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813c0cd9)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff8141b1f6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814b6295)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff815371ed)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8153be0a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff8188ec44)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff8188f772)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818968b4)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819c6cc9)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a5177d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/signal.c (ffffffff810cdba1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810d02fd)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810dce61)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811d2289)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81233c6c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff8123bf9e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff8125b3c1)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff8126a6ac)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81289135)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81296d6d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff812a3b81)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812a937e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff8135599a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8136efc8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813743ce)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff81379eda)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff81382299)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81389a38)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8138b6af)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8138c8f9)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x64_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x64_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff8138d4a7)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8139f55a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff813a5461)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff813b47c0)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff813b5546)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff813b5887)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813b7fa7)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff813ba871)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff813bb58a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff813bb9c6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca0a2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd423)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff813cf64c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff813d1637)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff813d2596)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff813d3602)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff813ef10f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/locks.c (ffffffff81405b98)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff81410d99)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/quota/quota.c (ffffffff8141eb70)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff8146e307)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8150ebd5)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff8159580d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8159aa6e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff819222c8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff81923072)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192a831)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In net/socket.c (ffffffff81a76019)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81b0a33d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/signal.c (ffffffff810e5d4d)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810e9235)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810f66ef)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff81206e63)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81277107)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff81281ab9)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff812a45c2)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff812b74e7)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff812de288)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff812ece85)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff812fbaa5)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8130253a)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff813ce2df)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff813ed93f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f3371)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff813f8e5f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff81403f74)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8140aad4)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8140c9fe)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8140d1cf)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff8140e7f0)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81422a48)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff81428aa9)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff81439ba6)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff8143a7ea)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff8143abbb)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8143d7eb)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff814405be)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff814416ad)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff81441c23)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814526e6)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456af2)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8145842a)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8145a8e4)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff8145c180)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff8145cbfe)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8147a80f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff81486798)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/quota/quota.c (ffffffff814968f4)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff814eeae7)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8159ffe9)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff81637ab1)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8163f826)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff816d8bef)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_get_sq_data
  - io_uring/io_uring.c:io_get_sq_data
  - io_uring/io_uring.c:io_get_sq_data
  - io_uring/io_uring.c:io_get_sq_data
```
```
In drivers/vfio/vfio.c (ffffffff81a76b15)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff81a78a97)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/socket.c (ffffffff81be90c0)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81c909be)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/signal.c (ffffffff811068ed)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff8110a0e5)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff81118d8f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff8124f1c3)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff812cd003)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff812d9814)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81302262)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81318b17)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81346527)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff813571f5)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81365c25)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8136ccfa)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff814537c2)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8147605f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147c096)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff8148248f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8148e3e0)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81495344)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8149748e)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff81497c7f)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff81499372)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff814af0d8)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff814b6109)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff814c7ee6)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff814c8c7a)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff814c907b)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff814cc0bb)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff814cf48e)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff814d064d)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff814d0f03)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e1276)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5b9a)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff814e7d6a)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff814e9e34)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff814eb850)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff814ec33e)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8150d310)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff8151a0e8)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/quota/quota.c (ffffffff8152a874)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff81588a5c)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff816498b9)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff816eee81)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff816f75cf)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff8178c7fb)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In io_uring/sqpoll.c (ffffffff8179af8d)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/cancel.c (ffffffff8179ea5d)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In net/socket.c (ffffffff81d95840)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81e4be2e)
Location: include/linux/file.h:42
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096640)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
```
```
In kernel/signal.c (ffffffff81112bdd)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff811163b8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff8112624f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/nsproxy.c (ffffffff81131c4f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
```
```
In kernel/module/main.c (ffffffff811e082a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/module/main.c:__ia32_sys_finit_module
  - kernel/module/main.c:__x64_sys_finit_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81226517)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
```
```
In kernel/taskstats.c (ffffffff81266576)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff812ee75d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff8130378e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81330df2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8133616e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
```
```
In kernel/bpf/btf.c (ffffffff8134893a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8137761a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81388a75)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/filemap.c (ffffffff8138ceb6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
```
```
In mm/fadvise.c (ffffffff81398108)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8139ef5a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff814895d4)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814aa97f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b0c96)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff814b70a2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff814c3b2c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff814ca40b)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff814cc539)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff814ccbef)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff814ce415)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff814e403b)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff814ea939)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff814fe116)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff814feeba)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff814ff2be)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff815022fe)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff815056aa)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff815068fd)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff81507a35)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81517b19)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151c58b)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8151e01d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81520bd7)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff815225f3)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81523501)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81544a9c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff81551a43)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/quota.c (ffffffff81562bd2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff815bf8a2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fuse/dev.c (ffffffff816518ab)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/mqueue.c (ffffffff81681e1f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff81729316)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8173184c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff817cda05)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In io_uring/sqpoll.c (ffffffff817dc040)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/cancel.c (ffffffff817dfc4d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In net/socket.c (ffffffff81e03e80)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/net_namespace.c (ffffffff81e238ef)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
```
In net/core/sock_map.c (ffffffff81ea752e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109dbb0)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
```
```
In kernel/signal.c (ffffffff8111c5cd)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff8111fda8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff8113084f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/nsproxy.c (ffffffff8113ca7f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
```
```
In kernel/module/main.c (ffffffff811f655a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/module/main.c:__ia32_sys_finit_module
  - kernel/module/main.c:__x64_sys_finit_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e1a7)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
```
```
In kernel/taskstats.c (ffffffff81280466)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff8130d51d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff81323289)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81355352)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8135a7ce)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
```
```
In kernel/bpf/btf.c (ffffffff8136f06a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff813a08f8)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff813b24d5)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/filemap.c (ffffffff813b69c6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
```
```
In mm/fadvise.c (ffffffff813c1f38)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff813c8bbb)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff814b8a33)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814dbe1f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e2456)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff814e9422)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff814f5ffc)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff814fccdb)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff814fedf9)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff814ff80f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff81500d55)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81517d6b)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff8151e7d9)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff81532c7b)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff81533aea)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81533eee)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81536f4e)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8153a47a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff8153b61d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff8153c1b6)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154bef9)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550ada)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff815525fd)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8155521a)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff81556c13)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81557c31)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81579f8c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff8158796d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/quota/quota.c (ffffffff815992c2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff815f8648)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fuse/dev.c (ffffffff8168aebb)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/mqueue.c (ffffffff816be21d)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff8176a6dc)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/landlock/syscalls.c:add_rule_path_beneath
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8177226c)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/sqpoll.c (ffffffff818203c2)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb12e5)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
```
```
In net/socket.c (ffffffff81ec08b0)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/net_namespace.c (ffffffff81ee184f)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
```
In net/core/sock_map.c (ffffffff81f69fde)
Location: include/linux/file.h:43
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In virt/kvm/eventfd.c (ffff8000100c1360)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In virt/kvm/vfio.c (ffff8000100c2250)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
```
```
In kernel/exit.c (ffff8000100fbca8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffff800010112914)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffff800010115044)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffff80001020d454)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffff800010265088)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:__bpf_map_get
```
```
In kernel/bpf/verifier.c (ffff8000102690ac)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffff80001027e37c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffff800010285bd0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffff80001029dc88)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffff8000102b9330)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffff8000102bfc7c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffff800010364f7c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffff80001037ec6c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__arm64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffff80001037ff40)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__arm64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffff80001038a608)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffff80001038cae8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffff800010394520)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffff80001039c644)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__arm64_sys_fcntl
```
```
In fs/ioctl.c (ffff80001039f0e4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffff80001039fc00)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:__arm64_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__arm64_sys_getdents
```
```
In fs/select.c (ffff8000103a3200)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffff8000103b85b8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
```
```
In fs/xattr.c (ffff8000103be288)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:__arm64_sys_flistxattr
  - fs/xattr.c:__arm64_sys_fgetxattr
  - fs/xattr.c:__arm64_sys_fsetxattr
```
```
In fs/splice.c (ffff8000103cdef8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_splice
  - fs/splice.c:__arm64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffff8000103d06b8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__arm64_sys_syncfs
```
```
In fs/utimes.c (ffff8000103d0aa4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffff8000103d3b54)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffff8000103d6bb4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__arm64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec6dc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103eea60)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffff8000103f2b4c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
```
In fs/signalfd.c (ffff8000103f3604)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (ffff8000103f4a1c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffff8000103f5d50)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffff800010403a2c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
```
In fs/locks.c (ffff800010418e7c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__arm64_sys_flock
```
```
In fs/compat_ioctl.c (ffff80001041d154)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
```
In fs/fhandle.c (ffff8000104294fc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffff80001048c3e0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffff80001052a998)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffff800010ba1b50)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffff800010c21be4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (c0359ca4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (c0369884)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (c036ae90)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (c044bdec)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (c04971c8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (c049b40c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (c04afae4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (c04b6190)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (c04cce48)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (c04e5b18)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (c04eb76c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (c0557ea4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (c05695a4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (c056ac6c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__se_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (c05727e0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (c057470c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (c0578ad8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (c0582424)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (c0583fb0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (c0584938)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
```
```
In fs/select.c (c0585b58)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (c05980b8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (c059c2f0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (c05aafe8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (c05aba64)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (c05abddc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (c05aded4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (c05b0b78)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (c05c3ad8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (c05c5a4c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/eventpoll.c (c05c6490)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
```
In fs/signalfd.c (c05c8a7c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (c05c9ae8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (c05cac08)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (c05d76b4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (c05e5430)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fhandle.c (c05f229c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/ext4/ioctl.c (c064db88)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (c06e4fb8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In sound/core/pcm_native.c (c0c95b40)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
```
```
In net/socket.c (c0cc3b98)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (c0d391f0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (c00000000014330c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (c00000000015a344)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (c00000000015cf88)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (c00000000028b288)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (c000000000309c58)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (c00000000030ed68)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (c0000000003281b8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (c000000000330a90)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (c00000000034e0d4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (c000000000371670)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (c000000000378d78)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (c000000000453544)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (c0000000004749a0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (c000000000475f34)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__se_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (c000000000481878)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (c000000000484b68)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (c00000000048a66c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (c000000000497510)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (c000000000499750)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (c000000000499e74)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:__se_compat_sys_getdents
  - fs/readdir.c:__se_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:__se_sys_old_readdir
```
```
In fs/select.c (c00000000049cfbc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (c0000000004b54fc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (c0000000004bce08)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (c0000000004d1088)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (c0000000004d2f2c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (c0000000004d3474)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (c0000000004d65c8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (c0000000004daf84)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3998)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f72b0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (c0000000004f86d0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
```
In fs/signalfd.c (c0000000004fb524)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (c0000000004fd650)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (c0000000004fe080)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (c000000000510780)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (c000000000527fe0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/compat_ioctl.c (c00000000052b2e0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
```
```
In fs/fhandle.c (c000000000539a0c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (c0000000005b2d48)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (c00000000067565c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (c000000000aaf4dc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (c000000000ab1c68)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab61ac)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (c000000000c762b8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (c000000000d14208)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (ffffffe0000c56f2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffe0000d17a0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffe0000d209c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffe00016e556)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffe0001a0a5a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffe0001a3ffc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffe0001b5500)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffe0001bae94)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffe0001cb73a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffe0001dcee8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffe0001e1c2c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffe000244a82)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffe0002548ca)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffe00025582c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffe00025c544)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffe00025e074)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffe0002630a2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffe000268a70)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (ffffffe000269fb6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffe00026a5e4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
```
```
In fs/select.c (ffffffe00026b23c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffe00027c814)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (ffffffe00027fe14)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (ffffffe00028c064)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffe00028c90a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (ffffffe00028cc52)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffe00028e3b4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffe000290ac0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0d32)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a2940)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/eventpoll.c (ffffffe0002a3276)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffe0002a4fe6)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (ffffffe0002a62cc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffe0002a66a4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffe0002b10f6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (ffffffe0002bfbcc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fhandle.c (ffffffe0002c74f6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/ext4/ioctl.c (ffffffe00031259a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffe00038cf76)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
```
In net/socket.c (ffffffe000739c3c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffe00079a9cc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (ffffffff8109f549)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b0901)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b2fb8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8118d59a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811da9ad)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811de36f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811f1415)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f7156)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8120bb30)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff81223661)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81228a3b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812bbede)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812d1f08)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812d2ebf)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff812db1fa)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812dd5dc)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812e346f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812eaa4a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812ec0f2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812ed056)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff812ee6d6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812fd2e3)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81302df2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff81310756)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff81311c91)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81312081)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81314792)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81316f98)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327aa2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329c2b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8132c8d2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8132e22e)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (ffffffff8132fbb3)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff813300ca)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8133e3b8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8134e929)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81350755)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8135b289)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813af131)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8143a528)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff818acc2b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8191a6d0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (ffffffff8108df79)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff8109f221)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810a18e8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff811806ba)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811cd76d)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811d112f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811e4165)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811e9ea6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff811fe900)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff81216811)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8121bb7b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812ad03e)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812c2b88)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812c3b3f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff812cbe7a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812ce25c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812d40af)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812db68a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812dcd22)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812ddc86)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff812df306)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812edf03)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff812f3a12)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff81301366)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff813028a1)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81302c91)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813053a2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81307b88)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81318642)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a7cb)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8131c1a2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8131ee8e)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (ffffffff813207cd)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81320cea)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8132f078)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8133f609)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81341435)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8134bf29)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8139fbc1)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8142af98)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff8177c2d9)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff8177c97f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780ff4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff81866b7b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff818d4480)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (ffffffff8109f4f9)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810afe61)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b2518)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8118b36a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811d877d)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811dc13f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811ef1e5)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f4f26)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff812098d0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff81221401)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812267db)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812b9cee)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812cfd18)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812d0ccf)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff812d900a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812db3ec)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812e127f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812e885a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812e9f02)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812eae66)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff812ec4e6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812fb0d3)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81300be2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff8130e546)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff8130fa81)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff8130fe71)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81312582)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81314a68)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81325572)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813276fb)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8132a3a2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8132bcfe)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (ffffffff8132d683)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff8132db9a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8133be88)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8134c3f9)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8134e225)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff81358d59)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813ac991)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814366c8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff817c70a9)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817c7755)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cbdc4)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff818fdc2b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8196b860)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
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
In kernel/exit.c (ffffffff810a7459)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b8131)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810bab18)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81198cda)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811e6b07)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811ea54f)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811fd6b5)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81203446)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81218670)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff812305c1)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81235b0b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812ca37e)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812e0b28)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812e1aff)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_readv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
  - fs/read_write.c:ksys_write
  - fs/read_write.c:ksys_read
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/read_write.c:ksys_lseek
```
```
In fs/stat.c (ffffffff812e9f1a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812ec36c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812f02aa)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812f982a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812faef2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812fbe56)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
```
```
In fs/select.c (ffffffff812fd4e6)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8130c723)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81311f22)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/splice.c (ffffffff8131fd46)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__ia32_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__x64_sys_tee
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__x64_sys_splice
  - fs/splice.c:__do_compat_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff81321281)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81321671)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81323dc2)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff813265d8)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813379c0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339b1b)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8133ae72)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8133e9ae)
Location: include/linux/file.h:41
Inline: True
```
```
In fs/timerfd.c (ffffffff8133f34a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff8134097a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8134f038)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8135ebe9)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff813617a5)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8136c459)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813c1331)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8144ce7a)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff817e1349)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817e197c)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6064)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff8191ecbb)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8198dcd0)
Location: include/linux/file.h:41
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
</details>
</li>
</ul>

## Differences
