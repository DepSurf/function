# Function: <code>posix_timers_register_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void posix_timers_register_clock(const clockid_t clock_id, struct k_clock *new_clock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f0e90)
Location: kernel/time/posix-timers.c:523
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/alarmtimer.c:alarmtimer_init
  - kernel/time/alarmtimer.c:alarmtimer_init
```
**Symbols:**

```
ffffffff810f0e90-ffffffff810f0f61: posix_timers_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void posix_timers_register_clock(const clockid_t clock_id, struct k_clock *new_clock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f7e90)
Location: kernel/time/posix-timers.c:523
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/alarmtimer.c:alarmtimer_init
  - kernel/time/alarmtimer.c:alarmtimer_init
```
**Symbols:**

```
ffffffff810f7e90-ffffffff810f7f61: posix_timers_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void posix_timers_register_clock(const clockid_t clock_id, struct k_clock *new_clock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81105820)
Location: kernel/time/posix-timers.c:523
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - kernel/time/alarmtimer.c:alarmtimer_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/time/posix-timers.c:init_posix_timers
```
**Symbols:**

```
ffffffff81105820-ffffffff811058f1: posix_timers_register_clock (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
