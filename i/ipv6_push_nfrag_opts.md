# Function: <code>ipv6_push_nfrag_opts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff817f3040)
Location: net/ipv6/exthdrs.c:689
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
**Symbols:**

```
ffffffff817f3040-ffffffff817f313f: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81861e80)
Location: net/ipv6/exthdrs.c:716
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81861e80-ffffffff81861f81: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818940a0)
Location: net/ipv6/exthdrs.c:932
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff818940a0-ffffffff818942c9: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818bb580)
Location: net/ipv6/exthdrs.c:934
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff818bb580-ffffffff818bb79b: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff8193e5c0)
Location: net/ipv6/exthdrs.c:984
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff8193e5c0-ffffffff8193e855: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819974f0)
Location: net/ipv6/exthdrs.c:971
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff819974f0-ffffffff819977a0: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819cddc0)
Location: net/ipv6/exthdrs.c:971
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff819cddc0-ffffffff819ce070: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/exthdrs.c (0)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a3cfaf-ffffffff81a3cfca: ipv6_push_nfrag_opts.cold (STB_LOCAL)
ffffffff81a3c9e0-ffffffff81a3cc7a: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a73660)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a73660-ffffffff81a738fd: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6dab0)
Location: net/ipv6/exthdrs.c:1164
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81b6dab0-ffffffff81b6db2d: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b7c560)
Location: net/ipv6/exthdrs.c:1159
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81b7c560-ffffffff81b7c5dd: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6b070)
Location: net/ipv6/exthdrs.c:1159
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81b6b070-ffffffff81b6b191: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c32ed0)
Location: net/ipv6/exthdrs.c:1207
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81c32ed0-ffffffff81c32ff1: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dd06c0)
Location: net/ipv6/exthdrs.c:1208
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81dd06c0-ffffffff81dd074e: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81fa1a80)
Location: net/ipv6/exthdrs.c:1208
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81fa1a80-ffffffff81fa1b0e: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff82002300)
Location: net/ipv6/exthdrs.c:1175
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff82002300-ffffffff82002385: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820d1100)
Location: net/ipv6/exthdrs.c:1180
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff820d1100-ffffffff820d1185: ipv6_push_nfrag_opts (STB_GLOBAL)
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
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffff800010d3c130)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffff800010d3c130-ffff800010d3c320: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c0e3f340)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
c0e3f340-c0e3f540: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c000000000e6fcc0)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
c000000000e6fcc0-c000000000e6ff7c: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffe000878b36)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffe000878b36-ffffffe000878d7a: ipv6_push_nfrag_opts (STB_GLOBAL)
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
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a12cf0)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a12cf0-ffffffff81a12f8d: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819cfab0)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff819cfab0-ffffffff819cfd4d: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a7d770)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a7d770-ffffffff81a7da0d: ipv6_push_nfrag_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipv6_push_nfrag_opts(struct sk_buff *skb, struct ipv6_txoptions *opt, u8 *proto, struct in6_addr **daddr, struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a89fc0)
Location: net/ipv6/exthdrs.c:967
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a89fc0-ffffffff81a8a25d: ipv6_push_nfrag_opts (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct in6_addr *saddr</code>
</li>
</ul>
</details>
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
