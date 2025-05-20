# Function: <code>__wake_up_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __wake_up_locked(wait_queue_head_t *q, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c33e0)
Location: kernel/sched/wait.c:103
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete
  - kernel/sched/completion.c:complete_all
  - fs/fs_pin.c:pin_remove
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_scan_ready_list
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/timerfd.c:timerfd_triggered
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/fuse/dev.c:queue_request
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
```
**Symbols:**

```
ffffffff810c33e0-ffffffff810c33f5: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __wake_up_locked(wait_queue_head_t *q, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6d60)
Location: kernel/sched/wait.c:103
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - fs/fs_pin.c:pin_remove
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
```
**Symbols:**

```
ffffffff810c6d60-ffffffff810c6d75: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __wake_up_locked(wait_queue_head_t *q, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccd40)
Location: kernel/sched/wait.c:103
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - fs/fs_pin.c:pin_remove
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
```
**Symbols:**

```
ffffffff810ccd40-ffffffff810ccd55: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9610)
Location: kernel/sched/wait.c:105
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - fs/fs_pin.c:pin_remove
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
```
**Symbols:**

```
ffffffff810c9610-ffffffff810c9625: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0e30)
Location: kernel/sched/wait.c:156
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - fs/fs_pin.c:pin_remove
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
```
**Symbols:**

```
ffffffff810d0e30-ffffffff810d0e48: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9380)
Location: kernel/sched/wait.c:150
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - fs/fs_pin.c:pin_remove
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
```
**Symbols:**

```
ffffffff810d9380-ffffffff810d9398: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2e80)
Location: kernel/sched/wait.c:152
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - fs/fs_pin.c:pin_remove
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
```
**Symbols:**

```
ffffffff810e2e80-ffffffff810e2e98: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9a80)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
```
**Symbols:**

```
ffffffff810e9a80-ffffffff810e9a98: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5450)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff810f5450-ffffffff810f5468: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810feb70)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff810feb70-ffffffff810feb88: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd4f0)
Location: kernel/sched/wait.c:164
Inline: False
Direct callers:
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff810fd4f0-ffffffff810fd508: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff8b0)
Location: kernel/sched/wait.c:164
Inline: False
Direct callers:
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff810ff8b0-ffffffff810ff8c8: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111b9a0)
Location: kernel/sched/wait.c:164
Inline: False
Direct callers:
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff8111b9a0-ffffffff8111b9b8: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113bcd0)
Location: kernel/sched/wait.c:163
Inline: False
Direct callers:
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff8113bcd0-ffffffff8113bcfc: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166790)
Location: kernel/sched/wait.c:167
Inline: False
Direct callers:
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff81166790-ffffffff811667bc: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176c00)
Location: kernel/sched/wait.c:167
Inline: False
Direct callers:
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff81176c00-ffffffff81176c2c: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184c30)
Location: kernel/sched/wait.c:139
Inline: False
Direct callers:
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff81184c30-ffffffff81184c56: __wake_up_locked (STB_GLOBAL)
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
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010157fa0)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffff800010157fa0-ffff800010157ff0: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5ad0)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
c03a5ad0-c03a5b00: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001acb20)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
c0000000001acb20-c0000000001acb40: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fe9f0)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffe0000fe9f0-ffffffe0000fea30: __wake_up_locked (STB_GLOBAL)
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
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee850)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff810ee850-ffffffff810ee868: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de8e0)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff810de8e0-ffffffff810de8f8: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb980)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff810eb980-ffffffff810eb998: __wake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wake_up_locked(struct wait_queue_head *wq_head, unsigned int mode, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f69e0)
Location: kernel/sched/wait.c:149
Inline: False
Direct callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/rcu/sync.c:rcu_sync_func
  - fs/fs_pin.c:pin_remove
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff810f69e0-ffffffff810f69f8: __wake_up_locked (STB_GLOBAL)
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
