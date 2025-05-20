# Function: <code>ipv6_addr_set_v4mapped</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177b196)
Location: include/net/ipv6.h:617
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/syncookies.c (ffffffff817ab593)
Location: include/net/ipv6.h:617
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff817e31ab)
Location: include/net/ipv6.h:617
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff817f4327)
Location: include/net/ipv6.h:617
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/tcp_ipv4.c (ffffffff817eab2a)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81819088)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff818517aa)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff818565df)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/datagram.c (ffffffff818640d9)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_connect
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
In net/ipv4/tcp_ipv4.c (ffffffff8181b47a)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8184a8fc)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81882329)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff818883cf)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81890e8e)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81896789)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/tcp_ipv4.c (ffffffff8183bcfe)
Location: include/net/ipv6.h:650
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8186e2ce)
Location: include/net/ipv6.h:650
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff818a9489)
Location: include/net/ipv6.h:650
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff818aeaad)
Location: include/net/ipv6.h:650
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7396)
Location: include/net/ipv6.h:650
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818bcd01)
Location: include/net/ipv6.h:650
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff81871352)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_set_state
  - net/core/net-traces.c:perf_trace_tcp_set_state
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_set_state
  - net/core/net-traces.c:trace_event_raw_event_tcp_set_state
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b976f)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff818eec5e)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff8192bf42)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff8193176d)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a1d6)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8193fe21)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff818c29e8)
Location: include/net/ipv6.h:679
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910030)
Location: include/net/ipv6.h:679
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81945582)
Location: include/net/ipv6.h:679
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81984195)
Location: include/net/ipv6.h:679
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff8198a29b)
Location: include/net/ipv6.h:679
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993033)
Location: include/net/ipv6.h:679
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81998c68)
Location: include/net/ipv6.h:679
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff818eb978)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e4b0)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81975934)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff819ba240)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff819c0b43)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c93ba)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819cf5b8)
Location: include/net/ipv6.h:671
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff8193e773)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a28e8)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff819df485)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81a297ea)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a2f836)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37f08)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a3e318)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff81971603)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d94d8)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a164ec)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81a60346)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a66386)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6ea48)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a74f88)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff81a45103)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac63a4)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b074fc)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81b58e5b)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81b5ed7f)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67662)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6f1d4)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff81a49264)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad36a7)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b158fc)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81b67498)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81b6d4ff)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75e62)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b7dd04)
Location: include/net/ipv6.h:734
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff81a2e1b4)
Location: include/net/ipv6.h:735
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe737)
Location: include/net/ipv6.h:735
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b0370e)
Location: include/net/ipv6.h:735
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81b55672)
Location: include/net/ipv6.h:735
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81b5b897)
Location: include/net/ipv6.h:735
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64896)
Location: include/net/ipv6.h:735
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6c8f8)
Location: include/net/ipv6.h:735
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/mptcp/subflow.c (ffffffff81bb3b65)
Location: include/net/ipv6.h:735
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
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
In net/core/net-traces.c (ffffffff81ae3794)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c267)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81bc599e)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81c1e14b)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81c22fa7)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2ca96)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81c347ed)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/mptcp/subflow.c (ffffffff81c822b5)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
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
In net/core/net-traces.c (ffffffff81c68312)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_cong_state_set
  - net/core/net-traces.c:trace_event_raw_event_tcp_cong_state_set
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c194)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81d5ac28)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81dba6eb)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81dbfe17)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc9e3a)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81dd2140)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/mptcp/subflow.c (ffffffff81e27fd9)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
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
In net/core/net-traces.c (ffffffff81e1f5de)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_cong_state_set
  - net/core/net-traces.c:trace_event_raw_event_tcp_cong_state_set
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea4da9)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1bd4)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81f25098)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81f8a7b3)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81f90577)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9ae35)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81fa35b0)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/mptcp/subflow.c (ffffffff81ffff29)
Location: include/net/ipv6.h:825
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
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
In net/core/net-traces.c (ffffffff81e91cdc)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_br_mdb_full
  - net/core/net-traces.c:perf_trace_br_mdb_full
  - net/core/net-traces.c:trace_event_raw_event_br_mdb_full
  - net/core/net-traces.c:trace_event_raw_event_br_mdb_full
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_cong_state_set
  - net/core/net-traces.c:trace_event_raw_event_tcp_cong_state_set
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03630)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f308a4)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81f84c28)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81fea111)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81ff0dd7)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffc235)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff82003e5a)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/mptcp/subflow.c (ffffffff8207c0c9)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
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
In net/core/net-traces.c (ffffffff81f5409b)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_br_mdb_full
  - net/core/net-traces.c:perf_trace_br_mdb_full
  - net/core/net-traces.c:trace_event_raw_event_br_mdb_full
  - net/core/net-traces.c:trace_event_raw_event_br_mdb_full
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_cong_state_set
  - net/core/net-traces.c:trace_event_raw_event_tcp_cong_state_set
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sk_error_report
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc787d)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_create
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff67b4)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8204b436)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff820b7ded)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff820be9b7)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c954a)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820d2c1a)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/mptcp/subflow.c (ffffffff82151599)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
```
```
In net/mptcp/pm_userspace.c (ffffffff821614d6)
Location: include/net/ipv6.h:822
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
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
In net/core/net-traces.c (ffff800010c1998c)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8cb04)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffff800010cd21f0)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffff800010d259c8)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffff800010d2c2f4)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37390)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3d99c)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (c0d2f3e8)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (c0d9cc10)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (c0ddc094)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (c0e28af8)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (c0e3019c)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (c0e397cc)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c0e40be8)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (c000000000d06334)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b9b4)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (c000000000df0660)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (c000000000e554e0)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (c000000000e5db90)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69b08)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c000000000e71e1c)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffe000791eae)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebefc)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffe00082358a)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffe000866436)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffe00086c5ae)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874746)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffe00087a08e)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff819115d3)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81979348)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff819b5b7c)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff819ff9d6)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a05a16)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e0d8)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a14618)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff818cb393)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81932e08)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8197296c)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff819bc796)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff819c27d6)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cae98)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819d13d8)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff81962603)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e3b18)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a2041c)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81a6a456)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a70496)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78b58)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7f098)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/net-traces.c (ffffffff81984873)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_retransmit_synack
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
  - net/core/net-traces.c:trace_event_raw_event_inet_sock_set_state
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819edc38)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a2b91c)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/udp.c (ffffffff81a76a73)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a7cab6)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a852e6)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a8b958)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
</details>
</li>
</ul>

## Differences
