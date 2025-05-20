# Function: <code>div_s64</code>

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
In kernel/time/ntp.c (0)
Location: include/linux/math64.h:108
Inline: True
```
```
In lib/vsprintf.c (ffffffff813f3422)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/rtc/rtc-lib.c (ffffffff81673025)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8168a056)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
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
In kernel/time/ntp.c (ffffffff810fea50)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In lib/vsprintf.c (ffffffff8143b0ba)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/rtc/rtc-lib.c (ffffffff816d3815)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff816eae6c)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In kernel/time/ntp.c (ffffffff81101840)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In lib/vsprintf.c (ffffffff8145808e)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/rtc/rtc-lib.c (ffffffff817034f5)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8171bd8c)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
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
In kernel/time/ntp.c (ffffffff81103942)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/rtc/rtc-lib.c (ffffffff81718ce5)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff8173401b)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff818f9c04)
Location: include/linux/math64.h:108
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810c9e3e)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/time/ntp.c (ffffffff8110e9d2)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/rtc/rtc-lib.c (ffffffff81789ec5)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
```
```
In drivers/thermal/power_allocator.c (ffffffff817a51dd)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81980882)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810d1e7a)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/time/ntp.c (ffffffff8111a41d)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffff817ecc8b)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff819dc8fb)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810db7de)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
```
```
In kernel/time/ntp.c (ffffffff8112591d)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffff81818db1)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81a14dfa)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810db779)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (ffffffff81130349)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffff8185aeda)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81a84668)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810e5e33)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (ffffffff8113c289)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffff8188c9ea)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81abb8cc)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810eceec)
Location: include/linux/math64.h:137
Inline: True
```
```
In kernel/time/ntp.c (ffffffff8114a919)
Location: include/linux/math64.h:137
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_offset
```
```
In lib/vsprintf.c (ffffffff815f7419)
Location: include/linux/math64.h:137
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8195b35f)
Location: include/linux/math64.h:137
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffffffff810eacea)
Location: include/linux/math64.h:137
Inline: True
```
```
In kernel/time/ntp.c (ffffffff81146e09)
Location: include/linux/math64.h:137
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_offset
```
```
In lib/vsprintf.c (ffffffff8161b844)
Location: include/linux/math64.h:137
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81962020)
Location: include/linux/math64.h:137
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffffffff810ecb73)
Location: include/linux/math64.h:137
Inline: True
```
```
In kernel/time/ntp.c (ffffffff811480dc)
Location: include/linux/math64.h:137
Inline: True
Inline callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8194561f)
Location: include/linux/math64.h:137
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffffffff811057c3)
Location: include/linux/math64.h:138
Inline: True
```
```
In kernel/time/ntp.c (ffffffff8116bac4)
Location: include/linux/math64.h:138
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_offset
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d73ce)
Location: include/linux/math64.h:138
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff819dafd0)
Location: include/linux/math64.h:138
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819ea04f)
Location: include/linux/math64.h:138
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/time/ntp.c (ffffffff8119f9ea)
Location: include/linux/math64.h:138
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_offset
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39f56)
Location: include/linux/math64.h:138
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3e7af)
Location: include/linux/math64.h:138
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4fd03)
Location: include/linux/math64.h:138
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/time/ntp.c (ffffffff811de74e)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_offset
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf8d6)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd4a95)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce7c53)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/time/ntp.c (ffffffff811f2c1e)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_offset
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d379cf)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3c6f5)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d50433)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffffffff8116bc8a)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:avg_vruntime
```
```
In kernel/time/ntp.c (ffffffff81208d5e)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_offset
```
```
In mm/ksm.c (ffffffff8148cef6)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - mm/ksm.c:scan_time_advisor
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb5683)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedc4f)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df3035)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e07288)
Location: include/linux/math64.h:142
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
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
In kernel/sched/fair.c (ffff800010145594)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (ffff8000101a6590)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffff800010adb62c)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/armada_thermal.c (ffff800010ade164)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In lib/vsprintf.c (ffff800010d98784)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (c0393080)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/sched/deadline.c (c03a115c)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/ntp.c (c03f1770)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (c0bbb9fc)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/armada_thermal.c (c0bbfff0)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_read_sensor
  - drivers/thermal/armada_thermal.c:armada_read_sensor
```
```
In lib/vsprintf.c (c0e9379c)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (c0000000001969ec)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (c0000000002088dc)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (c000000000bc31a0)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (c000000000edbe84)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffe0000f03c2)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (ffffffe0001326c0)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d571c)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffe0008c0092)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810dffe3)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (ffffffff81134a39)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffff8183286a)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81a5a71c)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810cefe3)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (ffffffff81127499)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffff817f9efa)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81a177fc)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810dc363)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (ffffffff81132759)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffff81881e9a)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a1a3d)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In lib/vsprintf.c (ffffffff81ac6b0c)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/fair.c (ffffffff810e8083)
Location: include/linux/math64.h:136
Inline: True
```
```
In kernel/time/ntp.c (ffffffff8113f179)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
```
In drivers/thermal/power_allocator.c (ffffffff8189d905)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In lib/vsprintf.c (ffffffff81ad2fec)
Location: include/linux/math64.h:136
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
</li>
</ul>

## Differences
