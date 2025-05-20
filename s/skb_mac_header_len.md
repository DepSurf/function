# Function: <code>skb_mac_header_len</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eb585)
Location: include/linux/skbuff.h:2225
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/filter.c (ffffffff81867455)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/filter.c (ffffffff818b644f)
Location: include/linux/skbuff.h:2323
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818db4ec)
Location: include/linux/skbuff.h:2401
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffff818eed81)
Location: include/linux/skbuff.h:2489
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81927f8b)
Location: include/linux/skbuff.h:2489
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffff81920e23)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff8195a5bb)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffff819f4667)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81a308de)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8d4c)
Location: include/linux/skbuff.h:2526
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In net/core/skbuff.c (ffffffff81c30617)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81a32c02)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/ipv4/tcp_input.c (ffffffff81abb064)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5266)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06baa)
Location: include/linux/skbuff.h:2547
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/core/skbuff.c (ffffffff81c228f5)
Location: include/linux/skbuff.h:2563
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81a1a566)
Location: include/linux/skbuff.h:2563
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6024)
Location: include/linux/skbuff.h:2563
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp_offload.c (ffffffff81ad04b8)
Location: include/linux/skbuff.h:2563
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af22c7)
Location: include/linux/skbuff.h:2563
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/core/skbuff.c (ffffffff81d34d7d)
Location: include/linux/skbuff.h:2592
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81acc846)
Location: include/linux/skbuff.h:2592
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_input.c (ffffffff81b62404)
Location: include/linux/skbuff.h:2592
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp_offload.c (ffffffff81b8eed6)
Location: include/linux/skbuff.h:2592
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb27d7)
Location: include/linux/skbuff.h:2592
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/core/skbuff.c (ffffffff81f0135a)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81c496f9)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_input.c (ffffffff81cf16b9)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fb48)
Location: include/linux/skbuff.h:2961
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In net/core/skbuff.c (ffffffff81da328f)
Location: include/linux/skbuff.h:2859
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81dfe70d)
Location: include/linux/skbuff.h:2859
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5eb9)
Location: include/linux/skbuff.h:2859
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6d38)
Location: include/linux/skbuff.h:2859
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In net/core/skbuff.c (ffffffff81e11e63)
Location: include/linux/skbuff.h:2913
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81e7052d)
Location: include/linux/skbuff.h:2913
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_input.c (ffffffff81f142d9)
Location: include/linux/skbuff.h:2913
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp_offload.c (ffffffff81f465cd)
Location: include/linux/skbuff.h:2913
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In net/core/skbuff.c (ffffffff81ecf023)
Location: include/linux/skbuff.h:2920
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81f2fbbd)
Location: include/linux/skbuff.h:2920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/ipv4/tcp_input.c (ffffffff81fd87b9)
Location: include/linux/skbuff.h:2920
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp_offload.c (ffffffff8200c70d)
Location: include/linux/skbuff.h:2920
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In net/core/skbuff.c (ffff800010bb43b4)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffff800010bfbce8)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (c0cd00c0)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (c0d16c94)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (c000000000c875cc)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (c000000000ce71d0)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffe000742160)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffe00077e6c0)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffff818c0e23)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff818fa58b)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffff8187ad63)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff818b43bb)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffff81911e23)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff8194b5bb)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffff81932f9a)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff8196cecb)
Location: include/linux/skbuff.h:2503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
</details>
</li>
</ul>

## Differences
