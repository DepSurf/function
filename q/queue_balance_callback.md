# Function: <code>queue_balance_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810bf479)
Location: kernel/sched/sched.h:766
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c179d)
Location: kernel/sched/sched.h:766
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c2d80)
Location: kernel/sched/sched.h:790
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c67ee)
Location: kernel/sched/sched.h:790
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/rt.c (ffffffff810c8dd0)
Location: kernel/sched/sched.h:822
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cc7de)
Location: kernel/sched/sched.h:822
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/rt.c (ffffffff810c4cd5)
Location: kernel/sched/sched.h:987
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810c81a2)
Location: kernel/sched/sched.h:987
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/rt.c (ffffffff810cc38b)
Location: kernel/sched/sched.h:1001
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf988)
Location: kernel/sched/sched.h:1001
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/rt.c (ffffffff810d40af)
Location: kernel/sched/sched.h:1090
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810d7acd)
Location: kernel/sched/sched.h:1090
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/rt.c (ffffffff810ddd4f)
Location: kernel/sched/sched.h:1241
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e06fd)
Location: kernel/sched/sched.h:1241
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/rt.c (ffffffff810e4d5e)
Location: kernel/sched/sched.h:1299
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e745a)
Location: kernel/sched/sched.h:1299
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/rt.c (ffffffff810ee234)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810f2a7a)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (ffffffff810f7811)
Location: kernel/sched/sched.h:1357
Inline: True
Inline callers:
  - kernel/sched/rt.c:switched_from_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810fc0c1)
Location: kernel/sched/sched.h:1357
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (ffffffff810f59e1)
Location: kernel/sched/sched.h:1415
Inline: True
Inline callers:
  - kernel/sched/rt.c:switched_from_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa622)
Location: kernel/sched/sched.h:1415
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (ffffffff810f7ab1)
Location: kernel/sched/sched.h:1428
Inline: True
Inline callers:
  - kernel/sched/rt.c:switched_from_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810fc551)
Location: kernel/sched/sched.h:1428
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/core.c (ffffffff810fb7d7)
Location: kernel/sched/sched.h:1715
Inline: True
Inline callers:
  - kernel/sched/core.c:queue_core_balance
```
```
In kernel/sched/rt.c (ffffffff811121cc)
Location: kernel/sched/sched.h:1715
Inline: True
Inline callers:
  - kernel/sched/rt.c:switched_from_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff811180ed)
Location: kernel/sched/sched.h:1715
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/core.c (ffffffff81112ef4)
Location: kernel/sched/sched.h:1690
Inline: True
Inline callers:
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/build_policy.c (ffffffff81132bea)
Location: kernel/sched/sched.h:1690
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/core.c (ffffffff81139fc1)
Location: kernel/sched/sched.h:1736
Inline: True
Inline callers:
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/build_policy.c (ffffffff8115cefa)
Location: kernel/sched/sched.h:1736
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/core.c (ffffffff81149236)
Location: kernel/sched/sched.h:1763
Inline: True
Inline callers:
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/build_policy.c (ffffffff8116dcd0)
Location: kernel/sched/sched.h:1763
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/core.c (ffffffff81154c29)
Location: kernel/sched/sched.h:1802
Inline: True
Inline callers:
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/build_policy.c (ffffffff8117aaa0)
Location: kernel/sched/sched.h:1802
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffff80001014eeec)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffff800010154ca4)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (c039d360)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (c03a1e24)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (c0000000001a3318)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (c0000000001aa238)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (ffffffe0000f7dc0)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fa360)
Location: kernel/sched/sched.h:1309
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
In kernel/sched/rt.c (ffffffff810e7f2d)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810ebe7a)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (ffffffff810d7584)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810dbe9a)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (ffffffff810e4764)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e8faa)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
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
In kernel/sched/rt.c (ffffffff810f0bed)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810f3f5a)
Location: kernel/sched/sched.h:1309
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
```
</details>
</li>
</ul>

## Differences
