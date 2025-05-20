# Function: <code>sf_setstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81795510)
Location: net/ipv4/igmp.c:1892
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff817e8dd0)
Location: net/ipv6/mcast.c:2214
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff81795510-ffffffff8179566e: sf_setstate (STB_LOCAL)
ffffffff817e8dd0-ffffffff817e8f78: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81802ef0)
Location: net/ipv4/igmp.c:1902
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff81857610)
Location: net/ipv6/mcast.c:2213
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff81802ef0-ffffffff81803056: sf_setstate (STB_LOCAL)
ffffffff81857610-ffffffff818577c7: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81833e90)
Location: net/ipv4/igmp.c:1940
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff81889410)
Location: net/ipv6/mcast.c:2237
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff81833e90-ffffffff81833ff6: sf_setstate (STB_LOCAL)
ffffffff81889410-ffffffff818895c7: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81855440)
Location: net/ipv4/igmp.c:1949
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff818afaa0)
Location: net/ipv6/mcast.c:2236
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff81855440-ffffffff818555b8: sf_setstate (STB_LOCAL)
ffffffff818afaa0-ffffffff818afc61: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d52e0)
Location: net/ipv4/igmp.c:1975
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff819327c0)
Location: net/ipv6/mcast.c:2241
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff818d52e0-ffffffff818d5458: sf_setstate (STB_LOCAL)
ffffffff819327c0-ffffffff81932981: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192bc40)
Location: net/ipv4/igmp.c:1986
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff8198b1d0)
Location: net/ipv6/mcast.c:2266
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff8192bc40-ffffffff8192bdb8: sf_setstate (STB_LOCAL)
ffffffff8198b1d0-ffffffff8198b38a: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195b0d0)
Location: net/ipv4/igmp.c:2002
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff819c1af0)
Location: net/ipv6/mcast.c:2266
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff8195b0d0-ffffffff8195b248: sf_setstate (STB_LOCAL)
ffffffff819c1af0-ffffffff819c1caa: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819bfdd0)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff81a30900)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff819bfdd0-ffffffff819bff3a: sf_setstate (STB_LOCAL)
ffffffff81a30900-ffffffff81a30aa5: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f6970)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff81a67450)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff819f6970-ffffffff819f6ada: sf_setstate (STB_LOCAL)
ffffffff81a67450-ffffffff81a675f5: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae4c70)
Location: net/ipv4/igmp.c:2002
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff81b5fee0)
Location: net/ipv6/mcast.c:2262
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff81ae4c70-ffffffff81ae4dda: sf_setstate (STB_LOCAL)
ffffffff81b5fee0-ffffffff81b60085: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af1b40)
Location: net/ipv4/igmp.c:2002
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff81b6e650)
Location: net/ipv6/mcast.c:2262
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff81af1b40-ffffffff81af1caa: sf_setstate (STB_LOCAL)
ffffffff81b6e650-ffffffff81b6e7f5: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81add330)
Location: net/ipv4/igmp.c:2010
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff81b5ca50)
Location: net/ipv6/mcast.c:2418
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff81add330-ffffffff81add49a: sf_setstate (STB_LOCAL)
ffffffff81b5ca50-ffffffff81b5cc0e: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9c7a0)
Location: net/ipv4/igmp.c:2010
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff81c242a0)
Location: net/ipv6/mcast.c:2416
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff81b9c7a0-ffffffff81b9c90a: sf_setstate (STB_LOCAL)
ffffffff81c242a0-ffffffff81c2445e: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d2e7d0)
Location: net/ipv4/igmp.c:2017
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff81dc13e0)
Location: net/ipv6/mcast.c:2418
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff81d2e7d0-ffffffff81d2e94f: sf_setstate (STB_LOCAL)
ffffffff81dc13e0-ffffffff81dc15b9: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef67b0)
Location: net/ipv4/igmp.c:2017
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff81f91b80)
Location: net/ipv6/mcast.c:2418
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff81ef67b0-ffffffff81ef692f: sf_setstate (STB_LOCAL)
ffffffff81f91b80-ffffffff81f91d59: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f56220)
Location: net/ipv4/igmp.c:2018
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff81ff24a0)
Location: net/ipv6/mcast.c:2418
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff81f56220-ffffffff81f5639f: sf_setstate (STB_LOCAL)
ffffffff81ff24a0-ffffffff81ff2674: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201c690)
Location: net/ipv4/igmp.c:2020
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
```
```
In net/ipv6/mcast.c (ffffffff820c00d0)
Location: net/ipv6/mcast.c:2415
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
```
**Symbols:**

```
ffffffff8201c690-ffffffff8201c83e: sf_setstate (STB_LOCAL)
ffffffff820c00d0-ffffffff820c02d3: sf_setstate (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cad468)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffff800010d2d478)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffff800010cad468-ffff800010cad5f0: sf_setstate (STB_LOCAL)
ffff800010d2d478-ffff800010d2d618: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0db9d64)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (c0e316dc)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
c0db9d64-c0db9f18: sf_setstate (STB_LOCAL)
c0e316dc-c0e318e0: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc3950)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (c000000000e5f520)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
c000000000dc3950-c000000000dc3b90: sf_setstate (STB_LOCAL)
c000000000e5f520-c000000000e5f7a0: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe00080749e)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffe00086d722)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffe00080749e-ffffffe0008075b0: sf_setstate (STB_LOCAL)
ffffffe00086d722-ffffffe00086d8aa: sf_setstate (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81996710)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff81a06ae0)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff81996710-ffffffff8199687a: sf_setstate (STB_LOCAL)
ffffffff81a06ae0-ffffffff81a06c85: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819501d0)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff819c38a0)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff819501d0-ffffffff8195033a: sf_setstate (STB_LOCAL)
ffffffff819c38a0-ffffffff819c3a45: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a00fb0)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff81a71560)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff81a00fb0-ffffffff81a0111a: sf_setstate (STB_LOCAL)
ffffffff81a71560-ffffffff81a71705: sf_setstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int sf_setstate(struct ip_mc_list *pmc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0b4a0)
Location: net/ipv4/igmp.c:2004
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
```
```
In net/ipv6/mcast.c (ffffffff81a7db80)
Location: net/ipv6/mcast.c:2265
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
```
**Symbols:**

```
ffffffff81a0b4a0-ffffffff81a0b60a: sf_setstate (STB_LOCAL)
ffffffff81a7db80-ffffffff81a7dd25: sf_setstate (STB_LOCAL)
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
