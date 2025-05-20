# Function: <code>__usecs_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810ead00)
Location: kernel/time/time.c:523
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff810ead00-ffffffff810ead3b: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f19a0)
Location: kernel/time/time.c:530
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff810f19a0-ffffffff810f19db: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8b20)
Location: kernel/time/time.c:530
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff810f8b20-ffffffff810f8b5b: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fab40)
Location: kernel/time/time.c:620
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff810fab40-ffffffff810fab7d: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811054d0)
Location: kernel/time/time.c:587
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff811054d0-ffffffff8110550d: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110330)
Location: kernel/time/time.c:599
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81110330-ffffffff8111036d: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111b920)
Location: kernel/time/time.c:537
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff8111b920-ffffffff8111b95d: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126350)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81126350-ffffffff81126390: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811322f0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff811322f0-ffffffff81132330: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141750)
Location: kernel/time/time.c:563
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_start_period
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_cubic.c:bictcp_update
```
**Symbols:**

```
ffffffff81141750-ffffffff8114178e: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113d960)
Location: kernel/time/time.c:563
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_start_period
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_cubic.c:bictcp_update
```
**Symbols:**

```
ffffffff8113d960-ffffffff8113d99e: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ebb0)
Location: kernel/time/time.c:563
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_start_period
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_cubic.c:bictcp_update
```
**Symbols:**

```
ffffffff8113ebb0-ffffffff8113ebee: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162040)
Location: kernel/time/time.c:563
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_start_period
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_cubic.c:bictcp_update
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
```
**Symbols:**

```
ffffffff81162040-ffffffff8116207e: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81194f80)
Location: kernel/time/time.c:563
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_start_period
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_cubic.c:bictcp_update
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
```
**Symbols:**

```
ffffffff81194f80-ffffffff81194fc1: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2cf0)
Location: kernel/time/time.c:563
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_start_period
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_cubic.c:bictcp_update
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
```
**Symbols:**

```
ffffffff811d2cf0-ffffffff811d2d31: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e6fe0)
Location: kernel/time/time.c:563
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_start_period
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_cubic.c:bictcp_update
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
```
**Symbols:**

```
ffffffff811e6fe0-ffffffff811e7022: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fcd30)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_start_period
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/core/filter.c:sol_tcp_sockopt
  - net/core/filter.c:sol_tcp_sockopt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_cubic.c:bictcp_update
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
```
**Symbols:**

```
ffffffff811fcd30-ffffffff811fcd76: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199d20)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffff800010199d20-ffff800010199d80: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4758)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - block/blk-iocost.c:ioc_start_period
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
c03e4758-c03e4790: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001f9fd0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
c0000000001f9fd0-c0000000001fa028: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a22c)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffe00012a22c-ffffffe00012a27a: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112aaa0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff8112aaa0-ffffffff8112aae0: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d310)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff8111d310-ffffffff8111d350: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811287c0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff811287c0-ffffffff81128800: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134e30)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - net/core/dev.c:net_rx_action
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81134e30-ffffffff81134e71: __usecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
