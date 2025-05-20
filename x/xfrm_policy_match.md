# Function: <code>xfrm_policy_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b4cf0)
Location: net/xfrm/xfrm_policy.c:1070
Inline: True
```
**Symbols:**

```
ffffffff817b4cf0-ffffffff817b4d6b: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81821d60)
Location: net/xfrm/xfrm_policy.c:1074
Inline: True
```
**Symbols:**

```
ffffffff81821d60-ffffffff81821ddb: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81853570)
Location: net/xfrm/xfrm_policy.c:1091
Inline: True
```
**Symbols:**

```
ffffffff81853570-ffffffff818535eb: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81876f60)
Location: net/xfrm/xfrm_policy.c:1086
Inline: False
```
**Symbols:**

```
ffffffff81876f60-ffffffff81876fe2: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f7bb0)
Location: net/xfrm/xfrm_policy.c:1057
Inline: False
```
**Symbols:**

```
ffffffff818f7bb0-ffffffff818f7c2c: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194e540)
Location: net/xfrm/xfrm_policy.c:1057
Inline: False
```
**Symbols:**

```
ffffffff8194e540-ffffffff8194e5ac: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81981860)
Location: net/xfrm/xfrm_policy.c:1880
Inline: False
```
**Symbols:**

```
ffffffff81981860-ffffffff819818d2: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819eb5e0)
Location: net/xfrm/xfrm_policy.c:1886
Inline: False
```
**Symbols:**

```
ffffffff819eb5e0-ffffffff819eb651: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a225e0)
Location: net/xfrm/xfrm_policy.c:1888
Inline: False
```
**Symbols:**

```
ffffffff81a225e0-ffffffff81a22651: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b145c0)
Location: net/xfrm/xfrm_policy.c:1879
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_eval_candidates
```
**Symbols:**

```
ffffffff81b145c0-ffffffff81b14630: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b22970)
Location: net/xfrm/xfrm_policy.c:1889
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_eval_candidates
```
**Symbols:**

```
ffffffff81b22970-ffffffff81b229e0: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b10560)
Location: net/xfrm/xfrm_policy.c:1888
Inline: False
```
**Symbols:**

```
ffffffff81b10560-ffffffff81b105d0: xfrm_policy_match (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81bd3ea0)
Location: net/xfrm/xfrm_policy.c:1890
Inline: True
```
**Symbols:**

```
ffffffff81bd3ea0-ffffffff81bd3f04: xfrm_policy_match.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81d6a390)
Location: net/xfrm/xfrm_policy.c:1890
Inline: True
```
**Symbols:**

```
ffffffff81d6a390-ffffffff81d6a412: xfrm_policy_match.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f356e0)
Location: net/xfrm/xfrm_policy.c:1961
Inline: False
```
**Symbols:**

```
ffffffff81f356e0-ffffffff81f35762: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f95280)
Location: net/xfrm/xfrm_policy.c:1963
Inline: False
```
**Symbols:**

```
ffffffff81f95280-ffffffff81f95302: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff82062670)
Location: net/xfrm/xfrm_policy.c:1983
Inline: False
```
**Symbols:**

```
ffffffff82062670-ffffffff820626f2: xfrm_policy_match (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffff800010cdf758)
Location: net/xfrm/xfrm_policy.c:1888
Inline: True
```
**Symbols:**

```
ffff800010cdf758-ffff800010cdf80c: xfrm_policy_match.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de8c18)
Location: net/xfrm/xfrm_policy.c:1888
Inline: True
```
**Symbols:**

```
c0de8c18-c0de8ca8: xfrm_policy_match.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (c000000000e01620)
Location: net/xfrm/xfrm_policy.c:1888
Inline: True
```
**Symbols:**

```
c000000000e01620-c000000000e01718: xfrm_policy_match.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082e5c8)
Location: net/xfrm/xfrm_policy.c:1888
Inline: True
```
**Symbols:**

```
ffffffe00082e5c8-ffffffe00082e64e: xfrm_policy_match.constprop.0 (STB_LOCAL)
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
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819c1c70)
Location: net/xfrm/xfrm_policy.c:1888
Inline: False
```
**Symbols:**

```
ffffffff819c1c70-ffffffff819c1ce1: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197ea60)
Location: net/xfrm/xfrm_policy.c:1888
Inline: False
```
**Symbols:**

```
ffffffff8197ea60-ffffffff8197ead1: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2c6f0)
Location: net/xfrm/xfrm_policy.c:1888
Inline: False
```
**Symbols:**

```
ffffffff81a2c6f0-ffffffff81a2c761: xfrm_policy_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xfrm_policy_match(const struct xfrm_policy *pol, const struct flowi *fl, u8 type, u16 family, int dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a37dd0)
Location: net/xfrm/xfrm_policy.c:1888
Inline: False
```
**Symbols:**

```
ffffffff81a37dd0-ffffffff81a37e41: xfrm_policy_match (STB_LOCAL)
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
<b>Param added. </b>
<code>u32 if_id</code>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
