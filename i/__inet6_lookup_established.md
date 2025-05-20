# Function: <code>__inet6_lookup_established</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81801df0)
Location: net/ipv6/inet6_hashtables.c:51
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81801df0-ffffffff81801f84: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81873160)
Location: net/ipv6/inet6_hashtables.c:53
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81873160-ffffffff818732f8: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff818a7780)
Location: net/ipv6/inet6_hashtables.c:53
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff818a7780-ffffffff818a7918: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff818ce080)
Location: net/ipv6/inet6_hashtables.c:53
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff818ce080-ffffffff818ce201: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81952ea0)
Location: net/ipv6/inet6_hashtables.c:53
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81952ea0-ffffffff81953066: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819ac430)
Location: net/ipv6/inet6_hashtables.c:53
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff819ac430-ffffffff819ac5f6: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819e3010)
Location: net/ipv6/inet6_hashtables.c:53
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff819e3010-ffffffff819e31da: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a51da0)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a51da0-ffffffff81a51f1c: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a889a0)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a889a0-ffffffff81a88b1c: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b83fe0)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81b83fe0-ffffffff81b84184: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b93840)
Location: net/ipv6/inet6_hashtables.c:51
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81b93840-ffffffff81b939e4: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b82960)
Location: net/ipv6/inet6_hashtables.c:51
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81b82960-ffffffff81b82afc: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ea30)
Location: net/ipv6/inet6_hashtables.c:51
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81c4ea30-ffffffff81c4ebcc: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81def380)
Location: net/ipv6/inet6_hashtables.c:51
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81def380-ffffffff81def582: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3440)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81fc3440-ffffffff81fc3642: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff82024290)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff82024290-ffffffff82024481: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff820f3400)
Location: net/ipv6/inet6_hashtables.c:50
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff820f3400-ffffffff820f35f1: __inet6_lookup_established (STB_GLOBAL)
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
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffff800010d55600)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffff800010d55600-ffff800010d557e4: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (c0e55b6c)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
c0e55b6c-c0e55dd4: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (c000000000e8e460)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
c000000000e8e460-c000000000e8e704: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffe00088cdb4)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffe00088cdb4-ffffffe00088cfe8: __inet6_lookup_established (STB_GLOBAL)
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
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a28030)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a28030-ffffffff81a281ac: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819e4df0)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff819e4df0-ffffffff819e4f6c: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a93be0)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a93be0-ffffffff81a93d5c: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__inet6_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a9fd30)
Location: net/ipv6/inet6_hashtables.c:49
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
**Symbols:**

```
ffffffff81a9fd30-ffffffff81a9feac: __inet6_lookup_established (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
