# Function: <code>local_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b1470)
Location: kernel/sched/clock.c:386
Inline: True
Direct callers:
  - kernel/sched/clock.c:running_clock
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:log_store
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
```
**Symbols:**

```
ffffffff810b1470-ffffffff810b148e: local_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002235)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In kernel/sched/clock.c (ffffffff810b3fb1)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff810c93d3)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff810dbc49)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_store
```
```
In kernel/trace/trace_clock.c (ffffffff81148411)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/events/core.c (ffffffff81188bf8)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff81249e6b)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d275)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/dev.c (ffffffff8178345a)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
```
```
In net/ipv4/tcp_input.c (ffffffff817dc024)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff817e5368)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff817e7acf)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_recovery.c (ffffffff817f0633)
Location: include/linux/sched.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
```
**Symbols:**

```
ffffffff81188bd0-ffffffff81188be2: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002259)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In kernel/sched/clock.c (ffffffff810ba5f1)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/fair.c (ffffffff810bd690)
Location: include/linux/sched.h:2569
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810cf3f3)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff810e2c09)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_store
```
```
In kernel/trace/trace_clock.c (ffffffff811522c1)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/events/core.c (ffffffff81197fd8)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff8125ce29)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174fe55)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/dev.c (ffffffff817aed22)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
```
```
In net/ipv4/tcp_input.c (ffffffff8180c102)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff818157f8)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81818298)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_recovery.c (ffffffff818213a3)
Location: include/linux/sched.h:2569
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
```
**Symbols:**

```
ffffffff81197fb0-ffffffff81197fc2: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002289)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In kernel/sched/clock.c (ffffffff810b4e71)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/fair.c (ffffffff810b75b4)
Location: include/linux/sched/clock.h:81
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810ce463)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff810e1cef)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_store
```
```
In kernel/trace/trace_clock.c (ffffffff811548a1)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/events/core.c (ffffffff8119fb08)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff81269ba6)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8129dce6)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176e910)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff817b30ff)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff817cd5fd)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/ipv4/tcp.c (ffffffff81823571)
Location: include/linux/sched/clock.h:81
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8182c2e4)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818373a6)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81838617)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cd55)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/syncookies.c (ffffffff8186e04d)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8c7e)
Location: include/linux/sched/clock.h:81
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
**Symbols:**

```
ffffffff8119fae0-ffffffff8119faf2: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810022ab)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In kernel/sched/clock.c (ffffffff810bc161)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/fair.c (ffffffff810beac3)
Location: include/linux/sched/clock.h:82
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810d5d43)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff810e9e3a)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_store
```
```
In kernel/trace/trace_clock.c (ffffffff811610c1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/events/core.c (ffffffff811b34f8)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff8128c446)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812c0ed6)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e4152)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/sock.c (ffffffff8182b3df)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81846d2d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/ipv4/tcp.c (ffffffff818a29a3)
Location: include/linux/sched/clock.h:82
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818ab175)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b6a56)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6da6)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc477)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/syncookies.c (ffffffff818ee9dd)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bb40)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
**Symbols:**

```
ffffffff811b3430-ffffffff811b3442: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002015)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810c37f0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/fair.c (ffffffff810c6c5a)
Location: include/linux/sched/clock.h:82
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810dde56)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff810f2093)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_store
```
```
In kernel/trace/trace_clock.c (ffffffff81170010)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/events/core.c (ffffffff811d2c60)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff812b2c3e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812e9e05)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d3c2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff819f1aff)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff818754f1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff8189039d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/ipv4/tcp.c (ffffffff818f804f)
Location: include/linux/sched/clock.h:82
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819005cc)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff8190c295)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c626)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911e66)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/syncookies.c (ffffffff819452e5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994da2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
**Symbols:**

```
ffffffff811d2b90-ffffffff811d2ba2: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002015)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810ccab0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/fair.c (ffffffff810cf1ab)
Location: include/linux/sched/clock.h:82
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810e85d6)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff810fd87d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
  - kernel/printk/printk.c:log_store
```
```
In kernel/time/timekeeping.c (ffffffff828af8ba)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff8117dbc0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/events/core.c (ffffffff811e2f70)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff812c7d53)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812fe98e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818593a3)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2d035)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff81895dc1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff818b0c4d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff811e2ea0-ffffffff811e2eb2: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810020b5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810d4ea0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff810ef3c6)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff811062c2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/time/timekeeping.c (ffffffff828c844b)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff8118aaa0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811a09a0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff811fa140)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff812e48fa)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131fb55)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cce7)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (ffffffff8189ed10)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d1c6)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff818e02d1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff818fd9ed)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff811fa070-ffffffff811fa082: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810020b5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810df460)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff810fb206)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff81112652)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (ffffffff81127c8c)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff828d0a29)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff81196990)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811ac3d0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff81207210)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff812f6309)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81332905)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf007)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (ffffffff818d1151)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad49ce)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff81912484)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff8193575d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81207140-ffffffff81207152: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810030e5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810e77b0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff81105636)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff8111de75)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (ffffffff811364ca)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff82cf196e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff811abcc0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811c4b74)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff81230700)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff8132e0c5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8136cbe8)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a17ec)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/governors/teo.c (ffffffff819a39d1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc9c0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff819e4307)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81a0a41d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81230630-ffffffff81230642: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810031b7)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810e53f0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff81103cf6)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff8111ad5e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/rcu/tree.c (ffffffff81131dda)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff82fde3f8)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff811a9580)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811c2774)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff8123a360)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff8133993d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8137a698)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff8199a852)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a4861)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/governors/teo.c (ffffffff819a69b1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c45520)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff819e3b87)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81a0c746)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff8123a290-ffffffff8123a2a2: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810031b7)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810e73a0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff81105e66)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff8111b2fe)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/rcu/tree.c (ffffffff81132e52)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff831e8f22)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff811aa130)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811c37e4)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff8123eb90)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff8133fed3)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81381310)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff8197f4a2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81989481)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (ffffffff8198b4c1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c387a0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff819c9c12)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff819f2a26)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff8123eac0-ffffffff8123ead2: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810031f7)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810fe9b0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff81124afa)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff8113b5ef)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/rcu/tree.c (ffffffff811550aa)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff832cd4d6)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/delayacct.c (ffffffff811d18ec)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
```
```
In kernel/trace/trace_clock.c (ffffffff811d3ca0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811ee994)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff812795a0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In mm/kfence/core.c (ffffffff8133bb97)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - mm/kfence/core.c:metadata_update_state
```
```
In fs/select.c (ffffffff8138d8a9)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813ce550)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81a285f2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a3393d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (ffffffff81a36864)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d57080)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff81a790b2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81aa48f6)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81279580-ffffffff81279592: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81144ee8)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
```
```
In kernel/printk/printk.c (ffffffff8115e83d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/rcu/tree.c (ffffffff8117c4e1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff834810a0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/delayacct.c (ffffffff8120611c)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In kernel/trace/trace_clock.c (ffffffff81208800)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff81226d6f)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff812cc645)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In mm/kfence/core.c (ffffffff813ae483)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - mm/kfence/core.c:metadata_update_state
```
```
In fs/select.c (ffffffff8140ec50)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814575ed)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81b92502)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81ba006d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/governors/teo.c (ffffffff81ba32fe)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f29a59)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff81becdae)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81c1c05e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff812cc620-ffffffff812cc638: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811718a8)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
```
```
In kernel/printk/printk.c (ffffffff8119178a)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/rcu/tree.c (ffffffff811b3d03)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff83eadeb2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/delayacct.c (ffffffff8124e3ec)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In kernel/trace/trace_clock.c (ffffffff81250cf0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff81272027)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff81334495)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In mm/kfence/core.c (ffffffff8142eaf3)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - mm/kfence/core.c:metadata_update_state
```
```
In fs/select.c (ffffffff81499752)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814e688d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81d32a12)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d41ba0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/cpuidle/governors/teo.c (ffffffff81d4527e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d58bb)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff81d9932e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81dcd03e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81334460-ffffffff81334478: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81182ca8)
Location: kernel/sched/clock.c:311
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/timekeeping.c:dummy_clock_read
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
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
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
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - net/core/sock.c:sk_busy_loop_end
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff81182c30-ffffffff81182c5f: local_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81191548)
Location: kernel/sched/clock.c:311
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/timekeeping.c:dummy_clock_read
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
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace.c:tracing_log_err
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
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
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff811914d0-ffffffff811914ff: local_clock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffff80001008469c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffff80001013ed08)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffff800010160e8c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffff8000101727fc)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (ffff80001018f3d4)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffff80001144897c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffff80001020ef48)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffff8000102293c8)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffff800010294150)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:__perf_event_account_interrupt
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
```
```
In fs/select.c (ffff8000103a35c0)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffff8000103f016c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26d8c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (ffff800010b29bc4)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In net/core/sock.c (ffff800010ba9fd8)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffff800010bd3b28)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffff800010290cd8-ffff800010290cec: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c0302e14)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (c038ec10)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (c03ad564)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (c03c5508)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (c03ddc78)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timekeeping.c (c1522974)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (c044d9e0)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (c04669ec)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (c04c053c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:__perf_event_account_interrupt
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
```
```
In fs/select.c (c0585d60)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c05c61b8)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (c0c01bf0)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (c0c046bc)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/firmware/tegra/bpmp.c (c0c41ec0)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
```
```
In net/core/sock.c (c0cc866c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (c0cee810)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
c04c0458-c04c046c: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c00000000000f360)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In arch/powerpc/kernel/time.c (c00000000002be80)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:running_clock
```
```
In kernel/sched/clock.c (c00000000018de94)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (c0000000001b606c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (c0000000001cc0ac)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (c0000000001eb598)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timekeeping.c (c00000000136dacc)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (c00000000028d4f4)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (c0000000002b08c4)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (c00000000033e5f8)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_update
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
```
```
In fs/select.c (c00000000049d248)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c0000000004f7cf0)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1deac)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (c000000000c21890)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In net/core/sock.c (c000000000c7f898)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (c000000000cb28b0)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
c00000000033dc30-c00000000033dc5c: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffe0000b3d36)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffe0000ed50c)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffe0001045a0)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffe00010ea82)
Location: include/linux/sched/clock.h:48
Inline: True
```
```
In kernel/rcu/tree.c (ffffffe000122e5a)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/timekeeping.c (ffffffe000009ef0)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffe00016faf2)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffe000183b0a)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffe0001c3782)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:__perf_event_account_interrupt
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
```
```
In fs/select.c (ffffffe00026b3f4)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffe0002a2f8a)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffe00073d506)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffe00075dc40)
Location: include/linux/sched/clock.h:48
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffe0001c36e2-ffffffe0001c36fa: local_clock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810020b5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810d9650)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff810f4536)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff8110ac32)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (ffffffff8112026c)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff828b98da)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff8118efb0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811a49f0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff811ff830)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff812ee8e9)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132aee5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872ac7)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/teo.c (ffffffff81874b21)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a7383e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff818b2484)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff818d572d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff811ff760-ffffffff811ff772: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810005a5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810c8030)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff810e4709)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff810fbbe2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (ffffffff81110586)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff828b1e2b)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff81182130)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811979a0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff811f2580)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff812df519)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131ba85)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c8a7)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (ffffffff8183e9e1)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fbb8)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff8186c3d4)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff8188f59d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff811f24b0-ffffffff811f24c2: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810020b5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810d5990)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff810f1736)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff81108b22)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (ffffffff8111e15c)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff828cc65d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff8118cd80)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811a27c0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff811fd600)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff812ec6f9)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813289b5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c44b7)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc4e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff81903484)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff8192675d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff811fd530-ffffffff811fd542: local_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 local_clock();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810020b5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
```
```
In kernel/sched/clock.c (ffffffff810e1280)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/clock.c:running_clock
```
```
In kernel/sched/debug.c (ffffffff810fc726)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
```
```
In kernel/printk/printk.c (ffffffff81113ec2)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/printk/printk.c:cont_add
```
```
In kernel/rcu/tree.c (ffffffff8112b1bc)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/timekeeping.c (ffffffff828d1a57)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
```
In kernel/trace/trace_clock.c (ffffffff8119a8e0)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock
```
```
In kernel/trace/trace.c (ffffffff811b0550)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_log_err
```
```
In kernel/events/core.c (ffffffff8120c360)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
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
```
```
In fs/select.c (ffffffff812fd6f9)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8133a7d5)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0837)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/cpuidle/governors/teo.c (ffffffff818e2a61)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec44e)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/sock.c (ffffffff81924464)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81947d5d)
Location: include/linux/sched/clock.h:82
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
**Symbols:**

```
ffffffff8120c290-ffffffff8120c2a2: local_clock (STB_LOCAL)
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
