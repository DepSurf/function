# Function: <code>mul_u32_u32</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100876)
Location: include/linux/math64.h:140
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b65c)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff811174f2)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81122b3d)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff8112d18a)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8b70)
Location: include/linux/math64.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6900)
Location: include/linux/math64.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e88cd)
Location: include/linux/math64.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810fffbb)
Location: include/linux/math64.h:151
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111b28f)
Location: include/linux/math64.h:151
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
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
In kernel/sched/fair.c (ffffffff81142d3f)
Location: include/linux/math64.h:155
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In net/ethtool/ioctl.c (ffffffff81e78029)
Location: include/linux/math64.h:155
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
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
In kernel/sched/fair.c (ffffffff81152d3b)
Location: include/linux/math64.h:155
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In net/ethtool/ioctl.c (ffffffff81ed41a9)
Location: include/linux/math64.h:155
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
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
In kernel/sched/fair.c (ffffffff8115ef54)
Location: include/linux/math64.h:155
Inline: True
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81a0ac1c)
Location: include/linux/math64.h:155
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
```
```
In drivers/gpu/drm/drm_modes.c (ffffffff81ca4c73)
Location: include/linux/math64.h:155
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modes.c:drm_mode_vrefresh
```
```
In drivers/gpu/drm/drm_rect.c (ffffffff81ccf420)
Location: include/linux/math64.h:155
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
```
```
In net/ethtool/ioctl.c (ffffffff81f97bb9)
Location: include/linux/math64.h:155
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
</details>
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
In kernel/time/timekeeping.c (ffff8000101a37e0)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/sched/fair.c (c039041c)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (c03ab520)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/timekeeping.c (c03ef5c0)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:mul_u64_u32_div
```
```
In kernel/time/clocksource.c (c03f2180)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In kernel/sched/fair.c (c00000000018f7b4)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (c0000000001b4058)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/timekeeping.c (c000000000205438)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
```
In kernel/time/clocksource.c (c000000000209a84)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In kernel/time/timekeeping.c (ffffffe00013036e)
Location: include/linux/math64.h:168
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
