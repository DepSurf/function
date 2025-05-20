# Function: <code>arch_atomic_read_acquire</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f9958)
Location: include/linux/atomic-arch-fallback.h:82
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f2fd)
Location: include/linux/atomic-arch-fallback.h:82
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
Location: include/linux/atomic-arch-fallback.h:152
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c4bd)
Location: include/linux/atomic-arch-fallback.h:152
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
Location: include/linux/atomic-arch-fallback.h:152
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e2fa)
Location: include/linux/atomic-arch-fallback.h:152
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
Location: include/linux/atomic/atomic-arch-fallback.h:152
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112da39)
Location: include/linux/atomic/atomic-arch-fallback.h:152
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/tree.c (ffffffff8115265f)
Location: include/linux/atomic/atomic-arch-fallback.h:152
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
Location: include/linux/atomic/atomic-arch-fallback.h:152
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
Location: include/linux/atomic/atomic-arch-fallback.h:222
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25ca2)
Location: include/linux/atomic/atomic-arch-fallback.h:222
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/rcu/tree.c (ffffffff8117aa7f)
Location: include/linux/atomic/atomic-arch-fallback.h:222
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
Location: include/linux/atomic/atomic-arch-fallback.h:222
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
Location: include/linux/atomic/atomic-arch-fallback.h:222
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d1702)
Location: include/linux/atomic/atomic-arch-fallback.h:222
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/rcu/tree.c (ffffffff811b57c2)
Location: include/linux/atomic/atomic-arch-fallback.h:222
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
Location: include/linux/atomic/atomic-arch-fallback.h:222
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
Location: include/linux/atomic/atomic-arch-fallback.h:222
Inline: True
Inline callers:
  - fs/file.c:__fget_light
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
