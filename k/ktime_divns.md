# Function: <code>ktime_divns</code>

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
In arch/x86/events/intel/rapl.c (0)
Location: include/linux/ktime.h:188
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:188
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/ktime.h:188
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff810eec3f)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff810faaca)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff810fe41e)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In drivers/base/power/sysfs.c (ffffffff81553c6f)
Location: include/linux/ktime.h:188
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:188
Inline: True
```
```
In drivers/power/charger-manager.c (0)
Location: include/linux/ktime.h:188
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/ktime.h:188
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816baf80)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bb9f1)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (0)
Location: include/linux/ktime.h:188
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/ktime.h:188
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
Location: include/linux/ktime.h:188
Inline: True
```
```
In kernel/power/process.c (ffffffff810d24e2)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff810d3e4b)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff810f5c7e)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff81101d3a)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff81105681)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In drivers/base/power/sysfs.c (ffffffff815a5c6f)
Location: include/linux/ktime.h:188
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815adf8a)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
```
```
In drivers/power/charger-manager.c (ffffffff816e36d2)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/power/charger-manager.c:try_charger_enable
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d2ca)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8171e927)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff81819a47)
Location: include/linux/ktime.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
Location: include/linux/ktime.h:162
Inline: True
```
```
In kernel/power/process.c (ffffffff810d9092)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff810da9db)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff810fcd30)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff811044ea)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff8110cdc1)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525383)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff815d442f)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815dcd8a)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81713b42)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174feaa)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81751487)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff8184b307)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8103ee85)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In kernel/power/process.c (ffffffff810d8093)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff810d9abb)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff810fefd9)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff81106630)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff8110ec99)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537c80)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff815e8f9f)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815f1734)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172b101)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176e964)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8176ff6a)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff8186ed8c)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81041f32)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In kernel/power/process.c (ffffffff810e0184)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff810e1c5b)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff81109dbf)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff811116d0)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff81119ef0)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815994d7)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff816502af)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81658d21)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
```
```
In drivers/base/power/domain.c (ffffffff8165b092)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_active_time_show
  - drivers/base/power/domain.c:genpd_idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179c8a1)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e41ab)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff817e588d)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff818ef71c)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In kernel/power/process.c (ffffffff810e884b)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff810eabf9)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff81115363)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff8111d0c0)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff81126a92)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d0d54)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff8168be5f)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81694881)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/domain.c (ffffffff81696c7b)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_active_time_show
  - drivers/base/power/domain.c:genpd_idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e3d58)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817ea045)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d436)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8182f045)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff81946088)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/process.c (ffffffff810f3e5b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff810f6229)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff811209a3)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff81128800)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff81132172)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea384)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816a2e69)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff816abd8f)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b4f11)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/domain.c (ffffffff816b760b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180f688)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81816205)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8185942d)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8185b2e4)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff81976228)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/main.c (ffffffff810fbe4c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff810fc5fb)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff810fe7e2)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff8112b733)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff811332bc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff8113cfaa)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In lib/dim/dim.c (ffffffff81538780)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c154)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816dc3bb)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff816e59bf)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816ef561)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/domain.c (ffffffff816f25cf)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851d15)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81858435)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cf61)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8189ec72)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff8189f1dc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff819dfdac)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/main.c (ffffffff811073cc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81108a1b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff8110ac2e)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff81137229)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff8113f1a0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff8114885a)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff81511fe5)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81559560)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163dba4)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816ffc3b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff81709c8f)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81712db4)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81713dd2)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff817159bf)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81882f45)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81889ee5)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf095)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818d1052)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff818d148e)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a16d9c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:147
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:147
Inline: True
```
```
In kernel/power/main.c (ffffffff81111ecc)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff8111361d)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff8111580d)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff81145f7c)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff8114f224)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
```
```
In kernel/time/tick-sched.c (ffffffff81158e13)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff81572fa1)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff815e2e30)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eaf64)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff817b9b7e)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff817c4cef)
Location: include/linux/ktime.h:147
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817cea24)
Location: include/linux/ktime.h:147
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817cf8b2)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff817d0b86)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:147
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81951947)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819588df)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a150a)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff819a25c5)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff819a31e8)
Location: include/linux/ktime.h:147
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/power/main.c (ffffffff8110ef9c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81bde950)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff81bdf0a6)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff8114249c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff8114b6f4)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
```
```
In kernel/time/tick-sched.c (ffffffff81154df3)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff8158f914)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81607268)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817086c4)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff817ce65e)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff817d9793)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817e30e4)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817e3e72)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff817e50a2)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81956ed8)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195df7f)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a456e)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff819a55a5)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff819a61c8)
Location: include/linux/ktime.h:148
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/power/main.c (ffffffff8110fa3c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81bd0ac9)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff81bd11f9)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff8114367c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff8114cba4)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
```
```
In kernel/time/tick-sched.c (ffffffff81155ed3)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff81596897)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff815e9fb8)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9cc4)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff8172b45a)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff817b2065)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff817bdb53)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817c74a4)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817c82b2)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff817c9463)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193ae08)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8194152f)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819893a3)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/sysfs.c (ffffffff8198a215)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8198b26d)
Location: include/linux/ktime.h:148
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/power/main.c (ffffffff8112f38c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81ca97d7)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff81ca9d62)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff81166c5c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff811704c4)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
```
```
In kernel/time/tick-sched.c (ffffffff8117ab6f)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff815fdead)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81656398)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81763565)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff817ab34d)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff8183b2aa)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff81847ed3)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8184dcb1)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81851884)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff818527b2)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff81853983)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff819df5f2)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e5dbf)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a33743)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/sysfs.c (ffffffff81a34b75)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81a35fb9)
Location: include/linux/ktime.h:148
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
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/power/main.c (ffffffff811509dc)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81152107)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff81e59d70)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff8119a3fc)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff811a4a50)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
```
```
In kernel/time/tick-sched.c (ffffffff811b0543)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff816ae5a1)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff8176dad2)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818974c7)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff818e5ff5)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff8197d834)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff8198cacf)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81993511)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff819975c4)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff819986f2)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/cdrom/cdrom.c (ffffffff81a8bfbd)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b43e16)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4b29f)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81b9f293)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff81ba1475)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81ba29d2)
Location: include/linux/ktime.h:148
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
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/power/main.c (ffffffff8117f40c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81180f0e)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff8118343b)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff811d8b1c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff811e43d0)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
```
```
In kernel/time/tick-sched.c (ffffffff811f1033)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (ffffffff8176b09e)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff8189d312)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df22f)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81a3e987)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81aeacd6)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff81afc6df)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81b03ed3)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81b085c4)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b09822)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/cdrom/cdrom.c (ffffffff81c0cf3d)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cda9d6)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce2cf1)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d40c83)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff81d43235)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81d44922)
Location: include/linux/ktime.h:148
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
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In kernel/power/main.c (ffffffff8119011c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81191e03)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff811942ab)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff811ecf4c)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff811f8a30)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
```
```
In kernel/time/tick-sched.c (ffffffff81204f99)
Location: include/linux/ktime.h:148
Inline: True
```
```
In block/blk-iocost.c (ffffffff817acd96)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff818df8c3)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a26f3f)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81a8841a)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81b38fbe)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff81b4aacf)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81b52a36)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81b565f4)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b57831)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/cdrom/cdrom.c (ffffffff81c74a6b)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:148
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d42c96)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d4af81)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff821421b0)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff81dad455)
Location: include/linux/ktime.h:148
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81daed8f)
Location: include/linux/ktime.h:148
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
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:146
Inline: True
```
```
In kernel/power/main.c (ffffffff8119eadc)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff811a07f3)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff811a2c9b)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff812030ac)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff8120ebd0)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In kernel/time/tick-sched.c (ffffffff8121b669)
Location: include/linux/ktime.h:146
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/ktime.h:146
Inline: True
```
```
In block/blk-iocost.c (ffffffff817f0b95)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81926403)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a71f4f)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81adab0a)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81b90a7e)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff81ba2ebf)
Location: include/linux/ktime.h:146
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81bab0e6)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81baebe4)
Location: include/linux/ktime.h:146
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81bafe21)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3b08)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:commit_tail
```
```
In drivers/cdrom/cdrom.c (ffffffff81d2946a)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:146
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df9646)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e01ca1)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff822248a0)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/sysfs.c (ffffffff81e654f5)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_state_time
  - drivers/cpuidle/sysfs.c:show_state_target_residency
  - drivers/cpuidle/sysfs.c:show_state_exit_latency
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81e66ef9)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In net/core/page_pool_user.c (ffffffff81f4622e)
Location: include/linux/ktime.h:146
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_detached
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
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/main.c (ffff80001016e334)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffff80001016fb54)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffff8000101a0748)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffff8000101a8c10)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffff8000101b4a70)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffff8000106156bc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffff800010665c58)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8a84)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffff8000108eae74)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffff8000108f7d4c)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (ffff800010903e88)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffff800010905778)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffff800010906abc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4b68)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/power/supply/charger-manager.c (ffff800010acfa64)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad7940)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26df0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffff800010b29af8)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffff800010b29f24)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2f1c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
s64 ktime_divns(const ktime_t kt, s64 div);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (c03a0a24)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/power/main.c (c03ba0d4)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (c03ba500)
Location: include/linux/ktime.h:147
Inline: True
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (c03bc5dc)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (c03eb818)
Location: include/linux/ktime.h:147
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (c03f4554)
Location: include/linux/ktime.h:147
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (c03ff0ec)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In block/blk-iocost.c (c07c12a8)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/dim/dim.c (c080e804)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/clk/samsung/clk-pll.c (c090a8cc)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
```
```
In drivers/clk/ti/clkctrl.c (c09185f0)
Location: include/linux/ktime.h:147
Inline: True
```
```
In drivers/base/dd.c (c09d83b4)
Location: include/linux/ktime.h:147
Inline: True
Direct callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (c09e3cf0)
Location: include/linux/ktime.h:147
Inline: True
```
```
In drivers/base/power/wakeup.c (c09ee6ac)
Location: include/linux/ktime.h:147
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (c09ef598)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/base/power/domain.c (c09f3e20)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
Direct callers:
  - drivers/base/power/domain.c:total_idle_time_show
```
```
In drivers/usb/dwc2/core.c (c0b0d500)
Location: include/linux/ktime.h:147
Inline: True
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e8b0)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
```
```
In drivers/power/supply/charger-manager.c (c0baf89c)
Location: include/linux/ktime.h:147
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (c0bb7e90)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (c0c01734)
Location: include/linux/ktime.h:147
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (c0c03e34)
Location: include/linux/ktime.h:147
Inline: True
Direct callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (c0c04754)
Location: include/linux/ktime.h:147
Inline: True
Direct callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/firmware/tegra/bpmp.c (c0c41f38)
Location: include/linux/ktime.h:147
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
Direct callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
```
```
In net/ipv4/tcp_cubic.c (c0ddc940)
Location: include/linux/ktime.h:147
Inline: True
```
**Symbols:**

```
c03ba500-c03ba588: ktime_divns.constprop.0 (STB_LOCAL)
c03eb818-c03eb844: ktime_divns (STB_LOCAL)
c03f4554-c03f4580: ktime_divns (STB_LOCAL)
c03fe90c-c03fe938: ktime_divns (STB_LOCAL)
c07bfd50-c07bfde0: ktime_divns.constprop.0 (STB_LOCAL)
c09d83b4-c09d8448: ktime_divns.constprop.0 (STB_LOCAL)
c09e3cf0-c09e3d78: ktime_divns.constprop.0 (STB_LOCAL)
c09ee6ac-c09ee738: ktime_divns.constprop.0 (STB_LOCAL)
c09f2138-c09f21c0: ktime_divns.constprop.0 (STB_LOCAL)
c0baf89c-c0baf928: ktime_divns.constprop.0 (STB_LOCAL)
c0c01734-c0c017c8: ktime_divns.constprop.0 (STB_LOCAL)
c0c03e34-c0c03ec8: ktime_divns.constprop.0 (STB_LOCAL)
c0c04754-c0c047e8: ktime_divns.constprop.0 (STB_LOCAL)
c0c41d9c-c0c41e30: ktime_divns.constprop.0 (STB_LOCAL)
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
In arch/powerpc/platforms/pseries/lpar.c (c0000000000e9080)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/main.c (c0000000001c5c6c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (c0000000001c7b8c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (c0000000002020b0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (c00000000020c3e0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (c000000000219e44)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (c0000000007b4e2c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (c00000000081b500)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/base/dd.c (c000000000982274)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (c00000000099383c)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (c0000000009a2238)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (c0000000009a406c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (c0000000009a5eb4)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c000000000bb3578)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbded0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1df50)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (c000000000c216d4)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (c000000000c21bdc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In net/ipv4/tcp_cubic.c (c000000000df1140)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/process.c (ffffffe00010dbdc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffe00012dfd0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffe000134a7a)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffe00013adb0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffe00044c810)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffe000491e64)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/base/dd.c (ffffffe00057ebf4)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/domain.c (ffffffe00058e196)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cc466)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d25c8)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffe000823cc0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/main.c (ffffffff811006dc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81101b5b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff81102e8e)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff8112f9d9)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff81137950)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff81140e7a)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff8150a5c5)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81551b40)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816095d4)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816c542b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff816cf3df)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816d9134)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816da102)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff816dbcef)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/nvme/host/core.c (ffffffff81747a29)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182fd65)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872b55)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81874a2b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff81874e5e)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff819b642c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/main.c (ffffffff810f08cc)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff810f1f1b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff810f40ee)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff81122449)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff8112a3a0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff81133c1a)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff814faa55)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff81541e20)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb214)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816a06ab)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff816aa70f)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b3774)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816b4782)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff816b636f)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/nvme/host/core.c (ffffffff81729679)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f73f5)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c92a)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8183e8e2)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff8183ed1e)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff8197321c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/main.c (ffffffff810fd89c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff810feeeb)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff811010fe)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff8112d6f9)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff81135670)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff8113ed2a)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff81506655)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff8154d880)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816319e4)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff816f38fb)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff816fd94f)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81706a74)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81707a92)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff8170967f)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff818783f5)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187f395)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c4545)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818c6502)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a20eac)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In kernel/power/main.c (ffffffff81108b5c)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff8110a1eb)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/hibernate.c (ffffffff8110c4ce)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/time/hrtimer.c (ffffffff8113a029)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
```
```
In kernel/time/alarmtimer.c (ffffffff811420a0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_forward
```
```
In kernel/time/tick-sched.c (ffffffff8114b89a)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
```
In block/blk-iocost.c (ffffffff8151f945)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
```
```
In lib/dim/dim.c (ffffffff815676d0)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164bd14)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff8170e12b)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/sysfs.c (ffffffff81718471)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81721484)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817224c2)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff817241ef)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:165
Inline: True
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c816)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/power/supply/charger-manager.c (ffffffff81893d95)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8189ab05)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e08c5)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818e2962)
Location: include/linux/ktime.h:165
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/governors/teo.c (ffffffff818e2d9e)
Location: include/linux/ktime.h:165
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
<b>Arch</b>
<ul>
</ul>
