# Function: <code>kthread_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0bc0)
Location: kernel/kthread.c:135
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_waking_up
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:set_worker_desc
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810a0bc0-ffffffff810a0bd6: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a42b0)
Location: kernel/kthread.c:135
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_waking_up
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810a42b0-ffffffff810a42c6: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9ae0)
Location: kernel/kthread.c:144
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_waking_up
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810a9ae0-ffffffff810a9b20: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6740)
Location: kernel/kthread.c:147
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_waking_up
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810a6740-ffffffff810a676b: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810aceb0)
Location: kernel/kthread.c:155
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_waking_up
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810aceb0-ffffffff810aceda: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3c20)
Location: kernel/kthread.c:154
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_waking_up
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810b3c20-ffffffff810b3c4a: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bcd70)
Location: kernel/kthread.c:154
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_waking_up
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810bcd70-ffffffff810bcd9a: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810c33a2-ffffffff810c33b5: kthread_data.cold (STB_LOCAL)
ffffffff810c2c40-ffffffff810c2c65: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9210)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810c9210-ffffffff810c923b: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d06a0)
Location: kernel/kthread.c:184
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
  - fs/io-wq.c:io_wq_worker_sleeping
  - fs/io-wq.c:io_wq_worker_running
```
**Symbols:**

```
ffffffff810d06a0-ffffffff810d06cb: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb0c0)
Location: kernel/kthread.c:185
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
  - fs/io-wq.c:io_wq_worker_sleeping
  - fs/io-wq.c:io_wq_worker_running
```
**Symbols:**

```
ffffffff810cb0c0-ffffffff810cb0eb: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cca30)
Location: kernel/kthread.c:211
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810cca30-ffffffff810cca5b: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df680)
Location: kernel/kthread.c:211
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810df680-ffffffff810df6ab: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f96e0)
Location: kernel/kthread.c:232
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810f96e0-ffffffff810f9717: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c370)
Location: kernel/kthread.c:232
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff8111c370-ffffffff8111c3a7: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811295c0)
Location: kernel/kthread.c:243
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_tick
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff811295c0-ffffffff811295f7: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81133c00)
Location: kernel/kthread.c:242
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:delayed_work_timer_fn
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_tick
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff81133c00-ffffffff81133c37: kthread_data (STB_GLOBAL)
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
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128e40)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffff800010128e40-ffff800010128e8c: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b3e4)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
c037b3e4-c037b42c: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000173650)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
c000000000173650-c000000000173674: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dfd68)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffe0000dfd68-ffffffe0000dfdaa: kthread_data (STB_GLOBAL)
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
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3590)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810c3590-ffffffff810c35bb: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1dc0)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810b1dc0-ffffffff810b1deb: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2ae0)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810c2ae0-ffffffff810c2b0b: kthread_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *kthread_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caf20)
Location: kernel/kthread.c:163
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_last_func
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/workqueue.c:wq_worker_running
  - kernel/async.c:current_is_async
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810caf20-ffffffff810caf4b: kthread_data (STB_GLOBAL)
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
