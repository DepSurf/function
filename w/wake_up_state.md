# Function: <code>wake_up_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ac7d0)
Location: kernel/sched/core.c:2071
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:prepare_signal
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/fence.c:fence_default_wait_cb
```
**Symbols:**

```
ffffffff810ac7d0-ffffffff810ac7e2: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af0f0)
Location: kernel/sched/core.c:2160
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/sched/swait.c:swake_up_all
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/fence.c:fence_default_wait_cb
```
**Symbols:**

```
ffffffff810af0f0-ffffffff810af102: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5230)
Location: kernel/sched/core.c:2170
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810b5230-ffffffff810b5242: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b14b0)
Location: kernel/sched/core.c:2137
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810b14b0-ffffffff810b14c2: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b88e0)
Location: kernel/sched/core.c:2156
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810b88e0-ffffffff810b88f2: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c03e0)
Location: kernel/sched/core.c:2152
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810c03e0-ffffffff810c03f2: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c9750)
Location: kernel/sched/core.c:2146
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810c9750-ffffffff810c9762: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1380)
Location: kernel/sched/core.c:2552
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810d1380-ffffffff810d1392: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810db330)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810db330-ffffffff810db342: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e41b0)
Location: kernel/sched/core.c:2828
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810e41b0-ffffffff810e41c2: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1bf0)
Location: kernel/sched/core.c:3537
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - mm/filemap.c:wake_page_function
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810e1bf0-ffffffff810e1c02: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3a00)
Location: kernel/sched/core.c:3558
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - mm/filemap.c:wake_page_function
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810e3a00-ffffffff810e3a12: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fa660)
Location: kernel/sched/core.c:4173
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - mm/filemap.c:wake_page_function
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810fa660-ffffffff810fa672: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81116b90)
Location: kernel/sched/core.c:4292
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/build_utility.c:swake_up_all
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/filemap.c:wake_page_function
  - fs/userfaultfd.c:userfaultfd_wake_function
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff81116b90-ffffffff81116bac: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113e170)
Location: kernel/sched/core.c:4406
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/build_utility.c:swake_up_all
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/filemap.c:wake_page_function
  - fs/userfaultfd.c:userfaultfd_wake_function
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff8113e170-ffffffff8113e18c: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81151260)
Location: kernel/sched/core.c:4483
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/build_utility.c:swake_up_all
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/filemap.c:wake_page_function
  - fs/userfaultfd.c:userfaultfd_wake_function
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff81151260-ffffffff8115127c: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115d0f0)
Location: kernel/sched/core.c:4505
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/build_utility.c:swake_up_all
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/filemap.c:wake_page_function
  - fs/userfaultfd.c:userfaultfd_wake_function
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff8115d0f0-ffffffff8115d10c: wake_up_state (STB_GLOBAL)
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
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013aff8)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffff80001013aff8-ffff80001013b030: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038a9b8)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
c038a9b8-c038a9d8: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000188c40)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
c000000000188c40-c000000000188c58: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ea69e)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffe0000ea69e-ffffffe0000ea6d2: wake_up_state (STB_GLOBAL)
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
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d57e0)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810d57e0-ffffffff810d57f2: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3e30)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810c3e30-ffffffff810c3e42: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2620)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810d2620-ffffffff810d2632: wake_up_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wake_up_state(struct task_struct *p, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd0d0)
Location: kernel/sched/core.c:2672
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:signal_wake_up_state
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/swait.c:swake_up_all
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/freezer.c:freeze_task
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb
```
**Symbols:**

```
ffffffff810dd0d0-ffffffff810dd0e2: wake_up_state (STB_GLOBAL)
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
