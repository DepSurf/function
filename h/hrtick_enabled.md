# Function: <code>hrtick_enabled</code>

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
In kernel/sched/fair.c (ffffffff810b46c5)
Location: kernel/sched/sched.h:1376
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810c23dc)
Location: kernel/sched/sched.h:1376
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
In kernel/sched/fair.c (ffffffff810c13e7)
Location: kernel/sched/sched.h:1413
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810c6798)
Location: kernel/sched/sched.h:1413
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
In kernel/sched/fair.c (ffffffff810c73e4)
Location: kernel/sched/sched.h:1452
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810cc788)
Location: kernel/sched/sched.h:1452
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
In kernel/sched/fair.c (ffffffff810c0fbb)
Location: kernel/sched/sched.h:1633
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810c813e)
Location: kernel/sched/sched.h:1633
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
In kernel/sched/fair.c (ffffffff810c8972)
Location: kernel/sched/sched.h:1672
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810cf924)
Location: kernel/sched/sched.h:1672
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
In kernel/sched/fair.c (ffffffff810d0f2b)
Location: kernel/sched/sched.h:1709
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810d74db)
Location: kernel/sched/sched.h:1709
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffff810da7b2)
Location: kernel/sched/sched.h:1855
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e1a9b)
Location: kernel/sched/sched.h:1855
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/fair.c (ffffffff810e1cf1)
Location: kernel/sched/sched.h:1917
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e8580)
Location: kernel/sched/sched.h:1917
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/fair.c (ffffffff810ec5f7)
Location: kernel/sched/sched.h:1960
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f170a)
Location: kernel/sched/sched.h:1960
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
In kernel/sched/fair.c (ffffffff810f61f2)
Location: kernel/sched/sched.h:1993
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810fa97a)
Location: kernel/sched/sched.h:1993
Inline: True
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
In kernel/sched/fair.c (ffffffff810f434b)
Location: kernel/sched/sched.h:2106
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f8e2a)
Location: kernel/sched/sched.h:2106
Inline: True
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
In kernel/sched/fair.c (ffffffff810f5d62)
Location: kernel/sched/sched.h:2120
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810fae6f)
Location: kernel/sched/sched.h:2120
Inline: True
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
In kernel/sched/fair.c (ffffffff8110fa8c)
Location: kernel/sched/sched.h:2426
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff81116a5c)
Location: kernel/sched/sched.h:2426
Inline: True
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
In kernel/sched/fair.c (ffffffff8112ba6d)
Location: kernel/sched/sched.h:2422
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81138e9d)
Location: kernel/sched/sched.h:2422
Inline: True
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
In kernel/sched/fair.c (ffffffff81155598)
Location: kernel/sched/sched.h:2480
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff8116354d)
Location: kernel/sched/sched.h:2480
Inline: True
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
In kernel/sched/fair.c (ffffffff8116572b)
Location: kernel/sched/sched.h:2526
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81173d2d)
Location: kernel/sched/sched.h:2526
Inline: True
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
In kernel/sched/fair.c (ffffffff81172443)
Location: kernel/sched/sched.h:2576
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81181936)
Location: kernel/sched/sched.h:2576
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
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
In kernel/sched/fair.c (ffff80001014cabc)
Location: kernel/sched/sched.h:1960
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffff800010153f90)
Location: kernel/sched/sched.h:1960
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
In kernel/sched/fair.c (c039a7cc)
Location: kernel/sched/sched.h:1960
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (c03a0774)
Location: kernel/sched/sched.h:1960
Inline: True
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
In kernel/sched/fair.c (c00000000019f658)
Location: kernel/sched/sched.h:1960
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (c0000000001a765c)
Location: kernel/sched/sched.h:1960
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1960
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1960
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
In kernel/sched/fair.c (ffffffff810e6757)
Location: kernel/sched/sched.h:1960
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810eab0a)
Location: kernel/sched/sched.h:1960
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
In kernel/sched/fair.c (ffffffff810d58f7)
Location: kernel/sched/sched.h:1960
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810dab2a)
Location: kernel/sched/sched.h:1960
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
In kernel/sched/fair.c (ffffffff810e2b27)
Location: kernel/sched/sched.h:1960
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e7c3a)
Location: kernel/sched/sched.h:1960
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
In kernel/sched/fair.c (ffffffff810ee6f7)
Location: kernel/sched/sched.h:1960
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f2eaa)
Location: kernel/sched/sched.h:1960
Inline: True
```
</details>
</li>
</ul>

## Differences
