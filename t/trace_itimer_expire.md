# Function: <code>trace_itimer_expire</code>

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
In kernel/time/itimer.c (ffffffff810f0542)
Location: include/trace/events/timer.h:308
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f29b1)
Location: include/trace/events/timer.h:308
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
In kernel/time/itimer.c (ffffffff810f7572)
Location: include/trace/events/timer.h:308
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f9ac1)
Location: include/trace/events/timer.h:308
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
In kernel/time/posix-cpu-timers.c (ffffffff81107451)
Location: include/trace/events/timer.h:306
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81109c32)
Location: include/trace/events/timer.h:306
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff8110980b)
Location: include/trace/events/timer.h:316
Inline: True
```
```
In kernel/time/itimer.c (ffffffff8110bab5)
Location: include/trace/events/timer.h:316
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff811149db)
Location: include/trace/events/timer.h:317
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81116d05)
Location: include/trace/events/timer.h:317
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff81121194)
Location: include/trace/events/timer.h:336
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81123665)
Location: include/trace/events/timer.h:336
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff8112c8b4)
Location: include/trace/events/timer.h:336
Inline: True
```
```
In kernel/time/itimer.c (ffffffff8112ed33)
Location: include/trace/events/timer.h:336
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff81137284)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (ffffffff811397c3)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff81143413)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81145443)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff811525f0)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81155793)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff8114e869)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81151a04)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff8114fd09)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81152e94)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff81173e89)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811774a4)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff811a8afd)
Location: include/trace/events/timer.h:344
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811ac504)
Location: include/trace/events/timer.h:344
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff811e892b)
Location: include/trace/events/timer.h:344
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811ec864)
Location: include/trace/events/timer.h:344
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff811fcf3b)
Location: include/trace/events/timer.h:348
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81200f94)
Location: include/trace/events/timer.h:348
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff8121312b)
Location: include/trace/events/timer.h:368
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81217434)
Location: include/trace/events/timer.h:368
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffff8000101ad598)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (ffff8000101afc7c)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (c03f84c0)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (c03fa994)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (c0000000002118d4)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (c0000000002145b4)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffe00013753e)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (ffffffe000138ff2)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff8113bbc3)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (ffffffff8113dbf3)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff8112e583)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81130723)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff811398e3)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (ffffffff8113b913)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
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
In kernel/time/posix-cpu-timers.c (ffffffff811463b3)
Location: include/trace/events/timer.h:341
Inline: True
```
```
In kernel/time/itimer.c (ffffffff811483d3)
Location: include/trace/events/timer.h:341
Inline: True
Inline callers:
  - kernel/time/itimer.c:it_real_fn
```
</details>
</li>
</ul>

## Differences
