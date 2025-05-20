# Function: <code>__ipv6_select_ident</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, u32 hashrnd, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81800700)
Location: net/ipv6/output_core.c:13
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/output_core.c:ipv6_select_ident
```
**Symbols:**

```
ffffffff81800700-ffffffff818007de: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, u32 hashrnd, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81871e20)
Location: net/ipv6/output_core.c:13
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81871e20-ffffffff81871efe: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, u32 hashrnd, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff818a6400)
Location: net/ipv6/output_core.c:13
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff818a6400-ffffffff818a64de: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, u32 hashrnd, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff818cce50)
Location: net/ipv6/output_core.c:13
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff818cce50-ffffffff818ccf2e: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, u32 hashrnd, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81951c40)
Location: net/ipv6/output_core.c:13
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81951c40-ffffffff81951d1e: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, u32 hashrnd, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff819ab1d0)
Location: net/ipv6/output_core.c:13
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff819ab1d0-ffffffff819ab2a9: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, u32 hashrnd, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff819e1cf0)
Location: net/ipv6/output_core.c:13
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff819e1cf0-ffffffff819e1dc9: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a50ab0)
Location: net/ipv6/output_core.c:14
Inline: True
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81a50ab0-ffffffff81a50b3b: __ipv6_select_ident.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a876d0)
Location: net/ipv6/output_core.c:14
Inline: True
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81a876d0-ffffffff81a8775b: __ipv6_select_ident.isra.0 (STB_LOCAL)
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
In net/ipv6/output_core.c (ffffffff81b82ca6)
Location: net/ipv6/output_core.c:14
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
Direct callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81b82b30-ffffffff81b82bbb: __ipv6_select_ident.isra.0 (STB_LOCAL)
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
In net/ipv6/output_core.c (ffffffff81b92326)
Location: net/ipv6/output_core.c:14
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
Direct callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81b921b0-ffffffff81b9223b: __ipv6_select_ident.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81b810e9)
Location: net/ipv6/output_core.c:14
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81c4d109)
Location: net/ipv6/output_core.c:14
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81ded5d9)
Location: net/ipv6/output_core.c:14
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (0)
Location: net/ipv6/output_core.c:14
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
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
In net/ipv6/output_core.c (0)
Location: net/ipv6/output_core.c:14
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
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
In net/ipv6/output_core.c (0)
Location: net/ipv6/output_core.c:14
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/output_core.c (ffff800010d53fa8)
Location: net/ipv6/output_core.c:14
Inline: True
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffff800010d53fa8-ffff800010d54040: __ipv6_select_ident.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (c0e54750)
Location: net/ipv6/output_core.c:14
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
c0e54750-c0e54800: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/output_core.c (c000000000e8c9b0)
Location: net/ipv6/output_core.c:14
Inline: True
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
c000000000e8c9b0-c000000000e8cab0: __ipv6_select_ident.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 __ipv6_select_ident(struct net *net, const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/output_core.c (ffffffe00088baa6)
Location: net/ipv6/output_core.c:14
Inline: False
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffe00088baa6-ffffffe00088bb72: __ipv6_select_ident (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a26d60)
Location: net/ipv6/output_core.c:14
Inline: True
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81a26d60-ffffffff81a26deb: __ipv6_select_ident.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/output_core.c (ffffffff819e3b20)
Location: net/ipv6/output_core.c:14
Inline: True
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff819e3b20-ffffffff819e3bab: __ipv6_select_ident.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a92910)
Location: net/ipv6/output_core.c:14
Inline: True
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81a92910-ffffffff81a9299b: __ipv6_select_ident.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/output_core.c (ffffffff81a9ea10)
Location: net/ipv6/output_core.c:14
Inline: True
Direct callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
**Symbols:**

```
ffffffff81a9ea10-ffffffff81a9ea9b: __ipv6_select_ident.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
