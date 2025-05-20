# Function: <code>timespec64_add</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110d22d)
Location: include/linux/time64.h:64
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff8110e464)
Location: include/linux/time64.h:64
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff8178a2d2)
Location: include/linux/time64.h:64
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffff81118dac)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff81119dcf)
Location: include/linux/time64.h:65
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff817cb3e8)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffff81124836)
Location: include/linux/time64.h:66
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff811252cf)
Location: include/linux/time64.h:66
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff817f2a98)
Location: include/linux/time64.h:66
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffff8112f177)
Location: include/linux/time64.h:69
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff8112fd51)
Location: include/linux/time64.h:69
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff81833775)
Location: include/linux/time64.h:69
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffff8113b137)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff8113bc91)
Location: include/linux/time64.h:71
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff818650b5)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/sys.c (ffffffff810c0f13)
Location: include/linux/time64.h:63
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff8114a17b)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff8114b004)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_cmos_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8114e2c1)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114f9e1)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
```
```
In kernel/time/namespace.c (ffffffff8115a483)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff813c5b34)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/rtc/systohc.c (ffffffff81938905)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/sys.c (ffffffff810bc073)
Location: include/linux/time64.h:63
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff811466cb)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff81147441)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8114a551)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114bc61)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
```
```
In kernel/time/namespace.c (ffffffff811564dc)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff813d7ad4)
Location: include/linux/time64.h:63
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
In kernel/sys.c (ffffffff810bd8f3)
Location: include/linux/time64.h:63
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff81147841)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff81148571)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8114ba11)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114d111)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
```
```
In kernel/time/namespace.c (ffffffff811578dc)
Location: include/linux/time64.h:63
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff813de98a)
Location: include/linux/time64.h:63
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
In kernel/sys.c (ffffffff810d03c8)
Location: include/linux/time64.h:65
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff8116b359)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff8116c121)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8116f721)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff81171151)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
```
```
In kernel/time/namespace.c (ffffffff8117c751)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff814302e0)
Location: include/linux/time64.h:65
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
In kernel/sys.c (ffffffff810e931a)
Location: include/linux/time64.h:65
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff8119f228)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff811a00cc)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff811a3c4a)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811a584a)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
```
```
In kernel/time/namespace.c (ffffffff811b2043)
Location: include/linux/time64.h:65
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff814a9f99)
Location: include/linux/time64.h:65
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
In kernel/sys.c (ffffffff8110a1ea)
Location: include/linux/time64.h:68
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff811ddeb8)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff811deedc)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff811e349a)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811e528a)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
```
```
In kernel/time/namespace.c (ffffffff811f2e73)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff8153fb3f)
Location: include/linux/time64.h:68
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
In kernel/sys.c (ffffffff811164ba)
Location: include/linux/time64.h:68
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff811f2388)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff811f33bc)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff811f7aca)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811f98ea)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
```
```
In kernel/time/namespace.c (ffffffff81207649)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff81577ebf)
Location: include/linux/time64.h:68
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
In kernel/sys.c (ffffffff8111feaa)
Location: include/linux/time64.h:68
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff812084c8)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff812094fc)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8120dc6a)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8120fada)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
```
```
In kernel/time/namespace.c (ffffffff8121e859)
Location: include/linux/time64.h:68
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In fs/proc/uptime.c (ffffffff815b061b)
Location: include/linux/time64.h:68
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
In arch/arm/xen/enlighten.c (ffff80001143aa70)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_pm_init
  - arch/arm/xen/enlighten.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffff8000101a52bc)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In drivers/rtc/systohc.c (ffff800010aa690c)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (c03f02ac)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In drivers/rtc/systohc.c (c0b85420)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (c000000000207090)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (c0000000002081ac)
Location: include/linux/time64.h:71
Inline: True
```
```
In drivers/rtc/systohc.c (c000000000b87544)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffe000131862)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In drivers/rtc/systohc.c (ffffffe0006b2c1e)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffff811338e7)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff81134441)
Location: include/linux/time64.h:71
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff81817d65)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffff81126347)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff81126ea1)
Location: include/linux/time64.h:71
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff817df455)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffff81131607)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff81132161)
Location: include/linux/time64.h:71
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff81859245)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/timekeeping.c (ffffffff8113e027)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff8113eb81)
Location: include/linux/time64.h:71
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff81874325)
Location: include/linux/time64.h:71
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
</ul>

## Differences
