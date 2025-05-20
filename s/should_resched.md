# Function: <code>should_resched</code>

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
In kernel/sched/core.c (ffffffff81820615)
Location: arch/x86/include/asm/preempt.h:90
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
  - kernel/sched/core.c:__cond_resched_lock
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
In kernel/sched/core.c (ffffffff8189aa75)
Location: arch/x86/include/asm/preempt.h:90
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff818cf055)
Location: arch/x86/include/asm/preempt.h:96
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff819065b5)
Location: arch/x86/include/asm/preempt.h:96
Inline: True
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
In kernel/sched/core.c (ffffffff81990646)
Location: arch/x86/include/asm/preempt.h:97
Inline: True
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
In kernel/sched/core.c (ffffffff819eceb5)
Location: arch/x86/include/asm/preempt.h:97
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff81a280e5)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff81a98875)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff81ad01c5)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff81bc89b5)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff810dfee6)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1ccb)
Location: arch/x86/include/asm/preempt.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f7f3b)
Location: arch/x86/include/asm/preempt.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
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
In kernel/softirq.c (ffffffff810d4898)
Location: arch/x86/include/asm/preempt.h:101
Inline: True
Inline callers:
  - kernel/softirq.c:__local_bh_enable_ip
```
```
In kernel/sched/core.c (ffffffff81f226a5)
Location: arch/x86/include/asm/preempt.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:__cond_resched
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
In kernel/softirq.c (ffffffff810f37c8)
Location: arch/x86/include/asm/preempt.h:102
Inline: True
Inline callers:
  - kernel/softirq.c:__local_bh_enable_ip
```
```
In kernel/sched/core.c (ffffffff820ccf55)
Location: arch/x86/include/asm/preempt.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:__cond_resched
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
In kernel/softirq.c (ffffffff810ffb18)
Location: arch/x86/include/asm/preempt.h:102
Inline: True
Inline callers:
  - kernel/softirq.c:__local_bh_enable_ip
```
```
In kernel/sched/core.c (ffffffff8114958f)
Location: arch/x86/include/asm/preempt.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:klp_cond_resched
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
In kernel/softirq.c (ffffffff811090a8)
Location: arch/x86/include/asm/preempt.h:101
Inline: True
Inline callers:
  - kernel/softirq.c:__local_bh_enable_ip
```
```
In kernel/sched/core.c (ffffffff81154f8f)
Location: arch/x86/include/asm/preempt.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:klp_cond_resched
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
In kernel/sched/core.c (ffff800010da1f38)
Location: arch/arm64/include/asm/preempt.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (c0e9a064)
Location: include/asm-generic/preempt.h:75
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (c000000000ee32fc)
Location: include/asm-generic/preempt.h:75
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffe0008c566a)
Location: include/asm-generic/preempt.h:75
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff81a6f035)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff81a2b3f5)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff81adb445)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/softirq.c (ffffffff810a9508)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/softirq.c:__local_bh_enable_ip
```
```
In kernel/sched/core.c (ffffffff810da925)
Location: arch/x86/include/asm/preempt.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:__cond_resched_lock
```
</details>
</li>
</ul>

## Differences
