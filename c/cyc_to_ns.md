# Function: <code>cyc_to_ns</code>

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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (ffff800011449248)
Location: kernel/time/sched_clock.c:91
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:update_sched_clock
  - kernel/time/sched_clock.c:sched_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (c1523378)
Location: kernel/time/sched_clock.c:91
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:update_sched_clock
  - kernel/time/sched_clock.c:sched_clock
```
```
In arch/arm/lib/delay.c (c15baffc)
Location: arch/arm/lib/delay.c:40
Inline: True
Inline callers:
  - arch/arm/lib/delay.c:register_current_timer_delay
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (ffffffe00000a6ea)
Location: kernel/time/sched_clock.c:91
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/sched_clock.c:update_sched_clock
  - kernel/time/sched_clock.c:sched_clock
```
</details>
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
