# Function: <code>__udp4_lib_mcast_deliver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81789c30)
Location: net/ipv4/udp.c:1668
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81789c30-ffffffff81789fa2: __udp4_lib_mcast_deliver (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff817f7921)
Location: net/ipv4/udp.c:1634
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff8182880f)
Location: net/ipv4/udp.c:1790
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff81849aa6)
Location: net/ipv4/udp.c:1953
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff818c9608)
Location: net/ipv4/udp.c:1952
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff8191f5e7)
Location: net/ipv4/udp.c:2035
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff8194e27f)
Location: net/ipv4/udp.c:2121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b2afb)
Location: net/ipv4/udp.c:2107
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff819e989e)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad6780)
Location: net/ipv4/udp.c:2151
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ad6780-ffffffff81ad6af1: __udp4_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae2d60)
Location: net/ipv4/udp.c:2204
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ae2d60-ffffffff81ae30d1: __udp4_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81acdcc0)
Location: net/ipv4/udp.c:2255
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81acdcc0-ffffffff81ace02f: __udp4_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8c680)
Location: net/ipv4/udp.c:2267
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81b8c680-ffffffff81b8c9ef: __udp4_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1cd00)
Location: net/ipv4/udp.c:2276
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81d1cd00-ffffffff81d1d0a9: __udp4_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee3e00)
Location: net/ipv4/udp.c:2278
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ee3e00-ffffffff81ee41a9: __udp4_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f43670)
Location: net/ipv4/udp.c:2250
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81f43670-ffffffff81f43a19: __udp4_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __udp4_lib_mcast_deliver(struct net *net, struct sk_buff *skb, struct udphdr *uh, __be32 saddr, __be32 daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff820095e0)
Location: net/ipv4/udp.c:2223
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff820095e0-ffffffff82009989: __udp4_lib_mcast_deliver (STB_LOCAL)
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
In net/ipv4/udp.c (ffff800010c9f178)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (c0dac384)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (c000000000db1aa0)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffe0007fbb4a)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff8198970e)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff819431ce)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f3ede)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff819fe09e)
Location: net/ipv4/udp.c:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
