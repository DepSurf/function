# Function: <code>ipv6_select_ident</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81800900)
Location: net/ipv6/output_core.c:65
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81800900-ffffffff818009a2: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81872020)
Location: net/ipv6/output_core.c:65
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81872020-ffffffff818720c2: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff818a6600)
Location: net/ipv6/output_core.c:65
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff818a6600-ffffffff818a66a2: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff818cd060)
Location: net/ipv6/output_core.c:65
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff818cd060-ffffffff818cd102: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81951e40)
Location: net/ipv6/output_core.c:65
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81951e40-ffffffff81951ee2: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff819ab3c0)
Location: net/ipv6/output_core.c:65
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff819ab3c0-ffffffff819ab462: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff819e1ee0)
Location: net/ipv6/output_core.c:65
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff819e1ee0-ffffffff819e1f82: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a50b40)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a50b40-ffffffff81a50b66: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a87810)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a87810-ffffffff81a87836: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81b82c70)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b82c70-ffffffff81b82cfc: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81b922f0)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b922f0-ffffffff81b9237c: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81b810e0)
Location: net/ipv6/output_core.c:53
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b810e0-ffffffff81b810f6: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81c4d100)
Location: net/ipv6/output_core.c:53
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81c4d100-ffffffff81c4d116: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81ded5d0)
Location: net/ipv6/output_core.c:53
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81ded5d0-ffffffff81ded5ea: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81fc1720)
Location: net/ipv6/output_core.c:47
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81fc1720-ffffffff81fc1754: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff820226a0)
Location: net/ipv6/output_core.c:47
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff820226a0-ffffffff820226d4: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff820f17c0)
Location: net/ipv6/output_core.c:47
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff820f17c0-ffffffff820f17f4: ipv6_select_ident (STB_GLOBAL)
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
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffff800010d54110)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffff800010d54110-ffff800010d54168: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (c0e548cc)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c0e548cc-c0e548ec: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (c000000000e8cbb0)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c000000000e8cbb0-c000000000e8cc04: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffe00088bc1a)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffe00088bc1a-ffffffe00088bc7a: ipv6_select_ident (STB_GLOBAL)
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
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a26ea0)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a26ea0-ffffffff81a26ec6: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff819e3c60)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff819e3c60-ffffffff819e3c86: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a92a50)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a92a50-ffffffff81a92a76: ipv6_select_ident (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__be32 ipv6_select_ident(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a9eb50)
Location: net/ipv6/output_core.c:71
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a9eb50-ffffffff81a9eb76: ipv6_select_ident (STB_GLOBAL)
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
