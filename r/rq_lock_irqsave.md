# Function: <code>rq_lock_irqsave</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3c81)
Location: kernel/sched/sched.h:1710
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810c2387)
Location: kernel/sched/sched.h:1710
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/core.c (ffffffff810baf1e)
Location: kernel/sched/sched.h:1749
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810c9a2f)
Location: kernel/sched/sched.h:1749
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/core.c (ffffffff810c23fc)
Location: kernel/sched/sched.h:1793
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810d1b8e)
Location: kernel/sched/sched.h:1793
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/core.c (ffffffff810cb6ec)
Location: kernel/sched/sched.h:1130
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810db4ce)
Location: kernel/sched/sched.h:1130
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/core.c (ffffffff810d36ff)
Location: kernel/sched/sched.h:1188
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810e2953)
Location: kernel/sched/sched.h:1188
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810ddc72)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810ed003)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810e6421)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810f6f13)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810e433a)
Location: kernel/sched/sched.h:1302
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810f50f7)
Location: kernel/sched/sched.h:1302
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810e6307)
Location: kernel/sched/sched.h:1315
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810f71e1)
Location: kernel/sched/sched.h:1315
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810fd7c7)
Location: kernel/sched/sched.h:1602
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff811115ee)
Location: kernel/sched/sched.h:1602
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff8111a1e7)
Location: kernel/sched/sched.h:1583
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff8112d811)
Location: kernel/sched/sched.h:1583
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff8114194d)
Location: kernel/sched/sched.h:1629
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff811575f6)
Location: kernel/sched/sched.h:1629
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff8115240b)
Location: kernel/sched/sched.h:1656
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff81167643)
Location: kernel/sched/sched.h:1656
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_utility.c (ffffffff81188815)
Location: kernel/sched/sched.h:1656
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:rq_attach_root
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
In kernel/sched/core.c (ffffffff8115e2cb)
Location: kernel/sched/sched.h:1680
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff81174433)
Location: kernel/sched/sched.h:1680
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_utility.c (ffffffff811970f5)
Location: kernel/sched/sched.h:1680
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:rq_attach_root
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
In kernel/sched/core.c (ffff80001013d570)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffff80001014d61c)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (c038d5ac)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (c039b20c)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (c00000000018c3cc)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (c0000000001a0534)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffe0000ec6d2)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffe0000f68e2)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810d7e62)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810e7163)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810c6834)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810d6303)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810d4652)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810e3533)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810dfa5f)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810ef113)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
</details>
</li>
</ul>

## Differences
