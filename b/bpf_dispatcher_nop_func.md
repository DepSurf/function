# Function: <code>bpf_dispatcher_nop_func</code>

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
In kernel/seccomp.c (ffffffff811a55b6)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8b3e)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
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
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121609d)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/cgroup.c (ffffffff8122ed69)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
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
```
```
In kernel/events/core.c (ffffffff8123119d)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff8188e756)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893431)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/flow_dissector.c (ffffffff819fb4da)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/filter.c (ffffffff81a3319c)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81a34a22)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81a3ccdd)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/ptp_classifier.c (ffffffff81a4b50e)
Location: include/linux/bpf.h:550
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a4c602)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/bpf/test_run.c (ffffffff81a7e3bd)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f792)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/packet/af_packet.c (ffffffff81b8b850)
Location: include/linux/bpf.h:550
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/seccomp.c (ffffffff811a391f)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff811e5f3e)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
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
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121801c)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/cgroup.c (ffffffff812372ca)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
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
```
```
In kernel/events/core.c (ffffffff8123adb2)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff8189d0bb)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a1721)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/flow_dissector.c (ffffffff819fb0d8)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/filter.c (ffffffff81a3555c)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81a36d62)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81a3f67c)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
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
```
```
In net/core/ptp_classifier.c (ffffffff81a511ae)
Location: include/linux/bpf.h:660
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a52282)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/bpf/test_run.c (ffffffff81a877f0)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad336)
Location: include/linux/bpf.h:660
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81adeae6)
Location: include/linux/bpf.h:660
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b66280)
Location: include/linux/bpf.h:660
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e742)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93460)
Location: include/linux/bpf.h:660
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9acc5)
Location: include/linux/bpf.h:660
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/seccomp.c (ffffffff811a4541)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff811e761e)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
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
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121b469)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/cgroup.c (ffffffff8123bb08)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
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
```
```
In kernel/events/core.c (ffffffff8123f582)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff8187f8eb)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883db1)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/flow_dissector.c (ffffffff819e12fd)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/filter.c (ffffffff81a1c6bc)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81a1defd)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/ptp_classifier.c (ffffffff81a36a1e)
Location: include/linux/bpf.h:678
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a37da0)
Location: include/linux/bpf.h:678
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a4e60d)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
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
```
```
In net/bpf/test_run.c (ffffffff81a724a0)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98416)
Location: include/linux/bpf.h:678
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ac9ad6)
Location: include/linux/bpf.h:678
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b54400)
Location: include/linux/bpf.h:678
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0fd)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82590)
Location: include/linux/bpf.h:678
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8a6cd)
Location: include/linux/bpf.h:678
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/seccomp.c (ffffffff811cdd8e)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff8121829b)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
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
```
```
In kernel/bpf/bpf_iter.c (ffffffff8125233b)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/cgroup.c (ffffffff81276420)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
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
```
```
In kernel/events/core.c (ffffffff81279c8c)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff81910a74)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191542b)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/flow_dissector.c (ffffffff81a9173a)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/filter.c (ffffffff81acfe2f)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81ad198a)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/ptp_classifier.c (ffffffff81aec76b)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81aedbb0)
Location: include/linux/bpf.h:711
Inline: True
```
```
In net/core/skmsg.c (ffffffff81b0734a)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
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
```
```
In net/bpf/test_run.c (ffffffff81b2bf40)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b538d3)
Location: include/linux/bpf.h:711
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b88353)
Location: include/linux/bpf.h:711
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1b37d)
Location: include/linux/bpf.h:711
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a94d)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e63d)
Location: include/linux/bpf.h:711
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c567dd)
Location: include/linux/bpf.h:711
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/seccomp.c (ffffffff81201cae)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/bpf_trace.c (ffffffff812574fc)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
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
```
```
In kernel/bpf/syscall.c (ffffffff8127798a)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff8129a072)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/cgroup.c (ffffffff812c5e72)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
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
```
```
In kernel/events/core.c (ffffffff812cd026)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff81a6084b)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6aae0)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/flow_dissector.c (ffffffff81c078ce)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/filter.c (ffffffff81c4d5d5)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81c4f269)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81c6f18b)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81c70719)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81c8bde7)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
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
```
```
In net/bpf/test_run.c (ffffffff81cb6575)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1417)
Location: include/linux/bpf.h:863
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d194f7)
Location: include/linux/bpf.h:863
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db7b04)
Location: include/linux/bpf.h:863
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81de7f09)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81deef34)
Location: include/linux/bpf.h:863
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df5b63)
Location: include/linux/bpf.h:863
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int bpf_dispatcher_nop_func(const void *ctx, const struct bpf_insn *insnsi, bpf_func_t bpf_func);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81249fea)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6edc)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
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
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7f99)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812cdd1a)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5f8d)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/dispatcher.c (ffffffff8131c8a0)
Location: include/linux/bpf.h:1084
Inline: False
```
```
In kernel/bpf/cgroup.c (ffffffff8132b3f2)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
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
```
```
In kernel/events/core.c (ffffffff813479d2)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff81bece0a)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfd923)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/flow_dissector.c (ffffffff81db7359)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/filter.c (ffffffff81e024e5)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e043f9)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81e26f4b)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e28709)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81e4834c)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
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
```
```
In net/bpf/test_run.c (ffffffff81e74a55)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2407)
Location: include/linux/bpf.h:1084
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81edfe77)
Location: include/linux/bpf.h:1084
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f87964)
Location: include/linux/bpf.h:1084
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb189)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc2fc4)
Location: include/linux/bpf.h:1084
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fca0e3)
Location: include/linux/bpf.h:1084
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8131c8a0-ffffffff8131c8b5: bpf_dispatcher_nop_func (STB_LOCAL)
ffffffff81deabc0-ffffffff81deabd5: bpf_dispatcher_nop_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int bpf_dispatcher_nop_func(const void *ctx, const struct bpf_insn *insnsi, bpf_func_t bpf_func);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812612d9)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812c87c7)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
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
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db5c8)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812f52a6)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323d2d)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/dispatcher.c (ffffffff8134c5a0)
Location: include/linux/bpf.h:1162
Inline: False
```
```
In kernel/bpf/cgroup.c (ffffffff8135b612)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
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
```
```
In kernel/events/core.c (ffffffff8137927c)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/tun.c (ffffffff81c45305)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6312c)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/flow_dissector.c (ffffffff81e27a19)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/filter.c (ffffffff81e74895)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e76c49)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81e9c4dc)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e9dd29)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81ea3b11)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
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
```
```
In net/bpf/test_run.c (ffffffff81ed0825)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81eea8ae)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00c26)
Location: include/linux/bpf.h:1162
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f2b6)
Location: include/linux/bpf.h:1162
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe7df1)
Location: include/linux/bpf.h:1162
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201b849)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82023f31)
Location: include/linux/bpf.h:1162
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202ade6)
Location: include/linux/bpf.h:1162
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff8134c5a0-ffffffff8134c5b5: bpf_dispatcher_nop_func (STB_LOCAL)
ffffffff81e5c3c0-ffffffff81e5c3d5: bpf_dispatcher_nop_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int bpf_dispatcher_nop_func(const void *ctx, const struct bpf_insn *insnsi, bpf_func_t bpf_func);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127b4d9)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (ffffffff812e57a7)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
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
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f96a7)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff8131409d)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347cbd)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/dispatcher.c (ffffffff81373ad0)
Location: include/linux/bpf.h:1226
Inline: False
```
```
In kernel/bpf/cgroup.c (ffffffff813842a2)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
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
```
```
In kernel/events/core.c (ffffffff813a258c)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
```
```
In drivers/net/netkit.c (ffffffff81ce52bb)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81cfac37)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19b4c)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/flow_dissector.c (ffffffff81ee59c9)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81ef9aea)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f34055)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81f36c09)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81f5ec6c)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81f604a9)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81f66411)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
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
```
```
In net/bpf/test_run.c (ffffffff81f94185)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81fae65e)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc4def)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4
  - net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4
```
```
In net/ipv6/seg6_local.c (ffffffff820ea809)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f304a)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6
  - net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6
```
```
In net/packet/af_packet.c (ffffffff820fa8e2)
Location: include/linux/bpf.h:1226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff81373ad0-ffffffff81373ae5: bpf_dispatcher_nop_func (STB_LOCAL)
ffffffff81f1b7b0-ffffffff81f1b7c5: bpf_dispatcher_nop_func (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
