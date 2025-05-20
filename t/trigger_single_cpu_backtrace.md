# Function: <code>trigger_single_cpu_backtrace</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f6ecd)
Location: include/linux/nmi.h:121
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81100f34)
Location: include/linux/nmi.h:154
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81108c68)
Location: include/linux/nmi.h:154
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114488)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e1b3)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
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
In kernel/rcu/tree.c (ffffffff8112a781)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81138b06)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81be23eb)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool trigger_single_cpu_backtrace(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bd41ad)
Location: include/linux/nmi.h:162
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff81bd41ad-ffffffff81bd41df: trigger_single_cpu_backtrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool trigger_single_cpu_backtrace(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81cae3f8)
Location: include/linux/nmi.h:162
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff81cae3f8-ffffffff81cae443: trigger_single_cpu_backtrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool trigger_single_cpu_backtrace(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81e5ea70)
Location: include/linux/nmi.h:164
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff81e5ea70-ffffffff81e5eac3: trigger_single_cpu_backtrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81142507)
Location: include/linux/nmi.h:164
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
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
In kernel/sched/core.c (ffffffff8114e217)
Location: include/linux/nmi.h:176
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
```
```
In kernel/watchdog.c (ffffffff8125e8ac)
Location: include/linux/nmi.h:176
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
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
In kernel/sched/core.c (ffffffff8115a057)
Location: include/linux/nmi.h:176
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
```
```
In kernel/watchdog.c (ffffffff812788a7)
Location: include/linux/nmi.h:176
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
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
In kernel/rcu/tree.c (0)
Location: include/linux/nmi.h:187
Inline: True
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
In kernel/rcu/tree.c (c03e01f4)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
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
In kernel/rcu/tree.c (c0000000001edf38)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
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
In kernel/rcu/tree.c (0)
Location: include/linux/nmi.h:187
Inline: True
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
In kernel/rcu/tree.c (ffffffff81122d61)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
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
In kernel/rcu/tree.c (ffffffff8111581d)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
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
In kernel/rcu/tree.c (ffffffff81120c51)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
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
In kernel/rcu/tree.c (ffffffff8112cf26)
Location: include/linux/nmi.h:162
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
