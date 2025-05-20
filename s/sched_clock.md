# Function: <code>sched_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037e70)
Location: arch/x86/kernel/tsc.c:323
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:cpu_clock
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace_clock.c:trace_clock_local
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/cfq-iosched.c:cfq_completed_request
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff81037e70-ffffffff81037e7d: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103779d)
Location: arch/x86/kernel/tsc.c:324
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace_clock.c:trace_clock_local
  - block/blk-core.c:blk_dequeue_request
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/cfq-iosched.c:cfq_completed_request
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
**Symbols:**

```
ffffffff81037070-ffffffff8103707d: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103752d)
Location: arch/x86/kernel/tsc.c:325
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace_clock.c:trace_clock_local
  - block/blk-core.c:blk_dequeue_request
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/cfq-iosched.c:cfq_completed_request
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
**Symbols:**

```
ffffffff81036db0-ffffffff81036dbd: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810355cd)
Location: arch/x86/kernel/tsc.c:225
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace_clock.c:trace_clock_local
  - block/blk-core.c:blk_dequeue_request
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_get_request
  - block/cfq-iosched.c:cfq_completed_request
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
**Symbols:**

```
ffffffff81034e70-ffffffff81034e7d: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103791d)
Location: arch/x86/kernel/tsc.c:225
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace_clock.c:trace_clock_local
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_get_request
  - block/cfq-iosched.c:cfq_completed_request
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
**Symbols:**

```
ffffffff810371d0-ffffffff810371dd: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103884d)
Location: arch/x86/kernel/tsc.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/trace/trace_clock.c:trace_clock_local
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
**Symbols:**

```
ffffffff810381d0-ffffffff810381dd: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81039abd)
Location: arch/x86/kernel/tsc.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:update_stats
  - kernel/sched/psi.c:group_init
  - kernel/trace/trace_clock.c:trace_clock_local
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
**Symbols:**

```
ffffffff81039910-ffffffff8103991d: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c08d)
Location: arch/x86/kernel/tsc.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8103bea0-ffffffff8103bead: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c84d)
Location: arch/x86/kernel/tsc.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8103c660-ffffffff8103c66d: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f63d)
Location: arch/x86/kernel/tsc.c:250
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8103f450-ffffffff8103f45d: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f6fd)
Location: arch/x86/kernel/tsc.c:250
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8103f510-ffffffff8103f51d: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8104107d)
Location: arch/x86/kernel/tsc.c:251
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81040e80-ffffffff81040e8b: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810471e9)
Location: arch/x86/kernel/tsc.c:251
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81046fe0-ffffffff81046feb: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8104fff5)
Location: arch/x86/kernel/tsc.c:251
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_avgs_work
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:sched_clock_local
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8104fda0-ffffffff8104fdaf: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105d3c5)
Location: arch/x86/kernel/tsc.c:251
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_avgs_work
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:sched_clock_local
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_enter_recur
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8105d130-ffffffff8105d13f: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105e965)
Location: arch/x86/kernel/tsc.c:279
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_avgs_work
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
  - kernel/bpf/trampoline.c:__bpf_prog_enter_recur
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8105e6d0-ffffffff8105e6fa: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81065a15)
Location: arch/x86/kernel/tsc.c:279
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/build_policy.c:kcpustat_cpu_fetch
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:task_gtime
  - kernel/sched/build_policy.c:vtime_init_idle
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_account_kernel
  - kernel/sched/build_policy.c:get_vtime_delta
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_avgs_work
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:uprobe_prog_run
  - kernel/trace/bpf_trace.c:uprobe_prog_run
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/bpf_trace.c:trace_call_bpf
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_enter
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
  - kernel/bpf/trampoline.c:__bpf_prog_enter_recur
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
  - net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4
  - net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6
  - net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81065790-ffffffff810657ba: sched_clock (STB_GLOBAL)
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
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffff80001013ecc0)
Location: kernel/sched/clock.c:64
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/trace.c:tracing_log_err
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
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
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/perf/arm_pmu.c:armpmu_dispatch_irq
  - drivers/perf/arm_pmu.c:armpmu_dispatch_irq
  - net/core/sock.c:sk_busy_loop_end
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffff8000101b4578-ffff8000101b4600: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (c038eba0)
Location: kernel/sched/clock.c:64
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - arch/arm/mach-omap2/pm-debug.c:pwrdms_setup
  - arch/arm/mach-omap2/pm-debug.c:pm_dbg_update_time
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/trace.c:tracing_log_err
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
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
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_busy_loop_end
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
  - drivers/perf/arm_pmu.c:armpmu_dispatch_irq
  - drivers/perf/arm_pmu.c:armpmu_dispatch_irq
  - net/core/sock.c:sk_busy_loop_end
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
c03fe17c-c03fe234: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/time.c (c00000000002be80)
Location: arch/powerpc/kernel/time.c:722
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:running_clock
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/printk/printk.c:cont_add
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/trace.c:tracing_log_err
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
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
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/governors/teo.c:teo_reflect
  - drivers/cpuidle/governors/teo.c:teo_select
  - net/core/sock.c:sk_busy_loop_end
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
c00000000002bde0-c00000000002be14: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffe0000ed4ba)
Location: kernel/sched/clock.c:64
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:running_clock
  - kernel/sched/clock.c:sched_clock_cpu
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - kernel/sched/psi.c:group_init
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/trace.c:tracing_log_err
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:calc_timer_values
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
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
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/sock.c:sk_busy_loop_end
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffe00013a932-ffffffe00013a9aa: sched_clock (STB_GLOBAL)
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
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c9ad)
Location: arch/x86/kernel/tsc.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8103c7c0-ffffffff8103c7cd: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102c007)
Location: arch/x86/kernel/tsc.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/cputime.c:task_gtime
  - kernel/sched/cputime.c:vtime_init_idle
  - kernel/sched/cputime.c:arch_vtime_task_switch
  - kernel/sched/cputime.c:get_vtime_delta
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8102beb0-ffffffff8102bebd: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c80d)
Location: arch/x86/kernel/tsc.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8103c620-ffffffff8103c62d: sched_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int sched_clock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103d89d)
Location: arch/x86/kernel/tsc.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/nmi.c:nmi_handle
  - kernel/sched/core.c:init_idle
  - kernel/sched/clock.c:sched_clock_local
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:group_init
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/trace/trace_clock.c:trace_clock_local
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8103d6b0-ffffffff8103d6bd: sched_clock (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long long unsigned int</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
