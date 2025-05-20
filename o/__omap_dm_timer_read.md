# Function: <code>__omap_dm_timer_read</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/timer.c (c0335b04)
Location: include/clocksource/timer-ti-dm.h:255
Inline: True
Inline callers:
  - arch/arm/mach-omap2/timer.c:clocksource_read_cycles
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
```
```
In drivers/clocksource/timer-ti-dm.c (c0c48860)
Location: include/clocksource/timer-ti-dm.h:255
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timers_active
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_prescaler
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_pwm
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_start
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
```
</details>
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
