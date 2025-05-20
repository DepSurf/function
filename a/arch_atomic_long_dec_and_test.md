# Function: <code>arch_atomic_long_dec_and_test</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8118c5fd)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff811ba985)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff8128d32e)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In fs/file_table.c (ffffffff81374bb5)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
```
```
In fs/notify/mark.c (ffffffff813c8cd3)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff81597877)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff815d1e23)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
```
```
In net/unix/scm.c (ffffffff81bebc9a)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff811bba77)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff811edcd5)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff812e202f)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In fs/file_table.c (ffffffff813f3645)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
```
```
In fs/notify/mark.c (ffffffff8144f1b6)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8163937d)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff8167dcbd)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
```
```
In net/unix/scm.c (ffffffff81d8418a)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff811fd907)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff812342e5)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff8134a55e)
Location: include/linux/atomic/atomic-long.h:465
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
In fs/file_table.c (ffffffff8147c405)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
```
```
In fs/notify/mark.c (ffffffff814dd9e6)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff816f09dd)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff8173a8fd)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
```
```
In net/unix/scm.c (ffffffff81f51a2a)
Location: include/linux/atomic/atomic-long.h:465
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
