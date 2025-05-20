# Function: <code>inet6_lhash2_lookup</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819ac600)
Location: net/ipv6/inet6_hashtables.c:128
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff819ac600-ffffffff819ac787: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819e31e0)
Location: net/ipv6/inet6_hashtables.c:119
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff819e31e0-ffffffff819e332a: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a51f20)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81a51f20-ffffffff81a52072: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a88b20)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81a88b20-ffffffff81a88c74: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b844a0)
Location: net/ipv6/inet6_hashtables.c:115
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81b844a0-ffffffff81b84600: inet6_lhash2_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b93cf0)
Location: net/ipv6/inet6_hashtables.c:134
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81b93cf0-ffffffff81b93e57: inet6_lhash2_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b82e00)
Location: net/ipv6/inet6_hashtables.c:134
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81b82e00-ffffffff81b82f6a: inet6_lhash2_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81c4eed0)
Location: net/ipv6/inet6_hashtables.c:134
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81c4eed0-ffffffff81c4f03d: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81def8c0)
Location: net/ipv6/inet6_hashtables.c:134
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81def8c0-ffffffff81defa23: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81fc39a0)
Location: net/ipv6/inet6_hashtables.c:132
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81fc39a0-ffffffff81fc3b03: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff82024800)
Location: net/ipv6/inet6_hashtables.c:132
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff82024800-ffffffff82024964: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff820f3b10)
Location: net/ipv6/inet6_hashtables.c:151
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff820f3b10-ffffffff820f3c6d: inet6_lhash2_lookup (STB_LOCAL)
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
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffff800010d557e8)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffff800010d557e8-ffff800010d5597c: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (c0e55dd4)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
c0e55dd4-c0e55f70: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (c000000000e8e710)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
c000000000e8e710-c000000000e8e930: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffe00088cfe8)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffe00088cfe8-ffffffe00088d126: inet6_lhash2_lookup (STB_LOCAL)
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
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a281b0)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81a281b0-ffffffff81a28304: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819e4f70)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff819e4f70-ffffffff819e50c4: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a93d60)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81a93d60-ffffffff81a93eb4: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *inet6_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a9feb0)
Location: net/ipv6/inet6_hashtables.c:115
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81a9feb0-ffffffff81aa0004: inet6_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
