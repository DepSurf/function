# Function: <code>omap_dm_timer_write_reg</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
void omap_dm_timer_write_reg(struct omap_dm_timer *timer, u32 reg, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-ti-dm.c (c0c47864)
Location: drivers/clocksource/timer-ti-dm.c:88
Inline: False
Direct callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_prescaler
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_pwm
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_start
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_trigger
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:omap_timer_restore_context
  - drivers/clocksource/timer-ti-dm.c:omap_timer_restore_context
  - drivers/clocksource/timer-ti-dm.c:omap_timer_restore_context
  - drivers/clocksource/timer-ti-dm.c:omap_timer_restore_context
  - drivers/clocksource/timer-ti-dm.c:omap_timer_restore_context
  - drivers/clocksource/timer-ti-dm.c:omap_timer_restore_context
```
**Symbols:**

```
c0c47864-c0c47910: omap_dm_timer_write_reg (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
