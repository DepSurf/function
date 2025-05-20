# Function: <code>u64_stats_inc</code>

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
In drivers/net/loopback.c (ffffffff8187eb98)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81886b3f)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff8188ec17)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
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
In drivers/net/loopback.c (ffffffff8188d118)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81894f5e)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
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
In drivers/net/loopback.c (ffffffff8186fa58)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8187780e)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d78b)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
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
In kernel/seccomp.c (ffffffff811cde04)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff812182ee)
Location: include/linux/u64_stats_sync.h:91
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
In kernel/bpf/bpf_iter.c (ffffffff8125238e)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8125f3f6)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter
```
```
In kernel/bpf/devmap.c (ffffffff8126bdd7)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126d998)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff812764d8)
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
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In kernel/events/core.c (ffffffff81279d0e)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/loopback.c (ffffffff81900021)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81908551)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff8190f0dc)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81915770)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8191eb10)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81a917bf)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81aa1ddd)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81acfe95)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81ad1a2b)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/ptp_classifier.c (ffffffff81aec7b5)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81aedc96)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/core/skmsg.c (ffffffff81b073cf)
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
In net/bpf/test_run.c (ffffffff81b2c080)
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
In net/ipv4/inet_hashtables.c (ffffffff81b539a3)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b88423)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1b44d)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c48153)
Location: include/linux/u64_stats_sync.h:91
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e70d)
Location: include/linux/u64_stats_sync.h:91
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c56b88)
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81201d30)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff81257579)
Location: include/linux/u64_stats_sync.h:96
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
In kernel/bpf/syscall.c (ffffffff812779e7)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff8129a165)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff812a9afb)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter
```
```
In kernel/bpf/devmap.c (ffffffff812bac1d)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bc112)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff812c5f32)
Location: include/linux/u64_stats_sync.h:96
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
In kernel/events/core.c (ffffffff812cd0b3)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/loopback.c (ffffffff81a51a4b)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5bdc1)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81a63cb3)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6ae4e)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81a73d76)
Location: include/linux/u64_stats_sync.h:96
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81c07965)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81c1a035)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81c4d64f)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81c4f2d6)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81c6f1df)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81c70786)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81c8be87)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81cb668b)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce14f8)
Location: include/linux/u64_stats_sync.h:96
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d195d8)
Location: include/linux/u64_stats_sync.h:96
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db7be5)
Location: include/linux/u64_stats_sync.h:96
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81de7653)
Location: include/linux/u64_stats_sync.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def015)
Location: include/linux/u64_stats_sync.h:96
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df5f5e)
Location: include/linux/u64_stats_sync.h:96
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
In kernel/seccomp.c (ffffffff8124a102)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6f59)
Location: include/linux/u64_stats_sync.h:92
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
In kernel/trace/trace_uprobe.c (ffffffff812b8207)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812cdd77)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_misses_counter
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f60cf)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8130829c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff8131e001)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8131f4fb)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8132b4b2)
Location: include/linux/u64_stats_sync.h:92
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
In kernel/events/core.c (ffffffff81347a5f)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/spi/spi.c (ffffffff81bd7026)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81bdac8b)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be61f1)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81bf2e92)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfdc29)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c07f87)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81db73ec)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81dcb098)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81e0255f)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e0446a)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81e23f3e)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/ptp_classifier.c (ffffffff81e26f9f)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e2877a)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/devlink.c (ffffffff81e2aae6)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
```
```
In net/core/skmsg.c (ffffffff81e483be)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81e74b6c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea24e8)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81edff58)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0df2b)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/udp.c (ffffffff81f87a45)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81fba5d3)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc30a5)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fca4ba)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/8021q/vlan_core.c (ffffffff81fcea8d)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/seccomp.c (ffffffff8126141c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8837)
Location: include/linux/u64_stats_sync.h:92
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
In kernel/trace/trace_uprobe.c (ffffffff812db82e)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812f5307)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_misses_counter
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323e7e)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff813375cd)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/devmap.c (ffffffff8134ddf1)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8134f3de)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8135b6d2)
Location: include/linux/u64_stats_sync.h:92
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
In kernel/events/core.c (ffffffff81379317)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/spi/spi.c (ffffffff81c2da56)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81c3172f)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3eb70)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81c4a079)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/virtio_net.c (ffffffff81c4f78f)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63268)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d67a)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81e27aac)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3bc22)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81e7490f)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e76cba)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81e9947e)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/ptp_classifier.c (ffffffff81e9c527)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e9dd9a)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81ea3b83)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81ed093c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81eea911)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00d07)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f397)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dbdb)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/udp.c (ffffffff81fe7ed2)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201ad06)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024012)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202b30c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/devlink/leftover.c (ffffffff8202ea06)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_trap_report
  - net/devlink/leftover.c:devlink_trap_report
```
```
In net/8021q/vlan_core.c (ffffffff8204a3f5)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/seccomp.c (ffffffff8127b61c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812e583f)
Location: include/linux/u64_stats_sync.h:92
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
In kernel/trace/trace_uprobe.c (ffffffff812f9916)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff813140fe)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_misses_counter
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347e0e)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8135d40d)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/devmap.c (ffffffff813752fd)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81376a4c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff81384362)
Location: include/linux/u64_stats_sync.h:92
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
In kernel/events/core.c (ffffffff813a2627)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/spi/spi.c (ffffffff81ce0455)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81ce45af)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/netkit.c (ffffffff81ce537e)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf3650)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81cffa05)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/virtio_net.c (ffffffff81d01df0)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_tx_timeout
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19c88)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81d21fca)
Location: include/linux/u64_stats_sync.h:92
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81ee5a5c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81efa15e)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f340cf)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81f36c7a)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81f5bb6d)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/ptp_classifier.c (ffffffff81f5ecb7)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81f6051a)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81f66483)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81f9429c)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81fae6c1)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc4ed0)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034368)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/seg6_local.c (ffffffff820e9cc6)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f312b)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6
```
```
In net/packet/af_packet.c (ffffffff820faddf)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/devlink/trap.c (ffffffff82114836)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_trap_report
  - net/devlink/trap.c:devlink_trap_report
```
```
In net/8021q/vlan_core.c (ffffffff8211c861)
Location: include/linux/u64_stats_sync.h:92
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
