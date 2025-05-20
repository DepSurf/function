# Function: <code>timespec64_to_ns</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81115191)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
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
In kernel/time/posix-cpu-timers.c (ffffffff8112191f)
Location: include/linux/time64.h:117
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
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
In kernel/time/timekeeping.c (ffffffff828af944)
Location: include/linux/time64.h:118
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d03f)
Location: include/linux/time64.h:118
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
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
In kernel/time/timekeeping.c (ffffffff828c84d6)
Location: include/linux/time64.h:131
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828d0ab4)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff82cf19e4)
Location: include/linux/time64.h:125
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/itimer.c (ffffffff811549d2)
Location: include/linux/time64.h:125
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
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
In kernel/time/timekeeping.c (ffffffff82fde46e)
Location: include/linux/time64.h:125
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/itimer.c (ffffffff81150c08)
Location: include/linux/time64.h:125
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In fs/proc/array.c (ffffffff813d440a)
Location: include/linux/time64.h:125
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/time/timekeeping.c (ffffffff831e8f98)
Location: include/linux/time64.h:125
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/itimer.c (ffffffff81152038)
Location: include/linux/time64.h:125
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In fs/proc/array.c (ffffffff813db23c)
Location: include/linux/time64.h:125
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/time/timekeeping.c (ffffffff832cd54c)
Location: include/linux/time64.h:127
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/itimer.c (ffffffff81176594)
Location: include/linux/time64.h:127
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In fs/proc/array.c (ffffffff8142c8b1)
Location: include/linux/time64.h:127
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/ptp/ptp_vclock.c (ffffffff819dae9c)
Location: include/linux/time64.h:127
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_read
  - drivers/ptp/ptp_vclock.c:ptp_vclock_settime
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
In kernel/time/timekeeping.c (ffffffff8348113a)
Location: include/linux/time64.h:127
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/itimer.c (ffffffff811ab9e6)
Location: include/linux/time64.h:127
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In fs/proc/array.c (ffffffff814a6186)
Location: include/linux/time64.h:127
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3e688)
Location: include/linux/time64.h:127
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_read
  - drivers/ptp/ptp_vclock.c:ptp_vclock_settime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
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
In kernel/time/timekeeping.c (ffffffff83eadf7a)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/itimer.c (ffffffff811ebc76)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In fs/proc/array.c (ffffffff8153b7c6)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd48e8)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_read
  - drivers/ptp/ptp_vclock.c:ptp_vclock_settime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
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
In kernel/time/timekeeping.c (ffffffff836d2fb2)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/itimer.c (ffffffff812003a6)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In fs/proc/array.c (ffffffff81573af1)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3c548)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_read
  - drivers/ptp/ptp_vclock.c:ptp_vclock_settime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
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
In kernel/time/timekeeping.c (ffffffff83904d72)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/time/itimer.c (ffffffff81216846)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In fs/proc/array.c (ffffffff815ac4bd)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df2e88)
Location: include/linux/time64.h:130
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_read
  - drivers/ptp/ptp_vclock.c:ptp_vclock_settime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
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
In arch/arm/xen/enlighten.c (ffff8000100f01a0)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffff800011448a1c)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ec588)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime
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
In kernel/time/timekeeping.c (c1522a64)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0ace4c4)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0e34)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_ptp_settime
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
In kernel/time/timekeeping.c (c00000000136dbac)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffe000009f74)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828b9965)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828b1eb6)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828cc6e8)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828d1ae2)
Location: include/linux/time64.h:133
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
</details>
</li>
</ul>

## Differences
