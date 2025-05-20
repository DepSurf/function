# Function: <code>get_timer_cpu_base</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8189de76)
Location: kernel/time/timer.c:846
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
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
In kernel/time/timer.c (ffffffff818d2f4c)
Location: kernel/time/timer.c:846
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81909f79)
Location: kernel/time/timer.c:812
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff819943e7)
Location: kernel/time/timer.c:821
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff819f09d9)
Location: kernel/time/timer.c:838
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81a2bd59)
Location: kernel/time/timer.c:837
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81a9bf2d)
Location: kernel/time/timer.c:832
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81ad387d)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff811457b5)
Location: kernel/time/timer.c:844
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81141885)
Location: kernel/time/timer.c:848
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81142cd5)
Location: kernel/time/timer.c:850
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff8116621b)
Location: kernel/time/timer.c:850
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff811992e6)
Location: kernel/time/timer.c:903
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff811d79a8)
Location: kernel/time/timer.c:903
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff811ebcee)
Location: kernel/time/timer.c:903
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81201d0e)
Location: kernel/time/timer.c:900
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffff80001019e438)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (c0e9e0e4)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (c000000000ee8bd8)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffe0008c8832)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81a726ed)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81a2eabd)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81adeafd)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
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
In kernel/time/timer.c (ffffffff81aeaf91)
Location: kernel/time/timer.c:836
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
```
</details>
</li>
</ul>

## Differences
