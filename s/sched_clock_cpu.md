# Function: <code>sched_clock_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b1390)
Location: kernel/sched/clock.c:294
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_init
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/clock.c:cpu_clock
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/trace/trace_clock.c:trace_clock_global
```
**Symbols:**

```
ffffffff810b1390-ffffffff810b1428: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b3d20)
Location: kernel/sched/clock.c:299
Inline: False
Direct callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:log_store
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
```
**Symbols:**

```
ffffffff810b3d20-ffffffff810b3dc8: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810ba360)
Location: kernel/sched/clock.c:299
Inline: False
Direct callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:log_store
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
```
**Symbols:**

```
ffffffff810ba360-ffffffff810ba408: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b4c50)
Location: kernel/sched/clock.c:357
Inline: True
Direct callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:log_store
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
**Symbols:**

```
ffffffff810b4c50-ffffffff810b4cfe: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810bbf50)
Location: kernel/sched/clock.c:357
Inline: True
Direct callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:log_store
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
**Symbols:**

```
ffffffff810bbf50-ffffffff810bbffe: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c35d0)
Location: kernel/sched/clock.c:345
Inline: True
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:log_store
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
**Symbols:**

```
ffffffff810c35d0-ffffffff810c3681: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810cc8c0)
Location: kernel/sched/clock.c:364
Inline: True
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:update_stats
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:log_store
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810cc8c0-ffffffff810cc975: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d4cd0)
Location: kernel/sched/clock.c:365
Inline: True
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/printk/printk.c:cont_add
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810d4cd0-ffffffff810d4d7f: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810df290)
Location: kernel/sched/clock.c:365
Inline: True
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810df290-ffffffff810df33f: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e7570)
Location: kernel/sched/clock.c:365
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810e7570-ffffffff810e7622: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e51b0)
Location: kernel/sched/clock.c:365
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/printk/printk.c:vprintk_store
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810e51b0-ffffffff810e5262: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e7160)
Location: kernel/sched/clock.c:365
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/printk/printk.c:vprintk_store
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810e7160-ffffffff810e7212: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810fe760)
Location: kernel/sched/clock.c:365
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/printk/printk.c:vprintk_store
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - mm/kfence/core.c:metadata_update_state
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810fe760-ffffffff810fe841: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81143590)
Location: kernel/sched/clock.c:363
Inline: False
Direct callers:
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
  - kernel/sched/build_utility.c:sched_clock_idle_sleep_event
  - kernel/printk/printk.c:vprintk_store
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/delayacct.c:__delayacct_wpcopy_end
  - kernel/delayacct.c:__delayacct_wpcopy_start
  - kernel/delayacct.c:__delayacct_compact_end
  - kernel/delayacct.c:__delayacct_compact_start
  - kernel/delayacct.c:__delayacct_swapin_end
  - kernel/delayacct.c:__delayacct_swapin_start
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - mm/kfence/core.c:metadata_update_state
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81143590-ffffffff81143690: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116ecf0)
Location: kernel/sched/clock.c:363
Inline: False
Direct callers:
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:get_recent_times
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
  - kernel/sched/build_utility.c:sched_clock_idle_sleep_event
  - kernel/printk/printk.c:vprintk_store
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/delayacct.c:__delayacct_wpcopy_end
  - kernel/delayacct.c:__delayacct_wpcopy_start
  - kernel/delayacct.c:__delayacct_compact_end
  - kernel/delayacct.c:__delayacct_compact_start
  - kernel/delayacct.c:__delayacct_swapin_end
  - kernel/delayacct.c:__delayacct_swapin_start
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - mm/kfence/core.c:metadata_update_state
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff8116ecf0-ffffffff8116edf0: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81180380)
Location: kernel/sched/clock.c:388
Inline: False
Direct callers:
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:get_recent_times
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:sched_clock_idle_sleep_event
  - kernel/trace/trace_clock.c:trace_clock_global
```
**Symbols:**

```
ffffffff81180380-ffffffff81180555: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118e0d0)
Location: kernel/sched/clock.c:388
Inline: False
Direct callers:
  - kernel/sched/core.c:update_rq_clock
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:get_recent_times
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:sched_clock_idle_sleep_event
  - kernel/trace/trace_clock.c:trace_clock_global
```
**Symbols:**

```
ffffffff8118e0d0-ffffffff8118e2a5: sched_clock_cpu (STB_GLOBAL)
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
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffff80001013ece8)
Location: kernel/sched/clock.c:461
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/trace/trace_clock.c:trace_clock_global
```
**Symbols:**

```
ffff80001013ece8-ffff80001013ed08: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (c038ebd0)
Location: kernel/sched/clock.c:461
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/trace/trace_clock.c:trace_clock_global
```
**Symbols:**

```
c038ebd0-c038ec04: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (c00000000018de30)
Location: kernel/sched/clock.c:461
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/trace/trace_clock.c:trace_clock_global
```
**Symbols:**

```
c00000000018de30-c00000000018de74: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffe0000ed4e4)
Location: kernel/sched/clock.c:461
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/trace/trace_clock.c:trace_clock_global
```
**Symbols:**

```
ffffffe0000ed4e4-ffffffe0000ed50c: sched_clock_cpu (STB_GLOBAL)
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
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d9480)
Location: kernel/sched/clock.c:365
Inline: True
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810d9480-ffffffff810d952f: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c7e60)
Location: kernel/sched/clock.c:365
Inline: True
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810c7e60-ffffffff810c7f0f: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d57c0)
Location: kernel/sched/clock.c:365
Inline: True
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810d57c0-ffffffff810d586f: sched_clock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e1090)
Location: kernel/sched/clock.c:365
Inline: True
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_idle_sleep_event
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:record_times
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff810e1090-ffffffff810e1158: sched_clock_cpu (STB_GLOBAL)
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
