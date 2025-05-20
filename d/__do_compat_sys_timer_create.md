# Function: <code>__do_compat_sys_timer_create</code>

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
In kernel/time/posix-timers.c (ffffffff8111fd3b)
Location: kernel/time/posix-timers.c:602
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff8112b51b)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff811365bb)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff8114265b)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff81150f3b)
Location: kernel/time/posix-timers.c:592
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff8114d1bb)
Location: kernel/time/posix-timers.c:592
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff8114f6bc)
Location: kernel/time/posix-timers.c:592
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff8117389c)
Location: kernel/time/posix-timers.c:592
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x64_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff811a6b4c)
Location: kernel/time/posix-timers.c:592
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff811e670c)
Location: kernel/time/posix-timers.c:592
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff811fad0c)
Location: kernel/time/posix-timers.c:545
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff81210efc)
Location: kernel/time/posix-timers.c:545
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffff8000101ac864)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__arm64_compat_sys_timer_create
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c0000000002104c4)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_compat_sys_timer_create
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8113ae0b)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff8112d85b)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff81138b2b)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
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
In kernel/time/posix-timers.c (ffffffff811456fb)
Location: kernel/time/posix-timers.c:566
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
```
</details>
</li>
</ul>

## Differences
