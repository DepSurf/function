# Function: <code>clockid_to_kclock</code>

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
In kernel/time/posix-timers.c (ffffffff810f0fb5)
Location: kernel/time/posix-timers.c:583
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_clock_settime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:clock_nanosleep_restart
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
In kernel/time/posix-timers.c (ffffffff810f9281)
Location: kernel/time/posix-timers.c:583
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:clock_nanosleep_restart
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_clock_settime
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_create
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
In kernel/time/posix-timers.c (ffffffff81106c11)
Location: kernel/time/posix-timers.c:583
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:clock_nanosleep_restart
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_clock_settime
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81109041)
Location: kernel/time/posix-timers.c:1342
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:compat_SyS_clock_getres
  - kernel/time/posix-timers.c:C_SYSC_clock_adjtime
  - kernel/time/posix-timers.c:compat_SyS_clock_gettime
  - kernel/time/posix-timers.c:compat_SyS_clock_settime
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:compat_SyS_clock_getres
  - kernel/time/posix-timers.c:C_SYSC_clock_adjtime
  - kernel/time/posix-timers.c:compat_SyS_clock_gettime
  - kernel/time/posix-timers.c:compat_SyS_clock_settime
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81107ca0-ffffffff81107cbf: clockid_to_kclock.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81114211)
Location: kernel/time/posix-timers.c:1348
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:compat_SyS_clock_getres
  - kernel/time/posix-timers.c:C_SYSC_clock_adjtime
  - kernel/time/posix-timers.c:compat_SyS_clock_gettime
  - kernel/time/posix-timers.c:compat_SyS_clock_settime
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:compat_SyS_clock_getres
  - kernel/time/posix-timers.c:C_SYSC_clock_adjtime
  - kernel/time/posix-timers.c:compat_SyS_clock_gettime
  - kernel/time/posix-timers.c:compat_SyS_clock_settime
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81112e20-ffffffff81112e4a: clockid_to_kclock.part.6 (STB_LOCAL)
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
In kernel/time/posix-timers.c (ffffffff811205f3)
Location: kernel/time/posix-timers.c:1367
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__do_compat_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff8112bdd3)
Location: kernel/time/posix-timers.c:1333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__do_compat_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81135072)
Location: kernel/time/posix-timers.c:1318
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81141092)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811520a2)
Location: kernel/time/posix-timers.c:1398
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff8114e322)
Location: kernel/time/posix-timers.c:1398
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff8114ee15)
Location: kernel/time/posix-timers.c:1398
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81172f78)
Location: kernel/time/posix-timers.c:1398
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811a84d8)
Location: kernel/time/posix-timers.c:1407
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811e8268)
Location: kernel/time/posix-timers.c:1409
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811fc858)
Location: kernel/time/posix-timers.c:1528
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81212a48)
Location: kernel/time/posix-timers.c:1528
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffff8000101ab240)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__arm64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__arm64_sys_clock_settime32
  - kernel/time/posix-timers.c:__arm64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__arm64_sys_clock_gettime
  - kernel/time/posix-timers.c:__arm64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (c03f7b68)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__se_sys_clock_gettime32
  - kernel/time/posix-timers.c:__se_sys_clock_settime32
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (c00000000020f658)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__se_sys_clock_gettime32
  - kernel/time/posix-timers.c:__se_sys_clock_settime32
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffe000136d84)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81139842)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff8112c292)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81137562)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81143ff2)
Location: kernel/time/posix-timers.c:1357
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
</details>
</li>
</ul>

## Differences
