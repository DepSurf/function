# Function: <code>__to_fd</code>

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
In kernel/sys.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8117653b)
Location: include/linux/file.h:49
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff811819e3)
Location: include/linux/file.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/readahead.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In mm/fadvise.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/sync.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/compat.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/file.h:49
Inline: True
```
```
In ipc/mqueue.c (ffffffff8132dfd4)
Location: include/linux/file.h:49
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In net/socket.c (ffffffff816fd407)
Location: include/linux/file.h:49
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
In kernel/sys.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8118506a)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81193835)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/readahead.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In mm/fadvise.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/sync.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/timerfd.c (ffffffff8128091f)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/compat.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In ipc/mqueue.c (ffffffff81362c63)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In net/socket.c (ffffffff81763f37)
Location: include/linux/file.h:50
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
In kernel/sys.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff811925de)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff811a3024)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/readahead.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In mm/fadvise.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/sync.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/timerfd.c (ffffffff8129448f)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/compat.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In ipc/mqueue.c (ffffffff81379443)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In net/socket.c (ffffffff81790f67)
Location: include/linux/file.h:50
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
In kernel/sys.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8119939b)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff8119eb8e)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/events/core.c (ffffffff811aa7c4)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/readahead.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In mm/fadvise.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/sync.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/timerfd.c (ffffffff812a176f)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/file.h:50
Inline: True
```
```
In ipc/mqueue.c (ffffffff8138c1a4)
Location: include/linux/file.h:50
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In net/socket.c (ffffffff817ae887)
Location: include/linux/file.h:50
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
In kernel/sys.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff811a8314)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811aea2e)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/events/core.c (ffffffff811be101)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/readahead.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In mm/fadvise.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/readdir.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/sync.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/utimes.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/statfs.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/timerfd.c (ffffffff812c4a8f)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/compat_ioctl.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/file.h:51
Inline: True
```
```
In ipc/mqueue.c (ffffffff813b1554)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In net/socket.c (ffffffff81826967)
Location: include/linux/file.h:51
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
In kernel/sys.c (ffffffff810a3f40)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8116e650)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811b4bd2)
Location: include/linux/file.h:51
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
In kernel/bpf/verifier.c (ffffffff811bebab)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811c61e5)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811c94d6)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/bpf/sockmap.c (ffffffff811d068a)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sockmap_get_from_fd
```
```
In kernel/events/core.c (ffffffff811de026)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/readahead.c (ffffffff8120053d)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/fadvise.c (ffffffff81244705)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/memcontrol.c (ffffffff812813fa)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8129690d)
Location: include/linux/file.h:51
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
In fs/read_write.c (ffffffff8129793a)
Location: include/linux/file.h:51
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
In fs/stat.c (ffffffff8129f322)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812a144e)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812a7796)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812aee52)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812b0444)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812b1011)
Location: include/linux/file.h:51
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
In fs/select.c (ffffffff812b2950)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff812c53dd)
Location: include/linux/file.h:51
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
In fs/splice.c (ffffffff812d11ee)
Location: include/linux/file.h:51
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
In fs/sync.c (ffffffff812d28cc)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff812d2d33)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812d539a)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e70c6)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e8819)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff812ea8bc)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff812ed2ff)
Location: include/linux/file.h:51
Inline: True
```
```
In fs/timerfd.c (ffffffff812ed8f9)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff812eee26)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81300aca)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff81302bbd)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8130d49e)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8135c6fc)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813e1256)
Location: include/linux/file.h:51
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff8186ffd7)
Location: include/linux/file.h:51
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
In kernel/sys.c (ffffffff810acd10)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8117c120)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811c402e)
Location: include/linux/file.h:53
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
In kernel/bpf/verifier.c (ffffffff811cf86c)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/map_in_map.c (ffffffff811d7cd5)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811dcdd6)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff811ee436)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff81206294)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81212ee1)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81295e2a)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812ab6fd)
Location: include/linux/file.h:53
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
In fs/read_write.c (ffffffff812ac74e)
Location: include/linux/file.h:53
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
In fs/stat.c (ffffffff812b4302)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812b66ee)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812bc83f)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812c3f43)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812c55a4)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812c6211)
Location: include/linux/file.h:53
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
In fs/select.c (ffffffff812c7a60)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/xattr.c (ffffffff812da5dd)
Location: include/linux/file.h:53
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
In fs/splice.c (ffffffff812e642e)
Location: include/linux/file.h:53
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
In fs/sync.c (ffffffff812e7cac)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff812e8113)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812ea6ba)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fbd06)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fdc34)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff81300adc)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8130195f)
Location: include/linux/file.h:53
Inline: True
```
```
In fs/timerfd.c (ffffffff81302429)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff813037b6)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff813164c6)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8131824d)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8132308e)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff81374c00)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff813fbe36)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In net/socket.c (ffffffff81890ba7)
Location: include/linux/file.h:53
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff818f334a)
Location: include/linux/file.h:53
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
In kernel/signal.c (ffffffff810afeba)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b2550)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81188fb0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811d587e)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (ffffffff811d947f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811ec665)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f2410)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81205e76)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff8121d614)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812228f1)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812b1e70)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812c7efd)
Location: include/linux/file.h:55
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
In fs/read_write.c (ffffffff812c8ef5)
Location: include/linux/file.h:55
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
In fs/stat.c (ffffffff812d1072)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812d344d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812d931d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812e0943)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812e2024)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812e2cc1)
Location: include/linux/file.h:55
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
In fs/select.c (ffffffff812e46c7)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812f3128)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff812f8bad)
Location: include/linux/file.h:55
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
In fs/splice.c (ffffffff8130508e)
Location: include/linux/file.h:55
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
In fs/sync.c (ffffffff8130661a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81306a17)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8130912a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8130b98d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c66f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e797)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff81321d7d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81322ed0)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (ffffffff81323994)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81324d40)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff813321fb)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8133dcaf)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8133f8fd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8134aaa0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8139e2ee)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814280f9)
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
In net/socket.c (ffffffff818daab7)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8194581a)
Location: include/linux/file.h:55
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
In kernel/exit.c (ffffffff810a5bd0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b64da)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b8c20)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81194ef0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811e2375)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (ffffffff811e5b7f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811f8dc5)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811feb20)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81213591)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff8122aff4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812303a1)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812c3810)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812d990d)
Location: include/linux/file.h:55
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
In fs/read_write.c (ffffffff812da905)
Location: include/linux/file.h:55
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
In fs/stat.c (ffffffff812e2c02)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812e4fdd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812eae2d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812f23f3)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812f3af4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812f4a31)
Location: include/linux/file.h:55
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
In fs/select.c (ffffffff812f608e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81304ce8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff8130a7dd)
Location: include/linux/file.h:55
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
In fs/splice.c (ffffffff8131811e)
Location: include/linux/file.h:55
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
In fs/sync.c (ffffffff8131969a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81319a77)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8131c19a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8131e99d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f45f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331610)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff813342dd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81335c30)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (ffffffff813366f4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81337ad0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff81345dbb)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8135629f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8135810d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff81362c87)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813b6afc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81441e29)
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
In drivers/vfio/vfio.c (ffffffff817d2154)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817d2875)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d6f13)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff8190cc07)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8197a83a)
Location: include/linux/file.h:55
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
In kernel/exit.c (ffffffff810ad6f8)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810be6c9)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810c0660)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810cdb4b)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
```
In kernel/taskstats.c (ffffffff811aa680)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811fd1d8)
Location: include/linux/file.h:57
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
In kernel/bpf/verifier.c (ffffffff8120563f)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff8121cbc3)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81225ec6)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8123f35d)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff8124c64a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81257db4)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8125d651)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812f9490)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8130f6cd)
Location: include/linux/file.h:57
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
In fs/read_write.c (ffffffff81310e5d)
Location: include/linux/file.h:57
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
In fs/stat.c (ffffffff8131aed6)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff8131c08d)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff81322b6e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8132a61a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8132c00b)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8132d0ec)
Location: include/linux/file.h:57
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
In fs/select.c (ffffffff8132dc8e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8133e8bf)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff813437dd)
Location: include/linux/file.h:57
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
In fs/splice.c (ffffffff81352abe)
Location: include/linux/file.h:57
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
In fs/sync.c (ffffffff813535ed)
Location: include/linux/file.h:57
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
In fs/utimes.c (ffffffff81353a19)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81355ea8)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff813587b6)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8136984f)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136c0dc)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8136e88d)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8136f8c5)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff813707de)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff813718e3)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff813816fb)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_start
```
```
In fs/locks.c (ffffffff8139d0bf)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813a880a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff81402555)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81492a09)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/vfio/vfio.c (ffffffff8189cf2e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff8189d9d5)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a465a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819e1403)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a4fd22)
Location: include/linux/file.h:57
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
In kernel/signal.c (ffffffff810b99c9)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810bccd0)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810c85ab)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811a7c30)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811fc4a8)
Location: include/linux/file.h:58
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
In kernel/bpf/verifier.c (ffffffff8120636d)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff8121fae3)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff8122c926)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8124975d)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81256a8a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81262684)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81267a01)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81305b30)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8131b97d)
Location: include/linux/file.h:58
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
In fs/read_write.c (ffffffff81320c16)
Location: include/linux/file.h:58
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
In fs/stat.c (ffffffff8132662c)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8132e142)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81335b8a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8133768b)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff813388cc)
Location: include/linux/file.h:58
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
In fs/select.c (ffffffff813394dd)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8134a91f)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff8134ff9d)
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
In fs/splice.c (ffffffff8135f39e)
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
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff8135fecd)
Location: include/linux/file.h:58
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
In fs/utimes.c (ffffffff8136027b)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813627e8)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81365136)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff81365e51)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff81366325)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81376a6f)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137999e)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8137bc63)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8137d625)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff8137e54e)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff8137f695)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8138f7cb)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
```
```
In fs/locks.c (ffffffff813aea8f)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813b9b5a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff81414e2d)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814b0309)
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
In security/integrity/ima/ima_main.c (ffffffff815337da)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff818abb5e)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff818ac5f5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b36a5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819e0c53)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a55d32)
Location: include/linux/file.h:58
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
In kernel/signal.c (ffffffff810bb1b9)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810be560)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810ca0cc)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811a8566)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81201bcb)
Location: include/linux/file.h:58
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
In kernel/bpf/verifier.c (ffffffff812082d2)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81223563)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff812316e6)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8124d8e8)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff8125af2a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81267114)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8126c611)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff8130afd1)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81321acd)
Location: include/linux/file.h:58
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
In fs/read_write.c (ffffffff81326d16)
Location: include/linux/file.h:58
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
In fs/stat.c (ffffffff8132c73c)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff81334776)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8133bd1a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8133dcbb)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8133ef35)
Location: include/linux/file.h:58
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
In fs/select.c (ffffffff8133fa8a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8135117b)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff81356a4c)
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
In fs/splice.c (ffffffff81365e8e)
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
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff813669dc)
Location: include/linux/file.h:58
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
In fs/utimes.c (ffffffff81366d1b)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81369288)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8136bb86)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff8136c891)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff8136cd2c)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d43e)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8138056c)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff813823c7)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff813842a5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff813851ce)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81386315)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8139ee0e)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/locks.c (ffffffff813b5dee)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff813c0cb7)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/ext4/ioctl.c (ffffffff8141b19a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814b6159)
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
In security/landlock/syscalls.c (ffffffff81537198)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8153bdda)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff8188eade)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff8188f715)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff8189688d)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff819c6c93)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81a51732)
Location: include/linux/file.h:58
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
In kernel/signal.c (ffffffff810cdac9)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810d02da)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810dce3c)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff811d21c6)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff81233c54)
Location: include/linux/file.h:58
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
In kernel/bpf/verifier.c (ffffffff8123bb97)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff8125b383)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff8126a696)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81288638)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81296d2a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff812a3b54)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812a9331)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff81355851)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8136efad)
Location: include/linux/file.h:58
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
In fs/read_write.c (ffffffff813742d6)
Location: include/linux/file.h:58
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
In fs/stat.c (ffffffff81379eac)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff813820c1)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8138999a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8138b63b)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8138c8c5)
Location: include/linux/file.h:58
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
In fs/select.c (ffffffff8138d422)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8139f53f)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff813a542c)
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
In fs/splice.c (ffffffff813b477e)
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
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff813b552c)
Location: include/linux/file.h:58
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
In fs/utimes.c (ffffffff813b586b)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813b7f88)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff813ba856)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff813bb561)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff813bb9ec)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca05c)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd3c9)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff813cf637)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff813d1545)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff813d244e)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff813d35e5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff813ef0ee)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/locks.c (ffffffff81405aee)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/fhandle.c (ffffffff81410d77)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/quota/quota.c (ffffffff8141ea7e)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff8146e2b5)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8150ea99)
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
In security/landlock/syscalls.c (ffffffff815957b8)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8159aa3a)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In drivers/vfio/vfio.c (ffffffff8192213d)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff81923015)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192a815)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In net/socket.c (ffffffff81a75fe3)
Location: include/linux/file.h:58
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81b0a2f2)
Location: include/linux/file.h:58
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
In kernel/signal.c (ffffffff810e5c60)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810e920a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff810f66c9)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff81206d78)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff812770bc)
Location: include/linux/file.h:56
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
In kernel/bpf/verifier.c (ffffffff812816b2)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff812a4583)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff812b74cc)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff812dd7fc)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff812ece2a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff812fba74)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff813024e1)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff813ce1cb)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff813ed91d)
Location: include/linux/file.h:56
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
In fs/read_write.c (ffffffff813f3269)
Location: include/linux/file.h:56
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
In fs/stat.c (ffffffff813f8e2d)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff81403daf)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff8140aa02)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8140c98a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff8140d196)
Location: include/linux/file.h:56
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
In fs/select.c (ffffffff8140e8af)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81422a29)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff81428a6c)
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
In fs/splice.c (ffffffff81439b69)
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
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff8143a7cc)
Location: include/linux/file.h:56
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
In fs/utimes.c (ffffffff8143ab9b)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8143d7c8)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8144059f)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff81441682)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff81441c4a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8145269c)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814569e0)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff81458410)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8145a7e4)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff8145bfee)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff8145cbd8)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8147a7cc)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff8148671c)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/quota/quota.c (ffffffff814967fe)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff814eea91)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8159fea1)
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
In security/landlock/syscalls.c (ffffffff81637a58)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8163f7eb)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff816d8bca)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_get_sq_data
```
```
In drivers/vfio/vfio.c (ffffffff81a768fd)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/vfio/virqfd.c (ffffffff81a78a0d)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/socket.c (ffffffff81be9083)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81c9091f)
Location: include/linux/file.h:56
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
In kernel/signal.c (ffffffff81106820)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff8110a0ba)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff81118d69)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/taskstats.c (ffffffff8124f0d8)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff812ccfe7)
Location: include/linux/file.h:56
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
In kernel/bpf/verifier.c (ffffffff812d9422)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81302223)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81318afc)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81345bb3)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff8135719a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/fadvise.c (ffffffff81365bf4)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8136cca1)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff814536fb)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8147603d)
Location: include/linux/file.h:56
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
In fs/read_write.c (ffffffff8147bf76)
Location: include/linux/file.h:56
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
In fs/stat.c (ffffffff8148245d)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff8148e21b)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff81495272)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff8149741a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff81497c46)
Location: include/linux/file.h:56
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
In fs/select.c (ffffffff81499430)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff814af0b9)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff814b60cc)
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
In fs/splice.c (ffffffff814c7ea9)
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
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffff814c8c5c)
Location: include/linux/file.h:56
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
In fs/utimes.c (ffffffff814c905b)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff814cc098)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff814cf46f)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff814d0622)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff814d0f2a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e122c)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5a7d)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff814e7d50)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff814e9d34)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff814eb6be)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff814ec318)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff8150d25a)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff8151a06c)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/quota/quota.c (ffffffff8152a77e)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff81588a05)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff81649771)
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
In security/landlock/syscalls.c (ffffffff816eee28)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff816f758d)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff8178c7dc)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In io_uring/sqpoll.c (ffffffff8179ae73)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/cancel.c (ffffffff8179eab2)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In net/socket.c (ffffffff81d95803)
Location: include/linux/file.h:56
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff81e4bd8f)
Location: include/linux/file.h:56
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096604)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
```
```
In kernel/signal.c (ffffffff81112b10)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff8111638a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff81126229)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/nsproxy.c (ffffffff81131be8)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
```
```
In kernel/module/main.c (ffffffff811e0818)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/module/main.c:__ia32_sys_finit_module
  - kernel/module/main.c:__x64_sys_finit_module
```
```
In kernel/cgroup/cgroup.c (ffffffff812264d8)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
```
```
In kernel/taskstats.c (ffffffff81266488)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff812ee742)
Location: include/linux/file.h:57
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
In kernel/bpf/verifier.c (ffffffff813033a2)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81330db3)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff81336118)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
```
```
In kernel/bpf/btf.c (ffffffff8134891c)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81376c66)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff81388a1a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/filemap.c (ffffffff8138cd59)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
```
```
In mm/fadvise.c (ffffffff813980d4)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8139ef01)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff8148950b)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814aa95d)
Location: include/linux/file.h:57
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
In fs/read_write.c (ffffffff814b0b76)
Location: include/linux/file.h:57
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
In fs/stat.c (ffffffff814b706d)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff814c395e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff814ca2c2)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff814cc47a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff814ccbb6)
Location: include/linux/file.h:57
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
In fs/select.c (ffffffff814ce4e0)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff814e4019)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff814ea8fc)
Location: include/linux/file.h:57
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
In fs/splice.c (ffffffff814fe0d9)
Location: include/linux/file.h:57
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
In fs/sync.c (ffffffff814fee9c)
Location: include/linux/file.h:57
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
In fs/utimes.c (ffffffff814ff29b)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff815022d8)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81505688)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff815068d2)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff81507a5a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81517acc)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151c4f5)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff8151dffd)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81520ad4)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff8152245e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff815234d8)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff815449db)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff81551a02)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/quota.c (ffffffff81562b5e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff815bf84a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fuse/dev.c (ffffffff81651890)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/mqueue.c (ffffffff81681cd1)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff817292b8)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8173180b)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/io_uring.c (ffffffff817cda90)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In io_uring/sqpoll.c (ffffffff817dbf22)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/cancel.c (ffffffff817dfca2)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In net/socket.c (ffffffff81e03e43)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/net_namespace.c (ffffffff81e23898)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
```
In net/core/sock_map.c (ffffffff81ea748f)
Location: include/linux/file.h:57
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109db74)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute
```
```
In kernel/signal.c (ffffffff8111c500)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff8111fd7a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/pid.c (ffffffff81130829)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
  - kernel/pid.c:pidfd_get_pid
```
```
In kernel/nsproxy.c (ffffffff8113ca18)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/nsproxy.c:__do_sys_setns
```
```
In kernel/module/main.c (ffffffff811f6548)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/module/main.c:__ia32_sys_finit_module
  - kernel/module/main.c:__x64_sys_finit_module
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e168)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
```
```
In kernel/taskstats.c (ffffffff81280378)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff8130d502)
Location: include/linux/file.h:57
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
In kernel/bpf/verifier.c (ffffffff81322e72)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/map_in_map.c (ffffffff81355313)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8135a778)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
```
```
In kernel/bpf/btf.c (ffffffff8136f04c)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8139fef6)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/watch_queue.c (ffffffff813b247a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
```
```
In mm/filemap.c (ffffffff813b6869)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
```
```
In mm/fadvise.c (ffffffff813c1f04)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff813c8b61)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff814b896a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814dbdfd)
Location: include/linux/file.h:57
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
In fs/read_write.c (ffffffff814e2336)
Location: include/linux/file.h:57
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
In fs/stat.c (ffffffff814e93ed)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstat
```
```
In fs/namei.c (ffffffff814f5e2e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff814fcb92)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff814fed3a)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff814ff7d6)
Location: include/linux/file.h:57
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
In fs/select.c (ffffffff81500e20)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff81517d49)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_fsmount
```
```
In fs/xattr.c (ffffffff8151e79c)
Location: include/linux/file.h:57
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
In fs/splice.c (ffffffff81532c55)
Location: include/linux/file.h:57
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
In fs/sync.c (ffffffff81533acc)
Location: include/linux/file.h:57
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
In fs/utimes.c (ffffffff81533ecb)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81536f28)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff8153a458)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
```
```
In fs/kernel_read_file.c (ffffffff8153b5f2)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
```
```
In fs/remap_range.c (ffffffff8153c1dd)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154beac)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550a3e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/eventpoll.c (ffffffff815525dd)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/signalfd.c (ffffffff815550e4)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff81556a7e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/eventfd.c (ffffffff81557c08)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/locks.c (ffffffff81579ecb)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/locks.c:__do_sys_flock
```
```
In fs/fhandle.c (ffffffff81587935)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fhandle.c:handle_to_path
```
```
In fs/quota/quota.c (ffffffff8159924e)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_fd
  - fs/quota/quota.c:__x64_sys_quotactl_fd
```
```
In fs/ext4/ioctl.c (ffffffff815f85f0)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fuse/dev.c (ffffffff8168aea0)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/mqueue.c (ffffffff816be0db)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/landlock/syscalls.c (ffffffff8176a688)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - security/landlock/syscalls.c:add_rule_path_beneath
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/integrity/ima/ima_main.c (ffffffff8177222b)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
```
In io_uring/sqpoll.c (ffffffff818202a4)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1127)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
```
```
In net/socket.c (ffffffff81ec0873)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/net_namespace.c (ffffffff81ee17f8)
Location: include/linux/file.h:57
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_fd
```
```
In net/core/sock_map.c (ffffffff81f69f3f)
Location: include/linux/file.h:57
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
In virt/kvm/eventfd.c (ffff8000100c1170)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In virt/kvm/vfio.c (ffff8000100c21ac)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
```
```
In kernel/exit.c (ffff8000100fbc7c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffff800010112854)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffff800010115024)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffff80001020d3ec)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffff800010265044)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (ffff800010268ee0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffff80001027e354)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffff800010285bac)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffff80001029d6bc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffff8000102b9310)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffff8000102bfc30)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffff800010364eb0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffff80001037ec54)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__arm64_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffff80001037ff2c)
Location: include/linux/file.h:55
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
In fs/stat.c (ffff80001038a5e8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffff80001038cac4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffff8000103944d4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffff80001039c5e8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__arm64_sys_fcntl
```
```
In fs/ioctl.c (ffff80001039f0c4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffff80001039fb9c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:__arm64_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__arm64_sys_getdents
```
```
In fs/select.c (ffff8000103a31bc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffff8000103b8598)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
```
```
In fs/xattr.c (ffff8000103be25c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:__arm64_sys_flistxattr
  - fs/xattr.c:__arm64_sys_fgetxattr
  - fs/xattr.c:__arm64_sys_fsetxattr
```
```
In fs/splice.c (ffff8000103cde84)
Location: include/linux/file.h:55
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
In fs/sync.c (ffff8000103d0698)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__arm64_sys_syncfs
```
```
In fs/utimes.c (ffff8000103d0a88)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffff8000103d3b3c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffff8000103d6b94)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__arm64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec65c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee9f0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffff8000103f2b2c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
```
In fs/signalfd.c (ffff8000103f35e4)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (ffff8000103f4424)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffff8000103f5d30)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffff800010403a0c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
```
In fs/locks.c (ffff800010418ddc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__arm64_sys_flock
```
```
In fs/compat_ioctl.c (ffff80001041d0d8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
```
In fs/fhandle.c (ffff8000104294e8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffff80001048c364)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffff80001052a888)
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
In net/socket.c (ffff800010ba1b28)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffff800010c21bc4)
Location: include/linux/file.h:55
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
In kernel/exit.c (c0359c6c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (c03697c4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (c036ae74)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (c044bd7c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (c04971b4)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (c049b1d8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (c04afab8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (c04b6170)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (c04cced0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (c04e5aec)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (c04eb708)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (c0557df4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (c0569590)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (c056abe8)
Location: include/linux/file.h:55
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
In fs/stat.c (c05727c0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (c05746e4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (c0578a78)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (c05822e8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (c0583f94)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (c058490c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
```
```
In fs/select.c (c0585b08)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (c059809c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (c059c2b4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (c05aafd4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (c05aba3c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (c05abdc4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (c05adebc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (c05b0b5c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (c05c3a74)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (c05c5a08)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/eventpoll.c (c05c6474)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
```
In fs/signalfd.c (c05c89ec)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (c05c93ac)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (c05cabe8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (c05d7698)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (c05e538c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fhandle.c (c05f2288)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/ext4/ioctl.c (c064daf8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (c06e4ebc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In sound/core/pcm_native.c (c0c95b0c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
```
```
In net/socket.c (c0cc3b78)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (c0d391c4)
Location: include/linux/file.h:55
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
In kernel/exit.c (c0000000001432d0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (c00000000015a244)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (c00000000015cf58)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (c00000000028b204)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (c000000000309c38)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (c00000000030eb1c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (c00000000032817c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (c000000000330a6c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (c00000000034e20c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (c000000000371648)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (c000000000378d10)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (c00000000045335c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (c00000000047497c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (c000000000475f60)
Location: include/linux/file.h:55
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
In fs/stat.c (c000000000481850)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (c000000000484b40)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (c00000000048a600)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (c000000000497390)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (c000000000499724)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (c000000000499e24)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/readdir.c:__se_compat_sys_getdents
  - fs/readdir.c:__se_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:__se_sys_old_readdir
```
```
In fs/select.c (c00000000049cf5c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (c0000000004b54d8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (c0000000004bcdc4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (c0000000004d0ffc)
Location: include/linux/file.h:55
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
In fs/sync.c (c0000000004d2f08)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (c0000000004d3454)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (c0000000004d65a8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (c0000000004daf60)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3908)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f7228)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (c0000000004f86ac)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
```
In fs/signalfd.c (c0000000004fb4fc)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (c0000000004fc220)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (c0000000004fe05c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (c000000000510754)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (c000000000527f0c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/compat_ioctl.c (c00000000052b0fc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
```
```
In fs/fhandle.c (c0000000005399f4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (c0000000005b2ca0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (c000000000675514)
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
In drivers/vfio/vfio.c (c000000000aaf45c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (c000000000ab1bd8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab618c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (c000000000c7628c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (c000000000d141d0)
Location: include/linux/file.h:55
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
In kernel/exit.c (ffffffe0000c56c8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffe0000d175e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffe0000d207c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffe00016e4e8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffe0001a0a3e)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (ffffffe0001a3dfc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffe0001b54c8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffe0001bae7e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffe0001cb7c6)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffe0001dcecc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffe0001e1bea)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffe0002449c4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffe0002548b0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffe00025584e)
Location: include/linux/file.h:55
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
In fs/stat.c (ffffffe00025c526)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffe00025e054)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffe000263056)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffe000268a44)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (ffffffe000269f98)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffe00026a58e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
```
```
In fs/select.c (ffffffe00026b1f8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffe00027c7f6)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
```
```
In fs/xattr.c (ffffffe00027fdf0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/splice.c (ffffffe00028bffc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__se_sys_splice
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/sync.c (ffffffe00028c8ec)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__se_sys_syncfs
```
```
In fs/utimes.c (ffffffe00028cc34)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffe00028e39a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffe000290aa2)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0ca6)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a290c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/eventpoll.c (ffffffe0002a3258)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffe0002a4fc8)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (ffffffe0002a5666)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffe0002a668e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffe0002b10d6)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/locks.c (ffffffe0002bfb3e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
```
```
In fs/fhandle.c (ffffffe0002c74e8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/ext4/ioctl.c (ffffffe000312518)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffe00038ce38)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
```
In net/socket.c (ffffffe000739c16)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffe00079a998)
Location: include/linux/file.h:55
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
In kernel/exit.c (ffffffff8109f4f0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b084a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b2f90)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8118d510)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811da995)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (ffffffff811de19f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811f13e5)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f7140)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff8120bbe1)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff81223644)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff812289f1)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812bbdf0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812d1eed)
Location: include/linux/file.h:55
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
In fs/read_write.c (ffffffff812d2ee5)
Location: include/linux/file.h:55
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
In fs/stat.c (ffffffff812db1e2)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812dd5bd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812e340d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812ea9d3)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812ec0d4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812ed011)
Location: include/linux/file.h:55
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
In fs/select.c (ffffffff812ee66e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812fd2c8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81302dbd)
Location: include/linux/file.h:55
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
In fs/splice.c (ffffffff813106fe)
Location: include/linux/file.h:55
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
In fs/sync.c (ffffffff81311c7a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81312057)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8131477a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81316f7d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327a3f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329bf0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8132c8bd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8132e210)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (ffffffff8132ecd4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff813300b0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8133e39b)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8134e87f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff813506ed)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8135b267)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813af0dc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8143a409)
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
In net/socket.c (ffffffff818acc07)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8191a6aa)
Location: include/linux/file.h:55
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
In kernel/exit.c (ffffffff8108df20)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff8109f16a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810a18c0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81180630)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811cd755)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (ffffffff811d0f5f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811e4135)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811e9e90)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff811fe9b1)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff812167f4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff8121bb31)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812acf50)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812c2b6d)
Location: include/linux/file.h:55
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
In fs/read_write.c (ffffffff812c3b65)
Location: include/linux/file.h:55
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
In fs/stat.c (ffffffff812cbe62)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812ce23d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812d404d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812db613)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812dcd04)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812ddc41)
Location: include/linux/file.h:55
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
In fs/select.c (ffffffff812df29e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812edee8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff812f39dd)
Location: include/linux/file.h:55
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
In fs/splice.c (ffffffff8130130e)
Location: include/linux/file.h:55
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
In fs/sync.c (ffffffff8130288a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81302c67)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8130538a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81307b6d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813185df)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a790)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8131c18d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8131ee70)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (ffffffff8131f914)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81320cd0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8132f05b)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8133f55f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff813413cd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8134bf07)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff8139fb6c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8142ae79)
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
In drivers/vfio/vfio.c (ffffffff8177c204)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff8177c925)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780fc3)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff81866b57)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff818d445a)
Location: include/linux/file.h:55
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
In kernel/exit.c (ffffffff8109f4a0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810afdaa)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810b24f0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff8118b2e0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811d8765)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (ffffffff811dbf6f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811ef1b5)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff811f4f10)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81209981)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff812213e4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81226791)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812b9c00)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812cfcfd)
Location: include/linux/file.h:55
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
In fs/read_write.c (ffffffff812d0cf5)
Location: include/linux/file.h:55
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
In fs/stat.c (ffffffff812d8ff2)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812db3cd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812e121d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812e87e3)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812e9ee4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812eae21)
Location: include/linux/file.h:55
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
In fs/select.c (ffffffff812ec47e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff812fb0b8)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81300bad)
Location: include/linux/file.h:55
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
In fs/splice.c (ffffffff8130e4ee)
Location: include/linux/file.h:55
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
In fs/sync.c (ffffffff8130fa6a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff8130fe47)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8131256a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff81314a4d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132550f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813276c0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8132a38d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8132bce0)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (ffffffff8132c7a4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff8132db80)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8133be6b)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8134c34f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8134e1bd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff81358d37)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813ac93c)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff814365a9)
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
In drivers/vfio/vfio.c (ffffffff817c6fd4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817c76f5)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cbd93)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff818fdc07)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8196b83a)
Location: include/linux/file.h:55
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
In kernel/exit.c (ffffffff810a7400)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/signal.c (ffffffff810b807a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
```
```
In kernel/sys.c (ffffffff810baaf0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/taskstats.c (ffffffff81198c50)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In kernel/bpf/syscall.c (ffffffff811e6aec)
Location: include/linux/file.h:55
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
In kernel/bpf/verifier.c (ffffffff811ea37f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/map_in_map.c (ffffffff811fd685)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
```
In kernel/bpf/btf.c (ffffffff81203430)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/events/core.c (ffffffff81218721)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_perf_ioctl
```
```
In mm/fadvise.c (ffffffff812305a4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/readahead.c (ffffffff81235ac1)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/memcontrol.c (ffffffff812ca290)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff812e0b0d)
Location: include/linux/file.h:55
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
In fs/read_write.c (ffffffff812e1b25)
Location: include/linux/file.h:55
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
In fs/stat.c (ffffffff812e9f02)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx_fd
```
```
In fs/exec.c (ffffffff812ec34d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_fd
```
```
In fs/namei.c (ffffffff812f0246)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_init
```
```
In fs/fcntl.c (ffffffff812f97b3)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
```
In fs/ioctl.c (ffffffff812faed4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/readdir.c (ffffffff812fbe11)
Location: include/linux/file.h:55
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
In fs/select.c (ffffffff812fd47e)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/namespace.c (ffffffff8130c708)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
```
In fs/xattr.c (ffffffff81311eed)
Location: include/linux/file.h:55
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
In fs/splice.c (ffffffff8131fcee)
Location: include/linux/file.h:55
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
In fs/sync.c (ffffffff8132126a)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:do_fsync
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/utimes.c (ffffffff81321647)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81323daa)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/statfs.c:fd_statfs
```
```
In fs/fsopen.c (ffffffff813265bd)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8133795f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339ae0)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/eventpoll.c (ffffffff8133ae5d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/signalfd.c (ffffffff8133e990)
Location: include/linux/file.h:55
Inline: True
```
```
In fs/timerfd.c (ffffffff8133f1e4)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_fget
```
```
In fs/eventfd.c (ffffffff81340960)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/io_uring.c (ffffffff8134f01b)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
```
In fs/locks.c (ffffffff8135eb3f)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
```
In fs/compat_ioctl.c (ffffffff8136173d)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
```
In fs/fhandle.c (ffffffff8136c437)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/ext4/ioctl.c (ffffffff813c12dc)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In ipc/mqueue.c (ffffffff8144cd49)
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
In drivers/vfio/vfio.c (ffffffff817e1274)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/vfio/virqfd.c (ffffffff817e1925)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6033)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In net/socket.c (ffffffff8191ec97)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
```
```
In net/core/sock_map.c (ffffffff8198dcaa)
Location: include/linux/file.h:55
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
</details>
</li>
</ul>

## Differences
