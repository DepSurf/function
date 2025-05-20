# Function: <code>__udp6_lib_mcast_deliver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff817e4580)
Location: net/ipv6/udp.c:787
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff817e4580-ffffffff817e4940: __udp6_lib_mcast_deliver (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81852d12)
Location: net/ipv6/udp.c:692
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81884a12)
Location: net/ipv6/udp.c:678
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff818aad44)
Location: net/ipv6/udp.c:704
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff8192d8b8)
Location: net/ipv6/udp.c:707
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff819861ee)
Location: net/ipv6/udp.c:675
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff819bcab2)
Location: net/ipv6/udp.c:755
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a2b607)
Location: net/ipv6/udp.c:743
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a62167)
Location: net/ipv6/udp.c:743
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b59de0)
Location: net/ipv6/udp.c:745
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81b59de0-ffffffff81b5a137: __udp6_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b68440)
Location: net/ipv6/udp.c:799
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81b68440-ffffffff81b68797: __udp6_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b56730)
Location: net/ipv6/udp.c:812
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81b56730-ffffffff81b56a89: __udp6_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1cbe0)
Location: net/ipv6/udp.c:814
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81c1cbe0-ffffffff81c1cf39: __udp6_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81db94b0)
Location: net/ipv6/udp.c:816
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81db94b0-ffffffff81db980b: __udp6_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f89520)
Location: net/ipv6/udp.c:846
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81f89520-ffffffff81f8987b: __udp6_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81feaf90)
Location: net/ipv6/udp.c:862
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81feaf90-ffffffff81feb2eb: __udp6_lib_mcast_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b8a10)
Location: net/ipv6/udp.c:832
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff820b8a10-ffffffff820b8d6d: __udp6_lib_mcast_deliver (STB_LOCAL)
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
In net/ipv6/udp.c (ffff800010d271ac)
Location: net/ipv6/udp.c:743
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e2ac00)
Location: net/ipv6/udp.c:743
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
c0e2ac00-c0e2b2a0: __udp6_lib_mcast_deliver (STB_LOCAL)
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
In net/ipv6/udp.c (c000000000e580b0)
Location: net/ipv6/udp.c:743
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __udp6_lib_mcast_deliver(struct net *net, struct sk_buff *skb, const struct in6_addr *saddr, const struct in6_addr *daddr, struct udp_table *udptable, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffe00086780c)
Location: net/ipv6/udp.c:743
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffe00086780c-ffffffe000867f90: __udp6_lib_mcast_deliver (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81a017f7)
Location: net/ipv6/udp.c:743
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff819be5b7)
Location: net/ipv6/udp.c:743
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a6c277)
Location: net/ipv6/udp.c:743
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a78887)
Location: net/ipv6/udp.c:743
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
<b>Arch</b>
<ul>
</ul>
