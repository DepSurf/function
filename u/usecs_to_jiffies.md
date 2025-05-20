# Function: <code>usecs_to_jiffies</code>

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
In kernel/power/qos.c (ffffffff810ccb6e)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In drivers/acpi/ec.c (ffffffff81482d55)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff814d99fe)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150fabe)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815244db)
Location: include/linux/jiffies.h:401
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b36c7)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff816b47df)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff816b5885)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
```
```
In net/ipv4/tcp_input.c (ffffffff8176d371)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81775afd)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a539)
Location: include/linux/jiffies.h:401
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177de1f)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In kernel/power/qos.c (ffffffff810d162c)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In drivers/acpi/ec.c (ffffffff814d1867)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff81529f8e)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81562001)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81577464)
Location: include/linux/jiffies.h:401
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817db10b)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff817e6798)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff817e77a3)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb283)
Location: include/linux/jiffies.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In kernel/power/qos.c (ffffffff810d808c)
Location: include/linux/jiffies.h:405
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In drivers/acpi/ec.c (ffffffff814f39da)
Location: include/linux/jiffies.h:405
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff8155658e)
Location: include/linux/jiffies.h:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158e771)
Location: include/linux/jiffies.h:405
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3ae3)
Location: include/linux/jiffies.h:405
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8180ac45)
Location: include/linux/jiffies.h:405
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81816ed8)
Location: include/linux/jiffies.h:405
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81817f3f)
Location: include/linux/jiffies.h:405
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181bbd3)
Location: include/linux/jiffies.h:405
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In kernel/power/qos.c (ffffffff810d70c8)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In drivers/acpi/ec.c (ffffffff815018b9)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff8156aac9)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a27e0)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7c60)
Location: include/linux/jiffies.h:406
Inline: True
```
```
In net/core/dev.c (ffffffff817d1004)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff8182d7ad)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81837361)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff818383cd)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c480)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff81841c44)
Location: include/linux/jiffies.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff810df068)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In drivers/acpi/ec.c (ffffffff81543d19)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff815cecbc)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816085d4)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8161e773)
Location: include/linux/jiffies.h:407
Inline: True
```
```
In net/core/dev.c (ffffffff8184b0f4)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff818ac647)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff818b6a14)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7ae6)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbbb3)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff818c1482)
Location: include/linux/jiffies.h:407
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff810e76b8)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In drivers/acpi/ec.c (ffffffff81579bee)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff81606ddf)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81641cc0)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff816583d6)
Location: include/linux/jiffies.h:410
Inline: True
```
```
In net/core/dev.c (ffffffff818954f4)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff81901e74)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8190c18b)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d47c)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911686)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff81917012)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff810f2cb8)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In drivers/acpi/ec.c (ffffffff8159186e)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff816221af)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165fe20)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816770d6)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff818b7174)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff8192ff33)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8193a45b)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b862)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193fe79)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff81945822)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff810fb14a)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In drivers/acpi/ec.c (ffffffff815c2745)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff81655b88)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8169532c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816acd6d)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81902f94)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff8199348e)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8199e809)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8199fc25)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4381)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9e22)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff8110717a)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (ffffffff81510f36)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815e3a55)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff816780b8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7ec8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816cfa4d)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81935d34)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff819c9fd9)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819d5319)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff819d67fc)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dafa1)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0ae2)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In block/blk-iocost.c (ffffffff81571498)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/acpi/ec.c (ffffffff8168f975)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff8172aef6)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176bfaa)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff817849c6)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81a0ac44)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff81ab49d1)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1bfb)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac3435)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5012)
Location: include/linux/jiffies.h:409
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ace0d2)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b08043)
Location: include/linux/jiffies.h:409
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_update
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
In block/blk-iocost.c (ffffffff8158c5ca)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81639fd3)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
```
```
In drivers/acpi/ec.c (ffffffff816ad6c5)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff81747ab7)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81786b8a)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8179be06)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81a0be94)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/filter.c (ffffffff81a2ac69)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81abfa9e)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81acd65f)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81aceeaa)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad09a2)
Location: include/linux/jiffies.h:410
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ada0c8)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b16423)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_update
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
In block/blk-iocost.c (ffffffff8159330a)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dc23)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
```
```
In drivers/acpi/ec.c (ffffffff8168fc45)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a4ec)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8177e936)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff819f2ff4)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/filter.c (ffffffff81a11dee)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81aa9db1)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81ab882f)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81aba013)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abba7f)
Location: include/linux/jiffies.h:410
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac511e)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b04209)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_update
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
In block/blk-iocost.c (ffffffff815fa5ba)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d243)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
```
```
In drivers/acpi/ec.c (ffffffff81705595)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817eec29)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81804b8b)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81aa3e54)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/filter.c (ffffffff81acd0eb)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81b661a1)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81b75a4f)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81b77452)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78c55)
Location: include/linux/jiffies.h:410
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b8392e)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
```
In net/ipv4/tcp_cubic.c (ffffffff81bc655d)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_update
```
```
In net/mptcp/protocol.c (ffffffff81c7ea51)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
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
In block/blk-iocost.c (ffffffff816ac95a)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac003)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/acpi/ec.c (ffffffff81833916)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192ecf0)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff819445eb)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81c1c85e)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/filter.c (ffffffff81c4aa74)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81cf4495)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81d05387)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06d61)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08a68)
Location: include/linux/jiffies.h:410
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d14035)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
```
In net/ipv4/tcp_cubic.c (ffffffff81d5b8cf)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_update
```
```
In net/mptcp/protocol.c (ffffffff81e24200)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
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
In block/blk-iocost.c (ffffffff8176b46a)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4f83)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/acpi/ec.c (ffffffff819675b6)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/acpi/acpi_pcc.c (ffffffff8197a123)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8d012)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7240)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81dcd8ee)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/filter.c (ffffffff81df5399)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81eb8e65)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81eca457)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecbfc3)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecdba8)
Location: include/linux/jiffies.h:410
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81eda075)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f25d9f)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_update
```
```
In net/mptcp/protocol.c (ffffffff81ffbcc0)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
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
In block/blk-iocost.c (ffffffff817aa5ca)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908053)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/acpi/ec.c (ffffffff819adb86)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/acpi/acpi_pcc.c (ffffffff819c0bb3)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad7ff5)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af2a80)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81e3e4ee)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/filter.c (ffffffff81e66f02)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81f17275)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81f28f97)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2abe5)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c878)
Location: include/linux/jiffies.h:410
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f39155)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f8569f)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_update
```
```
In net/mptcp/protocol.c (ffffffff82078090)
Location: include/linux/jiffies.h:410
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
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
In block/blk-iocost.c (ffffffff817ee37a)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f860)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/acpi/ec.c (ffffffff819f8006)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/acpi/acpi_pcc.c (ffffffff81a0b5a3)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2b346)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46010)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81efcd9e)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/filter.c (ffffffff81f260b6)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81fdc727)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81fedad4)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef804)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1788)
Location: include/linux/jiffies.h:564
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff235)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
```
In net/ipv4/tcp_cubic.c (ffffffff8204bd6f)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_update
```
```
In net/mptcp/protocol.c (ffffffff8214d1e1)
Location: include/linux/jiffies.h:564
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
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
In kernel/power/qos.c (ffff80001016e044)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (ffff8000106143d4)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In drivers/acpi/ec.c (ffff800010770d88)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffff800010844c9c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a0404)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108ba038)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/misc/vexpress-syscfg.c (ffff80001092be80)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e5bf4)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In net/core/dev.c (ffff800010bd42a0)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffff800010c7ce8c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffff800010c87f08)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffff800010c896f8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e338)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffff800010c948ec)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In arch/arm/mach-vexpress/spc.c (c034d1d8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:spc_set_rate
  - arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps
```
```
In kernel/power/qos.c (c03b8ee8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (c07bf008)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/phy/samsung/phy-exynos5250-sata.c (c082cdac)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
```
```
In drivers/regulator/core.c (c094a4b4)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (c099a1c8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (c09b3410)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a524)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac8d0c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfdf0)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
```
In drivers/firmware/tegra/bpmp.c (c0c41994)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c751c4)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_clk_change_notify
```
```
In net/core/dev.c (c0cefaa8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (c0d89154)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (c0d97264)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (c0d987ac)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9d388)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (c0da3188)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (c0000000001c5904)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (c0000000007b3d94)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In drivers/regulator/core.c (c0000000008db21c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (c00000000093e100)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (c00000000095b180)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm_i2c_nuvoton.c (c000000000967170)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
```
```
In net/core/dev.c (c000000000cb32f8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (c000000000d86ca0)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (c000000000d94cc0)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (c000000000d96a44)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9cd4c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (c000000000da511c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffe00010d528)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (ffffffe00044bd5e)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In drivers/regulator/core.c (ffffffe000522ebc)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055d4ee)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056a790)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a79a)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In net/core/dev.c (ffffffe00075e1ce)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffe0007df6ae)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffe0007e91a4)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea5ca)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee742)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3caa)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff8110048a)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (ffffffff81509516)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815d5945)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff8163dda8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d928)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8169549d)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff818d5d04)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff81969e49)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81975189)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8197666c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197ae11)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff81980952)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff810f067a)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (ffffffff814f99c6)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815bf505)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff8161df98)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165ca18)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81672e8d)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff8188fb54)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff81923939)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8192ec49)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8193012c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819348d1)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a412)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff810fd64a)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (ffffffff815055a6)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815d7d35)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff8166bef8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816abd08)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c370d)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81926d34)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff819d4619)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819df959)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0e3c)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e55e1)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eb122)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/power/qos.c (ffffffff811088ea)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In block/blk-iocost.c (ffffffff8151eee6)
Location: include/linux/jiffies.h:411
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815f1bf5)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/regulator/core.c (ffffffff816864b8)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c6168)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ddcdd)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In net/core/dev.c (ffffffff81948384)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/tcp_input.c (ffffffff819de1f9)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819e9609)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff819eaafc)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef28f)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f4fa2)
Location: include/linux/jiffies.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
</details>
</li>
</ul>

## Differences
