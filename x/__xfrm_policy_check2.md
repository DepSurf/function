# Function: <code>__xfrm_policy_check2</code>

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
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff8175a799)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e5e0)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81785a56)
Location: include/net/xfrm.h:1066
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81789686)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8178f0ad)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff817c690e)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff817c8653)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff817e4016)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff817e6bb6)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e85cd)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f1cb2)
Location: include/net/xfrm.h:1066
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
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817c4eb0)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff817c6b57)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eba1d)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff817f3066)
Location: include/net/xfrm.h:1062
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f7ccf)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff817fc863)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81833a0f)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8183587c)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff81852bd9)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81854f56)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81857083)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860538)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff817e9cd0-ffffffff817e9d43: __xfrm_policy_check2.constprop.38 (STB_LOCAL)
ffffffff8185eba0-ffffffff8185ec13: __xfrm_policy_check2.constprop.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817f49d0)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff817f6657)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c393)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81823e46)
Location: include/net/xfrm.h:1062
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81828b9f)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff8182d7c6)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81865489)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff818673ac)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818848d9)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81886cc6)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888e83)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818924cc)
Location: include/net/xfrm.h:1062
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8181a460-ffffffff8181a4d3: __xfrm_policy_check2.constprop.43 (STB_LOCAL)
ffffffff81890c60-ffffffff81890cd3: __xfrm_policy_check2.constprop.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81814dea)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff81816a69)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cb4d)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81844b36)
Location: include/net/xfrm.h:1121
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81849e3c)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff8184ed1e)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81889c73)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8188bc00)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818ab019)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff818ad1e6)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af569)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8b1d)
Location: include/net/xfrm.h:1121
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8183abd0-ffffffff8183ac43: __xfrm_policy_check2.constprop.39 (STB_LOCAL)
ffffffff818b7240-ffffffff818b72b3: __xfrm_policy_check2.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81893fb0)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff81895c29)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc246)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff818c4576)
Location: include/net/xfrm.h:1127
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c9a40)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff818ceaa4)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff8190ae63)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8190ceeb)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8192db96)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff8192fdf6)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8193227f)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b9e2)
Location: include/net/xfrm.h:1127
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff818ba800-ffffffff818ba873: __xfrm_policy_check2.constprop.33 (STB_LOCAL)
ffffffff8193a080-ffffffff8193a0f3: __xfrm_policy_check2.constprop.23 (STB_LOCAL)
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
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_forward.c (ffffffff818e9ee9)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911bd5)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8191a225)
Location: include/net/xfrm.h:1159
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191f987)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/icmp.c (ffffffff81924e7a)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81962365)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819642d6)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff81986510)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81988aa5)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198abcd)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994bf6)
Location: include/net/xfrm.h:1159
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
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81917316)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819403a6)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81948a85)
Location: include/net/xfrm.h:1164
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194e60a)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81953c8c)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81997338)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81999baa)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bcde9)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819bf405)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c149b)
Location: include/net/xfrm.h:1164
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb4e4)
Location: include/net/xfrm.h:1164
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81979246)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a48e1)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ad135)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2d95)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819b8589)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81a03313)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a05ae5)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a2b8d2)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a2e055)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a30279)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39f52)
Location: include/net/xfrm.h:1089
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819afbb6)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db5e1)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819e3e05)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e9b38)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819ef289)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81a39ee3)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c659)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a62435)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a64bc5)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66dc9)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70ae2)
Location: include/net/xfrm.h:1089
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
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a984d0)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81a99a86)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac86a7)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ad14d5)
Location: include/net/xfrm.h:1088
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad78a5)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81add1db)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f718)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b31cf9)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b5afe4)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5d505)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f856)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a2d7)
Location: include/net/xfrm.h:1088
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ac4f10-ffffffff81ac4f7f: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81b672b0-ffffffff81b6731f: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa2420)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81aa39d6)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4647)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81add563)
Location: include/net/xfrm.h:1091
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae3ef5)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81ae9f2b)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e16b)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b408f9)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b697d4)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b6bd03)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6dff6)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78da4)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ad08a0-ffffffff81ad090f: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81b75830-ffffffff81b7589f: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a8d120)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ea97)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf780)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ac8625)
Location: include/net/xfrm.h:1091
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acf0e2)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81ad567e)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ccdd)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e191)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b57ab0)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b5a015)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c3bf)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b678c8)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81abb970-ffffffff81abb9e1: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81b64250-ffffffff81b642c1: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81b482b2)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49c9b)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d2e0)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81b86e85)
Location: include/net/xfrm.h:1104
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8da79)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81b944b0)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2e52)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf447e)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81c1f0b5)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81c21685)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23af4)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f5aa)
Location: include/net/xfrm.h:1104
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81b78f20-ffffffff81b78faf: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81c2be60-ffffffff81c2beef: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81cd5559)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7207)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d599)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81d17b05)
Location: include/net/xfrm.h:1112
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ebc1)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81d25d34)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b99b)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d1a4)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81dbb926)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe535)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0a17)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc92e)
Location: include/net/xfrm.h:1112
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81d08430-ffffffff81d084d5: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81dc91b0-ffffffff81dc9266: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81e95400)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81e977d7)
Location: include/net/xfrm.h:1153
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecddc0)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81edcb10)
Location: include/net/xfrm.h:1153
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee0640)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81eeb7e0)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81f55240)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5a960)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81f87a90)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81f8cac0)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f8f7d0)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a610)
Location: include/net/xfrm.h:1153
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81e95400-ffffffff81e95504: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81ecddc0-ffffffff81ecdf48: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81edcb10-ffffffff81edcc98: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81ee0640-ffffffff81ee07c8: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81eeb7e0-ffffffff81eeb8f5: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f55240-ffffffff81f55357: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f5a960-ffffffff81f5aa74: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f87a90-ffffffff81f87c2e: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f8cac0-ffffffff81f8cc5e: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f8f7d0-ffffffff81f8f8f5: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f9a610-ffffffff81f9a7ae: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81ef3bd0)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6007)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2cbe0)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81f3bd30)
Location: include/net/xfrm.h:1159
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f8f0)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81f4b110)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4c90)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fba6c0)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81fe7f20)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81fed270)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff0000)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb020)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ef3bd0-ffffffff81ef3d0a: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f2cbe0-ffffffff81f2cd91: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f3bd30-ffffffff81f3bee1: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f3f8f0-ffffffff81f3faa1: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81f4b110-ffffffff81f4b259: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81fb4c90-ffffffff81fb4ddd: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81fba6c0-ffffffff81fba80a: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81fe7f20-ffffffff81fe80df: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81fed270-ffffffff81fed42f: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81ff0000-ffffffff81ff015b: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81ffb020-ffffffff81ffb1df: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81fb7b60)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81fb9f97)
Location: include/net/xfrm.h:1159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2430)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff82001e50)
Location: include/net/xfrm.h:1159
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82005740)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff82011220)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff82082330)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff82087af0)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff820b6160)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bae70)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bdbd0)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8a30)
Location: include/net/xfrm.h:1159
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81fb7b60-ffffffff81fb7c9a: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff81ff2430-ffffffff81ff25e1: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff82001e50-ffffffff82002001: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff82005740-ffffffff820058f1: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff82011220-ffffffff82011369: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff82082330-ffffffff8208247d: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff82087af0-ffffffff82087c3a: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff820b6160-ffffffff820b631f: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff820bae70-ffffffff820bb02f: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff820bdbd0-ffffffff820bdd2b: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
ffffffff820c8a30-ffffffff820c8bef: __xfrm_policy_check2.constprop.0 (STB_LOCAL)
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffff800010c60278)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e994)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffff800010c987bc)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f420)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffff800010ca50c0)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffff800010cfae84)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfd988)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffff800010d2747c)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d2aafc)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cd2c)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38f8c)
Location: include/net/xfrm.h:1089
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (c0d6fb2c)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (c0d9d918)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c0da6610)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (c0dac664)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (c0db19cc)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (c0e01788)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e0514c)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c0e2c3b8)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c0e2ea48)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30d88)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3bb68)
Location: include/net/xfrm.h:1089
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (c000000000d6317c)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d3b4)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c000000000da9f04)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1d50)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (c000000000db8e14)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (c000000000e22320)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e25a40)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c000000000e583f8)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (c000000000e5bd54)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e818)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c454)
Location: include/net/xfrm.h:1089
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8526)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eec80)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffe0007f6972)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fbefe)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffe0008009de)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffe000845a1a)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe000847e3a)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffe000869142)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffe00086b168)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cf6c)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087633a)
Location: include/net/xfrm.h:1089
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff8194fa26)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b451)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81983c75)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819899a8)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff8198f029)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff819d9573)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819dbce9)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a01ac5)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a04255)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a06459)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10172)
Location: include/net/xfrm.h:1089
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81909516)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934f11)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8193d735)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81943468)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81948ae9)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81996333)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81998aa9)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819be885)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff819c1015)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c3219)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccf32)
Location: include/net/xfrm.h:1089
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819ba1f6)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5c21)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ee445)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f4178)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff819f98c9)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81a43ff3)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a46769)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6c545)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a6ecd5)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70ed9)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7abf2)
Location: include/net/xfrm.h:1089
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
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff819c3ae6)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef8e1)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819f84a5)
Location: include/net/xfrm.h:1089
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fe338)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81a03bb9)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fc94)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a52499)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a78b7d)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81a7b305)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d4e9)
Location: include/net/xfrm.h:1089
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87432)
Location: include/net/xfrm.h:1089
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
