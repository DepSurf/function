# Function: <code>hrtimer_is_hres_active</code>

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
In kernel/sched/fair.c (ffffffff810b46e2)
Location: include/linux/hrtimer.h:286
Inline: True
Inline callers:
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/deadline.c (ffffffff810c23ff)
Location: include/linux/hrtimer.h:286
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:286
Inline: True
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
In kernel/sched/fair.c (ffffffff810c176c)
Location: include/linux/hrtimer.h:286
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810c67af)
Location: include/linux/hrtimer.h:286
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:286
Inline: True
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
In kernel/sched/fair.c (ffffffff810c775a)
Location: include/linux/hrtimer.h:286
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810cc79f)
Location: include/linux/hrtimer.h:286
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:286
Inline: True
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
In kernel/sched/fair.c (ffffffff810c140c)
Location: include/linux/hrtimer.h:274
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810c816d)
Location: include/linux/hrtimer.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:274
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
In kernel/sched/fair.c (ffffffff810c89ba)
Location: include/linux/hrtimer.h:274
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810cf953)
Location: include/linux/hrtimer.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:274
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
In kernel/sched/fair.c (ffffffff810d115d)
Location: include/linux/hrtimer.h:293
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810d753f)
Location: include/linux/hrtimer.h:293
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
In kernel/sched/fair.c (ffffffff810da9b6)
Location: include/linux/hrtimer.h:290
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e1b32)
Location: include/linux/hrtimer.h:290
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
In kernel/sched/fair.c (ffffffff810e1d5f)
Location: include/linux/hrtimer.h:290
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e8625)
Location: include/linux/hrtimer.h:290
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
In kernel/sched/fair.c (ffffffff810ec6bf)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f17a1)
Location: include/linux/hrtimer.h:309
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
In kernel/sched/fair.c (ffffffff810f62ba)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810faa11)
Location: include/linux/hrtimer.h:309
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
In kernel/sched/fair.c (ffffffff810f4416)
Location: include/linux/hrtimer.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f8ed1)
Location: include/linux/hrtimer.h:310
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
In kernel/sched/fair.c (ffffffff810f5d76)
Location: include/linux/hrtimer.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810fae83)
Location: include/linux/hrtimer.h:310
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
In kernel/sched/fair.c (ffffffff8110faa0)
Location: include/linux/hrtimer.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff81116a70)
Location: include/linux/hrtimer.h:310
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
In kernel/sched/fair.c (ffffffff8112ba83)
Location: include/linux/hrtimer.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81138ead)
Location: include/linux/hrtimer.h:310
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
In kernel/sched/fair.c (ffffffff811555ae)
Location: include/linux/hrtimer.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff8116355d)
Location: include/linux/hrtimer.h:310
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
In kernel/sched/fair.c (ffffffff81165741)
Location: include/linux/hrtimer.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81173d3d)
Location: include/linux/hrtimer.h:310
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
In kernel/sched/fair.c (ffffffff81172459)
Location: include/linux/hrtimer.h:272
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81181948)
Location: include/linux/hrtimer.h:272
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
In kernel/sched/fair.c (ffff80001014cbac)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffff800010154054)
Location: include/linux/hrtimer.h:309
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
In kernel/sched/fair.c (c039a800)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (c03a07b8)
Location: include/linux/hrtimer.h:309
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
In kernel/sched/fair.c (c00000000019f7b0)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (c0000000001a7740)
Location: include/linux/hrtimer.h:309
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
Location: include/linux/hrtimer.h:309
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:309
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
In kernel/sched/fair.c (ffffffff810e681f)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810eaba1)
Location: include/linux/hrtimer.h:309
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
In kernel/sched/fair.c (ffffffff810d59bf)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810dabc1)
Location: include/linux/hrtimer.h:309
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
In kernel/sched/fair.c (ffffffff810e2bef)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810e7cd1)
Location: include/linux/hrtimer.h:309
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
In kernel/sched/fair.c (ffffffff810ee7bf)
Location: include/linux/hrtimer.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810f2f41)
Location: include/linux/hrtimer.h:309
Inline: True
```
</details>
</li>
</ul>

## Differences
