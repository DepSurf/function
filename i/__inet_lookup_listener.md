# Function: <code>__inet_lookup_listener</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817624c0)
Location: net/ipv4/inet_hashtables.c:206
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
**Symbols:**

```
ffffffff817624c0-ffffffff81762774: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ce300)
Location: net/ipv4/inet_hashtables.c:208
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff817ce300-ffffffff817ce49c: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fe0a0)
Location: net/ipv4/inet_hashtables.c:209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff817fe0a0-ffffffff817fe2b0: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181e4d0)
Location: net/ipv4/inet_hashtables.c:206
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8181e4d0-ffffffff8181e67b: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189d3d0)
Location: net/ipv4/inet_hashtables.c:210
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8189d3d0-ffffffff8189d594: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f1fa0)
Location: net/ipv4/inet_hashtables.c:299
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff818f1fa0-ffffffff818f2298: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191f9a0)
Location: net/ipv4/inet_hashtables.c:295
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8191f9a0-ffffffff8191fb0a: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819822c0)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819822c0-ffffffff8198241d: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b8b20)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819b8b20-ffffffff819b8c83: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa3540)
Location: net/ipv4/inet_hashtables.c:292
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81aa3540-ffffffff81aa36a7: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aada70)
Location: net/ipv4/inet_hashtables.c:327
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81aada70-ffffffff81aadce2: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a98b30)
Location: net/ipv4/inet_hashtables.c:327
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81a98b30-ffffffff81a98d84: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b54010)
Location: net/ipv4/inet_hashtables.c:329
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81b54010-ffffffff81b54260: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce1f20)
Location: net/ipv4/inet_hashtables.c:292
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81ce1f20-ffffffff81ce2190: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea3110)
Location: net/ipv4/inet_hashtables.c:408
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81ea3110-ffffffff81ea3380: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f01950)
Location: net/ipv4/inet_hashtables.c:408
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81f01950-ffffffff81f01bb8: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc6640)
Location: net/ipv4/inet_hashtables.c:427
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
**Symbols:**

```
ffffffff81fc6640-ffffffff81fc6805: __inet_lookup_listener (STB_GLOBAL)
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
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c69f18)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffff800010c69f18-ffff800010c6a0d0: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d7949c)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
c0d7949c-c0d79618: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6f410)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
c000000000d6f410-c000000000d6f600: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007cfd92)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffe0007cfd92-ffffffe0007cff6c: __inet_lookup_listener (STB_GLOBAL)
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
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81958990)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81958990-ffffffff81958af3: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912480)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81912480-ffffffff819125e3: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c3160)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819c3160-ffffffff819c32c3: __inet_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__inet_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cce30)
Location: net/ipv4/inet_hashtables.c:291
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819cce30-ffffffff819ccf93: __inet_lookup_listener (STB_GLOBAL)
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
<li>
<b>Param added. </b>
<code>int doff</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, hashinfo, saddr, sport, daddr, hnum, dif</code> ➡️ <code>net, hashinfo, skb, doff, saddr, sport, daddr, hnum, dif</code>
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
<code>const int sdif</code>
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
