# Function: <code>addrconf_dad_failure</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void addrconf_dad_failure(struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817d0540)
Location: net/ipv6/addrconf.c:1817
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff817d0540-ffffffff817d084b: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void addrconf_dad_failure(struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183def0)
Location: net/ipv6/addrconf.c:1880
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8183def0-ffffffff8183e186: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void addrconf_dad_failure(struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186fb00)
Location: net/ipv6/addrconf.c:1928
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8186fb00-ffffffff8186fd96: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void addrconf_dad_failure(struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81894860)
Location: net/ipv6/addrconf.c:1970
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81894860-ffffffff81894af4: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81915cf0)
Location: net/ipv6/addrconf.c:1994
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81915cf0-ffffffff81915fc8: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2017
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8196f40c-ffffffff8196f473: addrconf_dad_failure.cold.79 (STB_LOCAL)
ffffffff8196d460-ffffffff8196d6c4: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2033
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819a4fbc-ffffffff819a5023: addrconf_dad_failure.cold.81 (STB_LOCAL)
ffffffff819a2fc0-ffffffff819a3224: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2066
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a113fa-ffffffff81a11463: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81a0f2a0-ffffffff81a0f51e: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a48069-ffffffff81a480d2: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81a45fe0-ffffffff81a4625e: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2059
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81b3eb4f-ffffffff81b3ebb8: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81b3ced0-ffffffff81b3d247: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2085
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81c32bf9-ffffffff81c32c62: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81b4bbe0-ffffffff81b4beb0: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2087
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81c24f1f-ffffffff81c24f88: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81b397a0-ffffffff81b39a74: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2094
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81d3fa30-ffffffff81d3fa99: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81bfff50-ffffffff81c00224: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2097
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81f0c3a5-ffffffff81f0c40e: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81d99a60-ffffffff81d99d52: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f687b0)
Location: net/ipv6/addrconf.c:2097
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81f687b0-ffffffff81f68b0a: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc88a0)
Location: net/ipv6/addrconf.c:2096
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81fc88a0-ffffffff81fc8be0: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff82096000)
Location: net/ipv6/addrconf.c:2124
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff82096000-ffffffff82096355: addrconf_dad_failure (STB_GLOBAL)
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
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d08a78)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffff800010d08a78-ffff800010d08e70: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0f16c)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
c0e0f16c-c0e0f410: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e330a0)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
c000000000e330a0-c000000000e33434: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00085098c)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffe00085098c-ffffffe000850bd6: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819e76f9-ffffffff819e7762: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff819e5670-ffffffff819e58ee: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819a44b9-ffffffff819a4522: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff819a2430-ffffffff819a26ae: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a52179-ffffffff81a521e2: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81a500f0-ffffffff81a5036e: addrconf_dad_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void addrconf_dad_failure(struct sk_buff *skb, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a5e0c9-ffffffff81a5e132: addrconf_dad_failure.cold (STB_LOCAL)
ffffffff81a5c0f0-ffffffff81a5c386: addrconf_dad_failure (STB_GLOBAL)
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
<code>struct sk_buff *skb</code>
</li>
<li>
<b>Param reordered. </b>
<code>ifp</code> ➡️ <code>skb, ifp</code>
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
