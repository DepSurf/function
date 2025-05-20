# Function: <code>rq_unlock_irqrestore</code>

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
In kernel/sched/core.c (ffffffff810b3df6)
Location: kernel/sched/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810c2789)
Location: kernel/sched/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
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
In kernel/sched/core.c (ffffffff810bb0a1)
Location: kernel/sched/sched.h:1781
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810c9fc0)
Location: kernel/sched/sched.h:1781
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
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
In kernel/sched/core.c (ffffffff810c2570)
Location: kernel/sched/sched.h:1825
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810d2004)
Location: kernel/sched/sched.h:1825
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810cb862)
Location: kernel/sched/sched.h:1162
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810db966)
Location: kernel/sched/sched.h:1162
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810d3936)
Location: kernel/sched/sched.h:1220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810e2998)
Location: kernel/sched/sched.h:1220
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810dddc7)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810ed048)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810e6479)
Location: kernel/sched/sched.h:1276
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810f6f58)
Location: kernel/sched/sched.h:1276
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810e4385)
Location: kernel/sched/sched.h:1334
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
In kernel/sched/fair.c (ffffffff810f515b)
Location: kernel/sched/sched.h:1334
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810e634e)
Location: kernel/sched/sched.h:1347
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
In kernel/sched/fair.c (ffffffff810f7245)
Location: kernel/sched/sched.h:1347
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
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
In kernel/sched/core.c (ffffffff810fd831)
Location: kernel/sched/sched.h:1634
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
In kernel/sched/fair.c (ffffffff811116aa)
Location: kernel/sched/sched.h:1634
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
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
In kernel/sched/core.c (ffffffff8111a241)
Location: kernel/sched/sched.h:1607
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
In kernel/sched/fair.c (ffffffff8112d8fb)
Location: kernel/sched/sched.h:1607
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
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
In kernel/sched/core.c (ffffffff811419a8)
Location: kernel/sched/sched.h:1653
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
In kernel/sched/fair.c (ffffffff811576e0)
Location: kernel/sched/sched.h:1653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
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
In kernel/sched/core.c (ffffffff81152482)
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
In kernel/sched/fair.c (ffffffff8116770e)
Location: kernel/sched/sched.h:1680
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_utility.c (ffffffff811888cc)
Location: kernel/sched/sched.h:1680
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
In kernel/sched/core.c (ffffffff8115e347)
Location: kernel/sched/sched.h:1704
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
In kernel/sched/fair.c (ffffffff81174507)
Location: kernel/sched/sched.h:1704
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_utility.c (ffffffff811971ac)
Location: kernel/sched/sched.h:1704
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
In kernel/sched/core.c (ffff80001013d728)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffff80001014d688)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (c038d76c)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (c039b254)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (c00000000018c5d0)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (c0000000001a0594)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffe0000ec714)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffe0000f6946)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810d7fb7)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810e71a8)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810c6988)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810d6348)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810d47a7)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810e3578)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
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
In kernel/sched/core.c (ffffffff810dfbaf)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/fair.c (ffffffff810ef158)
Location: kernel/sched/sched.h:1228
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
</details>
</li>
</ul>

## Differences
