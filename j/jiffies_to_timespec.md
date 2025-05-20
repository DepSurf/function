# Function: <code>jiffies_to_timespec</code>

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
In kernel/sched/core.c (ffffffff810ae392)
Location: include/linux/jiffies.h:422
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
```
```
In kernel/time/itimer.c (ffffffff810f0210)
Location: include/linux/jiffies.h:422
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f24fc)
Location: include/linux/jiffies.h:422
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
```
```
In drivers/ata/libata-transport.c (ffffffff815da9f8)
Location: include/linux/jiffies.h:422
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_show_ering
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
In kernel/sched/core.c (ffffffff810b0d74)
Location: include/linux/jiffies.h:422
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
```
```
In kernel/time/itimer.c (ffffffff810f7240)
Location: include/linux/jiffies.h:422
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f95dc)
Location: include/linux/jiffies.h:422
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
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
In kernel/sched/core.c (ffffffff810b6fd4)
Location: include/linux/jiffies.h:426
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81106f6c)
Location: include/linux/jiffies.h:426
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
```
```
In kernel/time/itimer.c (ffffffff81109900)
Location: include/linux/jiffies.h:426
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
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
In kernel/sched/core.c (ffffffff810b3305)
Location: include/linux/jiffies.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
```
</details>
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
