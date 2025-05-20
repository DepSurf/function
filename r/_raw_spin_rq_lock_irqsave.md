# Function: <code>_raw_spin_rq_lock_irqsave</code>

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
In kernel/sched/core.c (ffffffff810fd7c7)
Location: kernel/sched/sched.h:1333
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
```
```
In kernel/sched/fair.c (ffffffff811115ee)
Location: kernel/sched/sched.h:1333
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/topology.c (ffffffff8111f2c5)
Location: kernel/sched/sched.h:1333
Inline: True
Inline callers:
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/debug.c (ffffffff81125c66)
Location: kernel/sched/sched.h:1333
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq *rq);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110e510)
Location: kernel/sched/sched.h:1319
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
```
```
In kernel/sched/fair.c (ffffffff8111b480)
Location: kernel/sched/sched.h:1319
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_utility.c (ffffffff8113d550)
Location: kernel/sched/sched.h:1319
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:print_cfs_rq
```
**Symbols:**

```
ffffffff8110e510-ffffffff8110e53c: _raw_spin_rq_lock_irqsave (STB_LOCAL)
ffffffff8111b480-ffffffff8111b4ac: _raw_spin_rq_lock_irqsave (STB_LOCAL)
ffffffff8113d550-ffffffff8113d57c: _raw_spin_rq_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq *rq);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81135260)
Location: kernel/sched/sched.h:1373
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
```
```
In kernel/sched/fair.c (ffffffff81142f60)
Location: kernel/sched/sched.h:1373
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_utility.c (ffffffff81167fb0)
Location: kernel/sched/sched.h:1373
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:print_cfs_rq
```
**Symbols:**

```
ffffffff81135260-ffffffff81135299: _raw_spin_rq_lock_irqsave (STB_LOCAL)
ffffffff81142f60-ffffffff81142f99: _raw_spin_rq_lock_irqsave (STB_LOCAL)
ffffffff81167fb0-ffffffff81167fe9: _raw_spin_rq_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq *rq);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144470)
Location: kernel/sched/sched.h:1381
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
```
```
In kernel/sched/fair.c (ffffffff81152f20)
Location: kernel/sched/sched.h:1381
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_utility.c (ffffffff81178670)
Location: kernel/sched/sched.h:1381
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:print_cfs_rq
```
**Symbols:**

```
ffffffff81144470-ffffffff811444a9: _raw_spin_rq_lock_irqsave (STB_LOCAL)
ffffffff81152f20-ffffffff81152f59: _raw_spin_rq_lock_irqsave (STB_LOCAL)
ffffffff81178670-ffffffff811786a9: _raw_spin_rq_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq *rq);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114f990)
Location: kernel/sched/sched.h:1400
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
```
```
In kernel/sched/fair.c (ffffffff8115ea00)
Location: kernel/sched/sched.h:1400
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_utility.c (ffffffff81186390)
Location: kernel/sched/sched.h:1400
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:print_cfs_rq
```
**Symbols:**

```
ffffffff8114f990-ffffffff8114f9c9: _raw_spin_rq_lock_irqsave (STB_LOCAL)
ffffffff8115ea00-ffffffff8115ea39: _raw_spin_rq_lock_irqsave (STB_LOCAL)
ffffffff81186390-ffffffff811863c9: _raw_spin_rq_lock_irqsave (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
