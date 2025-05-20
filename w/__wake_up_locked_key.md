# Function: <code>__wake_up_locked_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_locked_key(wait_queue_head_t *q, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3400)
Location: kernel/sched/wait.c:109
Inline: True
Inline callers:
  - kernel/sched/wait.c:abort_exclusive_wait
Direct callers:
  - fs/eventfd.c:eventfd_signal
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810c3400-ffffffff810c341a: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_locked_key(wait_queue_head_t *q, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6f90)
Location: kernel/sched/wait.c:109
Inline: True
Inline callers:
  - kernel/sched/wait.c:abort_exclusive_wait
Direct callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810c6d80-ffffffff810c6d9a: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __wake_up_locked_key(wait_queue_head_t *q, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccd60)
Location: kernel/sched/wait.c:109
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810ccd60-ffffffff810ccd7a: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9630)
Location: kernel/sched/wait.c:111
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810c9630-ffffffff810c964a: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0e50)
Location: kernel/sched/wait.c:162
Inline: False
Direct callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810d0e50-ffffffff810d0e6d: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d93a0)
Location: kernel/sched/wait.c:156
Inline: False
Direct callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810d93a0-ffffffff810d93bd: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2ea0)
Location: kernel/sched/wait.c:158
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810e2ea0-ffffffff810e2ebd: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9aa0)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810e9aa0-ffffffff810e9abd: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5470)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810f5470-ffffffff810f548d: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810feb90)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_alarmproc
  - fs/timerfd.c:timerfd_tmrproc
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff810feb90-ffffffff810febad: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd510)
Location: kernel/sched/wait.c:170
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_alarmproc
  - fs/timerfd.c:timerfd_tmrproc
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff810fd510-ffffffff810fd52d: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff8d0)
Location: kernel/sched/wait.c:170
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_alarmproc
  - fs/timerfd.c:timerfd_tmrproc
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff810ff8d0-ffffffff810ff8ed: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111b9c0)
Location: kernel/sched/wait.c:170
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_alarmproc
  - fs/timerfd.c:timerfd_tmrproc
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff8111b9c0-ffffffff8111b9dd: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113bd00)
Location: kernel/sched/wait.c:169
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_alarmproc
  - fs/timerfd.c:timerfd_tmrproc
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff8113bd00-ffffffff8113bd31: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811667d0)
Location: kernel/sched/wait.c:173
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_alarmproc
  - fs/timerfd.c:timerfd_tmrproc
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal_mask
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff811667d0-ffffffff81166801: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176c40)
Location: kernel/sched/wait.c:173
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_alarmproc
  - fs/timerfd.c:timerfd_tmrproc
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal_mask
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff81176c40-ffffffff81176c71: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184c70)
Location: kernel/sched/wait.c:145
Inline: False
Direct callers:
  - mm/filemap.c:folio_wake_bit
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_alarmproc
  - fs/timerfd.c:timerfd_tmrproc
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal_mask
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff81184c70-ffffffff81184c9b: __wake_up_locked_key (STB_GLOBAL)
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
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010157ff0)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffff800010157ff0-ffff800010158040: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5b00)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
c03a5b00-c03a5b30: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001acb40)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
c0000000001acb40-c0000000001acb64: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fea30)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffe0000fea30-ffffffe0000fea70: __wake_up_locked_key (STB_GLOBAL)
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
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee870)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810ee870-ffffffff810ee88d: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de900)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810de900-ffffffff810de91d: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb9a0)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810eb9a0-ffffffff810eb9bd: __wake_up_locked_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6a00)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_release
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
**Symbols:**

```
ffffffff810f6a00-ffffffff810f6a1d: __wake_up_locked_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_head *wq_head</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t *q</code>
</li>
</ul>
</details>
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
