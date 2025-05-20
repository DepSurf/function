# Function: <code>ip6_route_output_flags_noref</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12f10)
Location: net/ipv6/route.c:2455
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81a12f10-ffffffff81a13017: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49b00)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81a49b00-ffffffff81a49c07: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b404d0)
Location: net/ipv6/route.c:2480
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81b404d0-ffffffff81b405d7: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4ef90)
Location: net/ipv6/route.c:2463
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81b4ef90-ffffffff81b4f097: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3cdd0)
Location: net/ipv6/route.c:2470
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81b3cdd0-ffffffff81b3ced7: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2600
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81d3fc4b-ffffffff81d3fc73: ip6_route_output_flags_noref.cold (STB_LOCAL)
ffffffff81c05540-ffffffff81c0564c: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2596
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81f0c5d1-ffffffff81f0c5f1: ip6_route_output_flags_noref.cold (STB_LOCAL)
ffffffff81d9fac0-ffffffff81d9fc14: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2596
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff820b3c22-ffffffff820b3c42: ip6_route_output_flags_noref.cold (STB_LOCAL)
ffffffff81f6eb50-ffffffff81f6eca4: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcea7b)
Location: net/ipv6/route.c:2595
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209c2db)
Location: net/ipv6/route.c:2597
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
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
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0cc68)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffff800010d0cc68-ffff800010d0cd84: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1346c)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
c0e1346c-c0e13584: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e38310)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
c000000000e38310-c000000000e384dc: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085440c)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffe00085440c-ffffffe0008544fe: ip6_route_output_flags_noref (STB_GLOBAL)
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
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e9190)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff819e9190-ffffffff819e9297: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5f50)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff819a5f50-ffffffff819a6057: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53c10)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81a53c10-ffffffff81a53d17: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *ip6_route_output_flags_noref(struct net *net, const struct sock *sk, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5fc00)
Location: net/ipv6/route.c:2461
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
**Symbols:**

```
ffffffff81a5fc00-ffffffff81a5fd07: ip6_route_output_flags_noref (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
