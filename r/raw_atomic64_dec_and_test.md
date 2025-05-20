# Function: <code>raw_atomic64_dec_and_test</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81212a87)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff8124afd5)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff812f4989)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:__bpf_prog_put
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/events/core.c (ffffffff8137b59e)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In fs/file_table.c (ffffffff814b0f85)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
```
```
In fs/notify/mark.c (ffffffff815156e0)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8172ae7a)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff81776ffd)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
```
```
In net/unix/scm.c (ffffffff81fb13da)
Location: include/linux/atomic/atomic-arch-fallback.h:4374
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff8122a127)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff81264ed5)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff813138c9)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:__bpf_prog_put
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/events/core.c (ffffffff813a479e)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In fs/file_table.c (ffffffff814e2bf5)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
Inline callers:
  - fs/file_table.c:__fput_sync
```
```
In fs/notify/mark.c (ffffffff81549aa0)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8176c99a)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff817b922d)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
```
```
In net/unix/scm.c (ffffffff8207eafa)
Location: include/linux/atomic/atomic-arch-fallback.h:4379
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
