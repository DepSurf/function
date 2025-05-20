# Function: <code>get_monotonic_boottime</code>

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
In kernel/sys.c (ffffffff81092bc7)
Location: include/linux/timekeeping.h:240
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff810f0ab6)
Location: include/linux/timekeeping.h:240
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff8128340d)
Location: include/linux/timekeeping.h:240
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff81095d57)
Location: include/linux/timekeeping.h:256
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff810f7ad6)
Location: include/linux/timekeeping.h:256
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff812b0468)
Location: include/linux/timekeeping.h:256
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff8109ad27)
Location: include/linux/timekeeping.h:257
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff81105476)
Location: include/linux/timekeeping.h:257
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff812c5e5d)
Location: include/linux/timekeeping.h:257
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff81097b29)
Location: include/linux/timekeeping.h:246
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In fs/proc/uptime.c (ffffffff812d3066)
Location: include/linux/timekeeping.h:246
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff8109e819)
Location: include/linux/timekeeping32.h:135
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In fs/proc/uptime.c (ffffffff812f785c)
Location: include/linux/timekeeping32.h:135
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff810a4087)
Location: include/linux/timekeeping32.h:84
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In fs/proc/uptime.c (ffffffff81324bda)
Location: include/linux/timekeeping32.h:84
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
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
