# Function: <code>__bpf_prog_run</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int __bpf_prog_run(void *ctx, const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81171550)
Location: kernel/bpf/core.c:195
Inline: False
```
**Symbols:**

```
ffffffff81171550-ffffffff81172964: __bpf_prog_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int __bpf_prog_run(void *ctx, const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117f370)
Location: kernel/bpf/core.c:468
Inline: False
```
**Symbols:**

```
ffffffff8117f370-ffffffff81180782: __bpf_prog_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int __bpf_prog_run(void *ctx, const struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118b1e0)
Location: kernel/bpf/core.c:550
Inline: False
```
**Symbols:**

```
ffffffff8118b1e0-ffffffff8118c5f2: __bpf_prog_run (STB_LOCAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cdd8c)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff81218299)
Location: include/linux/filter.h:606
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
In kernel/bpf/bpf_iter.c (ffffffff81252339)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/devmap.c (ffffffff8126bc76)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126d7f8)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8127641b)
Location: include/linux/filter.h:606
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
In kernel/events/core.c (ffffffff81279c8a)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff8190ef75)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81915426)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8191ea14)
Location: include/linux/filter.h:606
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81a91738)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81aa1c6a)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81acfe2d)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81ad1988)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/ptp_classifier.c (ffffffff81aec769)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81aedbab)
Location: include/linux/filter.h:606
Inline: True
```
```
In net/core/skmsg.c (ffffffff81b07348)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81b2bf3b)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b538ce)
Location: include/linux/filter.h:606
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8834e)
Location: include/linux/filter.h:606
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1b378)
Location: include/linux/filter.h:606
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a948)
Location: include/linux/filter.h:606
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e638)
Location: include/linux/filter.h:606
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c567d4)
Location: include/linux/filter.h:606
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
In kernel/seccomp.c (ffffffff81201cac)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff812574fa)
Location: include/linux/filter.h:609
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
In kernel/bpf/syscall.c (ffffffff81277988)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff8129a06d)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/devmap.c (ffffffff812baab7)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bbff8)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff812c5e6d)
Location: include/linux/filter.h:609
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
In kernel/events/core.c (ffffffff812cd024)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff81a639b6)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6aadb)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81a73c6c)
Location: include/linux/filter.h:609
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81c078cc)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81c19e4a)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81c4d5d3)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81c4f267)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81c6f189)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81c70717)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81c8bde5)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81cb6570)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1412)
Location: include/linux/filter.h:609
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d194f2)
Location: include/linux/filter.h:609
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db7aff)
Location: include/linux/filter.h:609
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81de7f07)
Location: include/linux/filter.h:609
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81deef2f)
Location: include/linux/filter.h:609
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df5b5a)
Location: include/linux/filter.h:609
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
In kernel/seccomp.c (ffffffff81249fe5)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6eda)
Location: include/linux/filter.h:581
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
In kernel/trace/trace_uprobe.c (ffffffff812b7f94)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812cdd18)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5f88)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/devmap.c (ffffffff8131dea3)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8131f3e4)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8132b3ed)
Location: include/linux/filter.h:581
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
In kernel/events/core.c (ffffffff813479d0)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff81bf2b96)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfd91e)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c07d9c)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81db7357)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81dcaeca)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81e024e3)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e043f7)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81e26f49)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e28707)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81e4834a)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81e74a50)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2402)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81edfe72)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f8795f)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb187)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc2fbf)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fca0da)
Location: include/linux/filter.h:581
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812612d4)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812c87c5)
Location: include/linux/filter.h:581
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
In kernel/trace/trace_uprobe.c (ffffffff812db5c3)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812f52a4)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323d28)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/devmap.c (ffffffff8134dc93)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8134f234)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8135b60d)
Location: include/linux/filter.h:581
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
In kernel/events/core.c (ffffffff8137927a)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff81c49dca)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/virtio_net.c (ffffffff81c4f6fc)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63127)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d4bc)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81e27a17)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3ba53)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81e74893)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e76c47)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81e9c4d4)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e9dd27)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81ea3b0f)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81ed0820)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81eea8ac)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00c21)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f2b1)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe7dec)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201b847)
Location: include/linux/filter.h:581
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82023f2c)
Location: include/linux/filter.h:581
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202addd)
Location: include/linux/filter.h:581
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127b4d4)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812e57a5)
Location: include/linux/filter.h:632
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
In kernel/trace/trace_uprobe.c (ffffffff812f96a2)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff8131409b)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347cb8)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/devmap.c (ffffffff813751a3)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff813768a6)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8138429d)
Location: include/linux/filter.h:632
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
In kernel/events/core.c (ffffffff813a258a)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/netkit.c (ffffffff81ce52b6)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81cff75a)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/virtio_net.c (ffffffff81d053ec)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19b47)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81d21e0c)
Location: include/linux/filter.h:632
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81ee59c7)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81ef9f93)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f34053)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81f36c07)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81f5ec64)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81f604a7)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81f6640f)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81f94180)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81fae65c)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc4dea)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4
```
```
In net/ipv6/seg6_local.c (ffffffff820ea807)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3045)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6
```
```
In net/packet/af_packet.c (ffffffff820fa8d9)
Location: include/linux/filter.h:632
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
