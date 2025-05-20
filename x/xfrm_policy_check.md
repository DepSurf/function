# Function: <code>xfrm_policy_check</code>

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
In net/ipv4/ip_input.c (ffffffff81758afe)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff8175a799)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e5e0)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81785a56)
Location: include/net/xfrm.h:1081
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81789686)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8178f0ad)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff817c690e)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff817c8653)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff817e4016)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff817e6bb6)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e85cd)
Location: include/net/xfrm.h:1081
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f1cb2)
Location: include/net/xfrm.h:1081
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
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817c4eb0)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff817c6b57)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eba1d)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff817f3066)
Location: include/net/xfrm.h:1077
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f7ccf)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff817fc70d)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81833a0f)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8183587c)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff81852bd9)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81854f56)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856d6d)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860538)
Location: include/net/xfrm.h:1077
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817f49d0)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff817f6657)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c393)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81823e46)
Location: include/net/xfrm.h:1077
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81828b9f)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff8182d66d)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81865489)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff818673ac)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818848d9)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81886cc6)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888b6d)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818924cc)
Location: include/net/xfrm.h:1077
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81814dea)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff81816a69)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cb4d)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81844b36)
Location: include/net/xfrm.h:1136
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81849e3c)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff8184eb0c)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81889c73)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8188bc00)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818ab019)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818ad1e6)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af1fd)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8b1d)
Location: include/net/xfrm.h:1136
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81893fb0)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff81895c29)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc246)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff818c4576)
Location: include/net/xfrm.h:1142
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c9a40)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff818ce88c)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8190ae63)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8190ceeb)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8192db96)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff8192fdf6)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81931f0d)
Location: include/net/xfrm.h:1142
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b9e2)
Location: include/net/xfrm.h:1142
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff818e8230)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff818e9ee9)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911bd5)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8191a225)
Location: include/net/xfrm.h:1174
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191f987)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff81924c9c)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81962365)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819642d6)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff81986510)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81988aa5)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198a9ed)
Location: include/net/xfrm.h:1174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994bf6)
Location: include/net/xfrm.h:1174
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81915753)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81917316)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819403a6)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81948a85)
Location: include/net/xfrm.h:1179
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194e60a)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81953aac)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81997338)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81999baa)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bcde9)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bf405)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c12ad)
Location: include/net/xfrm.h:1179
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb4e4)
Location: include/net/xfrm.h:1179
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
In net/ipv4/ip_input.c (ffffffff81977ca0)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81979246)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a48e1)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ad135)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2d95)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819b838b)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81a03313)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a05ae5)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a2b8d2)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a2e055)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a3007c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39f52)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (ffffffff819ae630)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819afbb6)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db5e1)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819e3e05)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e9b38)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819ef08b)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81a39ee3)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c659)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a62435)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a64bc5)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66bcc)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70ae2)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (ffffffff81a984d0)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81a99a86)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac86a7)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ad14d5)
Location: include/net/xfrm.h:1103
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad78a5)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81adcfdb)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f718)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b31cf9)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b5afe4)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5d505)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f5fc)
Location: include/net/xfrm.h:1103
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a2d7)
Location: include/net/xfrm.h:1103
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa2420)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81aa39d6)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4647)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81add563)
Location: include/net/xfrm.h:1106
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae3ef5)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81ae9d2b)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e16b)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b408f9)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b697d4)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b6bd03)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6dd9c)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78da4)
Location: include/net/xfrm.h:1106
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a8d120)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ea97)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf780)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ac8625)
Location: include/net/xfrm.h:1106
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acf0e2)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81ad546b)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ccdd)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e191)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b57ab0)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5a015)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c12c)
Location: include/net/xfrm.h:1106
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b678c8)
Location: include/net/xfrm.h:1106
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81b482b2)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49c9b)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d2e0)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81b86e85)
Location: include/net/xfrm.h:1123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8da79)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81b9427b)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2e52)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf447e)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81c1f0b5)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81c21685)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23882)
Location: include/net/xfrm.h:1123
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f5aa)
Location: include/net/xfrm.h:1123
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81cd5559)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7207)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d599)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81d17b05)
Location: include/net/xfrm.h:1127
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ebc1)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81d25b5c)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b99b)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d1a4)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81dbb926)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe535)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc07b2)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc92e)
Location: include/net/xfrm.h:1127
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81e95a49)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81e977d7)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2fd2)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ede3e2)
Location: include/net/xfrm.h:1177
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee5d8a)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81eed41e)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81f59634)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b29b)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81f8ba65)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81f8eab2)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f90f54)
Location: include/net/xfrm.h:1177
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9da75)
Location: include/net/xfrm.h:1177
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81ef4289)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6007)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31cd3)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81f3d715)
Location: include/net/xfrm.h:1183
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f4550d)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81f4cdde)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb92e5)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb037)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81fec169)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81fef2b5)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff1844)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe4f6)
Location: include/net/xfrm.h:1183
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81fb8209)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81fb9f97)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7d1e)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff82003825)
Location: include/net/xfrm.h:1183
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8200b51c)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff82012eee)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff82086865)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff82088447)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff820b9d66)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bce95)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf443)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd5f2)
Location: include/net/xfrm.h:1183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ip_input.c (ffff800010c5eb1c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffff800010c60278)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e994)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffff800010c987bc)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f420)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffff800010ca4e88)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffff800010cfae84)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfd988)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffff800010d2747c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d2aafc)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cb24)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38f8c)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (c0d6e180)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (c0d6fb2c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (c0d9d918)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c0da6610)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (c0dac664)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (c0db1788)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (c0e01788)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e0514c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c0e2c3b8)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c0e2ea48)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e309d8)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3bb68)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (c000000000d61560)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (c000000000d6317c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d3b4)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c000000000da9f04)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1d50)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (c000000000db8b8c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (c000000000e22320)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e25a40)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c000000000e583f8)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e5bd54)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e5f0)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c454)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (ffffffe0007c7106)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8526)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eec80)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffe0007f6972)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fbefe)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffe000800808)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffe000845a1a)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe000847e3a)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffe000869142)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffe00086b168)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cda4)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087633a)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (ffffffff8194e4a0)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff8194fa26)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b451)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81983c75)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819899a8)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff8198ee2b)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff819d9573)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819dbce9)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a01ac5)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a04255)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a0625c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10172)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (ffffffff81907f90)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81909516)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934f11)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8193d735)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81943468)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819488eb)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81996333)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81998aa9)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819be885)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819c1015)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c301c)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccf32)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (ffffffff819b8c70)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819ba1f6)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5c21)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ee445)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f4178)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819f96cb)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81a43ff3)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a46769)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6c545)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a6ecd5)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70cdc)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7abf2)
Location: include/net/xfrm.h:1104
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
In net/ipv4/ip_input.c (ffffffff819c24f0)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819c3ae6)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef8e1)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819f84a5)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fe338)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81a039bb)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fc94)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a52499)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a78b7d)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a7b305)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d2ec)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87432)
Location: include/net/xfrm.h:1104
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
