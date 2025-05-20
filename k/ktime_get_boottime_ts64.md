# Function: <code>ktime_get_boottime_ts64</code>

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
In kernel/time/posix-timers.c (ffffffff8111e4d5)
Location: include/linux/timekeeping.h:144
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ace57)
Location: include/linux/timekeeping.h:159
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff81129d25)
Location: include/linux/timekeeping.h:159
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff8133bd7a)
Location: include/linux/timekeeping.h:159
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b26a6)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff811347a5)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff81363fb7)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b8d76)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff811407b5)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff8137c247)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c0eea)
Location: include/linux/timekeeping.h:187
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8114e296)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114f9b6)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff8115a44c)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff813c5b0b)
Location: include/linux/timekeeping.h:187
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
In kernel/sys.c (ffffffff810bc04a)
Location: include/linux/timekeeping.h:186
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8114a526)
Location: include/linux/timekeeping.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114bc36)
Location: include/linux/timekeeping.h:186
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff811564a5)
Location: include/linux/timekeeping.h:186
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff813d7aab)
Location: include/linux/timekeeping.h:186
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
In kernel/sys.c (ffffffff810bd8ca)
Location: include/linux/timekeeping.h:187
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8114b9e6)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114d0e6)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff811578a5)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff813de961)
Location: include/linux/timekeeping.h:187
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
In kernel/sys.c (ffffffff810d039d)
Location: include/linux/timekeeping.h:187
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8116f6f6)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff81171126)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff8117c71a)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff814302b7)
Location: include/linux/timekeeping.h:187
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
In kernel/sys.c (ffffffff810e92dd)
Location: include/linux/timekeeping.h:188
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811a3c06)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811a5806)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff811b2008)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff814a9f5c)
Location: include/linux/timekeeping.h:188
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
In kernel/sys.c (ffffffff8110a1ad)
Location: include/linux/timekeeping.h:188
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811e3456)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811e5246)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff811f2e38)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff8153fb02)
Location: include/linux/timekeeping.h:188
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
In kernel/sys.c (ffffffff8111647d)
Location: include/linux/timekeeping.h:188
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811f7a86)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811f98a6)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff81207605)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff81577e82)
Location: include/linux/timekeeping.h:188
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
In kernel/sys.c (ffffffff8111fe6d)
Location: include/linux/timekeeping.h:189
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8120dc26)
Location: include/linux/timekeeping.h:189
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8120fa96)
Location: include/linux/timekeeping.h:189
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff8121e815)
Location: include/linux/timekeeping.h:189
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff815b05e1)
Location: include/linux/timekeeping.h:189
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff8000101144d8)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffff8000101aab80)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffff8000104489f8)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036ea60)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_sysinfo
```
```
In kernel/time/posix-timers.c (c03f6210)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (c060db70)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015d164)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (c00000000020e7d0)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (c00000000055f100)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d217c)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffe000135ecc)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffe0002de550)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b30e6)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff81138f65)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff81374827)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a1a16)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff8112b9b5)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff813652f7)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2646)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff81136c85)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff813722f7)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bac46)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/posix-timers.c (ffffffff81143715)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In fs/proc/uptime.c (ffffffff81385cd7)
Location: include/linux/timekeeping.h:187
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
</details>
</li>
</ul>

## Differences
