# Function: <code>skb_flow_dissect_flow_keys</code>

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
In drivers/net/tun.c (ffffffff815eec18)
Location: include/linux/skbuff.h:1015
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff817126fb)
Location: include/linux/skbuff.h:1015
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:skb_get_poff
```
```
In net/packet/af_packet.c (ffffffff8181734c)
Location: include/linux/skbuff.h:1015
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8164d808)
Location: include/linux/skbuff.h:1113
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff8177a946)
Location: include/linux/skbuff.h:1113
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/packet/af_packet.c (ffffffff81879f3d)
Location: include/linux/skbuff.h:1113
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8167f50c)
Location: include/linux/skbuff.h:1128
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff817a7f36)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/packet/af_packet.c (ffffffff818ae70f)
Location: include/linux/skbuff.h:1128
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff81694747)
Location: include/linux/skbuff.h:1121
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff817c6556)
Location: include/linux/skbuff.h:1121
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff8180fc9e)
Location: include/linux/skbuff.h:1121
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/packet/af_packet.c (ffffffff818d5047)
Location: include/linux/skbuff.h:1121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff816fe7b7)
Location: include/linux/skbuff.h:1195
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81840156)
Location: include/linux/skbuff.h:1195
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff8188f1ce)
Location: include/linux/skbuff.h:1195
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/packet/af_packet.c (ffffffff81959ad0)
Location: include/linux/skbuff.h:1195
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/core/flow_dissector.c (ffffffff8188a37a)
Location: include/linux/skbuff.h:1200
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff818e4bfc)
Location: include/linux/skbuff.h:1200
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81931482)
Location: include/linux/skbuff.h:1200
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff8197750b)
Location: include/linux/skbuff.h:1200
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff818ab292)
Location: include/linux/skbuff.h:1238
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81911b21)
Location: include/linux/skbuff.h:1238
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81960da6)
Location: include/linux/skbuff.h:1238
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff819ad135)
Location: include/linux/skbuff.h:1238
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff818f6bf3)
Location: include/linux/skbuff.h:1303
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff8197427c)
Location: include/linux/skbuff.h:1303
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff819c57ee)
Location: include/linux/skbuff.h:1303
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff81a1a2a0)
Location: include/linux/skbuff.h:1303
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81928a53)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff819aac9c)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc38e)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff81a50f10)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff819fcab2)
Location: include/linux/skbuff.h:1305
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81a94fe8)
Location: include/linux/skbuff.h:1305
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81aea58e)
Location: include/linux/skbuff.h:1305
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff81b48590)
Location: include/linux/skbuff.h:1305
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff819fc6f2)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81a9efe8)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7404)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff81b57170)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff819e2f72)
Location: include/linux/skbuff.h:1329
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81a89f5c)
Location: include/linux/skbuff.h:1329
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae2b4a)
Location: include/linux/skbuff.h:1329
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81b03cd9)
Location: include/linux/skbuff.h:1329
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81b44d6d)
Location: include/linux/skbuff.h:1329
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/netfilter.c (ffffffff81b7773d)
Location: include/linux/skbuff.h:1329
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
In net/core/flow_dissector.c (ffffffff81a93627)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81b44dec)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba23e8)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81bc5f89)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81c0be7d)
Location: include/linux/skbuff.h:1342
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/netfilter.c (ffffffff81c4220e)
Location: include/linux/skbuff.h:1342
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
In net/core/flow_dissector.c (ffffffff81c09827)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81cd1ada)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34a10)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81d5b2b8)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81da6d1b)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/netfilter.c (ffffffff81de0c14)
Location: include/linux/skbuff.h:1649
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
In net/core/flow_dissector.c (ffffffff81db9597)
Location: include/linux/skbuff.h:1493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81e92019)
Location: include/linux/skbuff.h:1493
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81efcf0e)
Location: include/linux/skbuff.h:1493
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81f25748)
Location: include/linux/skbuff.h:1493
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81f762eb)
Location: include/linux/skbuff.h:1493
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/netfilter.c (ffffffff81fb3054)
Location: include/linux/skbuff.h:1493
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
In net/core/flow_dissector.c (ffffffff81e29c17)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81ef07a0)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c94e)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81f852d8)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81fd6381)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/netfilter.c (ffffffff82013744)
Location: include/linux/skbuff.h:1512
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
In net/core/flow_dissector.c (ffffffff81ee7c87)
Location: include/linux/skbuff.h:1519
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff81fb4602)
Location: include/linux/skbuff.h:1519
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff820a2aaf)
Location: include/linux/skbuff.h:1519
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffff800010bc4d0c)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffff800010c5af88)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffff800010cb46dc)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffff800010d14e9c)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (c0ce0330)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (c0d6a4a4)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (c0dbfafc)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (c0e1ab08)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (c000000000c9f51c)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (c000000000d5cd20)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (c000000000dcb724)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (c000000000e41d20)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffe0007517ba)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffe0007c4348)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c39e)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffe00085a5ee)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff818c8a53)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff8194ab0c)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff8199c12e)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff819f05a0)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81882993)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff819045fc)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81955bee)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff819ad360)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81919a53)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff819b52dc)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81a069ce)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff81a5b020)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff8193ac93)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/route.c (ffffffff819be9ed)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11069)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv6/route.c (ffffffff81a67300)
Location: include/linux/skbuff.h:1299
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
</details>
</li>
</ul>

## Differences
