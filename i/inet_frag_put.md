# Function: <code>inet_frag_put</code>

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
In net/ipv4/ip_fragment.c (ffffffff81759640)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff817a2160)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff817ee02e)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff817c5ca3)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff8180fe35)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff8185c875)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff817f57a3)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff81841385)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff8188e785)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81815c35)
Location: include/net/inet_frag.h:120
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff81862be3)
Location: include/net/inet_frag.h:120
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff818b4f5a)
Location: include/net/inet_frag.h:120
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81894e1a)
Location: include/net/inet_frag.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2d1f)
Location: include/net/inet_frag.h:121
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81937cca)
Location: include/net/inet_frag.h:121
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff818e9278)
Location: include/net/inet_frag.h:115
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff81939089)
Location: include/net/inet_frag.h:115
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81990b57)
Location: include/net/inet_frag.h:115
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81916363)
Location: include/net/inet_frag.h:122
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_fragment.c (ffffffff81968c59)
Location: include/net/inet_frag.h:122
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff819c7292)
Location: include/net/inet_frag.h:122
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81978cc5)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81a36481)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff819af635)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81a6cfa1)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81a994bc)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81b663ba)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81aa342c)
Location: include/net/inet_frag.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81b74c26)
Location: include/net/inet_frag.h:132
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81a8e599)
Location: include/net/inet_frag.h:132
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81b63754)
Location: include/net/inet_frag.h:132
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81b49789)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81c2b214)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81cd6d70)
Location: include/net/inet_frag.h:141
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81dc84c4)
Location: include/net/inet_frag.h:141
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81e97300)
Location: include/net/inet_frag.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81f99254)
Location: include/net/inet_frag.h:148
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81ef5b30)
Location: include/net/inet_frag.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81ff9c24)
Location: include/net/inet_frag.h:148
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81fb9ae0)
Location: include/net/inet_frag.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff820c7894)
Location: include/net/inet_frag.h:148
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffff800010c5fe30)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffff800010d359c8)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (c0d6f600)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (c0e37c78)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (c000000000d62bb8)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (c000000000e67ac8)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffe0007c7f5a)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffe000872ea4)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff8194f4a5)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81a0c631)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff81908f95)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff819c93f1)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
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
In net/ipv4/ip_fragment.c (ffffffff819b9c75)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81a770b1)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a9133c)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_expire
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
In net/ipv4/ip_fragment.c (ffffffff819c36b3)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv6/reassembly.c (ffffffff81a836cf)
Location: include/net/inet_frag.h:131
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
</details>
</li>
</ul>

## Differences
