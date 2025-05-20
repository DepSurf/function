# Function: <code>skb_rtable</code>

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
In net/ipv4/route.c (ffffffff817531de)
Location: include/linux/skbuff.h:792
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81758789)
Location: include/linux/skbuff.h:792
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/skbuff.h:792
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:792
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff8175abe7)
Location: include/linux/skbuff.h:792
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
```
```
In net/ipv4/ip_output.c (ffffffff8175c6f0)
Location: include/linux/skbuff.h:792
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:792
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e8ab)
Location: include/linux/skbuff.h:792
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8178a34e)
Location: include/linux/skbuff.h:792
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/arp.c (ffffffff8178ce08)
Location: include/linux/skbuff.h:792
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8178e39b)
Location: include/linux/skbuff.h:792
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:792
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/skbuff.h:792
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/skbuff.h:792
Inline: True
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
In net/ipv4/route.c (ffffffff817c3795)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff817c4ad9)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5b17)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:880
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff817c7724)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
```
```
In net/ipv4/ip_output.c (ffffffff817cb8be)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:880
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e857d)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff817f7758)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/arp.c (ffffffff817fa425)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff817fc6f9)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff81805fcd)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff818086a8)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81818285)
Location: include/linux/skbuff.h:880
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
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
In net/ipv4/route.c (ffffffff817f3152)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff817f45f9)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5617)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:894
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff817f7214)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
```
```
In net/ipv4/ip_output.c (ffffffff817fb51e)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:894
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181a143)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff81828665)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/arp.c (ffffffff8182b2f5)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8182d659)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/igmp.c (ffffffff8183704d)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81839758)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81849ae5)
Location: include/linux/skbuff.h:894
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
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
In net/ipv4/route.c (ffffffff818135e3)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81814a31)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff81815aac)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:847
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff81817676)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8181b8ff)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:847
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183a23f)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff81849924)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/arp.c (ffffffff8184c6e2)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8184eaf9)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8185849f)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff8185acc8)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff8186d34c)
Location: include/linux/skbuff.h:847
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
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
In net/ipv4/route.c (ffffffff81892c33)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81893bd4)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff81894c87)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:927
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff818966f6)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8189a835)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:927
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b9cd7)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff818c8faf)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/arp.c (ffffffff818cc398)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff818ce879)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff818d836f)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff818dabf8)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff818edc5c)
Location: include/linux/skbuff.h:927
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
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
In net/ipv4/route.c (ffffffff818e6cb0)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff818e7e82)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8d36)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:931
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff818ea9c5)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff818eed08)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f16ef)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911ee8)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff8191f118)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff819227df)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81924c75)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8192ee20)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81931b75)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff819439e8)
Location: include/linux/skbuff.h:931
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
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
In net/ipv4/route.c (ffffffff81913b67)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81914d5f)
Location: include/linux/skbuff.h:955
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81917069)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:955
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff81917735)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8191c4c0)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f24f)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819406b1)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff8194dd75)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff819515e5)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81953a85)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff8195e27e)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff819613d5)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81973b58)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca4b3)
Location: include/linux/skbuff.h:955
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81976218)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81977225)
Location: include/linux/skbuff.h:979
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81979052)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:979
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff81979e35)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8197e7fb)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981b9f)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4bec)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819ad29d)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b2554)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff819b5ead)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819b8365)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff819c3649)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5bb5)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff819dd667)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a390bf)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff819acc28)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819adbb5)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819af9c2)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff819b0795)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819b519b)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b83df)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db8ec)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819e3f5d)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e92f4)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff819ecbcd)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819ef065)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff819fa1e9)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc765)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81a14797)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6fc2f)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81a9672c)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a97af9)
Location: include/linux/skbuff.h:1007
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a998a1)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a99b1c)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81a9a625)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81a9c62a)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2cf6)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac89c0)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81ad1630)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad7463)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff81adab9d)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81adcfb5)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81ae89ec)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb4d5)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81b05717)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69b71)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/mptcp/subflow.c (ffffffff81bae248)
Location: include/linux/skbuff.h:1007
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In net/ipv4/route.c (ffffffff81aa07d2)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81aa1a59)
Location: include/linux/skbuff.h:1014
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3816)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3a6c)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81aa4585)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81aa648a)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aad006)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4960)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81add6b0)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae3ab3)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5b36)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81ae763d)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81ae9d05)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81af58ec)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81af83d5)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81b13937)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78643)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/mptcp/subflow.c (ffffffff81bc12b8)
Location: include/linux/skbuff.h:1014
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In net/ipv4/route.c (ffffffff81a8b702)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a8ca29)
Location: include/linux/skbuff.h:1020
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e966)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a8eb52)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81a8f69f)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81a944ec)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98256)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfa16)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81ac8780)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81aceca3)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0e26)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81ad28fd)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81ad5445)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81ae1048)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3af5)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81b01777)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6758b)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/mptcp/subflow.c (ffffffff81bb1c68)
Location: include/linux/skbuff.h:1020
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In net/ipv4/route.c (ffffffff81b46642)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81b47b59)
Location: include/linux/skbuff.h:1032
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49b65)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81b49d6b)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81b4a8df)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81b4f96c)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b536b0)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d582)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81b86fe0)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8d693)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f843)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81b9154d)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81b94255)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81ba06e8)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3405)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81bb0667)
Location: include/linux/skbuff.h:1032
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bc34f7)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f1b2)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/mptcp/subflow.c (ffffffff81c7fcf5)
Location: include/linux/skbuff.h:1032
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In net/ipv4/route.c (ffffffff81cd354a)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81cd4dc9)
Location: include/linux/skbuff.h:1322
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd66ed)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81cd72a1)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81cd7720)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81cdd3eb)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce1104)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d4e5)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81d17c8a)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1e7d4)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d20b3d)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81d228ba)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81d25b35)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81d32bbb)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35c65)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81d43b61)
Location: include/linux/skbuff.h:1322
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d58327)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc5cc)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/mptcp/subflow.c (ffffffff81e256e4)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In net/ipv4/route.c (ffffffff81e93746)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81e9511d)
Location: include/linux/skbuff.h:1164
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96c45)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81e978c2)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81e97da0)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81e9deaa)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1514)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2f1f)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81ede50a)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee5914)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7dc2)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81ee9e14)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81eed3f5)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81efae4b)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe255)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81f0cce9)
Location: include/linux/skbuff.h:1164
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f227e7)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d6e3)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/mptcp/subflow.c (ffffffff81ffd324)
Location: include/linux/skbuff.h:1164
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In net/ipv4/route.c (ffffffff81ef1eee)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81ef38ed)
Location: include/linux/skbuff.h:1174
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef547d)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81ef60ff)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81ef6600)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81efc674)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81effd20)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31c1d)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81f3d860)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81f45114)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f4762a)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81f4977a)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81f4cdb5)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff81f5a8dd)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5dce5)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81f6c960)
Location: include/linux/skbuff.h:1174
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f82317)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe164)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/mptcp/subflow.c (ffffffff820795f4)
Location: include/linux/skbuff.h:1174
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In net/ipv4/route.c (ffffffff81fb603e)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81fb787d)
Location: include/linux/skbuff.h:1181
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb942d)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81fba08f)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81fba590)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81fc05b4)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3ea7)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7c6b)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_ao_sign_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/raw.c (ffffffff82003970)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff8200b174)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200d76a)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff8200f8c2)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff82012ec5)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/igmp.c (ffffffff82020e1d)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff820242a5)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff820330b0)
Location: include/linux/skbuff.h:1181
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82048997)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccf7f)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/mptcp/subflow.c (ffffffff8214ea44)
Location: include/linux/skbuff.h:1181
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v4_conn_request
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
In net/ipv4/route.c (ffff800010c5ccf8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffff800010c5e35c)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f710)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (ffff800010c60db4)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffff800010c6595c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69788)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ec98)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffff800010c98930)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9ebf4)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffff800010ca269c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffff800010ca4e6c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffff800010cb183c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4bb0)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffff800010ccf9a0)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38544)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (c0d6c464)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (c0d6d3a8)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (c0d6f1b8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (c0d7077c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (c0d755a8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (c0d789bc)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (c0d9dbf0)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (c0da6798)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0dabe58)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (c0daf4a8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (c0db1764)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (c0dbd434)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (c0dc054c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (c0dda014)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (c0e3b854)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (c000000000d5f2d0)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (c000000000d60780)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (c000000000d626c0)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (c000000000d6402c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (c000000000d6a0b8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e4a0)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d7f8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (c000000000daa0dc)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db143c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (c000000000db5cd0)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (c000000000db8b68)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (c000000000dc86e8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (c000000000dcbdcc)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (c000000000dedaf8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6bd34)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffe0007c5b08)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffe0007c6816)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c82f2)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffe0007c8fac)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffe0007cd0ae)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf5ee)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eef4a)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffe0007f6a8e)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fb74e)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffe0007fe5d8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffe000800808)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffe00080a272)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c762)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffe000821b7a)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008756a8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff8194ca98)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff8194da25)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f832)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff81950605)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8195500b)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195824f)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b75c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81983dcd)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989164)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff8198c9b5)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8198ee05)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81999f89)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff8199c505)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff819b3e57)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f2bf)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81906588)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81907515)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81909322)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff8190a0f5)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8190eafb)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911d3f)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193521c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff8193d88d)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81942c24)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff81946475)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819488c5)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81953a49)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81955fc5)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ip_tunnel.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81970487)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc07f)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff819b7268)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819b81f5)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819ba002)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff819badd5)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819bf7db)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2a1f)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5f2c)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819ee59d)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f3934)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff819f720d)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819f96a5)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81a04829)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06da5)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81a1e6f7)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a79d3f)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff819c0aed)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819c1a55)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c32e8)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:975
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff819c46d5)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819c9157)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc41f)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efbec)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819f85fd)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fdaf4)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff81a0142d)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81a03995)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/igmp.c (ffffffff81a0eda9)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11455)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ipmr.c (ffffffff81a29a87)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86532)
Location: include/linux/skbuff.h:975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
</details>
</li>
</ul>

## Differences
