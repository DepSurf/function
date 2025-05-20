# Function: <code>__vlan_get_protocol</code>

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
In net/core/dev.c (ffffffff8171c037)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff817342a9)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff817848d7)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:__skb_csum_offload_chk
```
```
In net/core/tso.c (ffffffff8179fd69)
Location: include/linux/if_vlan.h:481
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff817b1f17)
Location: include/linux/if_vlan.h:482
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff817ce739)
Location: include/linux/if_vlan.h:482
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff817cf6f3)
Location: include/linux/if_vlan.h:482
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff817edbe9)
Location: include/linux/if_vlan.h:482
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff81849033)
Location: include/linux/if_vlan.h:482
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff81869e29)
Location: include/linux/if_vlan.h:482
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff81893003)
Location: include/linux/if_vlan.h:561
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff818b9af9)
Location: include/linux/if_vlan.h:561
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff818b3a73)
Location: include/linux/if_vlan.h:596
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff818e08b9)
Location: include/linux/if_vlan.h:596
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff81900303)
Location: include/linux/if_vlan.h:591
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff8192ef49)
Location: include/linux/if_vlan.h:591
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff81932623)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff819611b9)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff81a075da)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a2d38b)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a346cc)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:582
Inline: True
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
In net/core/dev.c (ffffffff81a08c5a)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a2ec2b)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a369cd)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81a6f65b)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:582
Inline: True
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
In net/core/dev.c (ffffffff819ef5f6)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a1628a)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a1db49)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81a57f28)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:582
Inline: True
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
In net/core/dev.c (ffffffff81aa0a16)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81ac71ea)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81ad15e9)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81b10ef8)
Location: include/linux/if_vlan.h:582
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:582
Inline: True
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
In net/core/dev.c (ffffffff81c18a8a)
Location: include/linux/if_vlan.h:587
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81c4294b)
Location: include/linux/if_vlan.h:587
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81c4eedd)
Location: include/linux/if_vlan.h:587
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81c97fc1)
Location: include/linux/if_vlan.h:587
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:587
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df364f)
Location: include/linux/if_vlan.h:587
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/dev.c (ffffffff81dc9a4a)
Location: include/linux/if_vlan.h:584
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81df793b)
Location: include/linux/if_vlan.h:584
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e03f8d)
Location: include/linux/if_vlan.h:584
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81e53f71)
Location: include/linux/if_vlan.h:584
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:584
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc841f)
Location: include/linux/if_vlan.h:584
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/dev.c (ffffffff81e3a56f)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81e6963b)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e7677a)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81eaf7f1)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:593
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82028f3f)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/dev.c (ffffffff81ef88ff)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81f28c1b)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81f3673d)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/sched/sch_frag.c (ffffffff81f72271)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/if_vlan.h:593
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f897f)
Location: include/linux/if_vlan.h:593
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In net/core/dev.c (ffff800010bd0670)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffff800010c04a7c)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (c0ceb1a4)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (c0d1dee0)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (c000000000cae454)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (c000000000ceea28)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffe00075ae16)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffe000783676)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff818d2623)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff81901189)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff8188c4b3)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff818bafb9)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff81923623)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff819521b9)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
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
In net/core/dev.c (ffffffff81944a73)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/tso.c (ffffffff81973bf9)
Location: include/linux/if_vlan.h:580
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
</ul>

## Differences
