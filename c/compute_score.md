# Function: <code>compute_score</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762555)
Location: net/ipv4/inet_hashtables.c:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff8178917b)
Location: net/ipv4/udp.c:339
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv6/udp.c (ffffffff817e3acf)
Location: net/ipv6/udp.c:144
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8180200b)
Location: net/ipv6/inet6_hashtables.c:96
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int compute_score(struct sock *sk, struct net *net, const short unsigned int hnum, const __be32 daddr, const int dif);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ce38a)
Location: net/ipv4/inet_hashtables.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff817f33e0)
Location: net/ipv4/udp.c:394
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81851e3d)
Location: net/ipv6/udp.c:118
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81873385)
Location: net/ipv6/inet6_hashtables.c:96
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff817f33e0-ffffffff817f346d: compute_score (STB_LOCAL)
ffffffff8184fe40-ffffffff8184fef0: compute_score.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int compute_score(struct sock *sk, struct net *net, const short unsigned int hnum, const __be32 daddr, const int dif, bool exact_dif);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fe14f)
Location: net/ipv4/inet_hashtables.c:174
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff818241c0)
Location: net/ipv4/udp.c:395
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81883bfd)
Location: net/ipv6/udp.c:118
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a79cc)
Location: net/ipv6/inet6_hashtables.c:96
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff818241c0-ffffffff8182424d: compute_score (STB_LOCAL)
ffffffff81881c40-ffffffff81881cf0: compute_score.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int compute_score(struct sock *sk, struct net *net, const short unsigned int hnum, const __be32 daddr, const int dif, bool exact_dif);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181e55e)
Location: net/ipv4/inet_hashtables.c:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81844eb0)
Location: net/ipv4/udp.c:381
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff818a7c50)
Location: net/ipv6/udp.c:129
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce2a6)
Location: net/ipv6/inet6_hashtables.c:96
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81844eb0-ffffffff81844f3e: compute_score (STB_LOCAL)
ffffffff818a7c50-ffffffff818a7cfa: compute_score (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int compute_score(struct sock *sk, struct net *net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif, bool exact_dif);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189d465)
Location: net/ipv4/inet_hashtables.c:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff818c4910)
Location: net/ipv4/udp.c:378
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff8192a700)
Location: net/ipv6/udp.c:129
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953106)
Location: net/ipv6/inet6_hashtables.c:96
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff818c4910-ffffffff818c49af: compute_score (STB_LOCAL)
ffffffff8192a700-ffffffff8192a7bd: compute_score (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int compute_score(struct sock *sk, struct net *net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif, bool exact_dif);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f20e3)
Location: net/ipv4/inet_hashtables.c:226
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff8191a620)
Location: net/ipv4/udp.c:366
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81982a30)
Location: net/ipv6/udp.c:113
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac90b)
Location: net/ipv6/inet6_hashtables.c:96
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff8191a620-ffffffff8191a6b3: compute_score (STB_LOCAL)
ffffffff81982a30-ffffffff81982add: compute_score (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191f664)
Location: net/ipv4/inet_hashtables.c:232
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff8194bcf0)
Location: net/ipv4/udp.c:369
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff819bacfe)
Location: net/ipv6/udp.c:114
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3244)
Location: net/ipv6/inet6_hashtables.c:96
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81981fc8)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff819b046c)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a28bc0)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51f88)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b8828)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff819e712c)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a5f700)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88b88)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa3438)
Location: net/ipv4/inet_hashtables.c:229
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad29e9)
Location: net/ipv4/udp.c:356
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b594e3)
Location: net/ipv6/udp.c:101
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84508)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aad967)
Location: net/ipv4/inet_hashtables.c:232
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81adef37)
Location: net/ipv4/udp.c:357
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b67b1a)
Location: net/ipv6/udp.c:101
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93d57)
Location: net/ipv6/inet6_hashtables.c:94
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a98a27)
Location: net/ipv4/inet_hashtables.c:232
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ac9f87)
Location: net/ipv4/udp.c:357
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b55cfa)
Location: net/ipv6/udp.c:101
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82e67)
Location: net/ipv6/inet6_hashtables.c:94
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b53f06)
Location: net/ipv4/inet_hashtables.c:232
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81b8880b)
Location: net/ipv4/udp.c:357
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81c1b7be)
Location: net/ipv6/udp.c:102
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ef35)
Location: net/ipv6/inet6_hashtables.c:94
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce1e1f)
Location: net/ipv4/inet_hashtables.c:196
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81d19ccc)
Location: net/ipv4/udp.c:357
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81db7f06)
Location: net/ipv6/udp.c:103
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def921)
Location: net/ipv6/inet6_hashtables.c:94
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea2fff)
Location: net/ipv4/inet_hashtables.c:312
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81ee08ac)
Location: net/ipv4/udp.c:364
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81f87f46)
Location: net/ipv6/udp.c:117
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3a01)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int compute_score(struct sock *sk, struct net *net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f01831)
Location: net/ipv4/inet_hashtables.c:312
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81f3dad0)
Location: net/ipv4/udp.c:366
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81fe7870)
Location: net/ipv6/udp.c:119
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024861)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff81f3dad0-ffffffff81f3dba8: compute_score (STB_LOCAL)
ffffffff81fe7870-ffffffff81fe796f: compute_score (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int compute_score(struct sock *sk, struct net *net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc5b80)
Location: net/ipv4/inet_hashtables.c:314
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff82003c00)
Location: net/ipv4/udp.c:366
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff820b56d0)
Location: net/ipv6/udp.c:120
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3b70)
Location: net/ipv6/inet6_hashtables.c:93
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff82003c00-ffffffff82003cd8: compute_score (STB_LOCAL)
ffffffff820b56d0-ffffffff820b57cf: compute_score (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c69c88)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffff800010c99a90)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffff800010d23ba8)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55858)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d78f3c)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (c0daad98)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (c0e29618)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (c0e55e34)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6ecb0)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (c000000000dae5d0)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (c000000000e55b30)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e7b0)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007cfaa8)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffe0007f966a)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffe0008667a4)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d03a)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81958698)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81986f9c)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff819fed90)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28218)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912188)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81940a5c)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff819bbb50)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e4fd8)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c2e68)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff819f176c)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a69810)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93dc8)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cc938)
Location: net/ipv4/inet_hashtables.c:228
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff819fca71)
Location: net/ipv4/udp.c:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a75df4)
Location: net/ipv6/udp.c:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9ff18)
Location: net/ipv6/inet6_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exact_dif</code>
</li>
</ul>
</details>
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
<li>
<b>Param reordered. </b>
<code>sk, net, hnum, daddr, dif, exact_dif</code> ➡️ <code>sk, net, hnum, daddr, dif, sdif, exact_dif</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
