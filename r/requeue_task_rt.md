# Function: <code>requeue_task_rt</code>

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
In kernel/sched/rt.c (ffffffff810bf030)
Location: kernel/sched/rt.c:1297
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:task_tick_rt
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
In kernel/sched/rt.c (ffffffff810c3cdd)
Location: kernel/sched/rt.c:1359
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810c9d4d)
Location: kernel/sched/rt.c:1358
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810c4a68)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810cc118)
Location: kernel/sched/rt.c:1360
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810d37aa)
Location: kernel/sched/rt.c:1369
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810dcb4f)
Location: kernel/sched/rt.c:1369
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810e3af7)
Location: kernel/sched/rt.c:1369
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810ed4d7)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f784d)
Location: kernel/sched/rt.c:1411
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
**Symbols:**

```
ffffffff810f7410-ffffffff810f749f: requeue_task_rt.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f5a1d)
Location: kernel/sched/rt.c:1413
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
**Symbols:**

```
ffffffff810f5610-ffffffff810f569f: requeue_task_rt.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7aed)
Location: kernel/sched/rt.c:1413
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
**Symbols:**

```
ffffffff810f76e0-ffffffff810f7772: requeue_task_rt.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff81112237)
Location: kernel/sched/rt.c:1428
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
Direct callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
**Symbols:**

```
ffffffff81111cd0-ffffffff81111da6: requeue_task_rt.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f427)
Location: kernel/sched/rt.c:1583
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
Direct callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:check_preempt_curr_rt
```
**Symbols:**

```
ffffffff8112eb50-ffffffff8112ec42: requeue_task_rt.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811591d7)
Location: kernel/sched/rt.c:1579
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
Direct callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:check_preempt_curr_rt
```
**Symbols:**

```
ffffffff81158910-ffffffff81158a02: requeue_task_rt.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81169497)
Location: kernel/sched/rt.c:1579
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
Direct callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:check_preempt_curr_rt
```
**Symbols:**

```
ffffffff81168ca0-ffffffff81168d92: requeue_task_rt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81176657)
Location: kernel/sched/rt.c:1524
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
Direct callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:wakeup_preempt_rt
```
**Symbols:**

```
ffffffff81175f50-ffffffff81176042: requeue_task_rt.isra.0 (STB_LOCAL)
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
In kernel/sched/rt.c (ffff80001014e114)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (c039e554)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (c0000000001a0d38)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffe0000f8f32)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810e8eb7)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810d67d7)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810e3a07)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
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
In kernel/sched/rt.c (ffffffff810f0a4b)
Location: kernel/sched/rt.c:1370
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
```
</details>
</li>
</ul>

## Differences
