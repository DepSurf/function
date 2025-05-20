# Function: <code>rcu_segcblist_is_enabled</code>

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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:99
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:99
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:77
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:77
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:77
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:77
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:77
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:77
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:64
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:64
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
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
In kernel/rcu/tree.c (ffffffff81138d9c)
Location: kernel/rcu/rcu_segcblist.h:57
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81139a95)
Location: kernel/rcu/rcu_segcblist.h:57
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/tree.c (ffffffff81be276f)
Location: kernel/rcu/rcu_segcblist.h:57
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81134565)
Location: kernel/rcu/rcu_segcblist.h:57
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/tree.c (ffffffff81bd4712)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81135405)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/tree.c (ffffffff81caeae3)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81157da5)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/update.c (ffffffff811736d1)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff81e5f18c)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811810f5)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/update.c (ffffffff811aab09)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811b7c12)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811bba55)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/update.c (ffffffff811bca39)
Location: kernel/rcu/rcu_segcblist.h:80
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811c96d2)
Location: kernel/rcu/rcu_segcblist.h:80
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce3f5)
Location: kernel/rcu/rcu_segcblist.h:80
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/update.c (ffffffff811cb86e)
Location: kernel/rcu/rcu_segcblist.h:80
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811d8a42)
Location: kernel/rcu/rcu_segcblist.h:80
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2fe5)
Location: kernel/rcu/rcu_segcblist.h:80
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
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
In kernel/rcu/tree.c (c03dfdf0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (c03e0bec)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
```
</details>
</li>
</ul>

## Differences
