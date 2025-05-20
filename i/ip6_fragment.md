# Function: <code>ip6_fragment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c7130)
Location: net/ipv6/ip6_output.c:559
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff817c7130-ffffffff817c7b0d: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81834210)
Location: net/ipv6/ip6_output.c:558
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81834210-ffffffff81834c34: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81865c70)
Location: net/ipv6/ip6_output.c:584
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81865c70-ffffffff818666cc: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8188a420)
Location: net/ipv6/ip6_output.c:585
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff8188a420-ffffffff8188ae0d: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8190b620)
Location: net/ipv6/ip6_output.c:604
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff8190b620-ffffffff8190c002: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81962ab0)
Location: net/ipv6/ip6_output.c:580
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81962ab0-ffffffff81963482: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81997aa0)
Location: net/ipv6/ip6_output.c:589
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81997aa0-ffffffff81998444: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a03b70)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81a03b70-ffffffff81a04278: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a3a740)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81a3a740-ffffffff81a3ae67: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2fd20)
Location: net/ipv6/ip6_output.c:763
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81b2fd20-ffffffff81b3042b: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3e7c0)
Location: net/ipv6/ip6_output.c:800
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81b3e7c0-ffffffff81b3eed7: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2b560)
Location: net/ipv6/ip6_output.c:831
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81b2b560-ffffffff81b2bca6: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:812
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81d3f467-ffffffff81d3f4bb: ip6_fragment.cold (STB_LOCAL)
ffffffff81bf1690-ffffffff81bf1e04: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:834
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81f0be18-ffffffff81f0be80: ip6_fragment.cold (STB_LOCAL)
ffffffff81d89ff0-ffffffff81d8a877: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:847
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff820b364d-ffffffff820b36b5: ip6_fragment.cold (STB_LOCAL)
ffffffff81f57f80-ffffffff81f58815: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:848
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff821347ba-ffffffff821347ff: ip6_fragment.cold (STB_LOCAL)
ffffffff81fb7b60-ffffffff81fb84d5: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:858
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff82216340-ffffffff82216385: ip6_fragment.cold (STB_LOCAL)
ffffffff820851a0-ffffffff82085ac4: ip6_fragment (STB_GLOBAL)
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
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfb7f0)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffff800010cfb7f0-ffff800010cfbf08: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e026e4)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
c0e026e4-c0e0328c: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e22ec0)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
c000000000e22ec0-c000000000e23868: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe0008461b8)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffe0008461b8-ffffffe00084688e: ip6_fragment (STB_GLOBAL)
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
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d9dd0)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff819d9dd0-ffffffff819da4f7: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81996b90)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81996b90-ffffffff819972b7: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a44850)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81a44850-ffffffff81a44f77: ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, int (*output)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a50510)
Location: net/ipv6/ip6_output.c:762
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
**Symbols:**

```
ffffffff81a50510-ffffffff81a50c37: ip6_fragment (STB_GLOBAL)
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
