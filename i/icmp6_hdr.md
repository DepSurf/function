# Function: <code>icmp6_hdr</code>

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
In net/ipv4/ping.c (ffffffff817a2ed1)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:7
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d7c55)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff817de9a0)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff817e764e)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817ece5c)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/datagram.c (ffffffff817f4a6d)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff818119d1)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81835262)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff818464b5)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff8184c8d3)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81856f8c)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff8185bd5b)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81863b1e)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81842ee1)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81866da0)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff81878222)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff8187e78f)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81888d8c)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff8188dc5b)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff818961ce)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81864751)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:7
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189d422)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff818a47d1)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff818af410)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff818b430c)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff818bc77e)
Location: include/linux/icmpv6.h:7
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff818e4891)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191f732)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81927181)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81932120)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81937075)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff8193f870)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff8193b147)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81977931)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff8197f5ad)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff8198ac70)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff8198fdaf)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81998684)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff8196ae37)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ad529)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff819b5bad)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff819c1534)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff819c6649)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff819ceff4)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff819d1b07)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a1a688)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81a2468d)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81a30323)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a3545c)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81a3dd19)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81a08667)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a512f8)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81a5b10d)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81a66e73)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a6bf9c)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81a74989)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81af8427)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81b30c0c)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff81b48a05)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81b53d00)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81b5f73b)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81b64f0c)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81b6ebdb)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81b05287)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f834)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff81b57615)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81b622f0)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81b6dedb)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81b736ac)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81b7d69b)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81af0b03)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d6d8)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff81b451fd)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81b5063a)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81b5c25a)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81b5ee0e)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/datagram.c (ffffffff81b6c27d)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81bb0db3)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81bf38b7)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff81c0c33d)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81c179b1)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81c239c1)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81c265b3)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/datagram.c (ffffffff81c34125)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81d442ca)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c48e)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff81da7211)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81db37f9)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81dc08da)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81dc420b)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/datagram.c (ffffffff81dd1a0d)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81f0cf8a)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a44e)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff81f76821)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81f83199)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81f91057)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81f9436b)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/datagram.c (ffffffff81fa25bd)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81f6cbfa)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff81fba105)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff81fd6851)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81fe3499)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81ff1947)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81ff4ceb)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/datagram.c (ffffffff82002e4d)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff8203334a)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (ffffffff82087567)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff820a41d1)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff820b13b9)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff820bf546)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff820c28bb)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/datagram.c (ffffffff820d1575)
Location: include/linux/icmpv6.h:9
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffff800010cc193c)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffff800010d15250)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffff800010d2094c)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffff800010d2cdcc)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffff800010d33a04)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffff800010d3d3a4)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (c0dcbeac)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (c0e1aee0)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (c0e24fbc)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (c0e30bf4)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (c0e366a0)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (c0e405fc)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (c000000000ddcd90)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (c000000000e421c4)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (c000000000e4ed60)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (c000000000e5e8d8)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (c000000000e66108)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (c000000000e71624)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffe000816588)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffe00085a912)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffe000862980)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffe00086d006)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffe000871c42)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffe000879b7c)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff819a8407)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff819f0988)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff819fa79d)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81a06503)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a0b62c)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81a14019)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81961ec7)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ad748)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff819b755d)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff819c32c3)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff819c83ec)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff819d0dd9)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81a12ca7)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a5b408)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81a6521d)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81a70f83)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a760ac)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81a7ea99)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
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
In net/ipv4/ping.c (ffffffff81a1d677)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/icmpv6.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a67718)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81a7178e)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/icmp.c (ffffffff81a7d593)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a827dc)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/datagram.c (ffffffff81a8b359)
Location: include/linux/icmpv6.h:8
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
```
</details>
</li>
</ul>

## Differences
