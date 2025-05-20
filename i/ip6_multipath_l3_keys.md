# Function: <code>ip6_multipath_l3_keys</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191a5d0)
Location: net/ipv6/route.c:1818
Inline: False
```
**Symbols:**

```
ffffffff8191a5d0-ffffffff8191a709: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81975e25)
Location: net/ipv6/route.c:1950
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aba79)
Location: net/ipv6/route.c:1941
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a146a0)
Location: net/ipv6/route.c:2274
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81a146a0-ffffffff81a1484b: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4b290)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81a4b290-ffffffff81a4b43b: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b41110)
Location: net/ipv6/route.c:2302
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81b41110-ffffffff81b412bc: ip6_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4fbd0)
Location: net/ipv6/route.c:2285
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81b4fbd0-ffffffff81b4fd7c: ip6_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3da30)
Location: net/ipv6/route.c:2292
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81b3da30-ffffffff81b3dbdb: ip6_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04290)
Location: net/ipv6/route.c:2295
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81c04290-ffffffff81c0443b: ip6_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9e610)
Location: net/ipv6/route.c:2291
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81d9e610-ffffffff81d9e7ff: ip6_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6d500)
Location: net/ipv6/route.c:2291
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81f6d500-ffffffff81f6d6ef: ip6_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcd620)
Location: net/ipv6/route.c:2290
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81fcd620-ffffffff81fcd80f: ip6_multipath_l3_keys.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff8209ae70)
Location: net/ipv6/route.c:2292
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff8209ae70-ffffffff8209b05f: ip6_multipath_l3_keys.constprop.0 (STB_LOCAL)
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
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0e300)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffff800010d0e300-ffff800010d0e484: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e14c1c)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
c0e14c1c-c0e14dcc: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3a400)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
c000000000e3a400-c000000000e3a638: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000855e1a)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffe000855e1a-ffffffe000855f80: ip6_multipath_l3_keys (STB_LOCAL)
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
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ea920)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff819ea920-ffffffff819eaacb: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a76e0)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff819a76e0-ffffffff819a788b: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a553a0)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81a553a0-ffffffff81a5554b: ip6_multipath_l3_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff *skb, struct flow_keys *keys, struct flow_keys *flkeys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a613a0)
Location: net/ipv6/route.c:2280
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81a613a0-ffffffff81a6154b: ip6_multipath_l3_keys (STB_LOCAL)
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
