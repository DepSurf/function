# Function: <code>__udp4_lib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, struct udp_table *udptable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81789000)
Location: net/ipv4/udp.c:495
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81789000-ffffffff81789444: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f6810)
Location: net/ipv4/udp.c:491
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff817f6810-ffffffff817f6acf: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81827770)
Location: net/ipv4/udp.c:492
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff81827770-ffffffff81827a2f: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81848ee0)
Location: net/ipv4/udp.c:479
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff81848ee0-ffffffff8184920d: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c8940)
Location: net/ipv4/udp.c:482
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff818c8940-ffffffff818c8c7b: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191eb00)
Location: net/ipv4/udp.c:463
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff8191eb00-ffffffff8191edd9: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194c360)
Location: net/ipv4/udp.c:460
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff8194c360-ffffffff8194c4f0: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b0980)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff819b0980-ffffffff819b0adf: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e7610)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff819e7610-ffffffff819e7775: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad38f0)
Location: net/ipv4/udp.c:451
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err_encap
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff81ad38f0-ffffffff81ad3a47: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81adf960)
Location: net/ipv4/udp.c:484
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err_encap
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffff81adf960-ffffffff81adfbd6: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81aca850)
Location: net/ipv4/udp.c:484
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffff81aca850-ffffffff81acaade: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b89510)
Location: net/ipv4/udp.c:485
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffff81b89510-ffffffff81b89799: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1c220)
Location: net/ipv4/udp.c:485
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffff81d1c220-ffffffff81d1c4b1: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee3110)
Location: net/ipv4/udp.c:492
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffff81ee3110-ffffffff81ee33a1: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f429b0)
Location: net/ipv4/udp.c:504
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffff81f429b0-ffffffff81f42c40: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff820089c0)
Location: net/ipv4/udp.c:472
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffff820089c0-ffffffff82008b92: __udp4_lib_lookup (STB_GLOBAL)
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
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9b0f0)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffff800010c9b0f0-ffff800010c9b2a0: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0dab7b8)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
c0dab7b8-c0dab918: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000db0b40)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
c000000000db0b40-c000000000db0d44: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007fa1a6)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffe0007fa1a6-ffffffe0007fa38c: __udp4_lib_lookup (STB_GLOBAL)
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
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81987480)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff81987480-ffffffff819875e5: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81940f40)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff81940f40-ffffffff819410a5: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f1c50)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff819f1c50-ffffffff819f1db5: __udp4_lib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__udp4_lib_lookup(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table *udptable, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fd460)
Location: net/ipv4/udp.c:445
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
**Symbols:**

```
ffffffff819fd460-ffffffff819fd5c5: __udp4_lib_lookup (STB_GLOBAL)
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
