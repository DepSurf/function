# Function: <code>kthread_queue_work</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8f80)
Location: kernel/kthread.c:788
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff810a8f80-ffffffff810a8fe9: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a5d10)
Location: kernel/kthread.c:794
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff810a5d10-ffffffff810a5d82: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac2e0)
Location: kernel/kthread.c:801
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff810ac2e0-ffffffff810ac352: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b2c30)
Location: kernel/kthread.c:819
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff810b2c30-ffffffff810b2c99: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bbeb0)
Location: kernel/kthread.c:821
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810bbeb0-ffffffff810bbf19: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2000)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810c2000-ffffffff810c2069: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8560)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810c8560-ffffffff810c85c9: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0632)
Location: kernel/kthread.c:866
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_queued_transfer
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810d02f0-ffffffff810d0357: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb052)
Location: kernel/kthread.c:919
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/spi/spi.c:spi_queued_transfer
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810cad10-ffffffff810cad77: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc9c2)
Location: kernel/kthread.c:946
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_queued_transfer
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810cc620-ffffffff810cc687: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0042)
Location: kernel/kthread.c:946
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810dfb20-ffffffff810dfb87: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fadc1)
Location: kernel/kthread.c:1006
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
Direct callers:
  - kernel/sched/build_utility.c:sugov_irq_work
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810fa3a0-ffffffff810fa414: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111dc21)
Location: kernel/kthread.c:1007
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
Direct callers:
  - kernel/sched/build_utility.c:sugov_irq_work
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/spi/spi.c:spi_queued_transfer
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff8111d160-ffffffff8111d1d4: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112ae11)
Location: kernel/kthread.c:1008
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
Direct callers:
  - kernel/sched/build_utility.c:sugov_irq_work
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/spi/spi.c:spi_queued_transfer
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff8112a280-ffffffff8112a2f4: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81135531)
Location: kernel/kthread.c:1025
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_pod
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/sched/build_utility.c:sugov_irq_work
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_schedule
  - drivers/gpu/drm/drm_vblank_work.c:drm_handle_vblank_works
  - drivers/spi/spi.c:spi_controller_resume
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/spi/spi.c:spi_queued_transfer
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff81134910-ffffffff81134984: kthread_queue_work (STB_GLOBAL)
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
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127f28)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffff800010127f28-ffff80001012800c: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a1a4)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
c037a1a4-c037a218: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000171d90)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
c000000000171d90-c000000000171e88: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000deed4)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffe0000deed4-ffffffe0000def44: kthread_queue_work (STB_GLOBAL)
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
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c28e0)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810c28e0-ffffffff810c2949: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1130)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810b1130-ffffffff810b1199: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1e30)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810c1e30-ffffffff810c1e99: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kthread_queue_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca410)
Location: kernel/kthread.c:830
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_irq_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/watchdog/watchdog_dev.c:watchdog_timer_expired
```
**Symbols:**

```
ffffffff810ca410-ffffffff810ca479: kthread_queue_work (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
