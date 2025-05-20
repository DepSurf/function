# Function: <code>ktime_us_delta</code>

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
Location: include/linux/ktime.h:209
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/ktime.h:209
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816baf80)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
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
In kernel/sched/deadline.c (ffffffff810c50cc)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d2c2)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/sched/deadline.c (ffffffff810cb0f8)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525383)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174fea2)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/sched/deadline.c (ffffffff810c6c39)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537c80)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176e960)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/sched/deadline.c (ffffffff810ce478)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815994d7)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e41a7)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/sched/deadline.c (ffffffff810d5668)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d0d54)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d429)
Location: include/linux/ktime.h:183
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (ffffffff810df098)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea384)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8185942d)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (ffffffff810e6938)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff81538780)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c154)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cf61)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (ffffffff810f12a8)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff81559560)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163dba4)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf095)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (ffffffff810fa718)
Location: include/linux/ktime.h:168
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff815e2e30)
Location: include/linux/ktime.h:168
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eaf64)
Location: include/linux/ktime.h:168
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a150a)
Location: include/linux/ktime.h:168
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
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
In kernel/sched/deadline.c (ffffffff810f8bb8)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff81607268)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817086c4)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/dd.c (ffffffff817ce65e)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a456e)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
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
In kernel/sched/deadline.c (ffffffff810fac5b)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff815e9fb8)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9cc4)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff8172b44b)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff817b2065)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819893a3)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (ffffffff81116618)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff81656398)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81763565)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff817ab33e)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff8183b2aa)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff8184dcb1)
Location: include/linux/ktime.h:169
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a33743)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (ffffffff8113053c)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff8176dad2)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818974c7)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff818e5fe5)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff8197d834)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff81993511)
Location: include/linux/ktime.h:169
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81b9f293)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
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
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (ffffffff8115a07c)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff8189d312)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df22f)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81a3e977)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81aeacd6)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff81b03ed3)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d40c83)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
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
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (ffffffff8116a28c)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff818df8c3)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a26f3f)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81a88414)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81b38fbe)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff81b52a36)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/cpuidle/cpuidle.c (ffffffff821421b0)
Location: include/linux/ktime.h:169
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
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
Location: include/linux/ktime.h:167
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
```
```
In kernel/sched/build_policy.c (ffffffff8117794e)
Location: include/linux/ktime.h:167
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff81926403)
Location: include/linux/ktime.h:167
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a71f4f)
Location: include/linux/ktime.h:167
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/regulator/core.c (ffffffff81adab04)
Location: include/linux/ktime.h:167
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/base/dd.c (ffffffff81b90a7e)
Location: include/linux/ktime.h:167
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/main.c (ffffffff81bab0e6)
Location: include/linux/ktime.h:167
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/cpuidle/cpuidle.c (ffffffff822248a0)
Location: include/linux/ktime.h:167
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
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
In kernel/sched/deadline.c (ffff800010153eac)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffff800010665c58)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8a84)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4b68)
Location: include/linux/ktime.h:186
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
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (c03a0a14)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (c080e7d8)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/clk/ti/clkctrl.c (c09185d8)
Location: include/linux/ktime.h:186
Inline: True
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e898)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
```
```
In drivers/cpuidle/cpuidle.c (c0c01cb8)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/firmware/tegra/bpmp.c (c0c41f18)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
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
In kernel/sched/deadline.c (c0000000001a752c)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (c00000000081b500)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1df50)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (ffffffe0000fb71e)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffe000491e64)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
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
In kernel/sched/deadline.c (ffffffff810ea6a8)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff81551b40)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816095d4)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872b55)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/sched/deadline.c (ffffffff810da6d8)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff81541e20)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb214)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c92a)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (ffffffff810e77d8)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff8154d880)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816319e4)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c4545)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In kernel/sched/deadline.c (ffffffff810f2dd8)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In lib/dim/dim.c (ffffffff815676d0)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164bd14)
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c816)
Location: include/linux/ktime.h:186
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
Location: include/linux/ktime.h:186
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
</details>
</li>
</ul>

## Differences
