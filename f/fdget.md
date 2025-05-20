# Function: <code>fdget</code>

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
In kernel/sys.c (ffffffff81092a65)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/module.c (ffffffff8110666b)
Location: include/linux/file.h:54
Inline: True
```
```
In kernel/kexec_file.c (ffffffff8110e3ef)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - kernel/kexec_file.c:copy_file_from_fd
```
```
In kernel/taskstats.c (ffffffff8113e2d2)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811729d1)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/verifier.c (ffffffff8117652f)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff8117eb48)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_event_get
```
```
In mm/readahead.c (ffffffff8119c428)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff811d11ef)
Location: include/linux/file.h:54
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fc363)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8120a3f5)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/open.c:SyS_fallocate
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchown
```
```
In fs/read_write.c (ffffffff8120cf63)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/read_write.c:__compat_sys_preadv64
  - fs/read_write.c:__compat_sys_pwritev64
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:SyS_pread64
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_preadv
  - fs/read_write.c:SyS_pwritev
```
```
In fs/ioctl.c (ffffffff8122030f)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
```
```
In fs/readdir.c (ffffffff81220797)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/readdir.c:SyS_old_readdir
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_getdents64
```
```
In fs/select.c (ffffffff81221329)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
```
```
In fs/xattr.c (ffffffff81232ed3)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fremovexattr
```
```
In fs/splice.c (ffffffff8123f6e8)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
```
```
In fs/sync.c (ffffffff81240675)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
  - fs/sync.c:SyS_sync_file_range2
```
```
In fs/utimes.c (ffffffff81240ec7)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81252442)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812537a6)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff81255bac)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
```
```
In fs/signalfd.c (ffffffff81257736)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
```
```
In fs/timerfd.c (ffffffff81257fe1)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81259127)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8126289c)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat.c (ffffffff81264e17)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_old_readdir
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_getdents64
```
```
In fs/compat_ioctl.c (ffffffff8126686e)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff81270301)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff812a0e05)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8132c21d)
Location: include/linux/file.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
```
```
In net/socket.c (ffffffff816fd402)
Location: include/linux/file.h:54
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
In kernel/sys.c (ffffffff81095bf5)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81146922)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff8118191e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff8118505d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff8119382d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_ioctl
```
```
In mm/readahead.c (ffffffff811b1628)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff811ee38f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/memcontrol.c (ffffffff8121f693)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81231018)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fallocate
```
```
In fs/read_write.c (ffffffff812320b5)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_pread64
```
```
In fs/exec.c (ffffffff81239743)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff81247dcf)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff81249d3f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff8125b823)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/splice.c (ffffffff812683f8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/sync.c (ffffffff81268e6b)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
```
```
In fs/utimes.c (ffffffff812691f7)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127af29)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127cbfb)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8127f59d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8128061d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/timerfd.c (ffffffff812808e1)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81281b07)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8128ea99)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat_ioctl.c (ffffffff81292bbe)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff8129bb3f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff812cfb89)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81360ead)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
```
In net/socket.c (ffffffff81763f32)
Location: include/linux/file.h:55
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
In kernel/sys.c (ffffffff8109abe5)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81150802)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff8118dba9)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811925d2)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff811a301c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_ioctl
```
```
In mm/readahead.c (ffffffff811c1c68)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff811fecdf)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/memcontrol.c (ffffffff81231d03)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812435c8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fallocate
```
```
In fs/read_write.c (ffffffff81244426)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_pread64
```
```
In fs/exec.c (ffffffff8124c483)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff8125ae0f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff8125cd06)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff8126edd3)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/splice.c (ffffffff8127b3c8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/sync.c (ffffffff8127be4b)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
```
```
In fs/utimes.c (ffffffff8127c1a7)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128ead9)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129079b)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8129311d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8129418d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/timerfd.c (ffffffff81294451)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81295637)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff812a3a29)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat_ioctl.c (ffffffff812a793e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff812b06ff)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff812e597e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813776bd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
```
In net/socket.c (ffffffff81790f62)
Location: include/linux/file.h:55
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
In kernel/sys.c (ffffffff810979e5)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81152df2)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81192b74)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff81199389)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff8119eb83)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/events/core.c (ffffffff811aa7bc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
```
```
In mm/readahead.c (ffffffff811c9f0a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff812098af)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/memcontrol.c (ffffffff8123de71)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8124ecfa)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fallocate
```
```
In fs/read_write.c (ffffffff8124fbad)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_pread64
```
```
In fs/exec.c (ffffffff81258593)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff8126780f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812698e1)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff8127c5e3)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/splice.c (ffffffff8128877b)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/sync.c (ffffffff81289196)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
```
```
In fs/utimes.c (ffffffff812894ae)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b939)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129d625)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff812a038f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff812a1462)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/timerfd.c (ffffffff812a1731)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff812a2941)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff812b26c9)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat_ioctl.c (ffffffff812b40df)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff812bdb8d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813094b9)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8138b1f3)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff817ae882)
Location: include/linux/file.h:55
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
In kernel/sys.c (ffffffff8109e6d5)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8115f612)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff8119fffa)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811a8302)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811aea23)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/events/core.c (ffffffff811be0f9)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
```
```
In mm/readahead.c (ffffffff811dedda)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/fadvise.c (ffffffff812229ef)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/memcontrol.c (ffffffff8125da01)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81270c7a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fallocate
```
```
In fs/read_write.c (ffffffff81271b01)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:SyS_pwrite64
  - fs/read_write.c:SyS_pread64
```
```
In fs/exec.c (ffffffff8127a903)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff8128a0bf)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff8128c17a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff8129f083)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/splice.c (ffffffff812ab2ab)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:compat_SyS_vmsplice
```
```
In fs/sync.c (ffffffff812abcc6)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:do_fsync
  - fs/sync.c:SyS_syncfs
```
```
In fs/utimes.c (ffffffff812abfce)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812bed49)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812c0aa4)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff812c376c)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff812c478f)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/timerfd.c (ffffffff812c4a51)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff812c5bf1)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff812d6229)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/locks.c:SyS_flock
```
```
In fs/compat_ioctl.c (ffffffff812d796f)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
```
In fs/fhandle.c (ffffffff812e127d)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8132e06d)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813b0583)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff81826962)
Location: include/linux/file.h:56
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
In kernel/sys.c (ffffffff810a3f25)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8116e648)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811b4bc7)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811beb8b)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811c61c5)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811c94c5)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/bpf/sockmap.c (ffffffff811d0665)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sockmap_get_from_fd
```
```
In kernel/events/core.c (ffffffff811de018)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/readahead.c (ffffffff81200525)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/fadvise.c (ffffffff812446e5)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/memcontrol.c (ffffffff812813f2)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812968f5)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8129792c)
Location: include/linux/file.h:56
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
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffff812a1425)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff812b0425)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812b2945)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff812c53d4)
Location: include/linux/file.h:56
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
In fs/splice.c (ffffffff812d11db)
Location: include/linux/file.h:56
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
In fs/sync.c (ffffffff812d28c1)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff812d2d28)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e70b6)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e8809)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff812ea8b1)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff812ed2fa)
Location: include/linux/file.h:56
Inline: True
```
```
In fs/timerfd.c (ffffffff812ed8e5)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff812eee15)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81300ac1)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81302bb2)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8130d490)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8135c6ed)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813e1251)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff8186ffc5)
Location: include/linux/file.h:56
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
In kernel/sys.c (ffffffff810accf5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8117c118)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811c4023)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811cf84d)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811d7cb5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811dcdc5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff811ee428)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff81206275)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81212ec5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81295e22)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812ab6e5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812ac741)
Location: include/linux/file.h:58
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
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffff812b66c5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff812c5585)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812c7a55)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff812da5d4)
Location: include/linux/file.h:58
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
In fs/splice.c (ffffffff812e641b)
Location: include/linux/file.h:58
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
In fs/sync.c (ffffffff812e7ca1)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff812e8108)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fbcf6)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fdc25)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff81300ad1)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8130195a)
Location: include/linux/file.h:58
Inline: True
```
```
In fs/timerfd.c (ffffffff81302415)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff813037a5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff813164b6)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81318242)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff81323080)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff81374bf1)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813fbe31)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff81890b95)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff818f3325)
Location: include/linux/file.h:58
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
In kernel/signal.c (ffffffff810afeaf)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b2535)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81188fa8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811d5870)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811d9469)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811ec645)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f2405)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81205e68)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff8121d5f5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812228d5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812b1e65)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812c7ee5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812c8ee6)
Location: include/linux/file.h:60
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
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffff812d3425)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff812e2005)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812e46bc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812f311a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff812f8ba4)
Location: include/linux/file.h:60
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
In fs/splice.c (ffffffff81305078)
Location: include/linux/file.h:60
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
In fs/sync.c (ffffffff813065f5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81306a0c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff8130b982)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c666)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e789)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff81321d72)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81322ecb)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (ffffffff81323985)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81324d35)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff813321f2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8133dca6)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8133f8f2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8134aa92)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8139e2df)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814280f1)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff818daaa5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff819457f5)
Location: include/linux/file.h:60
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
In kernel/exit.c (ffffffff810a5bc2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b64cf)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b8c05)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81194ee8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811e2367)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811e5b69)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811f8da5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811feb15)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81213583)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff8122afd5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81230385)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812c3805)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812d98f5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812da8f6)
Location: include/linux/file.h:60
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
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffff812e4fb5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff812f3ad5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812f6083)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81304cda)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff8130a7d4)
Location: include/linux/file.h:60
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
In fs/splice.c (ffffffff81318108)
Location: include/linux/file.h:60
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
In fs/sync.c (ffffffff81319675)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81319a6c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff8131e992)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f456)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331601)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff813342d2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81335c2b)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (ffffffff813366e5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81337ac5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff81345db2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff81356296)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81358102)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff81362c79)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813b6aed)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81441e21)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff817d214c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817d286a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d6f0a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff8190cbf5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8197a815)
Location: include/linux/file.h:60
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
In kernel/exit.c (ffffffff810ad6ea)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810be6be)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810c0645)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810cdb40)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
```
In kernel/taskstats.c (ffffffff811aa678)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811fd1c8)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff81205629)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff8121cba5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81225eb5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8123f355)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff8124c635)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81257d95)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8125d635)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812f9485)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8130f6b5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81310e4e)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
```
In fs/exec.c (ffffffff8131c065)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff8132bff0)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff8132dc86)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8133e8b1)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff813437d4)
Location: include/linux/file.h:62
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
In fs/splice.c (ffffffff81352aa8)
Location: include/linux/file.h:62
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
In fs/sync.c (ffffffff813535de)
Location: include/linux/file.h:62
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
In fs/utimes.c (ffffffff81353a0e)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff813587ab)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81369846)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136c0cd)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8136e882)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8136f8c0)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff813707c5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff813718d5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff813816f2)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_start
```
```
In fs/locks.c (ffffffff8139d0b6)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813a87fc)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff81402546)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81492a01)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff8189cf26)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff8189d9ca)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a4651)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819e13fe)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a4fd14)
Location: include/linux/file.h:62
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
In kernel/signal.c (ffffffff810b99be)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810bccc6)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810c85a0)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811a7c28)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811fc498)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff81206358)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff8121fad2)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff8122c915)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81249755)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81256a75)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81262665)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812679e5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81305b25)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8131b965)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81320c11)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
```
In fs/ioctl.c (ffffffff81337685)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff813394d5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8134a911)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff8134ff94)
Location: include/linux/file.h:63
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
In fs/splice.c (ffffffff8135f388)
Location: include/linux/file.h:63
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
```
```
In fs/sync.c (ffffffff8135febe)
Location: include/linux/file.h:63
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
In fs/utimes.c (ffffffff81360270)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff8136512b)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff81365e25)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff81366317)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81376a66)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81379992)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8137bc58)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8137d620)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff8137e535)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff8137f685)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8138f7c2)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
```
```
In fs/locks.c (ffffffff813aea86)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813b9b4c)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff81414e1e)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814b0301)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/integrity/ima/ima_main.c (ffffffff815337cf)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff818abb56)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff818ac5ea)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b369c)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819e0c4e)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a55d24)
Location: include/linux/file.h:63
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
In kernel/signal.c (ffffffff810bb1ae)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810be556)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810ca0bf)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811a8558)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81201bc3)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff812082bd)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81223552)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff812316d5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8124d8e0)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff8125af15)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff812670f5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8126c5f5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff8130afc5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81321ab5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81326d11)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
```
In fs/ioctl.c (ffffffff8133dcb5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff8133fa82)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8135116d)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff81356a44)
Location: include/linux/file.h:63
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
In fs/splice.c (ffffffff81365e76)
Location: include/linux/file.h:63
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
```
```
In fs/sync.c (ffffffff813669ce)
Location: include/linux/file.h:63
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
In fs/utimes.c (ffffffff81366d10)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff8136bb7b)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff8136c865)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff8136cd1e)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d436)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380560)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff813823bc)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff813842a0)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff813851b5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81386305)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8139ee09)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/locks.c (ffffffff813b5de6)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813c0ca9)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff8141b18b)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814b6151)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff81537265)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8153bdcf)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff8188ead6)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff8188f70a)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81896884)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819c6c8e)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a51724)
Location: include/linux/file.h:63
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
In kernel/signal.c (ffffffff810cdabe)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810d02d4)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810dce2f)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811d21b8)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81233c46)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff8123bb8a)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff8125b372)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff8126a685)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81288630)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81296d15)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff812a3b35)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812a9315)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81355845)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8136ef95)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813742d1)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
```
In fs/ioctl.c (ffffffff8138b635)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff8138d41b)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8139f531)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff813a5424)
Location: include/linux/file.h:63
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
In fs/splice.c (ffffffff813b4766)
Location: include/linux/file.h:63
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
```
```
In fs/sync.c (ffffffff813b551e)
Location: include/linux/file.h:63
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
In fs/utimes.c (ffffffff813b5860)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff813ba84b)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff813bb535)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff813bb9de)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca054)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd3bd)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff813cf62c)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff813d1540)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff813d2435)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff813d35d5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff813ef0e9)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/locks.c (ffffffff81405ae6)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff81410d69)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff8146e2a6)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8150ea91)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff815959e5)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8159aa2f)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff81922135)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff8192300a)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192a80c)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In net/socket.c (ffffffff81a75fde)
Location: include/linux/file.h:63
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81b0a2e4)
Location: include/linux/file.h:63
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
In kernel/signal.c (ffffffff810e5c55)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810e9204)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810f66bc)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff81206d70)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff812770af)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff812816a5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff812a4572)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff812b74b5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff812dd7f4)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff812ece15)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff812fba55)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff813024c5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff813ce1c3)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff813ed905)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f3261)
Location: include/linux/file.h:61
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
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
```
In fs/ioctl.c (ffffffff8140c985)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff8140e89c)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81422a1b)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff81428a64)
Location: include/linux/file.h:61
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
In fs/splice.c (ffffffff81439b54)
Location: include/linux/file.h:61
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
```
```
In fs/sync.c (ffffffff8143a7be)
Location: include/linux/file.h:61
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
In fs/utimes.c (ffffffff8143ab90)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff81440594)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff81441655)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff81441c3e)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81452694)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814569d5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff81458405)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8145a7df)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff8145bfd5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff8145cbc5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8147a7b0)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff81486711)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff814eea85)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8159fe92)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff81637cb5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8163f7e3)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff816d8bc2)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_get_sq_data
```
```
In drivers/vfio/vfio.c (ffffffff81a768f5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff81a78a05)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/socket.c (ffffffff81be907e)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81c90911)
Location: include/linux/file.h:61
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
In kernel/signal.c (ffffffff81106815)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff8110a0b4)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff81118d5c)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff8124f0d0)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff812ccfda)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff812d9415)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81302212)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81318ae5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81345bab)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81357185)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81365bd5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8136cc85)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff814536f3)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81476025)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bf71)
Location: include/linux/file.h:61
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
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
```
In fs/ioctl.c (ffffffff81497415)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff8149941d)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff814af0ab)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff814b60c4)
Location: include/linux/file.h:61
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
In fs/splice.c (ffffffff814c7e94)
Location: include/linux/file.h:61
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
```
```
In fs/sync.c (ffffffff814c8c4e)
Location: include/linux/file.h:61
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
In fs/utimes.c (ffffffff814c9050)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff814cf464)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff814d05f5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff814d0f1e)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e1224)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5a73)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff814e7d45)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff814e9d2f)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff814eb6a5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff814ec305)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8150d24c)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff8151a061)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff815889f7)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81649762)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff816ef0b5)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff816f7585)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff8178c7d1)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In io_uring/sqpoll.c (ffffffff8179ae65)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/cancel.c (ffffffff8179eaaa)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In net/socket.c (ffffffff81d957fe)
Location: include/linux/file.h:61
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81e4bd81)
Location: include/linux/file.h:61
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810965ff)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
```
```
In kernel/signal.c (ffffffff81112b05)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff81116384)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff8112621c)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/nsproxy.c (ffffffff81131be3)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
```
```
In kernel/module/main.c (ffffffff811e0805)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/module/main.c:__ia32_sys_finit_module
  - kernel/module/main.c:__x64_sys_finit_module
```
```
In kernel/taskstats.c (ffffffff81266480)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff812ee734)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff81303395)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81330da2)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81348905)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81376c5e)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81388a05)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/filemap.c (ffffffff8138cd51)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
```
```
In mm/fadvise.c (ffffffff813980b5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8139eee5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81489503)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814aa945)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b0b71)
Location: include/linux/file.h:62
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
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
```
In fs/ioctl.c (ffffffff814cc475)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff814ce4cd)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff814e400b)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff814ea8f4)
Location: include/linux/file.h:62
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
In fs/splice.c (ffffffff814fe0c4)
Location: include/linux/file.h:62
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
```
```
In fs/sync.c (ffffffff814fee8e)
Location: include/linux/file.h:62
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
In fs/utimes.c (ffffffff814ff290)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff8150567d)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff815068a5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff81507a50)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81517ac4)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151c4eb)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8151dff2)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81520acf)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff81522445)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff815234c5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff815449cd)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff815519f7)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff815bf842)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fuse/dev.c (ffffffff8165187e)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/mqueue.c (ffffffff81681cc2)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff81729555)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff81731803)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff817cda8b)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In io_uring/sqpoll.c (ffffffff817dbf14)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/cancel.c (ffffffff817dfc9a)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In net/socket.c (ffffffff81e03e3e)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/net_namespace.c (ffffffff81e23885)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
```
In net/core/sock_map.c (ffffffff81ea7481)
Location: include/linux/file.h:62
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109db6f)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
```
```
In kernel/signal.c (ffffffff8111c4f5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff8111fd74)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff8113081c)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/nsproxy.c (ffffffff8113ca13)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
```
```
In kernel/module/main.c (ffffffff811f6535)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/module/main.c:__ia32_sys_finit_module
  - kernel/module/main.c:__x64_sys_finit_module
```
```
In kernel/taskstats.c (ffffffff81280370)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff8130d4f4)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In kernel/bpf/verifier.c (ffffffff81322e65)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81355302)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff8136f035)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8139feee)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff813b2465)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/filemap.c (ffffffff813b6861)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
```
```
In mm/fadvise.c (ffffffff813c1ee5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff813c8b45)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff814b8962)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814dbde5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/open.c:__ia32_sys_fallocate
  - fs/open.c:__x64_sys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e2331)
Location: include/linux/file.h:62
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
  - fs/read_write.c:__ia32_sys_pwrite64
  - fs/read_write.c:__x64_sys_pwrite64
  - fs/read_write.c:__ia32_sys_pread64
  - fs/read_write.c:__x64_sys_pread64
```
```
In fs/ioctl.c (ffffffff814fed35)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff81500e0d)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81517d3b)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff8151e794)
Location: include/linux/file.h:62
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
In fs/splice.c (ffffffff81532c44)
Location: include/linux/file.h:62
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
```
```
In fs/sync.c (ffffffff81533abe)
Location: include/linux/file.h:62
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
In fs/utimes.c (ffffffff81533ec0)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff8153a44d)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff8153b5c5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff8153c1d1)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154bea4)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550a34)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff815525d2)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff815550df)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff81556a65)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81557bf5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81579ebd)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff8158792a)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff815f85e8)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fuse/dev.c (ffffffff8168ae8e)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/mqueue.c (ffffffff816be0d2)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff8176aba5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff81772223)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/sqpoll.c (ffffffff81820296)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb111c)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
```
```
In net/socket.c (ffffffff81ec086e)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/net_namespace.c (ffffffff81ee17e5)
Location: include/linux/file.h:62
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
```
In net/core/sock_map.c (ffffffff81f69f31)
Location: include/linux/file.h:62
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
In virt/kvm/eventfd.c (ffff8000100c1164)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In virt/kvm/vfio.c (ffff8000100c219c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
```
```
In kernel/exit.c (ffff8000100fbc6c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffff80001011284c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffff800010115018)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffff80001020d3d8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffff800010265030)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffff800010268ed0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffff80001027e340)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffff800010285ba4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffff80001029d6b4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffff8000102b9304)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffff8000102bfc24)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffff800010364ea4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffff80001037ec48)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffff80001037ff20)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffff80001038cab8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffff80001039f0b8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffff8000103a31b4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffff8000103b858c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
```
```
In fs/xattr.c (ffff8000103be254)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:__arm64_sys_flistxattr
  - fs/xattr.c:__arm64_sys_fgetxattr
  - fs/xattr.c:__arm64_sys_fsetxattr
```
```
In fs/splice.c (ffff8000103cde7c)
Location: include/linux/file.h:60
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
In fs/sync.c (ffff8000103d068c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__arm64_sys_syncfs
```
```
In fs/utimes.c (ffff8000103d0a78)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffff8000103d6b8c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__arm64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec654)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee9e4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffff8000103f2b20)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
```
In fs/signalfd.c (ffff8000103f35dc)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (ffff8000103f441c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffff8000103f5d24)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffff800010403a04)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
```
In fs/locks.c (ffff800010418dd4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__arm64_sys_flock
```
```
In fs/compat_ioctl.c (ffff80001041d0c8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
```
In fs/fhandle.c (ffff8000104294dc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffff80001048c35c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffff80001052a87c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffff800010ba1b14)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffff800010c21bb0)
Location: include/linux/file.h:60
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
In kernel/exit.c (c0359c5c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (c03697b8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (c036ae60)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (c044bd6c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (c04971a4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (c049b1c4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (c04afa98)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (c04b616c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (c04ccec8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (c04e5ad8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (c04eb6f4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (c0557de8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (c056957c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (c056abd8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (c05746d0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (c0583f7c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (c0585afc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (c059808c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (c059c2a4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (c05aafc8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (c05aba28)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (c05abdb4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (c05b0b50)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (c05c3a64)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (c05c59f8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/eventpoll.c (c05c6468)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
```
In fs/signalfd.c (c05c89e8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (c05c93a4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (c05cabdc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (c05d7688)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (c05e537c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fhandle.c (c05f2278)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/ext4/ioctl.c (c064daec)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (c06e4eb4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In sound/core/pcm_native.c (c0c95b00)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
```
```
In net/socket.c (c0cc3b58)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (c0d391a0)
Location: include/linux/file.h:60
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
In kernel/exit.c (c0000000001432b0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (c00000000015a21c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (c00000000015cf48)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (c00000000028b1d4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (c000000000309c2c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (c00000000030eb10)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (c00000000032816c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (c000000000330a60)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (c00000000034e200)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (c000000000371630)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (c000000000378cfc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (c00000000045334c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (c00000000047496c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (c000000000475f54)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (c000000000484b24)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (c000000000499710)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (c00000000049cf50)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (c0000000004b54cc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (c0000000004bcdb4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (c0000000004d0fc4)
Location: include/linux/file.h:60
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
In fs/sync.c (c0000000004d2ef0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (c0000000004d3430)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (c0000000004daf44)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3900)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f7210)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (c0000000004f8688)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
```
In fs/signalfd.c (c0000000004fb4ec)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (c0000000004fc210)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (c0000000004fe050)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (c00000000051074c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (c000000000527f04)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/compat_ioctl.c (c00000000052b0e8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
```
```
In fs/fhandle.c (c0000000005399e0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (c0000000005b2c98)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (c0000000006754fc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (c000000000aaf44c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (c000000000ab1bc4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab617c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (c000000000c76274)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (c000000000d141bc)
Location: include/linux/file.h:60
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
In kernel/exit.c (ffffffe0000c56be)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffe0000d1752)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffe0000d2072)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffe00016e4dc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffe0001a0a34)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffe0001a3df0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffe0001b54be)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffe0001bae72)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffe0001cb7bc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffe0001dcec2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffe0001e1be0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffe0002449a2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffe0002548a6)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffe000255842)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffe00025e04a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffe000269f8e)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffe00026b1f0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffe00027c7ea)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (ffffffe00027fde4)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (ffffffe00028bff0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffe00028c8e2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (ffffffe00028cc2a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffe000290a9a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0c9a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a2900)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/eventpoll.c (ffffffe0002a324e)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffe0002a4fbe)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (ffffffe0002a565c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffe0002a6682)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffe0002b10ca)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (ffffffe0002bfb32)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fhandle.c (ffffffe0002c74e0)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/ext4/ioctl.c (ffffffe000312508)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffe00038ce2e)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
```
In net/socket.c (ffffffe000739c0c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffe00079a98c)
Location: include/linux/file.h:60
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
In kernel/exit.c (ffffffff8109f4e2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b083f)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b2f75)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8118d508)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811da987)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811de189)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811f13c5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f7135)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8120bbd3)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff81223625)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812289d5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812bbde5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812d1ed5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812d2ed6)
Location: include/linux/file.h:60
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
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffff812dd595)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff812ec0b5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812ee663)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812fd2ba)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81302db4)
Location: include/linux/file.h:60
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
In fs/splice.c (ffffffff813106e8)
Location: include/linux/file.h:60
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
In fs/sync.c (ffffffff81311c55)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff8131204c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff81316f72)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327a36)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329be1)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8132c8b2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8132e20b)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (ffffffff8132ecc5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff813300a5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8133e392)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8134e876)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff813506e2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8135b259)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813af0cd)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8143a401)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff818acbf5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8191a685)
Location: include/linux/file.h:60
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
In kernel/exit.c (ffffffff8108df12)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff8109f15f)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810a18a5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81180628)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811cd747)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811d0f49)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811e4115)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811e9e85)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff811fe9a3)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff812167d5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8121bb15)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812acf45)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812c2b55)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812c3b56)
Location: include/linux/file.h:60
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
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffff812ce215)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff812dcce5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812df293)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812ededa)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff812f39d4)
Location: include/linux/file.h:60
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
In fs/splice.c (ffffffff813012f8)
Location: include/linux/file.h:60
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
In fs/sync.c (ffffffff81302865)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81302c5c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff81307b62)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813185d6)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a781)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8131c182)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8131ee6b)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (ffffffff8131f905)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81320cc5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8132f052)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8133f556)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff813413c2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8134bef9)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8139fb5d)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8142ae71)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff8177c1fc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff8177c91a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780fba)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff81866b45)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff818d4435)
Location: include/linux/file.h:60
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
In kernel/exit.c (ffffffff8109f492)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810afd9f)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b24d5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8118b2d8)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811d8757)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811dbf59)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811ef195)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f4f05)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81209973)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff812213c5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81226775)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812b9bf5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812cfce5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812d0ce6)
Location: include/linux/file.h:60
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
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffff812db3a5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff812e9ec5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812ec473)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812fb0aa)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81300ba4)
Location: include/linux/file.h:60
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
In fs/splice.c (ffffffff8130e4d8)
Location: include/linux/file.h:60
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
In fs/sync.c (ffffffff8130fa45)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff8130fe3c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff81314a42)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81325506)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813276b1)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8132a382)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8132bcdb)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (ffffffff8132c795)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff8132db75)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8133be62)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8134c346)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8134e1b2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff81358d29)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813ac92d)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814365a1)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff817c6fcc)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817c76ea)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cbd8a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff818fdbf5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8196b815)
Location: include/linux/file.h:60
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
In kernel/exit.c (ffffffff810a73f2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b806f)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810baad5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81198c48)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811e6ada)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/verifier.c (ffffffff811ea369)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811fd665)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81203425)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81218713)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff81230585)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81235aa5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812ca285)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812e0af5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff812e1b16)
Location: include/linux/file.h:60
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
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_preadv
  - fs/read_write.c:ksys_pwrite64
  - fs/read_write.c:ksys_pread64
```
```
In fs/exec.c (ffffffff812ec325)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/ioctl.c (ffffffff812faeb5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/select.c (ffffffff812fd473)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8130c6fa)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81311ee4)
Location: include/linux/file.h:60
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
In fs/splice.c (ffffffff8131fcd8)
Location: include/linux/file.h:60
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
In fs/sync.c (ffffffff81321245)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff8132163c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/fsopen.c (ffffffff813265b2)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337956)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339ad1)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8133ae52)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8133e98b)
Location: include/linux/file.h:60
Inline: True
```
```
In fs/timerfd.c (ffffffff8133f1d5)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81340955)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8134f012)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8135eb36)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81361732)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8136c429)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813c12cd)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8144cd41)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff817e126c)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817e191a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e602a)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff8191ec85)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8198dc85)
Location: include/linux/file.h:60
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
</details>
</li>
</ul>

## Differences
