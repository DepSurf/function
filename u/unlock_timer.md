# Function: <code>unlock_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f0e30)
Location: kernel/time/posix-timers.c:200
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:do_schedule_next_timer
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f8e14)
Location: kernel/time/posix-timers.c:200
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:do_schedule_next_timer
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
In kernel/time/posix-timers.c (ffffffff811067a4)
Location: kernel/time/posix-timers.c:200
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:do_schedule_next_timer
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
In kernel/time/posix-timers.c (ffffffff81108a48)
Location: kernel/time/posix-timers.c:191
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff81113bfb)
Location: kernel/time/posix-timers.c:192
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:posixtimer_rearm
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
In kernel/time/posix-timers.c (ffffffff81120a2c)
Location: kernel/time/posix-timers.c:192
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff8112c145)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff81134a4c)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff81140ad7)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff811510e7)
Location: kernel/time/posix-timers.c:164
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff8114d367)
Location: kernel/time/posix-timers.c:164
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff8114f986)
Location: kernel/time/posix-timers.c:164
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff81173a46)
Location: kernel/time/posix-timers.c:164
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff811a5d50)
Location: kernel/time/posix-timers.c:164
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff811e5840)
Location: kernel/time/posix-timers.c:164
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff811fa5f0)
Location: kernel/time/posix-timers.c:126
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff812107e0)
Location: kernel/time/posix-timers.c:126
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffff8000101ac0f0)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__arm64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (c03f7074)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (c00000000020ed24)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffe0001368d2)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__se_sys_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff81139287)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff8112da07)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff81136fa7)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
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
In kernel/time/posix-timers.c (ffffffff81143a3e)
Location: kernel/time/posix-timers.c:162
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:posixtimer_rearm
```
</details>
</li>
</ul>

## Differences
