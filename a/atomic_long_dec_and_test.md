# Function: <code>atomic_long_dec_and_test</code>

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
In kernel/acct.c (ffffffff8110bda5)
Location: include/asm-generic/atomic-long.h:140
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff8112bb85)
Location: include/asm-generic/atomic-long.h:140
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811808d0)
Location: include/asm-generic/atomic-long.h:140
Inline: True
```
```
In fs/file_table.c (ffffffff8120e355)
Location: include/asm-generic/atomic-long.h:140
Inline: True
Inline callers:
  - fs/file_table.c:__fput_sync
```
```
In block/blk-ioc.c (ffffffff813bee72)
Location: include/asm-generic/atomic-long.h:140
Inline: True
```
```
In net/unix/garbage.c (ffffffff817c242e)
Location: include/asm-generic/atomic-long.h:140
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
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
In kernel/acct.c (ffffffff81113605)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff81133d75)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff81192b60)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff81234d75)
Location: include/asm-generic/atomic-long.h:196
Inline: True
```
```
In block/blk-ioc.c (ffffffff81402bb2)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In net/unix/garbage.c (ffffffff8182f451)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
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
In kernel/acct.c (ffffffff8111ad15)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff8113daf5)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811a2340)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff81247925)
Location: include/asm-generic/atomic-long.h:196
Inline: True
```
```
In block/blk-ioc.c (ffffffff8141c8e2)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In net/unix/garbage.c (ffffffff81860edd)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
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
In kernel/acct.c (ffffffff8111c935)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff8113f145)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811a9ad0)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff81253155)
Location: include/asm-generic/atomic-long.h:196
Inline: True
```
```
In block/blk-ioc.c (ffffffff8142aae2)
Location: include/asm-generic/atomic-long.h:196
Inline: True
```
```
In net/unix/garbage.c (ffffffff8188562d)
Location: include/asm-generic/atomic-long.h:196
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
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
In kernel/acct.c (ffffffff81128059)
Location: include/asm-generic/atomic-long.h:197
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff8114bf6c)
Location: include/asm-generic/atomic-long.h:197
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811bd324)
Location: include/asm-generic/atomic-long.h:197
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff8127525a)
Location: include/asm-generic/atomic-long.h:197
Inline: True
```
```
In block/blk-ioc.c (ffffffff81455cdb)
Location: include/asm-generic/atomic-long.h:197
Inline: True
```
```
In net/unix/garbage.c (ffffffff819067dd)
Location: include/asm-generic/atomic-long.h:197
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
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
In kernel/acct.c (ffffffff81135ea5)
Location: include/asm-generic/atomic-long.h:214
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff8115a9a5)
Location: include/asm-generic/atomic-long.h:214
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811dd570)
Location: include/asm-generic/atomic-long.h:214
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff8129bae5)
Location: include/asm-generic/atomic-long.h:214
Inline: True
```
```
In block/blk-ioc.c (ffffffff8148905b)
Location: include/asm-generic/atomic-long.h:214
Inline: True
```
```
In net/unix/garbage.c (ffffffff8195d7a8)
Location: include/asm-generic/atomic-long.h:214
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
Location: include/asm-generic/atomic-long.h:214
Inline: True
Inline callers:
  - kernel/acct.c:acct_put
```
```
In kernel/audit_tree.c (ffffffff81167735)
Location: include/asm-generic/atomic-long.h:214
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811ed970)
Location: include/asm-generic/atomic-long.h:214
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812b0de5)
Location: include/asm-generic/atomic-long.h:214
Inline: True
```
```
In fs/notify/mark.c (ffffffff812f9ea6)
Location: include/asm-generic/atomic-long.h:214
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814a2f8b)
Location: include/asm-generic/atomic-long.h:214
Inline: True
```
```
In net/unix/garbage.c (ffffffff819922e8)
Location: include/asm-generic/atomic-long.h:214
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
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81174395)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff812053a0)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812cd765)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (ffffffff8131a5a6)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814d1043)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (ffffffff819fe03a)
Location: include/asm-generic/atomic-long.h:464
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
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81180205)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff81211fe0)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812df185)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (ffffffff8132d3c6)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814ea403)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (ffffffff81a34c2a)
Location: include/asm-generic/atomic-long.h:464
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
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/acct.c:acct_get
```
```
In kernel/audit_tree.c (ffffffff811939f5)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff81242afb)
Location: include/asm-generic/atomic-long.h:465
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
Location: include/asm-generic/atomic-long.h:465
Inline: True
```
```
In fs/notify/mark.c (ffffffff813671e6)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff815493a3)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In net/unix/scm.c (ffffffff81b29a6a)
Location: include/asm-generic/atomic-long.h:465
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
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/acct.c:acct_get
```
```
In kernel/audit_tree.c (ffffffff81190b65)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff8124d24c)
Location: include/asm-generic/atomic-long.h:465
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
Location: include/asm-generic/atomic-long.h:465
Inline: True
```
```
In fs/notify/mark.c (ffffffff81374546)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff815651c3)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In net/unix/scm.c (ffffffff81b3839a)
Location: include/asm-generic/atomic-long.h:465
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
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff81191ac5)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff81251b0c)
Location: include/asm-generic/atomic-long.h:465
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
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - fs/file_table.c:__fput_sync
```
```
In fs/notify/mark.c (ffffffff8137aef6)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In security/landlock/fs.c (ffffffff81539037)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff8156d833)
Location: include/asm-generic/atomic-long.h:465
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In net/unix/scm.c (ffffffff81b2603a)
Location: include/asm-generic/atomic-long.h:465
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
Location: include/linux/atomic/atomic-instrumented.h:1696
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff811ba985)
Location: include/linux/atomic/atomic-instrumented.h:1696
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff8128d32e)
Location: include/linux/atomic/atomic-instrumented.h:1696
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
Location: include/linux/atomic/atomic-instrumented.h:1696
Inline: True
```
```
In fs/notify/mark.c (ffffffff813c8cd3)
Location: include/linux/atomic/atomic-instrumented.h:1696
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff81597877)
Location: include/linux/atomic/atomic-instrumented.h:1696
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff815d1e23)
Location: include/linux/atomic/atomic-instrumented.h:1696
Inline: True
```
```
In net/unix/scm.c (ffffffff81bebc9a)
Location: include/linux/atomic/atomic-instrumented.h:1696
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
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff811edcd5)
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff812e202f)
Location: include/linux/atomic/atomic-instrumented.h:1810
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
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
```
```
In fs/notify/mark.c (ffffffff8144f1b6)
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8163937d)
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff8167dcbd)
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
```
```
In net/unix/scm.c (ffffffff81d8418a)
Location: include/linux/atomic/atomic-instrumented.h:1810
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
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff812342e5)
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff8134a55e)
Location: include/linux/atomic/atomic-instrumented.h:1810
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
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
```
```
In fs/notify/mark.c (ffffffff814dd9e6)
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff816f09dd)
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff8173a8fd)
Location: include/linux/atomic/atomic-instrumented.h:1810
Inline: True
```
```
In net/unix/scm.c (ffffffff81f51a2a)
Location: include/linux/atomic/atomic-instrumented.h:1810
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
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff8124afd5)
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff8137b59e)
Location: include/linux/atomic/atomic-instrumented.h:4500
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
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
```
```
In fs/notify/mark.c (ffffffff815156e0)
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8172ae7a)
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff81776ffd)
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
```
```
In net/unix/scm.c (ffffffff81fb13da)
Location: include/linux/atomic/atomic-instrumented.h:4500
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
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffff81264ed5)
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff813a479e)
Location: include/linux/atomic/atomic-instrumented.h:4500
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
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - fs/file_table.c:__fput_sync
```
```
In fs/notify/mark.c (ffffffff81549aa0)
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In security/landlock/fs.c (ffffffff8176c99a)
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In block/blk-ioc.c (ffffffff817b922d)
Location: include/linux/atomic/atomic-instrumented.h:4500
Inline: True
```
```
In net/unix/scm.c (ffffffff8207eafa)
Location: include/linux/atomic/atomic-instrumented.h:4500
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffff8000101c7f34)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In kernel/audit_tree.c (ffff8000101f550c)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffff80001029c468)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffff80001038571c)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (ffff8000103e93bc)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffff8000105e8858)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (ffff800010cf548c)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (c040e514)
Location: include/asm-generic/atomic-long.h:958
Inline: True
```
```
In kernel/audit_tree.c (c0435698)
Location: include/asm-generic/atomic-long.h:958
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (c04cba50)
Location: include/asm-generic/atomic-long.h:958
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (c056e7c0)
Location: include/asm-generic/atomic-long.h:958
Inline: True
```
```
In fs/notify/mark.c (c05c0ab8)
Location: include/asm-generic/atomic-long.h:958
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (c07951bc)
Location: include/asm-generic/atomic-long.h:958
Inline: True
```
```
In net/unix/scm.c (c0dfbf70)
Location: include/asm-generic/atomic-long.h:958
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (c0000000002301a4)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In kernel/audit_tree.c (c00000000026ab04)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (c00000000034c8fc)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (c00000000047bb54)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (c0000000004f0214)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (c00000000077d4b4)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (c000000000e1b618)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffe0001481d4)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffe0001679b0)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:__put_chunk
```
```
In kernel/events/core.c (ffffffe0001d04c4)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In fs/file_table.c (ffffffe00025861e)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (ffffffe00029dd4e)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffe0004293ae)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (ffffffe000840f6a)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffff81151025)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81178825)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff8120a630)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812d7765)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (ffffffff813259a6)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814e29e3)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (ffffffff819d42ba)
Location: include/asm-generic/atomic-long.h:464
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
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In kernel/audit_tree.c (ffffffff8116b9c5)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff811fd420)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812c83e5)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (ffffffff81316546)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814d3373)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (ffffffff8199107a)
Location: include/asm-generic/atomic-long.h:464
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
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In kernel/audit_tree.c (ffffffff811765f5)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff812083d0)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812d5575)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (ffffffff81323476)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814dea73)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (ffffffff81a3ed3a)
Location: include/asm-generic/atomic-long.h:464
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
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81183ec5)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffffffff81217170)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffffffff812e63c5)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In fs/notify/mark.c (ffffffff81335306)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffff814f78e3)
Location: include/asm-generic/atomic-long.h:464
Inline: True
```
```
In net/unix/scm.c (ffffffff81a4a7fa)
Location: include/asm-generic/atomic-long.h:464
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
</details>
</li>
</ul>

## Differences
