# Function: <code>skb_get_nfct</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4067
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4101
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adc9a5)
Location: include/linux/skbuff.h:4101
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b82685)
Location: include/linux/skbuff.h:4101
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4130
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae9705)
Location: include/linux/skbuff.h:4130
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91d1d)
Location: include/linux/skbuff.h:4130
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4194
Inline: True
```
```
In net/core/dev.c (ffffffff819e76bc)
Location: include/linux/skbuff.h:4194
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/ipv4/icmp.c (ffffffff81ad4dc5)
Location: include/linux/skbuff.h:4194
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b80f71)
Location: include/linux/skbuff.h:4194
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4231
Inline: True
```
```
In net/core/dev.c (ffffffff81a984f4)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/ipv4/icmp.c (ffffffff81b93c75)
Location: include/linux/skbuff.h:4231
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4cf91)
Location: include/linux/skbuff.h:4231
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
Location: include/linux/skbuff.h:4650
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_ct
```
```
In net/core/gro.c (ffffffff81c53c79)
Location: include/linux/skbuff.h:4650
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/ipv4/icmp.c (ffffffff81d24b65)
Location: include/linux/skbuff.h:4650
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded442)
Location: include/linux/skbuff.h:4650
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
Location: include/linux/skbuff.h:4546
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_ct
```
```
In net/core/gro.c (ffffffff81e093fe)
Location: include/linux/skbuff.h:4546
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/ipv4/icmp.c (ffffffff81eec355)
Location: include/linux/skbuff.h:4546
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc1262)
Location: include/linux/skbuff.h:4546
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
Location: include/linux/skbuff.h:4578
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_ct
```
```
In net/core/gro.c (ffffffff81e7ba6f)
Location: include/linux/skbuff.h:4578
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/ipv4/icmp.c (ffffffff81f4c145)
Location: include/linux/skbuff.h:4578
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff820221e2)
Location: include/linux/skbuff.h:4578
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
Location: include/linux/skbuff.h:4618
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_ct
```
```
In net/core/gro.c (ffffffff81f3bcf9)
Location: include/linux/skbuff.h:4618
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/ipv4/icmp.c (ffffffff82012255)
Location: include/linux/skbuff.h:4618
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f1302)
Location: include/linux/skbuff.h:4618
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4067
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
Location: include/linux/skbuff.h:4067
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4067
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4067
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4067
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4067
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4067
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (0)
Location: include/linux/skbuff.h:4067
Inline: True
```
```
In net/netfilter/nf_conntrack_proto.c (0)
Location: include/linux/skbuff.h:4067
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (0)
Location: include/linux/skbuff.h:4067
Inline: True
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (0)
Location: include/linux/skbuff.h:4067
Inline: True
```
```
In net/ipv6/netfilter/nf_defrag_ipv6_hooks.c (0)
Location: include/linux/skbuff.h:4067
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
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:4067
Inline: True
```
</details>
</li>
</ul>

## Differences
