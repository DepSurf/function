# Function: <code>ktime_to_us</code>

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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:199
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:199
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/ktime.h:199
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816baf80)
Location: include/linux/ktime.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bb9f1)
Location: include/linux/ktime.h:199
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (0)
Location: include/linux/ktime.h:199
Inline: True
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:199
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81105681)
Location: include/linux/ktime.h:199
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d2ca)
Location: include/linux/ktime.h:199
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8171e927)
Location: include/linux/ktime.h:199
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:173
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110cdc1)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525383)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174feaa)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81751487)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:173
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110ec99)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537c80)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176e964)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8176ff6a)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:173
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81119ef0)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815994d7)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e41ab)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff817e588d)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:173
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81126a92)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d0d54)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d436)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8182f045)
Location: include/linux/ktime.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81132172)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea384)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816a2e69)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8185942d)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8185b2e4)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113cfaa)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In lib/dim/dim.c (ffffffff81538780)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c154)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816dc3bb)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cf61)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8189ec72)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff8189f1dc)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8114885a)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff81511fe5)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81559560)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163dba4)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816ffc3b)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf095)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818d1052)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff818d148e)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:158
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81158e13)
Location: include/linux/ktime.h:158
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff81572fa1)
Location: include/linux/ktime.h:158
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff815e2e30)
Location: include/linux/ktime.h:158
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eaf64)
Location: include/linux/ktime.h:158
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff817b9b7e)
Location: include/linux/ktime.h:158
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a150a)
Location: include/linux/ktime.h:158
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff819a25c5)
Location: include/linux/ktime.h:158
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff819a31e8)
Location: include/linux/ktime.h:158
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_update
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:159
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81154df3)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff8158f914)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81607268)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817086c4)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff817ce65e)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a456e)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff819a55a5)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff819a61c8)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_update
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:159
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81155ed3)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff81596897)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff815e9fb8)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9cc4)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff8172b45a)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff817b2065)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819893a3)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/sysfs.c (ffffffff8198a215)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8198b26d)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:159
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8117ab6f)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff815fdead)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81656398)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81763565)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff817ab34d)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff8183b2aa)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff8184dcb1)
Location: include/linux/ktime.h:159
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a33743)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/sysfs.c (ffffffff81a34b75)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81a35fb9)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In init/main.c (ffffffff81000cab)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:159
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811b0543)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff816ae5a1)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff8176dad2)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818974c7)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff818e5ff5)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff8197d834)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff81993511)
Location: include/linux/ktime.h:159
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81b9f293)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff81ba1475)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81ba29d2)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In init/main.c (ffffffff810010cb)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:159
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811f1033)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff8176b09e)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff8189d312)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df22f)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81a3e987)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81aeacd6)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff81b03ed3)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d40c83)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff81d43235)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81d44922)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In init/main.c (ffffffff81000e8b)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:159
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81204f99)
Location: include/linux/ktime.h:159
Inline: True
```
```
In block/blk-iocost.c (ffffffff817acd96)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff818df8c3)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a26f3f)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81a8841a)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81b38fbe)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff81b52a36)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/cpuidle/cpuidle.c (ffffffff821421b0)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff81dad455)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81daed8f)
Location: include/linux/ktime.h:159
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In init/main.c (ffffffff81000e9b)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:157
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8121b669)
Location: include/linux/ktime.h:157
Inline: True
```
```
In block/blk-iocost.c (ffffffff817f0b95)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81926403)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a71f4f)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81adab0a)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81b90a7e)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff81bab0e6)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/cpuidle/cpuidle.c (ffffffff822248a0)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff81e654f5)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81e66ef9)
Location: include/linux/ktime.h:157
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffff8000101b4a70)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffff8000106156bc)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffff800010665c58)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8a84)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffff8000108eae74)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4b68)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26df0)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffff800010b29af8)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffff800010b29f24)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
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
In kernel/sched/deadline.c (c03a0a24)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/tick-sched.c (c03ff0ec)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (c07bfea8)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (c080e804)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/clk/ti/clkctrl.c (c09185f0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In drivers/base/dd.c (c09d8fe0)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e8b0)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
```
```
In drivers/cpuidle/cpuidle.c (c0c01cb8)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (c0c04610)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (c0c04ad8)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/firmware/tegra/bpmp.c (c0c425e0)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (c000000000219e44)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (c0000000007b4e2c)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (c00000000081b500)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/base/dd.c (c000000000982274)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1df50)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (c000000000c216d4)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (c000000000c21bdc)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffe00013adb0)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffe00044c810)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffe000491e64)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/base/dd.c (ffffffe00057ebf4)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81140e7a)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff8150a5c5)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81551b40)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816095d4)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816c542b)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872b55)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81874a2b)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff81874e5e)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81133c1a)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff814faa55)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81541e20)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb214)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816a06ab)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c92a)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8183e8e2)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff8183ed1e)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113ed2a)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff81506655)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff8154d880)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816319e4)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816f38fb)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c4545)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818c6502)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
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
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:176
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8114b89a)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff8151f945)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff815676d0)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164bd14)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff8170e12b)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c816)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e08c5)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818e2962)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff818e2d9e)
Location: include/linux/ktime.h:176
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
</details>
</li>
</ul>

## Differences
