# Function: <code>atomic_read_acquire</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e2c09)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ed389)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
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
In kernel/sched/rt.c (ffffffff810f9958)
Location: include/asm-generic/atomic-instrumented.h:34
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f2fd)
Location: include/asm-generic/atomic-instrumented.h:34
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
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
In kernel/sched/rt.c (ffffffff810f7d17)
Location: include/asm-generic/atomic-instrumented.h:34
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c4bd)
Location: include/asm-generic/atomic-instrumented.h:34
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
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
In kernel/sched/rt.c (ffffffff810f956c)
Location: include/asm-generic/atomic-instrumented.h:34
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e2fa)
Location: include/asm-generic/atomic-instrumented.h:34
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
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
In kernel/sched/rt.c (ffffffff81112d2c)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112da39)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/tree.c (ffffffff8115265f)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_is_idle_cpu
```
```
In kernel/futex.c (ffffffff8117f792)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
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
In kernel/sched/build_policy.c (ffffffff8112fffc)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25ca2)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/rcu/tree.c (ffffffff8117aa7f)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_is_idle_cpu
```
```
In kernel/futex/requeue.c (ffffffff811b643d)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
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
In kernel/sched/build_policy.c (ffffffff8115a24c)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d1702)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/rcu/tree.c (ffffffff811b57c2)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/futex/requeue.c (ffffffff811f757d)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In fs/file.c (ffffffff814a6e88)
Location: include/linux/atomic/atomic-instrumented.h:32
Inline: True
Inline callers:
  - fs/file.c:__fget_light
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
In kernel/sched/build_policy.c (ffffffff8116a45c)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155a72)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/rcu/tree.c (ffffffff811c6752)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/futex/requeue.c (ffffffff8120bd1d)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In fs/file.c (ffffffff814dbe68)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - fs/file.c:__fget_light
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
In kernel/sched/build_policy.c (ffffffff81177b1c)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff822388b2)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/power/swap.c (ffffffff811a9f62)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
```
```
In kernel/rcu/tree.c (ffffffff811d69b2)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/futex/requeue.c (ffffffff812232b2)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In fs/file.c (ffffffff8150fda2)
Location: include/linux/atomic/atomic-instrumented.h:47
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_raw
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014df78)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039b384)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a0ad8)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f6c08)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e7439)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d6689)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e38b9)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ef3f9)
Location: include/linux/atomic-fallback.h:80
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_next_cpu
```
</details>
</li>
</ul>

## Differences
