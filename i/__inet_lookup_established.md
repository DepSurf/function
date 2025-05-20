# Function: <code>__inet_lookup_established</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762860)
Location: net/ipv4/inet_hashtables.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
**Symbols:**

```
ffffffff81762860-ffffffff81762982: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ce660)
Location: net/ipv4/inet_hashtables.c:268
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff817ce660-ffffffff817ce785: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fe470)
Location: net/ipv4/inet_hashtables.c:270
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff817fe470-ffffffff817fe595: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181e820)
Location: net/ipv4/inet_hashtables.c:267
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8181e820-ffffffff8181e937: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189da00)
Location: net/ipv4/inet_hashtables.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8189da00-ffffffff8189db86: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f1ba0)
Location: net/ipv4/inet_hashtables.c:386
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff818f1ba0-ffffffff818f1d34: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191f750)
Location: net/ipv4/inet_hashtables.c:350
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8191f750-ffffffff8191f8cb: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819820c0)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819820c0-ffffffff819821e3: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b8920)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819b8920-ffffffff819b8a43: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa3280)
Location: net/ipv4/inet_hashtables.c:347
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81aa3280-ffffffff81aa33c7: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aad7b0)
Location: net/ipv4/inet_hashtables.c:390
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81aad7b0-ffffffff81aad8f7: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a98880)
Location: net/ipv4/inet_hashtables.c:390
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81a98880-ffffffff81a989b4: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b53d60)
Location: net/ipv4/inet_hashtables.c:392
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81b53d60-ffffffff81b53e94: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce1930)
Location: net/ipv4/inet_hashtables.c:355
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81ce1930-ffffffff81ce1ae1: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea2af0)
Location: net/ipv4/inet_hashtables.c:471
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81ea2af0-ffffffff81ea2ca1: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f01310)
Location: net/ipv4/inet_hashtables.c:471
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81f01310-ffffffff81f014bd: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc5660)
Location: net/ipv4/inet_hashtables.c:492
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
**Symbols:**

```
ffffffff81fc5660-ffffffff81fc580d: __inet_lookup_established (STB_GLOBAL)
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
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c69da8)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffff800010c69da8-ffff800010c69f18: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d7904c)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
c0d7904c-c0d791bc: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6ee30)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
c000000000d6ee30-c000000000d6f048: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007cfb74)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffe0007cfb74-ffffffe0007cfcac: __inet_lookup_established (STB_GLOBAL)
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
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81958790)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81958790-ffffffff819588b3: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912280)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81912280-ffffffff819123a3: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c2f60)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819c2f60-ffffffff819c3083: __inet_lookup_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__inet_lookup_established(struct net *net, struct inet_hashinfo *hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cca30)
Location: net/ipv4/inet_hashtables.c:346
Inline: False
Direct callers:
  - net/core/filter.c:sk_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819cca30-ffffffff819ccb53: __inet_lookup_established (STB_GLOBAL)
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
