# Function: <code>sock_net_uid</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f1fde)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff817fa5a7)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800b20)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ab4e)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81822322)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff8182c64a)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/af_inet.c (ffffffff81832db3)
Location: include/net/sock.h:1709
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81835721)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81839a1a)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81848398)
Location: include/net/sock.h:1709
Inline: True
```
```
In net/ipv6/route.c (ffffffff81878251)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81888615)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188fb37)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff818a0316)
Location: include/net/sock.h:1709
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (0)
Location: include/net/sock.h:1714
Inline: True
```
```
In net/ipv4/route.c (ffffffff81812f46)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8181a9b3)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820710)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b357)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81842f92)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff8184daca)
Location: include/net/sock.h:1714
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818540d3)
Location: include/net/sock.h:1714
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81856c71)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8185af90)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81869aba)
Location: include/net/sock.h:1714
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189d479)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff818aed74)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b61d9)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff818c6957)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (0)
Location: include/net/sock.h:1728
Inline: True
```
```
In net/ipv4/route.c (ffffffff81892586)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81899993)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f6e0)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb067)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff818c28f8)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff818cd7da)
Location: include/net/sock.h:1728
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818d3f53)
Location: include/net/sock.h:1728
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818d6b21)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff818daf22)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff818ea169)
Location: include/net/sock.h:1728
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191f789)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81931a74)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938f69)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81949d52)
Location: include/net/sock.h:1728
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff818b4e14)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/ipv4/route.c (ffffffff818e4bc3)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff818eddd7)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f40ff)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191065f)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81918555)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81923bc8)
Location: include/net/sock.h:1739
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8192a400)
Location: include/net/sock.h:1739
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8192d48b)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8193122b)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81940853)
Location: include/net/sock.h:1739
Inline: True
```
```
In net/ipv6/route.c (ffffffff8197796d)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff8198a53f)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199280d)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff819a2d5b)
Location: include/net/sock.h:1739
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff818da9d4)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/ipv4/route.c (ffffffff81911ac2)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8191b5b0)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921c0f)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193dfff)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81946cd5)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff819529b5)
Location: include/net/sock.h:1824
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81959b90)
Location: include/net/sock.h:1824
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8195c92b)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81960b1a)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff819706de)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff819ad52c)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff819c0dd9)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8f41)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff819d9a26)
Location: include/net/sock.h:1824
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff8192a066)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff819431f9)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81974228)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8197d864)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819845e1)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a2424)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff819ab358)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff819b7230)
Location: include/net/sock.h:1836
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819be4cf)
Location: include/net/sock.h:1836
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819c162a)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819c55f7)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff819d9f5a)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81a1a68b)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81a2fb14)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a378fd)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81a48296)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff8195c3f6)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff8197816e)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819aac48)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819b4204)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bad91)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d8ff4)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff819e2028)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff819edf30)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819f50ff)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819f81ca)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc197)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81a10e4c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81a512fb)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81a66664)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e429)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81a7ee46)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff81a30196)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81a4cc8c)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a94f82)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81a9e33f)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5651)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5b2b)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81acf328)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81adbcf4)
Location: include/net/sock.h:1895
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81ae38ce)
Location: include/net/sock.h:1895
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81ae5229)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81aea38d)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81b02841)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81b48a1c)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81b5f013)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6821f)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81b79a96)
Location: include/net/sock.h:1895
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff81a31e96)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81a5294c)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a9ef82)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81aa8233)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafc61)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad179b)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81adb32d)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81ae87d4)
Location: include/net/sock.h:1907
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81af0453)
Location: include/net/sock.h:1907
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81af20f7)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81af71ed)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81b10c08)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81b5762c)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81b6d7a3)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76a5c)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81b889e4)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff81a18c02)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81a380c6)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a89efd)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81a93216)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9af71)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abc7b7)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81ac638e)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81ad456b)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81adbb93)
Location: include/net/sock.h:1923
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81add8e7)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae292d)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81afe841)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81b4521e)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81b5bb3b)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b653c1)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81b77708)
Location: include/net/sock.h:1923
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff81aca412)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81aedf06)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81b44d8d)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81b4e647)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b563e1)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a400)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81b84b9e)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81b93f80)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81b9adc3)
Location: include/net/sock.h:1963
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81b9cd57)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba21bd)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81bc005b)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81c0c35e)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81c23272)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d49c)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81c421d9)
Location: include/net/sock.h:1963
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff81c47838)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81c70d31)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81cd1aa7)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81cdbf40)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4521)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a5d5)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81d15440)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81d25412)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81d2c786)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81d2ee26)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81d348f2)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81d54a36)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81da7215)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81dc017b)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca8b0)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81de0bce)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff81dfbf08)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81e28db1)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81e91fe7)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81e9c940)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea74d1)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfe65)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81edbc30)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81eeca02)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81ef5126)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81ef6e86)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81efcdf0)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec71)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81f76825)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81f908eb)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b916)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81fb300e)
Location: include/net/sock.h:2121
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff81e6f9f1)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81e9e3e5)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81ef076d)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81efb56b)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05c71)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2eb11)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81f3ad00)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81f4b5ee)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81f54a06)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81f56903)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c830)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81f7e771)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81fd6855)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81ff1167)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbcd2)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff820136fe)
Location: include/net/sock.h:2109
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff81f2f1aa)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81f60b61)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81fb48bd)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81fbf493)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9dd1)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff392b)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff82000dee)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff820116fe)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff8201ac56)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff8201cdb0)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff82022db2)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff82044e12)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff820a41d5)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff820bed45)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca3e4)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff820e2863)
Location: include/net/sock.h:2099
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffff800010bfe280)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffff800010c1e9e8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffff800010c5af78)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffff800010c64998)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6ca64)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c500)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffff800010c95cd8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffff800010ca3adc)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (ffff800010caaf70)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (ffff800010cafdf8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffff800010cb45c0)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffff800010cccbb8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffff800010d15250)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffff800010d2c5bc)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37d54)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffff800010d4a72c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (c0d188f8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (c0d36a2c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (c0d6a48c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (c0d7454c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (c0d7b764)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (c0d9be48)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (c0da4460)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (c0db0764)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (c0db7924)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (c0dbb78c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (c0dbfab0)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (c0dd71d0)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (c0e1aef8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (c0e304b0)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (c0e38a0c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (c0e4b658)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (c000000000ce5da0)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (c000000000d10b68)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (c000000000d5cd08)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (c000000000d68be4)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (c000000000d723f8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9aa38)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (c000000000da7540)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (c000000000db7414)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (c000000000dc13a4)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (c000000000dc5d00)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (c000000000dcb5c0)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (c000000000de87c8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (c000000000e421e4)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (c000000000e5de94)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (c000000000e692a8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (c000000000e7ffe0)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffe0007802fc)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffe000798614)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffe0007c430e)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffe0007cc320)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2376)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed540)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffe0007f5156)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffe0007ff9ce)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffe000805bc4)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (ffffffe000808ef0)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c282)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffe00081ec84)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffe00085a916)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffe00086c81e)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008741b8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffe0008835e4)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff818fc3c6)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff81917fde)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff8194aab8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81954074)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195ac01)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978e64)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff81981e98)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff8198dcd0)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81994e9f)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81997f6a)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8199bf37)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff819b07dc)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff819f098b)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81a05cf4)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0dab9)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81a1e4d6)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff818b61f6)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff818d1d8e)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819045a8)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8190db64)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819146f1)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81932924)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff8193b958)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81947790)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8194e95f)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81951a2a)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819559f7)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff8196ce0c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff819ad74b)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff819c2ab4)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca879)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff819db296)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff8194d3f6)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff8196916e)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819b5288)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819be844)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c53d1)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e3634)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff819ec668)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff819f8570)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819ff73f)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0280a)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81a067d7)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81a1b07c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81a5b40b)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81a70774)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78539)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81a88f56)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/core/filter.c (ffffffff8196edb6)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/lwt_bpf.c (ffffffff8198b54e)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819be9cb)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819c8181)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ceea6)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ed754)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/datagram.c (ffffffff819f6552)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/icmp.c (ffffffff81a02890)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81a09849)
Location: include/net/sock.h:1846
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0cd3a)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10e57)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/ipmr.c (ffffffff81a25f5c)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv6/route.c (ffffffff81a6771b)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/icmp.c (ffffffff81a7cd94)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84ca9)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81a95bb6)
Location: include/net/sock.h:1846
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
</details>
</li>
</ul>

## Differences
