# Function: <code>u64_stats_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff8187eb91)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8188ec1b)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff8188d111)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
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
In drivers/net/loopback.c (ffffffff8186fa51)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d78e)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
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
In kernel/seccomp.c (ffffffff811cde0c)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff812182f6)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81252396)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8125eedb)
Location: include/linux/u64_stats_sync.h:86
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff8126bde3)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126d9a0)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff812764e0)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In kernel/events/core.c (ffffffff81279d16)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/loopback.c (ffffffff8190001d)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8190f0e4)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81915778)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8191eb1c)
Location: include/linux/u64_stats_sync.h:86
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81a917c7)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81aa1de9)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81acfe9d)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81ad1a37)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/ptp_classifier.c (ffffffff81aec7bd)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81aedc9e)
Location: include/linux/u64_stats_sync.h:86
Inline: True
```
```
In net/core/skmsg.c (ffffffff81b073d7)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81b2c089)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b539ab)
Location: include/linux/u64_stats_sync.h:86
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8842b)
Location: include/linux/u64_stats_sync.h:86
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1b455)
Location: include/linux/u64_stats_sync.h:86
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c48156)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e715)
Location: include/linux/u64_stats_sync.h:86
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c56b94)
Location: include/linux/u64_stats_sync.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/seccomp.c (ffffffff81201d38)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff81257581)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/bpf/syscall.c (ffffffff812779ef)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff8129a16d)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff812a949f)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff812bac2c)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bc11a)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff812c5f3a)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In kernel/events/core.c (ffffffff812cd0bb)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/loopback.c (ffffffff81a51a47)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81a63cbf)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6ae56)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81a73d82)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/core/gen_stats.c (ffffffff81c029ec)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81c0796d)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81c1a041)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81c4d657)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81c4f2de)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81c6f1e8)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81c7078e)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81c8be8f)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/sched/sch_generic.c (ffffffff81c9484a)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81ca42a8)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81ca84a9)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/bpf/test_run.c (ffffffff81cb6693)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1500)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d195e0)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db7bed)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81de7656)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def01d)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df5f6a)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/seccomp.c (ffffffff8124a10a)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6f61)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b8213)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812cdd7f)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f60d7)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff813082a4)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff8131e010)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8131f508)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8132b4ba)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In kernel/events/core.c (ffffffff81347a67)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/spi/spi.c (ffffffff81bcf540)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81bdac87)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81bf2e9e)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfdc31)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c07f93)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/core/gen_stats.c (ffffffff81db1eac)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81db73f4)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81dcb0a4)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81e02567)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e04472)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81e25ed8)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/ptp_classifier.c (ffffffff81e26fa8)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e28782)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/devlink.c (ffffffff81e2aae3)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_stats_read
  - net/core/devlink.c:devlink_trap_stats_read
```
```
In net/core/skmsg.c (ffffffff81e483c6)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/sched/sch_generic.c (ffffffff81e5030a)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81e60c18)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81e652c9)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/bpf/test_run.c (ffffffff81e74b78)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea24f0)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81edff60)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0df27)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/udp.c (ffffffff81f87a4d)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81fba5d6)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc30ad)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fca4c6)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/8021q/vlan_core.c (ffffffff81fcea90)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/seccomp.c (ffffffff81261424)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8840)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db83a)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812f5310)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323e87)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff813375d5)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/devmap.c (ffffffff8134de00)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8134f3eb)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8135b6da)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In kernel/events/core.c (ffffffff8137931f)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/spi/spi.c (ffffffff81c271b0)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81c3172b)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81c4a085)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/virtio_net.c (ffffffff81c4f79b)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63270)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d686)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/core/gen_stats.c (ffffffff81e2247c)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81e27ab4)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3bc2e)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81e74917)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e76cc3)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81e9b478)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/ptp_classifier.c (ffffffff81e9c52f)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e9dda3)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81ea3b8b)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/sched/sch_generic.c (ffffffff81eabab0)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81ebcc68)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81ec1209)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/bpf/test_run.c (ffffffff81ed0948)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81eea919)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00d0f)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f39f)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dbd7)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/udp.c (ffffffff81fe7eda)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201ad09)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8202401a)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202b318)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/devlink/leftover.c (ffffffff8202ea03)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_trap_report
  - net/devlink/leftover.c:devlink_trap_report
  - net/devlink/leftover.c:devlink_trap_stats_read
  - net/devlink/leftover.c:devlink_trap_stats_read
```
```
In net/8021q/vlan_core.c (ffffffff8204a3f8)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/seccomp.c (ffffffff8127b624)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5848)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:uprobe_prog_run
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9922)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff81314107)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347e17)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8135d415)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/devmap.c (ffffffff8137530c)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81376a59)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8138436a)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In kernel/events/core.c (ffffffff813a262f)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/spi/spi.c (ffffffff81cdae60)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81ce45ab)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/netkit.c (ffffffff81ce5387)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81cffa11)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/virtio_net.c (ffffffff81d0c6b0)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:free_old_xmit_skbs
  - drivers/net/virtio_net.c:free_old_xmit_skbs
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19c90)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81d21fd6)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/core/gen_stats.c (ffffffff81ee03bc)
Location: include/linux/u64_stats_sync.h:87
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81ee5a64)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81efa16a)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tc_run
  - net/core/dev.c:tc_run
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81f340d7)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81f36c83)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81f5dbe8)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/ptp_classifier.c (ffffffff81f5ecbf)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81f60523)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81f6648b)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/sched/sch_generic.c (ffffffff81f6e550)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81f7fe68)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81f84509)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/bpf/test_run.c (ffffffff81f942a8)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81fae6c9)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc4ed8)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034364)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/seg6_local.c (ffffffff820e9cc9)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3133)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6
```
```
In net/packet/af_packet.c (ffffffff820fadeb)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/devlink/trap.c (ffffffff82114833)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_trap_report
  - net/devlink/trap.c:devlink_trap_report
  - net/devlink/trap.c:devlink_trap_stats_read
  - net/devlink/trap.c:devlink_trap_stats_read
```
```
In net/8021q/vlan_core.c (ffffffff8211c864)
Location: include/linux/u64_stats_sync.h:87
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
