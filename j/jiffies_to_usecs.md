# Function: <code>jiffies_to_usecs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eabc0)
Location: kernel/time/time.c:269
Inline: True
Direct callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_governor.c:dbs_check_cpu
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
```
**Symbols:**

```
ffffffff810eabc0-ffffffff810eabd1: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1860)
Location: kernel/time/time.c:269
Inline: True
Direct callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_group_served
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
  - drivers/cpufreq/cpufreq_conservative.c:cs_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_update_rtt_min
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff810f1860-ffffffff810f1871: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f89e0)
Location: kernel/time/time.c:269
Inline: True
Direct callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_group_served
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
  - drivers/cpufreq/cpufreq_conservative.c:cs_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff810f89e0-ffffffff810f89f1: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810faa00)
Location: kernel/time/time.c:359
Inline: True
Direct callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_group_served
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
  - drivers/cpufreq/cpufreq_conservative.c:cs_init
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff810faa00-ffffffff810faa11: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105390)
Location: kernel/time/time.c:325
Inline: True
Direct callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81105390-ffffffff811053a1: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110335)
Location: kernel/time/time.c:327
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff811101a0-ffffffff811101b1: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111b925)
Location: kernel/time/time.c:325
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8111b7e0-ffffffff8111b7f1: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126355)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81126210-ffffffff81126221: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811322f5)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff811321b0-ffffffff811321c1: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141755)
Location: kernel/time/time.c:391
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:disk_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm.c:dm_start_time_ns_from_clone
  - net/core/netpoll.c:__netpoll_send_skb
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81141620-ffffffff81141631: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113d965)
Location: kernel/time/time.c:391
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm.c:dm_start_time_ns_from_clone
  - net/core/netpoll.c:__netpoll_send_skb
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8113d830-ffffffff8113d841: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ebb5)
Location: kernel/time/time.c:391
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm.c:dm_start_time_ns_from_clone
  - net/core/netpoll.c:__netpoll_send_skb
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8113ea80-ffffffff8113ea91: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162045)
Location: kernel/time/time.c:391
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm.c:dm_start_time_ns_from_clone
  - net/core/netpoll.c:__netpoll_send_skb
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81161f10-ffffffff81161f21: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81194f85)
Location: kernel/time/time.c:391
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/build_utility.c:psi_init
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm.c:dm_start_time_ns_from_clone
  - net/core/netpoll.c:__netpoll_send_skb
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81194e30-ffffffff81194e47: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2cf5)
Location: kernel/time/time.c:391
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/build_utility.c:psi_init
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm.c:dm_start_time_ns_from_clone
  - net/core/netpoll.c:__netpoll_send_skb
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff811d2b60-ffffffff811d2b77: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e6fe5)
Location: kernel/time/time.c:391
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/build_utility.c:psi_init
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/net/virtio_net.c:virtnet_tx_timeout
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm.c:dm_start_time_ns_from_clone
  - net/core/netpoll.c:__netpoll_send_skb
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff811e6e50-ffffffff811e6e67: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fcd35)
Location: kernel/time/time.c:400
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/build_utility.c:psi_init
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/net/virtio_net.c:virtnet_tx_timeout
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm.c:dm_start_time_ns_from_clone
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - net/core/netpoll.c:__netpoll_send_skb
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff811fcba0-ffffffff811fcbb7: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199d38)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffff800010199b58-ffff800010199b84: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e476c)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - arch/arm/mach-vexpress/spc.c:spc_set_rate
  - arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_clk_change_notify
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
c03e4554-c03e4574: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001f9fd8)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
c0000000001f9e60-c0000000001f9e74: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a242)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffe00012a098-ffffffe00012a0c2: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112aaa5)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8112a960-ffffffff8112a971: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d315)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8111d1d0-ffffffff8111d1e1: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811287c5)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81128680-ffffffff81128691: jiffies_to_usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134e35)
Location: kernel/time/time.c:393
Inline: True
Inline callers:
  - kernel/time/time.c:__usecs_to_jiffies
Direct callers:
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:psi_init
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - drivers/acpi/ec.c:ec_guard
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:timeouts_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - drivers/char/tpm/tpm-sysfs.c:durations_show
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81134d00-ffffffff81134d11: jiffies_to_usecs (STB_GLOBAL)
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
