# Function: <code>ktime_to_ms</code>

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
Location: include/linux/ktime.h:204
Inline: True
```
```
In drivers/base/power/sysfs.c (ffffffff81553c6f)
Location: include/linux/ktime.h:204
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:204
Inline: True
```
```
In drivers/power/charger-manager.c (0)
Location: include/linux/ktime.h:204
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/ktime.h:204
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
In kernel/power/process.c (ffffffff810d24e2)
Location: include/linux/ktime.h:204
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/base/power/sysfs.c (ffffffff815a5c6f)
Location: include/linux/ktime.h:204
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815adf8a)
Location: include/linux/ktime.h:204
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
```
```
In drivers/power/charger-manager.c (ffffffff816e36d2)
Location: include/linux/ktime.h:204
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/power/charger-manager.c:try_charger_enable
```
```
In net/ipv4/tcp_cubic.c (ffffffff81819a47)
Location: include/linux/ktime.h:204
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
In kernel/power/process.c (ffffffff810d9092)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815253bf)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff815d442f)
Location: include/linux/ktime.h:178
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815dcd8a)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:178
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81713b42)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In net/ipv4/tcp_cubic.c (ffffffff8184b307)
Location: include/linux/ktime.h:178
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
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In kernel/power/process.c (ffffffff810d8093)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537d07)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff815e8f9f)
Location: include/linux/ktime.h:178
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815f1734)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:178
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172b101)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In net/ipv4/tcp_cubic.c (ffffffff8186ed8c)
Location: include/linux/ktime.h:178
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
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In kernel/power/process.c (ffffffff810e0184)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159956d)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff816502af)
Location: include/linux/ktime.h:178
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81658d21)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
```
```
In drivers/base/power/domain.c (ffffffff8165b092)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_active_time_show
  - drivers/base/power/domain.c:genpd_idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:178
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179c8a1)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In net/ipv4/tcp_cubic.c (ffffffff818ef71c)
Location: include/linux/ktime.h:178
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
Location: include/linux/ktime.h:178
Inline: True
```
```
In kernel/power/process.c (ffffffff810e884b)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d0dec)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff8168be5f)
Location: include/linux/ktime.h:178
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81694881)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/domain.c (ffffffff81696c7b)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_active_time_show
  - drivers/base/power/domain.c:genpd_idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:178
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e3d58)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817ea045)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffff81946088)
Location: include/linux/ktime.h:178
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
Location: include/linux/ktime.h:181
Inline: True
```
```
In kernel/power/process.c (ffffffff810f3e5b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea41c)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff816abd8f)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b4f11)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/domain.c (ffffffff816b760b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180f688)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81816205)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffff81976228)
Location: include/linux/ktime.h:181
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
Location: include/linux/ktime.h:181
Inline: True
```
```
In kernel/power/main.c (ffffffff810fbe4c)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff810fc5fb)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c1db)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff816e59bf)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816ef561)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/domain.c (ffffffff816f25cf)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851d15)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81858435)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffff819dfdac)
Location: include/linux/ktime.h:181
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
Location: include/linux/ktime.h:181
Inline: True
```
```
In kernel/power/main.c (ffffffff811073cc)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81108a1b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163dc2b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff81709c8f)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81712db4)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81713dd2)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff817159bf)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81882f45)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81889ee5)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a16d9c)
Location: include/linux/ktime.h:181
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
Location: include/linux/ktime.h:163
Inline: True
```
```
In kernel/power/main.c (ffffffff81111ecc)
Location: include/linux/ktime.h:163
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff8111361d)
Location: include/linux/ktime.h:163
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eaffc)
Location: include/linux/ktime.h:163
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff817c4cef)
Location: include/linux/ktime.h:163
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817cea24)
Location: include/linux/ktime.h:163
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817cf8b2)
Location: include/linux/ktime.h:163
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
Location: include/linux/ktime.h:163
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:163
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81951947)
Location: include/linux/ktime.h:163
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819588df)
Location: include/linux/ktime.h:163
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
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
Location: include/linux/ktime.h:164
Inline: True
```
```
In kernel/power/main.c (ffffffff8110ef9c)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81bde950)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8170875c)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff817d9793)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817e30e4)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817e3e72)
Location: include/linux/ktime.h:164
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
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81956ed8)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195df7f)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
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
Location: include/linux/ktime.h:164
Inline: True
```
```
In kernel/power/main.c (ffffffff8110fa3c)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81bd0ac9)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9d5c)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff817bdb53)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817c74a4)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817c82b2)
Location: include/linux/ktime.h:164
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
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193ae08)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8194152f)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
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
Location: include/linux/ktime.h:164
Inline: True
```
```
In kernel/power/main.c (ffffffff8112f38c)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81ca97d7)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817635dd)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff81847ed3)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81851884)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff818527b2)
Location: include/linux/ktime.h:164
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
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff819df5f2)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e5dbf)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
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
In kernel/power/main.c (ffffffff811509dc)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81152107)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8189753f)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff8198cacf)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff819975c4)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff819986f2)
Location: include/linux/ktime.h:164
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
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b43e16)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4b29f)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
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
In kernel/power/main.c (ffffffff8117f40c)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81180f0e)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df344)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff81afc6df)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b085c4)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b09822)
Location: include/linux/ktime.h:164
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
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cda9d6)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce2cf1)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
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
In kernel/power/main.c (ffffffff8119011c)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81191e03)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a27054)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff81b4aacf)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b565f4)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b57831)
Location: include/linux/ktime.h:164
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
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:164
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d42c96)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d4af81)
Location: include/linux/ktime.h:164
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
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
In kernel/power/main.c (ffffffff8119eadc)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff811a07f3)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/alarmtimer.c (ffffffff8120f129)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In mm/ksm.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a72064)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff81ba2ebf)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81baebe4)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81bafe21)
Location: include/linux/ktime.h:162
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
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:commit_tail
```
```
In drivers/cdrom/cdrom.c (ffffffff81d2946a)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:162
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df9646)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:check_charging_duration
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e01ca1)
Location: include/linux/ktime.h:162
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
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
In kernel/power/main.c (ffff80001016e334)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffff80001016fb54)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8b20)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffff8000108f7d4c)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (ffff800010903e88)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffff800010905778)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffff800010906abc)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffff800010acfa64)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad7940)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2f1c)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In kernel/power/main.c (c03ba0d4)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (c03ba794)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/clk/samsung/clk-pll.c (c090a8cc)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
```
```
In drivers/base/power/sysfs.c (c09e3da8)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (c09ee7b0)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (c09ef598)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/base/power/domain.c (c09f2288)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (c0b0d500)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c0bb0364)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (c0bb7e90)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (c0ddc940)
Location: include/linux/ktime.h:181
Inline: True
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
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
```
```
In kernel/power/main.c (c0000000001c5c6c)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (c0000000001c7b8c)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/base/power/sysfs.c (c00000000099383c)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (c0000000009a2238)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (c0000000009a406c)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (c0000000009a5eb4)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c000000000bb3578)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbded0)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (c000000000df1140)
Location: include/linux/ktime.h:181
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
In kernel/power/process.c (ffffffe00010dbdc)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/base/power/domain.c (ffffffe00058e196)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cc466)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d25c8)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffe000823cc0)
Location: include/linux/ktime.h:181
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
Location: include/linux/ktime.h:181
Inline: True
```
```
In kernel/power/main.c (ffffffff811006dc)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff81101b5b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160965b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff816cf3df)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816d9134)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816da102)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff816dbcef)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/nvme/host/core.c (ffffffff81747a29)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182fd65)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffff819b642c)
Location: include/linux/ktime.h:181
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
Location: include/linux/ktime.h:181
Inline: True
```
```
In kernel/power/main.c (ffffffff810f08cc)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff810f1f1b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb29b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff816aa70f)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b3774)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816b4782)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff816b636f)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/nvme/host/core.c (ffffffff81729679)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f73f5)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffff8197321c)
Location: include/linux/ktime.h:181
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
Location: include/linux/ktime.h:181
Inline: True
```
```
In kernel/power/main.c (ffffffff810fd89c)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff810feeeb)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81631a6b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff816fd94f)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81706a74)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81707a92)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff8170967f)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff818783f5)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187f395)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a20eac)
Location: include/linux/ktime.h:181
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
Location: include/linux/ktime.h:181
Inline: True
```
```
In kernel/power/main.c (ffffffff81108b5c)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (ffffffff8110a1eb)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164bd9b)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/power/sysfs.c (ffffffff81718471)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81721484)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817224c2)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
```
```
In drivers/base/power/domain.c (ffffffff817241ef)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/ktime.h:181
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81893d95)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8189ab05)
Location: include/linux/ktime.h:181
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
</details>
</li>
</ul>

## Differences
