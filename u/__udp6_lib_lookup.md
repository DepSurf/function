# Function: <code>__udp6_lib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, struct udp_table *udptable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff817e3990)
Location: net/ipv6/udp.c:287
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff817e3990-ffffffff817e3da2: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81851d60)
Location: net/ipv6/udp.c:205
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81851d60-ffffffff81851fe2: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81883b20)
Location: net/ipv6/udp.c:205
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81883b20-ffffffff81883da2: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818a9dd0)
Location: net/ipv6/udp.c:216
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff818a9dd0-ffffffff818aa08f: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192c7d0)
Location: net/ipv6/udp.c:220
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff8192c7d0-ffffffff8192ca9d: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81985660)
Location: net/ipv6/udp.c:197
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81985660-ffffffff81985b44: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bbdd0)
Location: net/ipv6/udp.c:191
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff819bbdd0-ffffffff819bc17f: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a2a9c0)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81a2a9c0-ffffffff81a2acc1: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a61520)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81a61520-ffffffff81a61827: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b5a140)
Location: net/ipv6/udp.c:182
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81b5a140-ffffffff81b5a226: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b687a0)
Location: net/ipv6/udp.c:217
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81b687a0-ffffffff81b689a4: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b56a90)
Location: net/ipv6/udp.c:217
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81b56a90-ffffffff81b56c8f: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1c1f0)
Location: net/ipv6/udp.c:219
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81c1c1f0-ffffffff81c1c3ea: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81db89f0)
Location: net/ipv6/udp.c:221
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81db89f0-ffffffff81db8c24: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f88a40)
Location: net/ipv6/udp.c:235
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81f88a40-ffffffff81f88c73: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81feac90)
Location: net/ipv6/udp.c:246
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81feac90-ffffffff81feaebd: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b8d80)
Location: net/ipv6/udp.c:211
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff820b8d80-ffffffff820b8ee9: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffff800010d247e8)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffff800010d247e8-ffff800010d24bd8: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e2b600)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
c0e2b600-c0e2b95c: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c000000000e570d0)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
c000000000e570d0-c000000000e57498: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffe000868402)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffe000868402-ffffffe0008688fe: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a00bb0)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81a00bb0-ffffffff81a00eb7: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bd970)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff819bd970-ffffffff819bdc77: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a6b630)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81a6b630-ffffffff81a6b937: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__udp6_lib_lookup(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a77c40)
Location: net/ipv6/udp.c:179
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
**Symbols:**

```
ffffffff81a77c40-ffffffff81a77f47: __udp6_lib_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff *skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sdif</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, saddr, sport, daddr, dport, dif, udptable, skb</code> ➡️ <code>net, saddr, sport, daddr, dport, dif, sdif, udptable, skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
