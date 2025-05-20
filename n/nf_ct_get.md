# Function: <code>nf_ct_get</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f4d35)
Location: include/net/netfilter/nf_conntrack.h:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81926c05)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
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
In net/core/flow_dissector.c (ffffffff819fab99)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adc9a5)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b82685)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In net/core/flow_dissector.c (ffffffff819fa7a9)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae9705)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91d1d)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In net/core/flow_dissector.c (ffffffff819e098f)
Location: include/net/netfilter/nf_conntrack.h:164
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad4dc5)
Location: include/net/netfilter/nf_conntrack.h:164
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b80f71)
Location: include/net/netfilter/nf_conntrack.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In net/core/flow_dissector.c (ffffffff81a90d03)
Location: include/net/netfilter/nf_conntrack.h:164
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b93c75)
Location: include/net/netfilter/nf_conntrack.h:164
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4cf91)
Location: include/net/netfilter/nf_conntrack.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In net/core/flow_dissector.c (ffffffff81c0687b)
Location: include/net/netfilter/nf_conntrack.h:170
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_ct
```
```
In net/ipv4/icmp.c (ffffffff81d24b65)
Location: include/net/netfilter/nf_conntrack.h:170
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded442)
Location: include/net/netfilter/nf_conntrack.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In net/core/flow_dissector.c (ffffffff81db641b)
Location: include/net/netfilter/nf_conntrack.h:168
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_ct
```
```
In net/ipv4/icmp.c (ffffffff81eec355)
Location: include/net/netfilter/nf_conntrack.h:168
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc1262)
Location: include/net/netfilter/nf_conntrack.h:168
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In net/core/flow_dissector.c (ffffffff81e267cb)
Location: include/net/netfilter/nf_conntrack.h:174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_ct
```
```
In net/ipv4/icmp.c (ffffffff81f4c145)
Location: include/net/netfilter/nf_conntrack.h:174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff820221e2)
Location: include/net/netfilter/nf_conntrack.h:174
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
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
In net/core/flow_dissector.c (ffffffff81ee475c)
Location: include/net/netfilter/nf_conntrack.h:170
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_ct
```
```
In net/ipv4/icmp.c (ffffffff82012255)
Location: include/net/netfilter/nf_conntrack.h:170
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f1302)
Location: include/net/netfilter/nf_conntrack.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc2f80)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c0cde2b4)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9d044)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffe00074fcf8)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c6c05)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81880b45)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
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
In net/core/flow_dissector.c (ffffffff81917c05)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199f5a8)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_update
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_attach
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a4995)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv4_confirm
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819abc75)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_get_ct
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20c19)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
```
In net/ipv6/netfilter/nf_defrag_ipv6_hooks.c (ffffffff81a907ea)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81938e15)
Location: include/net/netfilter/nf_conntrack.h:150
Inline: True
```
</details>
</li>
</ul>

## Differences
