# Function: <code>secpath_exists</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: include/net/xfrm.h:987
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: include/net/xfrm.h:983
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: include/net/xfrm.h:983
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: include/net/xfrm.h:1041
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: include/net/xfrm.h:1047
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: include/net/xfrm.h:1079
Inline: True
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
In net/core/netpoll.c (ffffffff818e82ac)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81915769)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff8191732f)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819403bb)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81948ab6)
Location: include/linux/skbuff.h:4062
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194e61f)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81953ca1)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81961625)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff8199734f)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81999bbf)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bcdfe)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bf43e)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c14b0)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb4f9)
Location: include/linux/skbuff.h:4062
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff81937ae6)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81977cb5)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81979260)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a48f7)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ad16c)
Location: include/linux/skbuff.h:4169
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2dab)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819b85a3)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5dc5)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81a03328)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a05afa)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a2b8e8)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a2e094)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a3028f)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39f67)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff8196a9a6)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff819ae645)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819afbd0)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db5f7)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819e3e3c)
Location: include/linux/skbuff.h:4253
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e9b4e)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819ef2a3)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc975)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81a39ef8)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c66e)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6244b)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a64c04)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66ddf)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70af7)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff81a3e5a9)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81a984e5)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81a99aa0)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac86bd)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ad1510)
Location: include/linux/skbuff.h:4293
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad78bb)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81add1f5)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb6e5)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f72d)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b31d0e)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b5affa)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5d546)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f86c)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a2ed)
Location: include/linux/skbuff.h:4293
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff81a41349)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81aa2435)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81aa39f0)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad465d)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81add590)
Location: include/linux/skbuff.h:4322
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae3f0b)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81ae9f45)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81af85f5)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e180)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b4090e)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b697ea)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b6bd36)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6e00c)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78dba)
Location: include/linux/skbuff.h:4322
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff81a25fa7)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81a8d135)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81a8eaad)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf796)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ac865f)
Location: include/linux/skbuff.h:4386
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acf0fc)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81ad568f)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3d15)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ccee)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e1a6)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b57aca)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5a055)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c3d5)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b678de)
Location: include/linux/skbuff.h:4386
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff81adad17)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81b482d0)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49cbc)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d2ff)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81b86ec8)
Location: include/linux/skbuff.h:4425
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8daa0)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81b94639)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba3635)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81bf322f)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf449c)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81c1f0dc)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81c216d0)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23dd6)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f5c9)
Location: include/linux/skbuff.h:4425
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff81c5b4ff)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81cd556f)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd721c)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d5bf)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81d17b3a)
Location: include/linux/skbuff.h:4847
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ebd6)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81d25d49)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35ea5)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81d8bbac)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d1b9)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81dbb93b)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe6f2)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0a2c)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc943)
Location: include/linux/skbuff.h:4847
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff81e117c9)
Location: include/linux/skbuff.h:4743
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe4a5)
Location: include/linux/skbuff.h:4743
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/skbuff.h:4743
Inline: True
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
In net/core/netpoll.c (ffffffff81e850d9)
Location: include/linux/skbuff.h:4775
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5df35)
Location: include/linux/skbuff.h:4775
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/skbuff.h:4775
Inline: True
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
In net/core/netpoll.c (ffffffff81f470c9)
Location: include/linux/skbuff.h:4815
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff820244f5)
Location: include/linux/skbuff.h:4815
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/skbuff.h:4815
Inline: True
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
In net/core/netpoll.c (ffff800010c10d10)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffff800010c5eb2c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffff800010c60288)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e9a4)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffff800010c987d8)
Location: include/linux/skbuff.h:4253
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f430)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffff800010ca50cc)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4dd8)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffff800010cfae90)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfd998)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffff800010d2748c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d2ab18)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cd38)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38f9c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (c0d27fe0)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (c0d6e194)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (c0d6fb40)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (c0d9d92c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c0da663c)
Location: include/linux/skbuff.h:4253
Inline: True
```
```
In net/ipv4/udp.c (c0dac678)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (c0db19dc)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (c0dc0758)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (c0e01798)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e05160)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c0e2c3cc)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c0e2ea74)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30d98)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3bb7c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (c000000000cfc60c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (c000000000d61574)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (c000000000d63190)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d3c8)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c000000000da9f30)
Location: include/linux/skbuff.h:4253
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1d64)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (c000000000db8e24)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (c000000000dcc0cc)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (c000000000e22330)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e25a54)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c000000000e5840c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e5bd80)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e828)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c468)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffe00078c6dc)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffe0007c7148)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8538)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eec9e)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffe0007f698c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fbf10)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffe000800a06)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c918)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffe000845a2a)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe000847e4c)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffe000869152)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffe00086b182)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cf94)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876352)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff8190a976)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff8194e4b5)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff8194fa40)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b467)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81983cac)
Location: include/linux/skbuff.h:4253
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819899be)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff8198f043)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff8199c715)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff819d9588)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819dbcfe)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a01adb)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a04294)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a0646f)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10187)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff818c3d9f)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff81907fa5)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81909530)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934f27)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8193d76c)
Location: include/linux/skbuff.h:4253
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194347e)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81948b03)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff819561d5)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81996348)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81998abe)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819be89b)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819c1054)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c322f)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccf47)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff8195b9a6)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff819b8c85)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819ba210)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5c37)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ee47c)
Location: include/linux/skbuff.h:4253
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f418e)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819f98e3)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06fb5)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81a44008)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a4677e)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6c55b)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a6ed14)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70eef)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7ac07)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/netpoll.c (ffffffff8197dd92)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_input.c (ffffffff819c2505)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819c3b00)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef8f7)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819f84dc)
Location: include/linux/skbuff.h:4253
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fe34e)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81a03bd3)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11685)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fca9)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a524ae)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a78b93)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a7b344)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d4ff)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87447)
Location: include/linux/skbuff.h:4253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
</details>
</li>
</ul>

## Differences
