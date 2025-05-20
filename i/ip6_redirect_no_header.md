# Function: <code>ip6_redirect_no_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d7c30)
Location: net/ipv6/route.c:1513
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff817d7c30-ffffffff817d7cf9: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81846490)
Location: net/ipv6/route.c:1537
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81846490-ffffffff81846559: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81878200)
Location: net/ipv6/route.c:1551
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81878200-ffffffff818782df: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189d400)
Location: net/ipv6/route.c:1588
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff8189d400-ffffffff8189d4e8: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191f710)
Location: net/ipv6/route.c:2276
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff8191f710-ffffffff8191f7f8: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819778d0)
Location: net/ipv6/route.c:2545
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff819778d0-ffffffff819779cb: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad4d0)
Location: net/ipv6/route.c:2537
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff819ad4d0-ffffffff819ad5b8: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1a630)
Location: net/ipv6/route.c:3009
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81a1a630-ffffffff81a1a713: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a512a0)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81a512a0-ffffffff81a51383: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b489c0)
Location: net/ipv6/route.c:3043
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81b489c0-ffffffff81b48aa2: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b575d0)
Location: net/ipv6/route.c:3027
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81b575d0-ffffffff81b576b2: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b451c0)
Location: net/ipv6/route.c:3036
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81b451c0-ffffffff81b452a6: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0c300)
Location: net/ipv6/route.c:3166
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81c0c300-ffffffff81c0c3e6: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da71c0)
Location: net/ipv6/route.c:3156
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81da71c0-ffffffff81da72b7: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f767d0)
Location: net/ipv6/route.c:3156
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81f767d0-ffffffff81f768c7: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd6800)
Location: net/ipv6/route.c:3156
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81fd6800-ffffffff81fd68f7: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a4180)
Location: net/ipv6/route.c:3158
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff820a4180-ffffffff820a4277: ip6_redirect_no_header (STB_GLOBAL)
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
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d151f8)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffff800010d151f8-ffff800010d152e0: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1ae88)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
c0e1ae88-c0e1af74: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e42160)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
c000000000e42160-c000000000e42288: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085a8e8)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffe00085a8e8-ffffffe00085a9da: ip6_redirect_no_header (STB_GLOBAL)
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
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f0930)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff819f0930-ffffffff819f0a13: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad6f0)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff819ad6f0-ffffffff819ad7d3: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5b3b0)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81a5b3b0-ffffffff81a5b493: ip6_redirect_no_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_redirect_no_header(struct sk_buff *skb, struct net *net, int oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a676c0)
Location: net/ipv6/route.c:3019
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
**Symbols:**

```
ffffffff81a676c0-ffffffff81a677a3: ip6_redirect_no_header (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 mark</code>
</li>
</ul>
</details>
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
