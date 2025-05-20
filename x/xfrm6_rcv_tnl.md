# Function: <code>xfrm6_rcv_tnl</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff8186c440)
Location: net/ipv6/xfrm6_input.c:53
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff8186c440-ffffffff8186c47e: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff8189f250)
Location: net/ipv6/xfrm6_input.c:53
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff8189f250-ffffffff8189f28e: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff818c57b0)
Location: net/ipv6/xfrm6_input.c:60
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff818c57b0-ffffffff818c57ee: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81948a90)
Location: net/ipv6/xfrm6_input.c:71
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81948a90-ffffffff81948ace: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff819a1b50)
Location: net/ipv6/xfrm6_input.c:71
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff819a1b50-ffffffff819a1b8e: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff819d8780)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff819d8780-ffffffff819d87be: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81a46fe0)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81a46fe0-ffffffff81a4701f: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81a7db90)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81a7db90-ffffffff81a7dbcf: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81b78725)
Location: net/ipv6/xfrm6_input.c:163
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81b786a0-ffffffff81b786df: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81b87695)
Location: net/ipv6/xfrm6_input.c:163
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81b87610-ffffffff81b8764f: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81b76345)
Location: net/ipv6/xfrm6_input.c:163
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81b762c0-ffffffff81b762ff: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81c40db5)
Location: net/ipv6/xfrm6_input.c:163
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81c40d30-ffffffff81c40d6f: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81ddf7a5)
Location: net/ipv6/xfrm6_input.c:163
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81ddf480-ffffffff81ddf4cb: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81fb1a65)
Location: net/ipv6/xfrm6_input.c:163
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81fb1710-ffffffff81fb175b: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff82012145)
Location: net/ipv6/xfrm6_input.c:166
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff82011db0-ffffffff82011dfb: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff820e12b5)
Location: net/ipv6/xfrm6_input.c:227
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff820e0d50-ffffffff820e0d9b: xfrm6_rcv_tnl (STB_GLOBAL)
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
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffff800010d48e38)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffff800010d48e38-ffff800010d48e90: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (c0e4a2b0)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
c0e4a2b0-c0e4a300: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (c000000000e7e1f0)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
c000000000e7e1f0-c000000000e7e258: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffe00088238e)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffe00088238e-ffffffe0008823e0: xfrm6_rcv_tnl (STB_GLOBAL)
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
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81a1d220)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81a1d220-ffffffff81a1d25f: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff819d9fe0)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff819d9fe0-ffffffff819da01f: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81a87ca0)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81a87ca0-ffffffff81a87cdf: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xfrm6_rcv_tnl(struct sk_buff *skb, struct ip6_tnl *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_input.c (ffffffff81a948d0)
Location: net/ipv6/xfrm6_input.c:72
Inline: False
Direct callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
```
**Symbols:**

```
ffffffff81a948d0-ffffffff81a9490f: xfrm6_rcv_tnl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
