# Function: <code>inet_lhash2_lookup</code>

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
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f1a20)
Location: net/ipv4/inet_hashtables.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff818f1a20-ffffffff818f1b92: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191f600)
Location: net/ipv4/inet_hashtables.c:261
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff8191f600-ffffffff8191f74b: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81981f60)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81981f60-ffffffff819820b3: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b87c0)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff819b87c0-ffffffff819b8915: inet_lhash2_lookup (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (ffffffff81aa33d0)
Location: net/ipv4/inet_hashtables.c:258
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81aa33d0-ffffffff81aa3531: inet_lhash2_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (ffffffff81aad900)
Location: net/ipv4/inet_hashtables.c:276
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81aad900-ffffffff81aada69: inet_lhash2_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (ffffffff81a989c0)
Location: net/ipv4/inet_hashtables.c:276
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81a989c0-ffffffff81a98b2e: inet_lhash2_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b53ea0)
Location: net/ipv4/inet_hashtables.c:278
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81b53ea0-ffffffff81b5400a: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce1dc0)
Location: net/ipv4/inet_hashtables.c:242
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81ce1dc0-ffffffff81ce1f1e: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea2fa0)
Location: net/ipv4/inet_hashtables.c:358
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81ea2fa0-ffffffff81ea30fe: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f017d0)
Location: net/ipv4/inet_hashtables.c:358
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81f017d0-ffffffff81f01931: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc5b20)
Location: net/ipv4/inet_hashtables.c:378
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81fc5b20-ffffffff81fc5c79: inet_lhash2_lookup (STB_LOCAL)
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
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c69c18)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffff800010c69c18-ffff800010c69da4: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d78edc)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
c0d78edc-c0d7904c: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6ec10)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
c000000000d6ec10-c000000000d6ee30: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007cfa58)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffe0007cfa58-ffffffe0007cfb74: inet_lhash2_lookup (STB_LOCAL)
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
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81958630)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81958630-ffffffff81958785: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912120)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81912120-ffffffff81912275: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c2e00)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff819c2e00-ffffffff819c2f55: inet_lhash2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *inet_lhash2_lookup(struct net *net, struct inet_listen_hashbucket *ilb2, struct sk_buff *skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cc8d0)
Location: net/ipv4/inet_hashtables.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff819cc8d0-ffffffff819cca25: inet_lhash2_lookup (STB_LOCAL)
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
