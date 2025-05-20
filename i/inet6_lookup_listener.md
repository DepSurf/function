# Function: <code>inet6_lookup_listener</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81801f90)
Location: net/ipv6/inet6_hashtables.c:123
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81801f90-ffffffff81802266: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81873300)
Location: net/ipv6/inet6_hashtables.c:124
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81873300-ffffffff818734cd: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff818a7920)
Location: net/ipv6/inet6_hashtables.c:124
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff818a7920-ffffffff818a7b34: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff818ce210)
Location: net/ipv6/inet6_hashtables.c:124
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff818ce210-ffffffff818ce3d3: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81953070)
Location: net/ipv6/inet6_hashtables.c:128
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81953070-ffffffff81953246: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819ac790)
Location: net/ipv6/inet6_hashtables.c:162
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff819ac790-ffffffff819acc8b: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819e3330)
Location: net/ipv6/inet6_hashtables.c:153
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff819e3330-ffffffff819e364c: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a52080)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a52080-ffffffff81a5236d: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a88c80)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a88c80-ffffffff81a88f73: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b84600)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81b84600-ffffffff81b846f0: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b93e60)
Location: net/ipv6/inet6_hashtables.c:187
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81b93e60-ffffffff81b9404b: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b82f70)
Location: net/ipv6/inet6_hashtables.c:187
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81b82f70-ffffffff81b83155: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81c4f040)
Location: net/ipv6/inet6_hashtables.c:187
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81c4f040-ffffffff81c4f221: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81defa30)
Location: net/ipv6/inet6_hashtables.c:186
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81defa30-ffffffff81defc2c: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3b20)
Location: net/ipv6/inet6_hashtables.c:184
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81fc3b20-ffffffff81fc3d1b: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff82024980)
Location: net/ipv6/inet6_hashtables.c:184
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff82024980-ffffffff82024d46: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff820f3c80)
Location: net/ipv6/inet6_hashtables.c:203
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff820f3c80-ffffffff820f4022: inet6_lookup_listener (STB_GLOBAL)
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
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffff800010d55980)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffff800010d55980-ffff800010d55d74: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (c0e55f70)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
c0e55f70-c0e56330: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (c000000000e8e930)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
c000000000e8e930-c000000000e8ed18: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffe00088d126)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffe00088d126-ffffffe00088d64e: inet6_lookup_listener (STB_GLOBAL)
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
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a28310)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a28310-ffffffff81a28603: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819e50d0)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff819e50d0-ffffffff819e53c3: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a93ec0)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a93ec0-ffffffff81a941b3: inet6_lookup_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *inet6_lookup_listener(struct net *net, struct inet_hashinfo *hashinfo, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81aa0010)
Location: net/ipv6/inet6_hashtables.c:149
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81aa0010-ffffffff81aa0303: inet6_lookup_listener (STB_GLOBAL)
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
