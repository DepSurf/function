# Function: <code>arch_atomic64_dec_and_test</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81135ea5)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff8115a9a5)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811dd570)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff8129bae5)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
```
```
In block/blk-ioc.c (ffffffff8148905b)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
```
```
In net/unix/garbage.c (ffffffff8195d7a8)
Location: arch/x86/include/asm/atomic64_64.h:113
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
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
In kernel/acct.c (ffffffff81141635)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff81167735)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811ed970)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812b0de5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff812f9ea6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814a2f8b)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/garbage.c (ffffffff819922e8)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
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
In kernel/acct.c (ffffffff8114cd35)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81174395)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff812053a0)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812cd765)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff8131a5a6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814d1043)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff819fe03a)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff81158a05)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81180205)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff81211fe0)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812df185)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff8132d3c6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814ea403)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff81a34c2a)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff81169956)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/acct.c:acct_get
```
```
In kernel/audit_tree.c (ffffffff811939f5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff81200b1c)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/events/core.c (ffffffff81242afb)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In fs/file_table.c (ffffffff81315fb5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff813671e6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff815493a3)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In net/unix/scm.c (ffffffff81b29a6a)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff811660e6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/acct.c:acct_get
```
```
In kernel/audit_tree.c (ffffffff81190b65)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff811fffdc)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/events/core.c (ffffffff8124d24c)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In fs/file_table.c (ffffffff81321575)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff81374546)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff815651c3)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In net/unix/scm.c (ffffffff81b3839a)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff81166e3d)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff81191ac5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff8120098c)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/events/core.c (ffffffff81251b0c)
Location: arch/x86/include/asm/atomic64_64.h:116
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
In fs/file_table.c (ffffffff81327765)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/file_table.c:__fput_sync
```
```
In fs/notify/mark.c (ffffffff8137aef6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In security/landlock/fs.c (ffffffff81539037)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff8156d833)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In net/unix/scm.c (ffffffff81b2603a)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff8118c5fd)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff811ba985)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff812326fc)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/events/core.c (ffffffff8128d32e)
Location: arch/x86/include/asm/atomic64_64.h:116
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
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff813c8cd3)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff81597877)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff815d1e23)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff81bebc9a)
Location: arch/x86/include/asm/atomic64_64.h:116
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
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff811edcd5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff81275aac)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/events/core.c (ffffffff812e202f)
Location: arch/x86/include/asm/atomic64_64.h:116
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
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff8144f1b6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8163937d)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff8167dcbd)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff81d8418a)
Location: arch/x86/include/asm/atomic64_64.h:116
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
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff812342e5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff812c73fc)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:__bpf_prog_put
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/events/core.c (ffffffff8134a55e)
Location: arch/x86/include/asm/atomic64_64.h:116
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
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff814dd9e6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff816f09dd)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff8173a8fd)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff81f51a2a)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff81212a87)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff8124afd5)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff812f4989)
Location: arch/x86/include/asm/atomic64_64.h:59
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
Location: arch/x86/include/asm/atomic64_64.h:59
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
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
```
```
In fs/notify/mark.c (ffffffff815156e0)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8172ae7a)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff81776ffd)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
```
```
In net/unix/scm.c (ffffffff81fb13da)
Location: arch/x86/include/asm/atomic64_64.h:59
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
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff81264ed5)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/syscall.c (ffffffff813138c9)
Location: arch/x86/include/asm/atomic64_64.h:59
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
Location: arch/x86/include/asm/atomic64_64.h:59
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
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - fs/file_table.c:__fput_sync
```
```
In fs/notify/mark.c (ffffffff81549aa0)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8176c99a)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff817b922d)
Location: arch/x86/include/asm/atomic64_64.h:59
Inline: True
```
```
In net/unix/scm.c (ffffffff8207eafa)
Location: arch/x86/include/asm/atomic64_64.h:59
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81151025)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81178825)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff8120a630)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812d7765)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff813259a6)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814e29e3)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff819d42ba)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff811442d5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In kernel/audit_tree.c (ffffffff8116b9c5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811fd420)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812c83e5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff81316546)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814d3373)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff8199107a)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff8114eed5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In kernel/audit_tree.c (ffffffff811765f5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff812083d0)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812d5575)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff81323476)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814dea73)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff81a3ed3a)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff8115bcd5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81183ec5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff81217170)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812e63c5)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In fs/notify/mark.c (ffffffff81335306)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814f78e3)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
```
```
In net/unix/scm.c (ffffffff81a4a7fa)
Location: arch/x86/include/asm/atomic64_64.h:116
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
</details>
</li>
</ul>

## Differences
