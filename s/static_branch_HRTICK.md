# Function: <code>static_branch_HRTICK</code>

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
In kernel/sched/core.c (ffffffff8181fa4d)
Location: kernel/sched/features.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810b46c5)
Location: kernel/sched/features.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810c23dc)
Location: kernel/sched/features.h:39
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
In kernel/sched/core.c (ffffffff8189a13c)
Location: kernel/sched/features.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810c13e7)
Location: kernel/sched/features.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810c6798)
Location: kernel/sched/features.h:39
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
In kernel/sched/core.c (ffffffff818ce7c4)
Location: kernel/sched/features.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810c73e4)
Location: kernel/sched/features.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810cc788)
Location: kernel/sched/features.h:39
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
In kernel/sched/core.c (ffffffff81905b80)
Location: kernel/sched/features.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810c0fbb)
Location: kernel/sched/features.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810c813e)
Location: kernel/sched/features.h:39
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
In kernel/sched/core.c (ffffffff8198fbf0)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810c8972)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810cf924)
Location: kernel/sched/features.h:40
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
In kernel/sched/core.c (ffffffff819ec44f)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810d0f2b)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810d74db)
Location: kernel/sched/features.h:40
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
In kernel/sched/core.c (ffffffff81a2769f)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810da7b2)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e1a9b)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81a97f63)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810e1cf1)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e8580)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81acf838)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810ec5f7)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f170a)
Location: kernel/sched/features.h:40
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
In kernel/sched/core.c (ffffffff81bc82f4)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810f61f2)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810fa97a)
Location: kernel/sched/features.h:40
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
In kernel/sched/core.c (ffffffff81c41025)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810f434b)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f8e2a)
Location: kernel/sched/features.h:40
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
In kernel/sched/core.c (ffffffff81c32f85)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810f5cab)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
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
In kernel/sched/core.c (ffffffff81d519ae)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff8110f9d9)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
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
In kernel/sched/core.c (ffffffff81f21ed1)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff8112b9cf)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
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
In kernel/sched/core.c (ffffffff820cc721)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff811553a7)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
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
In kernel/sched/core.c (ffffffff821509d1)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff81165557)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
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
In kernel/sched/core.c (ffffffff82233809)
Location: kernel/sched/features.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff811722a0)
Location: kernel/sched/features.h:29
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
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
In kernel/sched/core.c (ffff800010da14bc)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffff80001014cabc)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffff800010153f90)
Location: kernel/sched/features.h:40
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000ee251c)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (c00000000019f658)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (c0000000001a765c)
Location: kernel/sched/features.h:40
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/sched/core.c (ffffffff81a6e6a8)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810e6757)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810eab0a)
Location: kernel/sched/features.h:40
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
In kernel/sched/core.c (ffffffff81a2aaa9)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810d58f7)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810dab2a)
Location: kernel/sched/features.h:40
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
In kernel/sched/core.c (ffffffff81adaab8)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810e2b27)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e7c3a)
Location: kernel/sched/features.h:40
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
In kernel/sched/core.c (ffffffff81ae6f6a)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810ee6f7)
Location: kernel/sched/features.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f2eaa)
Location: kernel/sched/features.h:40
Inline: True
```
</details>
</li>
</ul>

## Differences
