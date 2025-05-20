# Function: <code>ip6_mtu_from_fib6</code>

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
u32 ip6_mtu_from_fib6(struct fib6_info *f6i, struct in6_addr *daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819779d0)
Location: net/ipv6/route.c:2626
Inline: False
```
**Symbols:**

```
ffffffff819779d0-ffffffff81977acb: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(struct fib6_info *f6i, struct in6_addr *daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad5c0)
Location: net/ipv6/route.c:2615
Inline: False
```
**Symbols:**

```
ffffffff819ad5c0-ffffffff819ad6bb: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1a720)
Location: net/ipv6/route.c:3087
Inline: False
```
**Symbols:**

```
ffffffff81a1a720-ffffffff81a1a7cf: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a51390)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
ffffffff81a51390-ffffffff81a5143f: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b48ab0)
Location: net/ipv6/route.c:3121
Inline: False
```
**Symbols:**

```
ffffffff81b48ab0-ffffffff81b48b53: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b576c0)
Location: net/ipv6/route.c:3105
Inline: False
```
**Symbols:**

```
ffffffff81b576c0-ffffffff81b57763: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b452b0)
Location: net/ipv6/route.c:3115
Inline: False
```
**Symbols:**

```
ffffffff81b452b0-ffffffff81b4534a: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0c3f0)
Location: net/ipv6/route.c:3227
Inline: False
```
**Symbols:**

```
ffffffff81c0c3f0-ffffffff81c0c48a: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da72c0)
Location: net/ipv6/route.c:3217
Inline: False
```
**Symbols:**

```
ffffffff81da72c0-ffffffff81da7372: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f768e0)
Location: net/ipv6/route.c:3217
Inline: False
```
**Symbols:**

```
ffffffff81f768e0-ffffffff81f76992: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd6910)
Location: net/ipv6/route.c:3217
Inline: False
```
**Symbols:**

```
ffffffff81fd6910-ffffffff81fd69c2: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a4290)
Location: net/ipv6/route.c:3219
Inline: False
```
**Symbols:**

```
ffffffff820a4290-ffffffff820a4342: ip6_mtu_from_fib6 (STB_GLOBAL)
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
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d152e0)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
ffff800010d152e0-ffff800010d153b8: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1af74)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
c0e1af74-c0e1b044: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e42290)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
c000000000e42290-c000000000e423c0: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085a9da)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
ffffffe00085a9da-ffffffe00085aa9c: ip6_mtu_from_fib6 (STB_GLOBAL)
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
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f0a20)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
ffffffff819f0a20-ffffffff819f0acf: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad7e0)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
ffffffff819ad7e0-ffffffff819ad88f: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5b4a0)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
ffffffff81a5b4a0-ffffffff81a5b54f: ip6_mtu_from_fib6 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 ip6_mtu_from_fib6(const struct fib6_result *res, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a677b0)
Location: net/ipv6/route.c:3097
Inline: False
```
**Symbols:**

```
ffffffff81a677b0-ffffffff81a6785f: ip6_mtu_from_fib6 (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct fib6_result *res</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info *f6i</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct in6_addr *daddr</code> ➡️ <code>const struct in6_addr *daddr</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct in6_addr *saddr</code> ➡️ <code>const struct in6_addr *saddr</code>
</li>
</ul>
</details>
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
