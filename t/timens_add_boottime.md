# Function: <code>timens_add_boottime</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c0efc)
Location: include/linux/time_namespace.h:72
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8114e2ad)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114f9cd)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In fs/proc/uptime.c (ffffffff813c5b1d)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff810bc05c)
Location: include/linux/time_namespace.h:72
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8114a53d)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114bc4d)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In fs/proc/uptime.c (ffffffff813d7abd)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff810bd8dc)
Location: include/linux/time_namespace.h:72
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8114b9fd)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114d0fd)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In fs/proc/uptime.c (ffffffff813de973)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff810d03af)
Location: include/linux/time_namespace.h:72
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8116f70d)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8117113d)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In fs/proc/uptime.c (ffffffff814302c9)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff810e92ef)
Location: include/linux/time_namespace.h:72
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811a3c1d)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811a581d)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In fs/proc/uptime.c (ffffffff814a9f6e)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff8110a1bf)
Location: include/linux/time_namespace.h:73
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811e346d)
Location: include/linux/time_namespace.h:73
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811e525d)
Location: include/linux/time_namespace.h:73
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In fs/proc/uptime.c (ffffffff8153fb14)
Location: include/linux/time_namespace.h:73
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff8111648f)
Location: include/linux/time_namespace.h:72
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811f7a9d)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811f98bd)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In fs/proc/uptime.c (ffffffff81577e94)
Location: include/linux/time_namespace.h:72
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
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
In kernel/sys.c (ffffffff8111fe7f)
Location: include/linux/time_namespace.h:75
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8120dc3d)
Location: include/linux/time_namespace.h:75
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8120faad)
Location: include/linux/time_namespace.h:75
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In fs/proc/uptime.c (ffffffff815b05f3)
Location: include/linux/time_namespace.h:75
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
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
