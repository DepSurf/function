# Function: <code>timer_overrun_to_int</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112087b)
Location: kernel/time/posix-timers.c:290
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff8112c086)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff81136857)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff81142907)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff8114fd8f)
Location: kernel/time/posix-timers.c:286
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff8114c00f)
Location: kernel/time/posix-timers.c:286
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff8114d4ce)
Location: kernel/time/posix-timers.c:286
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff81170c8e)
Location: kernel/time/posix-timers.c:286
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff811a52d6)
Location: kernel/time/posix-timers.c:286
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff811e4c46)
Location: kernel/time/posix-timers.c:286
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff811f92a6)
Location: kernel/time/posix-timers.c:236
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff8120f496)
Location: kernel/time/posix-timers.c:236
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffff8000101ac99c)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (c03f6d34)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (c00000000020dca0)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffe0001366d6)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff8113b0b7)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff8112db07)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff81138dd7)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff81145887)
Location: kernel/time/posix-timers.c:260
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posixtimer_rearm
```
</details>
</li>
</ul>

## Differences
