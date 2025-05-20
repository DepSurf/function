# Function: <code>set_tsk_need_resched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa379)
Location: include/linux/sched.h:2879
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810acfd3)
Location: include/linux/sched.h:3156
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b305f)
Location: include/linux/sched.h:3312
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cd809)
Location: include/linux/sched.h:3312
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aef3c)
Location: include/linux/sched.h:1507
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ca229)
Location: include/linux/sched.h:1507
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
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
In kernel/sched/core.c (ffffffff810b6192)
Location: include/linux/sched.h:1541
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d1a09)
Location: include/linux/sched.h:1541
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
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
In kernel/sched/core.c (ffffffff810be038)
Location: include/linux/sched.h:1663
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c40c6)
Location: include/linux/sched.h:1663
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
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
In kernel/sched/core.c (ffffffff810c72e8)
Location: include/linux/sched.h:1676
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cd3c6)
Location: include/linux/sched.h:1676
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff81114a65)
Location: include/linux/sched.h:1676
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/sched/core.c (ffffffff810cd849)
Location: include/linux/sched.h:1749
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d5786)
Location: include/linux/sched.h:1749
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8111a53c)
Location: include/linux/sched.h:1749
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810d7379)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810dfd96)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8112693c)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810e1de9)
Location: include/linux/sched.h:1792
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e8096)
Location: include/linux/sched.h:1792
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff81136cba)
Location: include/linux/sched.h:1792
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810df1ab)
Location: include/linux/sched.h:1853
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e5cb6)
Location: include/linux/sched.h:1853
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8113231a)
Location: include/linux/sched.h:1853
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810e0e3b)
Location: include/linux/sched.h:1875
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e7c76)
Location: include/linux/sched.h:1875
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff81bd48d4)
Location: include/linux/sched.h:1875
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810f5d78)
Location: include/linux/sched.h:1992
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ff356)
Location: include/linux/sched.h:1992
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff81caed4c)
Location: include/linux/sched.h:1992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff81110f29)
Location: include/linux/sched.h:2014
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff8112ecd6)
Location: include/linux/sched.h:2014
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8117dbe0)
Location: include/linux/sched.h:2014
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_flavor_sched_clock_irq
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff81137ed7)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff81158aa6)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff811b6a84)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff81147036)
Location: include/linux/sched.h:2049
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff81168c76)
Location: include/linux/sched.h:2049
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff811c74b4)
Location: include/linux/sched.h:2049
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff81152866)
Location: include/linux/sched.h:1951
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff81175f26)
Location: include/linux/sched.h:1951
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff811d79d4)
Location: include/linux/sched.h:1951
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffff800010138500)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffff80001013f994)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffff80001018c820)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (c03871d4)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (c038f8a8)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (c03da244)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (c000000000183470)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (c00000000018e808)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (c0000000001e66f8)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffe0000e84d0)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffe0000edc06)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffe000124bea)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810d1849)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d9f86)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8111ef1c)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810bfe09)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c8fb6)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8111092c)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810cfa09)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d62c6)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8111ce0c)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (ffffffff810d8f42)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e1c06)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/rcu/tree.c (ffffffff8112a693)
Location: include/linux/sched.h:1742
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
</details>
</li>
</ul>

## Differences
