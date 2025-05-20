# Function: <code>hrtimer_add_expires</code>

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
In kernel/time/hrtimer.c (ffffffff810eebb0)
Location: include/linux/hrtimer.h:235
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/posix-timers.c (ffffffff810f1230)
Location: include/linux/hrtimer.h:235
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
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
In kernel/time/hrtimer.c (ffffffff810f5bf0)
Location: include/linux/hrtimer.h:235
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/posix-timers.c (ffffffff810f82b0)
Location: include/linux/hrtimer.h:235
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
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
In kernel/time/hrtimer.c (ffffffff810fcca3)
Location: include/linux/hrtimer.h:235
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/posix-timers.c (ffffffff81105bd0)
Location: include/linux/hrtimer.h:235
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
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
In kernel/time/hrtimer.c (ffffffff810fef6e)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff81109d52)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff81115323)
Location: include/linux/hrtimer.h:247
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff81120963)
Location: include/linux/hrtimer.h:244
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff8112b6f6)
Location: include/linux/hrtimer.h:244
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff811371ee)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff81145f41)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff81142461)
Location: include/linux/hrtimer.h:264
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff81143641)
Location: include/linux/hrtimer.h:264
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff81166c21)
Location: include/linux/hrtimer.h:264
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119a391)
Location: include/linux/hrtimer.h:264
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff811d8ab1)
Location: include/linux/hrtimer.h:264
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ecee1)
Location: include/linux/hrtimer.h:264
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203041)
Location: include/linux/hrtimer.h:226
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffff8000101a06e8)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (c03eb8e8)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (c000000000202024)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffe00012df7e)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff8112f99e)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff8112240e)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff8112d6be)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
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
In kernel/time/hrtimer.c (ffffffff81139fee)
Location: include/linux/hrtimer.h:263
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
</details>
</li>
</ul>

## Differences
