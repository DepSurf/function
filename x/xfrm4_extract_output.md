# Function: <code>xfrm4_extract_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff817b01f0)
Location: net/ipv4/xfrm4_output.c:46
Inline: False
```
**Symbols:**

```
ffffffff817b01f0-ffffffff817b029e: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff8181d120)
Location: net/ipv4/xfrm4_output.c:46
Inline: False
```
**Symbols:**

```
ffffffff8181d120-ffffffff8181d1d3: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff8184e9e0)
Location: net/ipv4/xfrm4_output.c:46
Inline: False
```
**Symbols:**

```
ffffffff8184e9e0-ffffffff8184ea93: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff818724b0)
Location: net/ipv4/xfrm4_output.c:47
Inline: False
```
**Symbols:**

```
ffffffff818724b0-ffffffff81872635: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff818f2ea0)
Location: net/ipv4/xfrm4_output.c:47
Inline: False
```
**Symbols:**

```
ffffffff818f2ea0-ffffffff818f3031: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff819497d0)
Location: net/ipv4/xfrm4_output.c:48
Inline: False
```
**Symbols:**

```
ffffffff819497d0-ffffffff81949941: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff8197b490)
Location: net/ipv4/xfrm4_output.c:48
Inline: False
```
**Symbols:**

```
ffffffff8197b490-ffffffff8197b602: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff819e49b0)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
ffffffff819e49b0-ffffffff819e4b3b: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff81a1b9d0)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
ffffffff81a1b9d0-ffffffff81a1bb5d: xfrm4_extract_output (STB_GLOBAL)
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
In net/xfrm/xfrm_output.c (ffffffff81b1f8a0)
Location: net/xfrm/xfrm_output.c:659
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81b1f8a0-ffffffff81b1faab: xfrm4_extract_output.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffffffff81b2e170)
Location: net/xfrm/xfrm_output.c:659
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81b2e170-ffffffff81b2e3b3: xfrm4_extract_output.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:659
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81b1bb60-ffffffff81b1be28: xfrm4_extract_output.isra.0 (STB_LOCAL)
ffffffff81c24dba-ffffffff81c24dd0: xfrm4_extract_output.isra.0.cold (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:795
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81be03f0-ffffffff81be05d6: xfrm4_extract_output.isra.0 (STB_LOCAL)
ffffffff81d3ef52-ffffffff81d3ef68: xfrm4_extract_output.isra.0.cold (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:796
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81d77300-ffffffff81d77613: xfrm4_extract_output.isra.0 (STB_LOCAL)
ffffffff81f0b892-ffffffff81f0b8c3: xfrm4_extract_output.isra.0.cold (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:805
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81f43b90-ffffffff81f43ead: xfrm4_extract_output.isra.0 (STB_LOCAL)
ffffffff820b30fc-ffffffff820b311c: xfrm4_extract_output.isra.0.cold (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:806
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81fa3370-ffffffff81fa3691: xfrm4_extract_output.isra.0 (STB_LOCAL)
ffffffff821342fd-ffffffff8213431a: xfrm4_extract_output.isra.0.cold (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffffffff820705a0)
Location: net/xfrm/xfrm_output.c:810
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff820705a0-ffffffff82070755: xfrm4_extract_output.isra.0 (STB_LOCAL)
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
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffff800010cd7c58)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
ffff800010cd7c58-ffff800010cd7dfc: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (c0de1730)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
c0de1730-c0de18dc: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (c000000000df7cb0)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
c000000000df7cb0-c000000000df7ed4: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffe00082827c)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
ffffffe00082827c-ffffffe0008283dc: xfrm4_extract_output (STB_GLOBAL)
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
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff819bb060)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
ffffffff819bb060-ffffffff819bb1ed: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff81977e50)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
ffffffff81977e50-ffffffff81977fdd: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff81a25ae0)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
ffffffff81a25ae0-ffffffff81a25c6d: xfrm4_extract_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xfrm4_extract_output(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_output.c (ffffffff81a30f80)
Location: net/ipv4/xfrm4_output.c:44
Inline: False
```
**Symbols:**

```
ffffffff81a30f80-ffffffff81a3110d: xfrm4_extract_output (STB_GLOBAL)
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
