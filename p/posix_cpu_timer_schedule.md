# Function: <code>posix_cpu_timer_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void posix_cpu_timer_schedule(struct k_itimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f2f00)
Location: kernel/time/posix-cpu-timers.c:1046
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
**Symbols:**

```
ffffffff810f2f00-ffffffff810f3081: posix_cpu_timer_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void posix_cpu_timer_schedule(struct k_itimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810fa010)
Location: kernel/time/posix-cpu-timers.c:1019
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
**Symbols:**

```
ffffffff810fa010-ffffffff810fa194: posix_cpu_timer_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void posix_cpu_timer_schedule(struct k_itimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81107990)
Location: kernel/time/posix-cpu-timers.c:1015
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
**Symbols:**

```
ffffffff81107990-ffffffff81107b14: posix_cpu_timer_schedule (STB_GLOBAL)
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
