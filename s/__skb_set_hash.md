# Function: <code>__skb_set_hash</code>

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
In net/core/flow_dissector.c (ffffffff817119bf)
Location: include/linux/skbuff.h:964
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81774bcb)
Location: include/linux/skbuff.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff817c509d)
Location: include/linux/skbuff.h:964
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:__ip6_make_skb
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
In net/core/flow_dissector.c (ffffffff817793cc)
Location: include/linux/skbuff.h:1061
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/tcp_output.c (ffffffff817e1b4c)
Location: include/linux/skbuff.h:1061
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff8183533b)
Location: include/linux/skbuff.h:1061
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff817a6534)
Location: include/linux/skbuff.h:1076
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv4/tcp_output.c (ffffffff8181204c)
Location: include/linux/skbuff.h:1076
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81866e62)
Location: include/linux/skbuff.h:1076
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff817c4724)
Location: include/linux/skbuff.h:1069
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff817e7b76)
Location: include/linux/skbuff.h:1069
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff818323a2)
Location: include/linux/skbuff.h:1069
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff8188b60c)
Location: include/linux/skbuff.h:1069
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff8183f94e)
Location: include/linux/skbuff.h:1143
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81862ab6)
Location: include/linux/skbuff.h:1143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff818b14de)
Location: include/linux/skbuff.h:1143
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff8190c885)
Location: include/linux/skbuff.h:1143
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff8188a205)
Location: include/linux/skbuff.h:1148
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff818ae7f5)
Location: include/linux/skbuff.h:1148
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81906d1a)
Location: include/linux/skbuff.h:1148
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81963cca)
Location: include/linux/skbuff.h:1148
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff818ab11d)
Location: include/linux/skbuff.h:1168
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff818d2a95)
Location: include/linux/skbuff.h:1168
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81934ece)
Location: include/linux/skbuff.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81998c65)
Location: include/linux/skbuff.h:1168
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff818f6a6b)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff8191fd95)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81998e86)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81a04abe)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37bee)
Location: include/linux/skbuff.h:1220
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff81928936)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81951fd5)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff819cf9a6)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b6af)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e726)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff819fc9d7)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81a231d5)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81abc2f2)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81b30c7b)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b68324)
Location: include/linux/skbuff.h:1248
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff819fc621)
Location: include/linux/skbuff.h:1265
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81a23595)
Location: include/linux/skbuff.h:1265
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7b65)
Location: include/linux/skbuff.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f8a8)
Location: include/linux/skbuff.h:1265
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76b60)
Location: include/linux/skbuff.h:1265
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff819e2ea1)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81a0a8c5)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2bc5)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d759)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65598)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff81a93483)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81abcd45)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81b6fab9)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3977)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d7f4)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff81c09623)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81c37855)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81cff145)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c54f)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcabed)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff81db93a3)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81deb0f5)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff81ec41a5)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a50f)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b89c)
Location: include/linux/skbuff.h:1437
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In drivers/net/virtio_net.c (ffffffff81c56121)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_buf
```
```
In net/core/flow_dissector.c (ffffffff81e299f3)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81e5c8f5)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/ip_output.c (ffffffff81efca20)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_output.c (ffffffff81f224aa)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81fba215)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbc5d)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In drivers/net/virtio_net.c (ffffffff81d0c748)
Location: include/linux/skbuff.h:1463
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_buf
```
```
In net/core/flow_dissector.c (ffffffff81ee7a63)
Location: include/linux/skbuff.h:1463
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81f1bce5)
Location: include/linux/skbuff.h:1463
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/ip_output.c (ffffffff81fc0958)
Location: include/linux/skbuff.h:1463
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp_output.c (ffffffff81fe70b6)
Location: include/linux/skbuff.h:1463
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff82087665)
Location: include/linux/skbuff.h:1463
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca36d)
Location: include/linux/skbuff.h:1463
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffff800010bc4bec)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffff800010bf414c)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffff800010c82b98)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffff800010cfc824)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37fa8)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (c0ce01cc)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (c0d0c940)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (c0d91594)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (c0e03cb0)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (c0e38984)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (c000000000c9f324)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (c000000000cd92a8)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (c000000000d8d9ec)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (c000000000e2442c)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6962c)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffe0007516ae)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffe00077563c)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffe0007e43a4)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffe00084707a)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087439e)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff818c8936)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff818f1fa5)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff8196f816)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff819dad3f)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ddb6)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff81882876)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff818abdd5)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff819292e6)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81997aff)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cab76)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff81919936)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81942fd5)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff819d9fe6)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81a457bf)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78836)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/flow_dissector.c (ffffffff8193ab76)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff819648c5)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv4/tcp_output.c (ffffffff819e3c5b)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv6/ip6_output.c (ffffffff81a5148f)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84fc6)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
</details>
</li>
</ul>

## Differences
