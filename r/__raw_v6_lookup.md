# Function: <code>__raw_v6_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff817e5070)
Location: net/ipv6/raw.c:72
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff817e5070-ffffffff817e5151: __raw_v6_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81853350)
Location: net/ipv6/raw.c:72
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81853350-ffffffff81853431: __raw_v6_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81885040)
Location: net/ipv6/raw.c:73
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81885040-ffffffff81885121: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff818ab430)
Location: net/ipv6/raw.c:73
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff818ab430-ffffffff818ab51a: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff8192dfc0)
Location: net/ipv6/raw.c:73
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff8192dfc0-ffffffff8192e0b6: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81986c50)
Location: net/ipv6/raw.c:73
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81986c50-ffffffff81986d48: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff819bd550)
Location: net/ipv6/raw.c:73
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff819bd550-ffffffff819bd66d: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a2bff0)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81a2bff0-ffffffff81a2c10d: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a62b50)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81a62b50-ffffffff81a62c6d: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b5b410)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
**Symbols:**

```
ffffffff81b5b410-ffffffff81b5b52d: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b69c30)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
**Symbols:**

```
ffffffff81b69c30-ffffffff81b69d4d: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b57f20)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
**Symbols:**

```
ffffffff81b57f20-ffffffff81b5803e: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81c1f4d0)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
**Symbols:**

```
ffffffff81c1f4d0-ffffffff81c1f5ee: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffff800010d27d88)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffff800010d27d88-ffff800010d27ec4: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (c0e2c7dc)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
c0e2c7dc-c0e2c948: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (c000000000e58db0)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
c000000000e58db0-c000000000e58fb8: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffe0008695f2)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffe0008695f2-ffffffe000869718: __raw_v6_lookup (STB_GLOBAL)
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
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a021e0)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81a021e0-ffffffff81a022fd: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff819befa0)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff819befa0-ffffffff819bf0bd: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a6cc60)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81a6cc60-ffffffff81a6cd7d: __raw_v6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__raw_v6_lookup(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a792a0)
Location: net/ipv6/raw.c:69
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81a792a0-ffffffff81a793bd: __raw_v6_lookup (STB_GLOBAL)
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
<code>int sdif</code>
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
