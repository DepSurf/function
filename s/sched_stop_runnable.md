# Function: <code>sched_stop_runnable</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810efdfb)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f2186)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f959d)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffff810f9744)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd43f)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff811036a5)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffff810f7af3)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fb9ff)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff81101dc5)
Location: kernel/sched/sched.h:1922
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffff810f98e3)
Location: kernel/sched/sched.h:1933
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fdd1f)
Location: kernel/sched/sched.h:1933
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff81104135)
Location: kernel/sched/sched.h:1933
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffff81113143)
Location: kernel/sched/sched.h:2223
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff8111625f)
Location: kernel/sched/sched.h:2223
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff81121235)
Location: kernel/sched/sched.h:2223
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/build_policy.c (ffffffff8112fe55)
Location: kernel/sched/sched.h:2218
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff811443b5)
Location: kernel/sched/sched.h:2218
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
  - kernel/sched/build_utility.c:balance_stop
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
In kernel/sched/build_policy.c (ffffffff81159f25)
Location: kernel/sched/sched.h:2269
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff811701b5)
Location: kernel/sched/sched.h:2269
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
  - kernel/sched/build_utility.c:balance_stop
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
In kernel/sched/build_policy.c (ffffffff8116a135)
Location: kernel/sched/sched.h:2316
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff8117eda5)
Location: kernel/sched/sched.h:2316
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
  - kernel/sched/build_utility.c:balance_stop
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
In kernel/sched/build_policy.c (ffffffff811777f5)
Location: kernel/sched/sched.h:2368
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118c425)
Location: kernel/sched/sched.h:2368
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
  - kernel/sched/build_utility.c:balance_stop
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
In kernel/sched/rt.c (ffff8000101513a0)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (ffff800010153dc8)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffff80001015dec0)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (c039c5f4)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (c03a00ec)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (c03a9ca8)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (c0000000001a2248)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001a6c2c)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (c0000000001b2a5c)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffe0000f96a0)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fba7a)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffe000102384)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffff810e96eb)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eb586)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f299d)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffff810d91bb)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810db5a6)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e2aad)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffff810e632b)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e86b6)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff810efacd)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/rt.c (ffffffff810f004b)
Location: kernel/sched/sched.h:1804
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f29a6)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
```
```
In kernel/sched/stop_task.c (ffffffff810fab1d)
Location: kernel/sched/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
</details>
</li>
</ul>

## Differences
